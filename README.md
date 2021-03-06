# Backend Guidelines
- [Backend Guidelines](#backend-guidelines)
- [Technologies used](#technologies-used)
- [Naming conventions](#naming-conventions)
- [Folder structure](#folder-structure)
- [Don't repeat yourself (DRY)](#dont-repeat-yourself-dry)
- [Creating test case](#creating-test-case)
    - [This is required on every functionalities you will create.](#this-is-required-on-every-functionalities-you-will-create)
- [General rules](#general-rules)
- [Reference to improve your skills](#reference-to-improve-your-skills)
# Technologies used
- [Node js ](https://nodejs.org/en/)
- [Hapi js backend framework](https://hapi.dev/)
- [Jest for unit testing](https://jestjs.io/docs/en/getting-started)
- [mongoDB for database](https://www.mongodb.com/)
- [JOI for validation](https://hapi.dev/module/joi/)
- [mongoose](https://mongoosejs.com/)
# Naming conventions
| What | How | Implementation | Location | Other name rule |
| ----------- | ----------- | ----------- | ----------- | ----------- |
| Variable declaration | camelCase | - | - | the use of const and let should be strictly implemented for ES6 standard, variable should be understandable on it's purpose.|
|Function Declaration| camelCase | - | - | Functions that is created should be understandable on it's purpose and it should have maximum of 3 parameters and should only do one job for code reusability and so that it can be debug easily.
# Folder structure
- **app** (The whole application is stored on this folder)
- **controllers** (Controllers has the function for endpoints declared on the routes folder)
- **helpers** (Business logic of the application)
- **routes** (Endpoints for the REST API)
- **test** (This folder will have all the test of the functionalities created in the Application)
- **models** (Models for mongodb database)
# Don't repeat yourself (DRY)
functions inside libraries should have one purpose and responsibility, to lessen bugs and so that we can easily debug the code without affecting other parts of the app.
# Creating test case
### This is required on every functionalities you will create.
For every function you create it should have a test created first.
Example. If you create a function that adds two numbers. The function needs to have a corresponding test. You can check how to create test cases on this [link](https://jestjs.io/docs/en/getting-started)

# General rules

- Proper indentions of (2 spaces)
- Proper singular/plural naming
- Remove unused codes like variables, deprecated functions etc.
- Add comments that describes the functionalites of component or functions you will create.
- File/class names should be DESCRIPTIVE
- Method names should be DESCRIPTIVE
- DO NOT put logical codes inside controllers. Create libraries and actions for specific task in your code.
- Make sure that the next person that will read your code can understand it without you asking.

# Reference to improve your skills
- [Clean code](https://www.youtube.com/watch?v=RR_dQ4sBSBM)
- [Jest unit testing](https://www.youtube.com/watch?v=7r4xVDI2vho&t=1196s)
- [Using Clean Architecture for Microservice APIs in Node.js with MongoDB ](https://www.youtube.com/watch?v=CnailTcJV_U)
- [The Ultimate Coding Workflow](https://www.youtube.com/watch?v=nK3LP-pn_08)