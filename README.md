# jbosstools-releng
===Full JBoss Tools Build

==Prerequisites

Git
Java SDK 1.7+
maven

== Build Everything "one by one"

Clone repository as 

git clone git://github.com/dgolovin/jbosstools-releng.git


Change dir to repository root folder


cd jbosstools-releng


Start the build with unified target platform


mvn clean install -f full-build/pom.1by1.xml 


Start the build with multiple target platform


mvn clean install -DtpcKind=multiple -f full-build/pom.1by1.xml 

