Docker image to efficiently build Spring Boot/Cloud application in Coucourse pipeline.

This image contains the OWASP database for dependency check and SonarQube dependencies.

Build everyday to ensure that the database is up to date and full database refresh aren't necessary in builds.

When building the image, it fetches Spring Initializr projects for several Spring Boot version and a bunch of commonly used dependencies in order to baked them in the image and allow for faster builds.
# pipeline-cloud-owasp-sonar-gradle
