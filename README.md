# api-first-restaurant

This project generates spring-boot code from swagger using the swagger yaml under restaurant-app\src\main\resources
The spring-boot code gets generated under - restaurant-app\target\generated-sources\swagger\src\main

The swagger.yaml can be replaced for generating code

For generating the typescript-axios code for react/angular SPA front endfrom swagger yaml:
npm install @openapitools/openapi-generator-cli -g
npx @openapitools/openapi-generator-cli generate -i ./restaurant-app/src/main/resources/swagger.yaml -g  typescript-axios -o ./generated
