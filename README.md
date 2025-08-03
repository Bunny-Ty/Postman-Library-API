# Postman Library API Testing Project

A structured API testing project using **Postman** to validate the functionality of a Library Management System. This project includes a full set of test cases, test data, and request collection for various endpoints such as book retrieval, checkout, add, delete, and validation scenarios.  

## **Project Goals**  
- Verify that all API endpoints of the Library system function correctly.
- Perform both positive and negative test cases.
- Apply filtering, parameter passing, and HTTP method validations.

## **Overview**  
- Postman_Library_API.postman_collection.json
- Covered Endpoints:
#
| Method | Endpoint                   | Description                          |
|--------|----------------------------|--------------------------------------|
| GET    | `/books`                   | Get all books                        |
| GET    | `/books/:id`               | Get book by ID                       |
| GET    | `/books?checkedOut=true`   | Filter books by checked out status   |
| POST   | `/books`                   | Add a new book                       |
| PATCH  | `/books/:id/checkout`      | Checkout a book                      |
| DELETE | `/books/:id`               | Delete a book                        |  

- Test Cases:
  - Valid data submission.
  - Missing fields and validation errors.
  - Filtering using query parameters.
  - Test Cases in Notion: [Link](https://www.notion.so/2423747b546b80069075ee5b1157fd7b?v=2423747b546b80f586ee000cd9492c49&source=copy_link)

## **How to Run the Project**  
1. Open [Postman](https://www.postman.com/)
2. Import the collection: `Postman Library API v2.postman_collection.json`
3. Run each request manually or use **Collection Runner**
4. For local APIs, ensure mock server or `json-server` is running

## **Highlights**  
- Realistic API scenarios (add, fetch, delete, filter).
- Uses query parameters (`?checkedOut=false`).
- Includes validation cases for missing.
- Designed for learning and demonstration purposes.
