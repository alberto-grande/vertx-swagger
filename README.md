# Vert.X - Swagger
This project aims to provide a code generator based on Swagger to create web server with Vert.X and Vert.X Web.
It contains 2 modules:
 - **vertx-swagger-router** : a generic Router which can be configured with a swagger definition
 - **vertx-swagger-codegen** : a library which has to be used with [Swagger Codegen Generator](https://github.com/swagger-api/swagger-codegen#swagger-code-generator)
  
 
# todo :

- Clean up
- Try to properly manage path parameters (ie. getPetById in the example fails (tries to get a JsonObject instead of a string))

## vertx-swagger-router :
 - manage the authorization part of swagger definition
 - use more data from swagger definition if possible (responses, info)
  
## vertx-swagger-codegen :
 - add the possibility to validate the request according the swagger definition
 - support other languages (Groovy, JavaScript, ruby, Ceylon)
 - generate swagger definition using swagger annotations.
  
