# aspnet-core-ci-cd

[![.NET Core build](https://github.com/saravanaj/aspnet-core-ci-cd/workflows/.NET%20Core%20build/badge.svg)](https://github.com/saravanaj/aspnet-core-ci-cd/actions?query=workflow%3A%22.NET+Core+build%22)
[![Docker build & push](https://github.com/saravanaj/aspnet-core-ci-cd/workflows/Docker%20build%20&%20push/badge.svg)](https://github.com/saravanaj/aspnet-core-ci-cd/actions?query=workflow%3A%22Docker+build+%26+push%22)

Test repo to try out automated build and deployment for .NET core 5.0 apps using GH Actions

Things to do:
- [x] Build and publish assemblies to GH artifacts using `dotnet` command
- [x] Build and push Docker images to Docker Hub
- [ ] Deploy built artifact to AWS/Azure
- [ ] Deploy pushed Docker image to AWS/Azure
