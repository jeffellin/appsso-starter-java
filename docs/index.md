# AppSSO Starter Java Application

This application demonstrates the implementation of an authentication method in a Spring Boot application using [Application Single Sign-On for VMware Tanzu® (AppSSO)](https://docs-staging.vmware.com/en/Application-Single-Sign-On-for-VMware-Tanzu/index.html).

AppSSO provides APIs for curating and consuming a “Single Sign-On as a service” offering on Tanzu Application Platform.

At the core of AppSSO is the concept of an Authorization Server. Service Operators create those resources to provision running Authorization Servers, which are [OpenID Connect Providers](https://openid.net/specs/openid-connect-core-1_0.html). They issue [ID Tokens](https://openid.net/specs/openid-connect-core-1_0.html#IDToken) to Client applications, which contain identity information about the End-User (such as email, first name, last name, etc).

![AppSSO Concepts](https://grateful-human.static.app/images/docs-appsso-architecture.png)

AppSSO’s authorization server is based off of [Spring Authorization Server](https://github.com/spring-projects/spring-authorization-server).

For more information on securing Workloads with AppSSO, [click here](https://docs-staging.vmware.com/en/Application-Single-Sign-On-for-VMware-Tanzu/1.0/appsso/GUID-app-operators-tutorials-index.html).