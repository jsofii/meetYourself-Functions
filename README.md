# Azure Functions C# App

This repository contains a minimal Azure Functions project built using the .NET isolated worker model.

## Functions

- **Test**: Existing sample function that returns `Welcome to Azure Functions!`.
- **HelloWorld**: New function added as an example. It returns `Hello from Azure Functions!` when triggered via HTTP.

## Running locally

1. Install [Azure Functions Core Tools](https://learn.microsoft.com/azure/azure-functions/functions-run-local).
2. Run `func start` from the repository root to start the function host.

Both functions respond to HTTP requests and are defined in `TEst.cs` and `HelloWorld.cs` respectively.
