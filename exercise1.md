What are the common tools of linting, testing and building for C#?
Linting: StyleCop, Roslyn Analyzers
Testing: xUnit, NUnit
Building: MSBuild, dotnet CLI

What alternatives are there to set up the CI besides Jenkins and GitHub Actions?
Azure DevOps Pipelines
CircleCI
GitLab CI/CD

Would this setup be better in a self-hosted or a cloud-based environment? Why? What information would you need to make that decision?
We may consider the following factors when deciding which solution is more suited, such as cost, scalability, security, and customization. A cloud-based environment may cost less because it's pay-per-use, and there is no upfront cost for the infrastructure. This might change at scale. A cloud-based environment is also easier to scale. It can scale the service behind the scenes with some simple configurations from us. 
Self-hosted environment wins in security. We have full control of the data and infrastructure, so we can be ensured that the data is isolated. However the argument is getting weaker over the year, since more top-secret organizations such as government agencies are adapting cloud solutions. Self-hosted environment is also better at customization. It's easier to add modifications to the environment since we have full access to the software and infrastructure.
