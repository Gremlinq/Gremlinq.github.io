# From a `dotnet new` template

Install the Gremlinq templates package:

```sh
> dotnet new install ExRam.Gremlinq.Templates
```

There are two `dotnet new` templates included in the package: one for a simple console app and one that shows how to get things running on Asp.NET Core. Currently, there is out-of-the-box support for the generic Gremlin Server, AWS Neptune, Azure CosmosDb and JanusGraph.

Depending on the desired project type and provider, use `dotnet new` to create a new project:

=== "Console"

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

    === "Gremlin Server"

        ``` bat
        dotnet new gremlinq-console --name GettingStartedWithGremlinq --provider GremlinServer
        ```

=== "ASP.NET Core"

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

    === "Gremlin Server"

        ``` sh
        dotnet new gremlinq-aspnet --name GettingStartedWithGremlinq --provider GremlinServer
        ```

