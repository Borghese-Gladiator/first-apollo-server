# First Apollo GraphQL

## Notes
Apollo is a platform for building a unified supsergraph using GraphQL. Apollo is meant to handle Authentication, Pagination, State Management
- Apollo Client - state management library to manage both local and remote data with GraphQL (fetch, cache, modify application data)
- Apollo Server - open source GraphQL server compatible with any GraphQL client like Apollo Client and has a self-documenting GraphQL API
- Apollo Studio - cloud-hosted collection of tools to measure graph's performance
- Apollo Federation - divide functionality across multiple GraphQL services into subgraphs and a GraphQL gateway (both the gateway and subgraphs are a GraphQL server).


#### Steps

#### Archive
Legacy Apollo Tutorial content
- Initialization based on [https://github.com/apollographql/fullstack-tutorial](https://github.com/apollographql/fullstack-tutorial)
  - add .gitignore
  - server
    - `npm init -y`
    - download store.sqlite
    - `npm i apollo-datasource apollo-datasource-rest dotenv apollo-server graphql isemail nodemon sequelize sqlite3`
    - `npm i -D apollo apollo-link apollo-link-http jest nock node-fetch`
  - client
    - `npx create-react-app client --template typescript`