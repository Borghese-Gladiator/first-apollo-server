# First Apollo GraphQL

## Notes
Authentication, Pagination, State Management

#### Steps
- Initialization based on [https://github.com/apollographql/fullstack-tutorial](https://github.com/apollographql/fullstack-tutorial)
  - add .gitignore
  - server
    - `npm init -y`
    - download store.sqlite
    - `npm i apollo-datasource apollo-datasource-rest dotenv apollo-server graphql isemail nodemon sequelize sqlite3`
    - `npm i -D apollo apollo-link apollo-link-http jest nock node-fetch`
  - client
    - `npx create-react-app client --template typescript`