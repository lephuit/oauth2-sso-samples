oauth2-sso-samples
==================

Extended Spring OAuth2 tonr/sparklr samples to support Single sign on.

# Getting Started

## Preparation
To run sample applications, you need to download the [spring-security-oauth](https://github.com/spring-projects/spring-security-oauth) project first and 
build and install both spring-security-oauth2 and spring-security-jwt projects successfully into your local maven repository.

Normally executing "mvn install" in the spring-security-oauth directory will do all necessary steps for you.
	$ mvn install -p bootstrap
	
## Build samples applications (command line)

"mvn package" in oauth2-sso-samples directory will create three war files (tonr, sparklr, keyhole).

## Run in eclipse

- Import tonr, sparklr, keyhole and oauth2sso projects with "Existing Maven projects" (Import -> Maven)
- If necessary, import also "spring-security-oauth2" and "spring-security-jwt" from spring-security-oauth. (This should not be necessary, but eclipse will 
complain about spring-security-oauth2-2.0.xsd file if they are not imported).

Now you can deploy all 3 apps (tonr2, sparklr2, keyhole2) into your Servers environment!

## Next step

See this document how these sample apps works: [OAuth2 Single Sign On with spring-security-oauth2](
https://github.com/hkurosu/oauth2-sso-samples/blob/master/docs/OAuth2%20Single%20Sign%20On%20with%20Spring%20\(Demo\).pptx)


