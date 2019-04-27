# aws-cloudformation-pipeline-resources
CloudFormation templates for deployment with CodePipeline

# Description
The CodePipeline allow to deploy CloudFromation stack of resources that are located in resources.yml of this repository.

# Deployment
Just use CloudFromation AWS service UI or aws-cli to deploy `git-pipeline.yml`.
It requires some Git parameters such as `GitHubOAuthToken`, `GitHubSecret` and `RepositoryName`.
After CF stack is created it will be triggered by any Git push into master branch.
