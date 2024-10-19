# GRAPHQL-AUTO
This tool auto generates graphql docs based on user specific github workflow
## REQUIREMENTS

[Github token requirements](REQUIRED.png)

### USAGE

- Make sure you have a setup similar to this
- You can modify the github workflow in `.github/workflows/generate-docs.yml` (ex: choose what branch to trigger the workflow ...etc)
- Obviously ensure that your schema is correct
- This requires NOT using the `gql` template literal for schema definition (package is deprecated)
- 
  [Example](./graphql/typeDefs/Entity1.ts)
