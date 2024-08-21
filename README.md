# Postman-Newman

Automation API test with postman and newman

## Postman
Postman is a tool for interacting with APIs. Postman allows the user to automate test cases in javascript.

For API validation, upon receiving a response, Postman validates the response as described in the test scripts. This is done in the "Tests" section.

## Newman

Newman is a powerful command-line collection runner for Postman. It allows you to run and test a Postman collection directly from the command-line

We Write Tests in Postman, then export the collection and use Newman to run them directly from the command-line.
## Installation Newman


```bash
npm i newman -g
```

## Newman: how to run Postman collections from command line.

```bash
newman run -e EnviornmentName.json CollectionName.json
```

## Integración con GitHub Actions
Este proyecto utiliza GitHub Actions para automatizar las pruebas de API con Postman y Newman.
