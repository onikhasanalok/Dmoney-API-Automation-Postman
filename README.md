# Dmoney API Postman Collection

This repository contains the Postman collection for **Dmoney API**, covering user authentication, management, and other operations.

## Requirements

- [Postman](https://www.postman.com/downloads/)
- Dmoney API base URL and authentication tokens

## Installation

1. Clone the repo:

    ```bash
    git clone https://github.com/yourusername/dmoney-postman-collection.git
    ```

2. Import the `DmoneyCollection.json` into Postman.

## Usage

1. **Login** to generate a token.
2. Use the token in subsequent requests for user operations.

### Key Endpoints:

- **Login**: Correct/incorrect credentials tested.
- **User List**: Retrieves all users (`200 OK`).
- **Create User**: Creates a user with random credentials (`201 Created`).
- **Search User**: Finds a user by ID (`200 OK` or `404`).
- **Update/Delete User**: Modifies or deletes users (`200 OK`).

### Variables:

- `baseUrl`, `token`, `partnerkey`, `UserId`, `UserPhoneNumber`.

## Testing

Built-in tests for status codes and response validation (e.g., "Login successful", "User created").

## There is a Snapshort of newman (Dmoney API) ![DmoneyUsersSnapShot](https://github.com/user-attachments/assets/c8a9d484-7304-46a0-9e17-32b6e48f816c)
