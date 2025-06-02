# qa-api-tests

This project contains API test cases for the Swagger Petstore API (https://petstore.swagger.io), focusing on functional testing of the pet-related endpoints.

## 🔍 Project Goal
To validate the correctness of key API endpoints through automated tests using Postman.

## 🧪 What’s Covered

- `POST /https://api-dev.easyfin
- `GET /https://api-dev.easyfin/{Id}
- `PUT /https://api-dev.easyfin
- `DELETE /https://api-dev.easyfin
- `PATCH /https://api-dev.easyfin

- Negative test cases (404, 400 responses)
- Status code & body assertions

## 🛠 Tools & Tech Stack

- [✅] Postman (with Tests tab scripts)
- [✅] Newman (for CLI execution)
  

## 🚀 How to Run (if using Postman + Newman)

1. Install Newman:
   ```bash
   npm install -g newman
