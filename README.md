# Rick and Morty API

## Setup

Mock data is in src/data/characters.json.

## Objectives

1. Create a characters module, controller, and service

2. Implement endpoints

- GET /characters → return all characters from the JSON file.
- GET /characters/:id → return one character by ID.
- PATCH /characters/:id → update an existing character in the JSON file (Update a character "status" to "Alive").

### Bonus (if time allows)

- POST /characters → create a new character.
- DELETE /characters/:id → delete a character.

### Notes

- Return proper HTTP status codes (200, 404, etc.).
- Use fs to read/write the JSON file.
