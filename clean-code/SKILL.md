---
name: clean-code
description: Used to refrence a set of knowledge and skills when the agent
wanted to craft "maintainable", "reusable" and "readable" code that would
standout as high quality code.
---


# Clean Code

## General Rules
- Always try to minimize changes when you want to refactor, add feature, or change it
  - Dont overthrow a bunch of functions, most of the time reusing them would make the code more readable and predictable
- Be consistent, concider a well-defined architecture and follow them
- Try to learn the conventions, follow them and dont diverge from the code style much
  - naming, casing in each concepts like for example classes should be PascalCase


## Variables
- If a variable is not being used remove it
- If a variable is not changing convert it to a constant
- Always try to find a short, meaningful name for variables

## Functions/Methods
- If a function is not being reused and its small, dont make it a function
- Always define a simple, well-defined, reusable and general function or methods


## Configurations
- Always check the .env file and sync it with .env.template if its not
- Always validate .env file


## Refrences
- For "backend" specific code, refer to backend.md
- For "frontend" specific code, refer to backend.md
