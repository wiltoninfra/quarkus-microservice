## Project Java Microframework Quarkus

## Exemple Ifood services delivery


```
mvn clean package -DskipTests
mvn quarkus:add-extension -Dextensions="quarkus-smallrye-openapi, jdbc-postgres, hibernate-validator, orm-panache, hibernate-orm-panache, hibernate-validator, resteady-jsonb, health"
```