# Architecture
- Try to understand the architecture and hierarchy first and then start to implement

# API Responses

- Most of them time API responses should be consistent if somewhere you have structure for returning user entity anywhere should follow this style
- input and output a API endpoint, most of the times are snake_case
- don't use hyphen in the url always follow the entity hierarchy (Good: /products/features, Bad: /product-features)

# Database
- Database models and singular and table names are plural
- Database properties should be snake_case
- Always analyze code to verify the best indexing on the models
