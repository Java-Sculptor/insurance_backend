# Insurance Service Registry

This is the Eureka Server project for the Insurance Management System.

## Requirements
- JDK 21
- IntelliJ IDEA
- Maven available through IntelliJ (use the bundled Maven if your Maven Wrapper reports a Guice `ArtifactHandlerManager` error)

## Open in IntelliJ
1. Extract this ZIP to a folder.
2. In IntelliJ, choose **File > Open** and select the extracted `insurance-service-registry` folder.
3. If prompted, import/open it as a Maven project.
4. Set Project SDK to JDK 21.
5. In **Settings > Build Tools > Maven**, choose the bundled Maven if the wrapper causes the Guice injector error.
6. Reload Maven dependencies.
7. Run `src/main/java/insurance/ServiceRegistryApplication.java`.

## Verify
Open http://localhost:8761 in a browser. The Eureka dashboard should appear.

If dependency resolution fails, check the first Maven error and confirm your network/proxy settings. Do not randomly change the Spring Boot or Spring Cloud versions.
