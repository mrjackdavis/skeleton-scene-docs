# Toast-It

*Formally known as `skeleton scene`*

`Toast It` is an app that gives people the ability to experience their data, any data, in various ways. For more on how `Toast It` works, check out the [architecture](https://github.com/mrjackdavis/scene-skeleton-docs/blob/master/architecture.md).

## Related Projects

- [Toast It API](https://github.com/mrjackdavis/skeleton-scene-api)
- [Toast It Web App](https://github.com/mrjackdavis/skeleton-scene-app-web)

## Toaster

When data is ingested by the application, it is sent to a `Toaster`. A `Toaster` will then operate on the information received from the application and create some sort of interpretation of it. This result is then returned to the user as toast. The app is designed to support multiple `Toaster`s. Currently available `Toaster`s are:

- [Snowflake](https://github.com/mrjackdavis/skeleton-scene-generator-fractal)
- [Real Toast (website toast)](https://github.com/mrjackdavis/toaster-website-toast)

A full list of generators can be [found here](https://github.com/mrjackdavis/scene-skeleton-docs/blob/master/generators.md).
