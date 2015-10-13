# java

 mvn -X package -Dpkgtype=rpm

└── java
    ├── pom.xml
    ├── src
    │   └── main
    │       └── webapp
    │           ├── index.jsp
    │           └── WEB-INF
    │               └── web.xml
    └── target
        ├── maven-archiver
        │   └── pom.properties
        ├── rpm
        │   └── trucks
        │       ├── BUILD
        │       ├── BUILDROOT
        │       ├── RPMS
        │       │   └── noarch
        │       │       └── trucks-5-5_1.noarch.rpm
        │       ├── SOURCES
        │       ├── SPECS
        │       │   └── trucks.spec
        │       ├── SRPMS
        │       └── tmp-buildroot
        ├── trucks
        │   ├── index.jsp
        │   ├── META-INF
        │   └── WEB-INF
        │       ├── classes
        │       └── web.xml
        └── trucks.war
