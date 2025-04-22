# Internship

COMPANY: CODTECH IT SOLUTIONS

NAME: TWINKLE GAJBHIYE

INTERN ID: CTO6WR217

DOMAIN: SOFTWARE TESTING

DURATION: 6 WEEEKS

MENTOR: NEELA SANTOSH

## Description of Task-2:

This JSON file represents a **Postman Collection**, which is used to automate API testing. It consists of multiple API requests grouped under the collection name **"D3 Codetech API Tests"**. The collection includes endpoints for user management operations such as **creating, retrieving, updating, and deleting users**.

# This collection contains four main API requests:

1. **Create User (POST Request)**
   - This request is used to create a new user in the system.
   - It requires basic authentication, using the username **"postman"** and password **"postman123"**.
   - The request sends user data in the body (JSON format) with fields like `"name": "Twinkle"` and `"email": "twinklegajbhiye@gmail.com"`.
   - The request is sent to the endpoint **https://reqres.in/api/users**.

2. **Get User (GET Request)**
   - This request fetches details of users from the API.
   - It sends a request to **https://reqres.in/api/users** without requiring authentication.
   - The response will include information about existing users stored in the API's database.

3. **Update User (PUT Request)**
   - This request updates user details such as name, email, age, and company.
   - The body contains new details for the user, such as `"age": "25"` and `"company": "codtech"`.
   - The request is sent to **https://reqres.in/api/users/1**, meaning it targets user ID **1** for an update.

4. **Delete User (DELETE Request)**
   - This request deletes a user from the system.
   - It sends a DELETE request to **https://reqres.in/api/users/1**, removing user ID **1**.

### **Additional Components**
- **Events**
  - This section includes placeholders for pre-request scripts and tests written in JavaScript. They help automate tasks before sending requests and verify responses after execution.


### **Where Can This Be Used?**
- **Automated API Testing**: Developers and testers use Postman collections to validate API functionality without manual execution.
- **Continuous Integration (CI/CD)**: This collection can be integrated into testing pipelines for automated execution.
- **Learning API Testing**: This setup is useful for understanding RESTful API operations like authentication, data retrieval, and CRUD operations.

This collection ensures efficient API testing by automating key user-related requests. 
