# NubesGen sample application for Spring Boot

To generate the Spring Boot application:

```bash
curl https://start.spring.io/starter.tgz -d dependencies=web,data-jdbc,postgresql -d bootVersion=2.5.4.RELEASE -d javaVersion=11 | tar -xzvf -
```

To generate the NubesGen configuration:

```bash
curl "http://localhost:8080/nubesgen-judubois-000.tgz?iactool=TERRAFORM&region=westeurope&application=APP_SERVICE.basic&runtime=SPRING&database=POSTGRESQL.basic&addons=application_insights&gitops=true" | tar -xzvf -
```