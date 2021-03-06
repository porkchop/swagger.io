##Swagger Codegen

The Swagger codegen project allows generation of both client libraries and server stubs from a Swagger definition. Once you've read through the below please head over to [GitHub](https://github.com/swagger-api/swagger-codegen/tree/develop_2.0) to get the latest sources.

### Prerequisites
You need the following installed and available in your $PATH:

* [Java 7](http://java.oracle.com)

* [Apache maven 3.0.3 or greater](http://maven.apache.org/)

After cloning the project, you can build it from source with this command:

```
mvn package
```

Note!  The templates are included in the library generated.  If you want to modify the templates, you'll need to either repackage the library OR specify a path to your scripts

## Samples, Getting Started, etc

Head over to the [GitHub page](https://github.com/swagger-api/swagger-codegen/blob/master/README.md) for detailed documentation for now.

## Compatibility
The Swagger Specification has undergone several revisions since initial creation in 2010.  The swagger-codegen project has the following compatibilies with the swagger specification:


Swagger Codegen Version    | Release Date | OpenAPI Spec compatibility | Notes
-------------------------- | ------------ | -------------------------- | -----
2.3.0 (upcoming minor release) | TBD   | 1.0, 1.1, 1.2, 2.0   | Minor release with breaking changes
2.2.2 (upcoming patch release) | TBD   | 1.0, 1.1, 1.2, 2.0   | Patch release (without breaking changes)
2.2.1 (**current stable**) | 2016-08-07   | 1.0, 1.1, 1.2, 2.0   | [tag v2.2.1](https://github.com/swagger-api/swagger-codegen/tree/v2.2.1)
2.1.6 | 2016-04-06   | 1.0, 1.1, 1.2, 2.0   | [tag v2.1.6](https://github.com/swagger-api/swagger-codegen/tree/v2.1.6)
2.0.17                     | 2014-08-22   | 1.1, 1.2             | [tag v2.0.17](https://github.com/swagger-api/swagger-codegen/tree/v2.0.17)
1.0.4                      | 2012-04-12   | 1.0, 1.1             | [tag v1.0.4](https://github.com/swagger-api/swagger-codegen/tree/swagger-codegen_2.9.1-1.1)



