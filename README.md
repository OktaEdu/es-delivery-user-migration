# Course Lab Files

This files here are intended to be used with the Okta on-demand training course, Migrate and Integrate your Users with Okta, which can be found here: https://www.okta.com/services/training/.


## Dependencies
Java JDK 8

## How to run from source

To run the `scim` app from source using the command line:

1. Navigate to the `scim` directory
2. Issue the command `./gradlew bootRun`

## How to run the executable `war`
1. You will need the `war` file located in the `scim/build/libs` folder
2. Run the file by issuing the command `java -jar scim-0.0.1-SNAPSHOT.war`

## Rebuilding the `war`
If you make updates to the application and need to update the `war`:
1. Navigate to the `scim` directory
2. Run `./gradlew build`
3. Run `./gradlew bootRepackage`
4. Your updated `war` will be located in the `build/libs` directory

For more info, see: https://www.baeldung.com/spring-boot-gradle-plugin and 
reference the sections for Spring Boot 1.x
