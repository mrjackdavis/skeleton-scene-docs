# Skeleton Scene

Skeleton scene is an app that gives people the ability to experience their data, any data, in various ways. For more on how Skeleton Scene works, check out the [architecture](https://github.com/mrjackdavis/scene-skeleton-docs/blob/master/architecture.md).

## Related Projects

- [Skeleton Scene API](https://github.com/mrjackdavis/skeleton-scene-api)
- [Skeleton Scene Web App](https://github.com/mrjackdavis/skeleton-scene-app-web)

## Generators

When data is ingested by the application, it is sent to a **Generator**. A generator will then operate on the information received from the application and create some sort of interpretation of it. This result is then returned to the user. The app is designed to support multiple generators. Currently available generators are:

- [Snowflake](https://github.com/mrjackdavis/skeleton-scene-generator-fractal)

A full list of generators can be [found here](https://github.com/mrjackdavis/scene-skeleton-docs/blob/master/generators.md).
