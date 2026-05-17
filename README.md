# QA Postman HapifyMe

Postman homework for the HapifyMe HTTP API user lifecycle flow.

## Deliverables

- `Tema 18 - Radu.postman_collection.json`
- `HapifyMe Tema Env.postman_environment.json`

## Covered Flow

- Register a dynamic user with a generated email.
- Save generated data and API values in the environment.
- Login with the registered account and store the JWT token and user ID.
- Retrieve the user profile and validate that the response email matches the generated email.
- Delete the user profile using the Bearer token from login.

## How to Run

1. Import the collection into Postman.
2. Import the environment into Postman.
3. Select `HapifyMe Tema Env`.
4. Run the full `Tema 18 - Radu` collection in order.

The environment uses the required homework value for `baseUrl`:

```text
https://test.hapifyme.com/api
```

The collection scripts generate runtime values automatically, so no real sensitive data is stored in the exported environment.
