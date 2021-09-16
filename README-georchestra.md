# building

In order to build the searching microservice, without docker nor the SQL dependency,
use the following commands:


```
./mvnw -o clean install -P-docker -Dsearch_without_sql
./mvnw clean package spring-boot:repackage -P-docker -Dsearch_without_sql -f modules/services/searching/
```
