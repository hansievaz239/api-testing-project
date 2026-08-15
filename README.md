# api-testing-project
# API Testing Project — JSONPlaceholder

Automated API test suite built with Postman and Newman, covering status codes, 
response schema validation, and CRUD operations against a public REST API 
(JSONPlaceholder). Integrated into a GitHub Actions CI pipeline so tests run 
automatically on every push.

## Tests covered
- GET request returns 200 and expected response fields
- GET request for a non-existent resource returns 404
- POST request creates a resource and returns 201

## Tech stack
- Postman (test design)
- Newman (CLI test runner)
- GitHub Actions (CI automation)

## Run locally
\`\`\`
npm install -g newman
newman run collection.json
\`\`\`
