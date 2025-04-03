# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript and enable type-aware lint rules. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.

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
