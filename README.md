# Integrating Nuxt Into a Build Pipeline

This project accompaninies a [blog post](https://formcake.com/blog/using-nuxt-in-a-build-pipeline) about properly integrating Nuxt into a production build pipline written by [Formcake](https://formcake.com/).

## Generate Without Proper Failure

`nuxt build --target static && nuxt export`

## Generate With Proper Failure

`nuxt build --target static && nuxt export --fail-on-error`

