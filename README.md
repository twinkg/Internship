API TESTING WITH POSTMAN
-------------------------------
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

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## This specific collection, named "GitHub", focuses on retrieving all repositories for a user via the GitHub API
---

1. **Collection ID and Name**:
   - The `"name"` field specifies that this collection is named **"GitHub"**.
   - The `_postman_id` is a unique identifier assigned to this collection within Postman.

### **API Request (`item`)**
This collection contains one API request titled **"Get All Repositories"**. It demonstrates how to retrieve all repositories associated with a GitHub user.

#### **Request Details**
1. **Authentication**:
   - The `"auth"` field specifies **Bearer Token Authentication**, which is a common way to access GitHub's API securely.
   - The `"bearer"` object contains the token required for authenticating requests. Tokens provide secure access and must be kept private.

2. **HTTP Method**:
   - The `"method"` is `"GET"`, meaning it fetches data from the server (in this case, the list of repositories).

3. **Headers**:
   - The `"header"` array is empty, indicating that no additional headers (besides the token) are included in the request.

4. **Body**:
   - The `"body"` contains a raw JSON object, `{ "name": "D3 Codetech Bearer Token" }` it may serve for reference or metadata.

5. **URL**:
   - The request targets the URL **`https://api.github.com/users/repos`**.
   - The `"protocol"` is `"https"`, ensuring secure communication.
   - The `"path"` array breaks the endpoint into components: `users` and `repos`.


### **Purpose of the Collection**
This Postman collection allows developers to:
1. Test GitHub’s API for retrieving repositories.
2. Understand and validate token-based authentication with a Bearer Token.
3. Simulate API calls and gather data for debugging or performance testing.

---

### **Where to Use**
1. **Postman**:
   - Import the collection into the Postman app or web interface to execute and debug the request.
2. **GitHub Integrations**:
   - Use the collection for CI/CD pipelines that rely on GitHub repositories.
3. **Team Collaboration**:
   - Share the collection via the `_collection_link` to enable seamless testing across development teams.

This collection demonstrates how to interact with GitHub’s API using secure authentication and a GET request.


