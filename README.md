# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript and enable type-aware lint rules. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.
Setup instructions:
1. create a virtual env
2. create requirements.txt
3. install dependencies
4. add a main.py, database.py, models.py, schemas.py
5. go to render and create a postgresql database
6. add database to database.py
7. upload your fastAPI to github
8. add database variable
9. deploy your github repository to render
10. copy render link and put into vite
11. push vite to github
12. type command npm run build and npm run deploy
13. go to settings, then pages, then click your link and copy
14. paste to your origins in main.py
15. update your fastAPI github
    
List of API Endpoints:
1. Get all todos

Method: GET

Endpoint: /todos/

Description: Retrieves a list of all todo items.

2. Create a new todo

Method: POST

Endpoint: /todos/

Description: Adds a new todo item.

3. Get a specific todo by ID

Method: GET

Endpoint: /todos/<id>/

Description: Retrieves details of a specific todo item.

4. Update a specific todo by ID

Method: PUT

Endpoint: /todos/<id>/

Description: Updates an existing todo item.

5. Delete a specific todo by ID

Method: DELETE

Endpoint: /todos/<id>/

Description: Deletes a specific todo item.
