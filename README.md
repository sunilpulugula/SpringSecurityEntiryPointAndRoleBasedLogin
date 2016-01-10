# SpringSecurityEntiryPointAndRoleBasedLogin

This application is all about using entry point and role based login in Spring Security 4.

Spring Security handles this automatic triggering of the authentication process with the concept of an Entry Point – this is a required part of the configuration, and can be injected via the entry-point-ref attribute of the security:http  element.

Spring Security handles success handler & failure handler based on authentication result.Success handler and failure handler can be configured in security:form-login element.We use SimpleUrlAuthentication FailureHandler which is provided by spring, which will auto redirect to the access denied page.

# Build

mvn clean install

# Deploy 

deploy spring-security-entry-point-and-role-based-url.war in web server(eg, tomcat).

# Blog :

Here is the Blog[http://sunilkumarpblog.blogspot.in/2016/01/spring-security-entry-point-and-role.html] of this project with precise explination.
