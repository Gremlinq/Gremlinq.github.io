# Getting started with the `dotnet new` template

Install the Gremlinq templates package:

```sh
> dotnet new install ExRam.Gremlinq.Templates
```

There are two `dotnet new` templates included in the package: one for a simple console app and one that shows how to get things running on Asp.NET Core. Currently, there is out-of-the-box support for the generic Gremlin Server, AWS Neptune, Azure CosmosDb and JanusGraph.

Depending on the desired project type and provider, use `dotnet new` to create a new project:

=== "Console"

    === "Gremlin Server"

        ``` bat
        dotnet new gremlinq-console --name GettingStartedWithGremlinq --provider GremlinServer
        ```

    === "AWS Neptune"

        ``` sh
        dotnet new gremlinq-console --name GettingStartedWithGremlinq --provider Neptune
        ```

    === "Azure CosmosDb"

        ``` sh
        dotnet new gremlinq-console --name GettingStartedWithGremlinq --provider CosmosDb
        ```
  
    === "JanusGraph"

        ``` sh
        dotnet new gremlinq-console --name GettingStartedWithGremlinq --provider JanusGraph
        ```

=== "Asp.NET Core"

    === "Gremlin Server"

        ``` sh
        dotnet new gremlinq-aspnet --name GettingStartedWithGremlinq --provider GremlinServer
        ```

    === "AWS Neptune"

        ``` sh
        dotnet new gremlinq-aspnet --name GettingStartedWithGremlinq --provider Neptune
        ```

    === "Azure CosmosDb"

        ``` sh
        dotnet new gremlinq-aspnet --name GettingStartedWithGremlinq --provider CosmosDb
        ```
  
    === "JanusGraph"

        ``` sh
        dotnet new gremlinq-aspnet --name GettingStartedWithGremlinq --provider JanusGraph
        ```

## Getting started with the `dotnet new` template
