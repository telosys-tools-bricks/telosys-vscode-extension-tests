# python-web-rest-bottle

Telosys templates for Python REST web application based on **Bottle framework**.

This bundle provides templates to generate a REST controller for each entity with the associated JSON serializer/deserializer.

To launch the server after code generation, run "app_rest.py"

## Variables : 

This bundle requires the following variables :
- REST_URL_ROOT
- REST_API_ROOT

Example :   
- `ProjectVariable.REST_URL_ROOT=http://localhost:3000 `  
- `ProjectVariable.REST_API_ROOT=/api/v1  `  

## Dependencies : 

This bundle requires the following bundle(s)  :
- **python-persistence-sqlalchemy** (for persistence) : https://github.com/telosys-templates-v3/python-persistence-sqlalchemy
