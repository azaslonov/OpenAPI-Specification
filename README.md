# The Swagger Specification

![](https://raw.github.com/wordnik/swagger-spec/master/swagger-logo.jpg)
## Welcome to the Swagger Project! 

The goal of Swagger™ is to define a standard, language-agnostic interface to REST APIs which allows both humans and computers to discover and understand the capabilities of the service without access to source code, documentation, or through network traffic inspection.  When properly defined via Swagger, a consumer can understand and interact with the remote service with a minimal amount of implementation logic.  Similar to what interfaces have done for lower-level programming, Swager removes the guesswork in calling the service.

Use cases for machine-readable API interfaces include interactive documentation, code generation for documentation, client, and server, as well as automated test cases.  Swagger-enabled APIs expose JSON files that correctly ahere to the Swagger Specification, documented in this repository.  These files can either be produced and served statically, or be generated dynamically from your application.

Without going into a long history of interfaces to Web Services, this is not the first attempt to do so.  We can learn from CORBA, WSDL and WADL.  These specifications had good intentions but were limited by proprietary vendor-specific implementations, being bound to a specific programming language, and goals which were too open-ended.  In the end, they failed to gain traction.

Swagger does not require you to rewrite your existing API.  It does not require binding any software to a service--the service being described may not even be yours.  It does, however, require the capabilities of the service be described in the structure of the Swagger Specification.  Not all services can be described by Swagger--this specification is not intended to cover every possible use-case of a REST-ful API.  Swagger does not define a specific development process such as design-first or code-first.  It does facilitate either technique by establishing clear interactions with a REST API.

This GitHub project is the starting point for Swagger.
Here you will find the information you need about the Swagger Specification, a simple static sample of what it looks like,
and some general information regarding the project.

## Current Version - 1.2

The current version of the Swagger specification is 1.2 - and you can find it [here](versions/1.2.md).

### [Swagger 1.2 Specification](versions/1.2.md)

Please keep in mind that the other projects under Swagger use an independent version system.
As such, don't confuse the version of the Swagger Specification they support and the version of that given library.
For example, Swagger-Core with the version 1.3.2 supports Swagger Specification 1.2.

## The Wiki

Check out the [wiki](https://github.com/wordnik/swagger-spec/wiki) for additional and relevant information about the project.

This includes:
- Static sample tutorial.
- List of known deployments.
- Revision history.

## See it in Action

If you just want to see it work, check out the [pet store sample](http://swagger.wordnik.com).

## Additional Libraries

### Swagger-Group Projects

These are the projects that were created by the same people who authored the Swagger Specification:
- [swagger-core](https://github.com/wordnik/swagger-core) - A Swagger implementation for Java/Scala. Has integration with JAX-RS (Jersey, Resteasy, CXF...), Servlets and Play Framework.
- [swagger-js](https://github.com/wordnik/swagger-js) - A Swagger implementation for JavaScript.
- [swagger-node-express](https://github.com/wordnik/swagger-node-express) - A Swagger module for node.js with express module.
- [swagger-ui](https://github.com/wordnik/swagger-ui) - A dependency-free collection of HTML, Javascript, and CSS assets that dynamically generate beautiful documentation from a Swagger-compliant API.
- [swagger-codegen](https://github.com/wordnik/swagger-codegen) - A template-driven engine to generate client code in different languages by parsing your Swagger documentation.


### Community-Driven Language Integrations
These are third party tools generated by the Swagger community:

#### Clojure
- [octohipster](https://github.com/myfreeweb/octohipster) - A hypermedia REST HTTP API library for Clojure.
- [ring-swagger](https://github.com/metosin/ring-swagger) - Swagger implementation for Ring using Prismatic Schema for data modeling and input data coercion.

### ColdFusion / CFML
- [swagger-docs-cfml](https://github.com/webonix/swagger-docs-cfml) - create swagger docs from CFML (Railo) ReST components.

#### Go
- [go-restful](https://github.com/emicklei/go-restful) - library to build REST based Web Services using Google Go.

#### Java
- [swagger-springmvc](https://github.com/martypitt/swagger-springmvc) - integration with Spring MVC.
- [swagger4spring-web](https://github.com/wkennedy/swagger4spring-web) - integration with Spring MVC.
- [swagger-maven-plugin](https://github.com/kongchen/swagger-maven-plugin) - A maven build plugin which helps you generate API document during build phase.
- [swagger-jaxrs-doclet](https://github.com/ryankennedy/swagger-jaxrs-doclet) - A JavaDoc Doclet that can be used to generate a Swagger resource listing suitable for feeding to swagger-ui.

#### .Net
- [ServiceStack](https://github.com/ServiceStack/ServiceStack) - a high-performance .NET web services platform that simplifies the development of high-performance REST (JSON, XML, JSV, HTML, MsgPack, ProtoBuf, CSV) and WCF SOAP Web Services. Has support for [Swagger integration](https://github.com/ServiceStack/ServiceStack/wiki/Swagger-API).
- [fubumvc-swagger](https://github.com/KevM/fubumvc-swagger) - This project helps your [FubuMVC](https://github.com/DarthFubuMVC/fubumvc) web application generate API documentation via Swagger.
- [Swashbuckle](https://github.com/domaindrivendev/Swashbuckle) -  Adds some Swagger to your WebApi.
- [Swagger.Net](https://github.com/Swagger-Net/Swagger.Net) - Library to document the ASP.NET Web API using the Swagger specification.

#### Node.js
- [Swagger Framework](https://github.com/silas/swagger-framework) - a module for creating Swagger-based apis using the standard HTTP request listener interface (including Express). It supports request normalization/validation, pluggable consumes/produces, spec validation, and more.
- [swagger-jack](https://github.com/worldline/swagger-jack) - Express middleware to automatically create route and validate inputs from a swagger descriptor (for NodeJS).
- [hapi-swagger](https://github.com/glennjones/hapi-swagger) - A Swagger interface for HAPI.

#### PHP
- [Swagger-PHP](https://packagist.org/packages/zircote/swagger-php) - a library implementing the swagger.wordnik.com specification to describe web services, operations/actions and models enabling a uniform means of producing, consuming, and visualizing RESTful web services.
- [NelmioApiDocBundle](https://github.com/nelmio/NelmioApiDocBundle) - A Symphony Bundle.
- [Restler](https://github.com/Luracast/Restler) - PHP framework, swagger support in 3.0.

#### Python
- [django-rest-swagger](https://github.com/marcgibbons/django-rest-swagger) - Swagger Documentation Generator for Django REST Framework
- [django-tastypie-swagger](https://github.com/concentricsky/django-tastypie-swagger) - An adapter to use Swagger with django-tastypie.
- [flask-restful-swagger](https://github.com/rantav/flask-restful-swagger) - A Swagger spec extractor for flask-restful.

#### Ruby
- [grape-swagger](https://github.com/tim-vandecasteele/grape-swagger) - Add Swagger compliant documentation to your grape API.
- [swagger-docs](https://github.com/richhollis/swagger-docs) - Generates Swagger files for Rails APIs with a simple DSL.
- [source2swagger](https://github.com/solso/source2swagger) - Builds a swagger compliant JSON specification from annotations on the comments of your source code.

#### Scala
- [Scalatra](http://www.scalatra.org/) - see the [Swagger Guide](http://www.scalatra.org/2.2/guides/swagger.html)

### Community-Driven Tools
These are third party tools generated by the Swagger community:

- [gform-admin](https://github.com/stemey/gform-admin) - An alternative UI client for Swagger.

## Support

The following methods are available to obtain support for Swagger:

- [The Swagger Google Group](https://groups.google.com/forum/#!forum/swagger-swaggersocket) - This would normally be your first stop to get support for Swagger. Here you can find previously asked question, and ask new ones. When asking a question, please provide as much information as you can regarding the environment you use (development language, library, versions.
- The Issues tab of the respective project in GitHub. Please open feature requests and bugs here. If you're not sure you encountered a bug, or if it's a general usage question, please use the Google Group mentioned above.
- IRC! you can find us on [freenode](irc://irc.freenode.net) in the channel #Swagger. You can talk with us directly there.

Keep in mind that if you have an issue with a specific community-driven library, you may want to ask in their respective support channels.

## License

Copyright 2014 Reverb Technologies, Inc.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at [apache.org/licenses/LICENSE-2.0](http://www.apache.org/licenses/LICENSE-2.0)

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
