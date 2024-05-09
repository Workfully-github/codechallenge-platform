# Infrastucture as Code Challenge

Using [AWS CDK](https://www.npmjs.com/package/aws-cdk) for typescipt, provide an ECS cloud infrastructure to publish an API.

## Considerations
* The API is located on a Elastic Container Registry
* Our internal CI pipeline dockerizes and populates the ECR with new releases
* API needs to serve requests from anywhere on the internet using https
* API will be serving around 200 requests per minute 24/7
* The infrastructure must provide a MariaDB (the API will hadle tables creation)

  

  | :memo: | We understand that all decisions in Engineering are tradeoffs, so please include a readme with your decision-making process. |
  |--------|:-----------------------------------------------------------------------------------------------------------------------------|
