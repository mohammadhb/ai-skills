# Architecture
- Try to understand the architecture and hierarchy first and then start to implement

# API Requests/Responses

- Most of them time API responses should be consistent if somewhere you have structure for returning user entity anywhere should follow this style
- input and output a API endpoint, most of the times are snake_case
- don't use hyphen in the url always follow the entity hierarchy (Good: /products/features, Bad: /product-features)
- Always have a well-defined type for responses and reuse them across project ( for typescript )
- Have a DTO for entities
- Always define a validation for each endpoints
- Always concider having filtering, sorting and pagination defined and reused across the project
- Avoid implementing business logic in the controller always define them in services
- Have an eye for single responsibilty principle which is simply leave a simple task for each function and reuse them across

# Database
- Database models and singular and table names are plural
- Database properties should be snake_case
- Always analyze code to verify the best indexing on the models
