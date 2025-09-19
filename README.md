# API Documentation with Redocly

This project contains API documentation built with Redocly, with a global `simpleObject` schema used across all endpoints.

## Schema Structure

The `simpleObject` schema contains:
- `readOnly`: A string field marked as read-only
- `writeOnly`: A string field marked as write-only

This schema is used in:
1. API POST endpoint request/response
2. Webhook POST endpoint request/response  
3. API callback POST endpoint request/response

## Instructions

Run the following commands to install dependencies and build the project:
```
yarn install
yarn build
```

Open the generated html file in your browser to view the API documentation.