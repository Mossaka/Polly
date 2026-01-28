---
name: Build and Test Polly
on:
  workflow_dispatch:
permissions:
  contents: read
  issues: read
  pull-requests: read
engine: copilot
runtimes:
  dotnet:
    version: "8.0"
---

# Build and Test Polly

You are a C# developer. Your task is to build and test the Polly resilience library.

## Steps

1. First, explore the repository structure to understand the project layout
2. Restore NuGet packages using `dotnet restore`
3. Build the solution using `dotnet build`
4. Run the tests using `dotnet test`
5. Report the results of the build and test

If any step fails, investigate the error and try to resolve it.
