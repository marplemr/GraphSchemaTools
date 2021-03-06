# GraphSchema GraphQL tools

GraphSchema is a tool that can run a GraphQL API from just the declarative GraphQL schema.  It serves the GraphQL API over http and uses Dgraph as a backend graph database.

GraphSchema is currently released as an early alpha in a container image in the docker hub at [mjcomp/graphschema](https://hub.docker.com/r/mjcomp/graphschema) it works with Dgraph v1.0.13.

Main features

 - Running GraphQL API directly from schema
 - Graph database backend for a graph query langauge
 - Exposes all the Dgraph query power, plus GraphQL
 - Stateless API endpoint made for containers 
 - Easily run GraphQL API replicas against a single backend DB

 Read more in the [docs](https://github.com/MichaelJCompton/GraphSchemaTools/wiki) and explore the [examples](https://github.com/MichaelJCompton/GraphSchemaTools/tree/master/GraphSchema.Examples).

 See [these notes](https://github.com/MichaelJCompton/GraphSchemaTools/wiki/Roadmap-and-Issues) about current status and future directions.  
 
 Please add issues, requests and suggestions [here](https://github.com/MichaelJCompton/GraphSchemaTools/issues).
