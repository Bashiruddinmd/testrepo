# Test Repository

This repository contains a minimal Spring Boot project that demonstrates how to
connect to an Oracle database using QueryDSL.

## Building

```bash
mvn -f oracle-querydsl-demo/pom.xml clean package
```

## Running

```bash
mvn -f oracle-querydsl-demo/pom.xml spring-boot:run
```

Make sure an Oracle database is available and the connection properties in
`application.properties` are correct.
