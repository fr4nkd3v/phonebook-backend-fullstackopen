# Phonebook Backend - Full Stack Open Course

![fullstackopen banner](https://fullstackopen.com/static/EYE_green_wide-0a72f74a959f54d0f3e4bb8c67f6f158.jpg)

🔰 **Phonebook Backend for Full Stack Open course**

The Phonebook Backend project is part of the proposal exercises in Part 3 of the course [Full Stack Open](https://fullstackopen.com/) (Exercises 3.10., 3.11.).

This exercise consists of deploying the backend of the agenda to the Internet, in this case I used Render to host the project in the cloud, so I created this repository exclusively for this exercise, since Render needs the project to be in the root of the repository to deploy it correctly.

Below is a list of the App frontend and available endpoints:

- App Frontend url: <https://phonebook-backend-c66y.onrender.com>
- Endpoints:
  - Data detail: GET <https://phonebook-backend-c66y.onrender.com/info>
  - Get all persons: GET <https://phonebook-backend-c66y.onrender.com/api/persons>
  - Get on person by id: GET [https://phonebook-backend-c66y.onrender.com/api/persons/:id](https://phonebook-backend-c66y.onrender.com/api/persons/1)
  - Add person: POST <https://phonebook-backend-c66y.onrender.com/api/persons>
  - Delete person by id: DELETE <https://phonebook-backend-c66y.onrender.com/api/persons/:id>

## 🚀 Local Deploy

Execute this commands in root directory:

```bash
npm install
npm run dev
```
