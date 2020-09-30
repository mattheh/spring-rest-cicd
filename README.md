# Tekton Pipeline for Sample Spring Boot Application

A _build template_ is provided at `.template/build.yml` that defines resources required to build the app. Includes:
* A `ServiceAccount`
* Multiple `ImageStream`
* Multiple `BuildConfig` for the build step in different environments