# kafka-schema-repository
Example project for maintaining central kafka confluent schema repository and adding CI-CD pipeline so that any change to the schema triggers registration of new schema,
checks the compatibility with current subject in confluent schema registry and also triggers maven deployment of new version jar to the required JAR repository so that other projects could reference it.
## Inspiration
https://www.confluent.io/blog/creating-data-pipeline-kafka-connect-api-architecture-operations/
