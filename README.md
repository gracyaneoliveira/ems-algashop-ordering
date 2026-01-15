# ems-algashop-ordering
Microservice AlgaShop Ordering

**Flyway**
```
./gradlew flywayInfo -Dflyway.configFiles=flyway.conf

./gradlew -x check build flywayInfo -Dflyway.configFiles=flyway.conf

./gradlew -x check build flywayValidate -Dflyway.configFiles=flyway.conf

./gradlew -x check build flywayMigrate -Dflyway.configFiles=flyway.conf
```
