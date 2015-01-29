
# Full JBoss Tools Build

## Prerequisites

1. Git
1. Java SDK 1.7+
1. maven 3.1+

## Build Everything "one by one"

Clone repository as 

    git clone --recursive git://github.com/dgolovin/jbosstools-releng.git

Change dir to repository root folder

    cd jbosstools-releng

Start the build with unified target platform

    mvn clean install -f jbosstools-dev/full-build/pom.1by1.xml 

Start the build with multiple target platform

    mvn clean install -DtpcKind=multiple -f jbosstools-dev/full-build/pom.1by1.xml 

## Buildin everything in one reactor

Clone repository as 

    git clone --recursive git://github.com/dgolovin/jbosstools-releng.git

Change dir to repository root folder

    cd jbosstools-releng

Start the build with unified target platform

    mvn clean install -f jbosstools-dev/full-build/pom.xml 

Start the build with multiple target platform

    mvn clean install -DtpcKind=multiple -f jbosstools-dev/full-build/pom.xml 
