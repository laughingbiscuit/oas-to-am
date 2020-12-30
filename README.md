# OpenAPI Specification to Service Callout

A simple tool to generate a service callout policy from a JSON OpenAPI Spec.

## Dependencies

- jq
- libxml2

## Current Behaviour

Takes the OAS spec [here](./test/features/fixtures/petstore.json), parses it to
generate [this](./test/features/fixtures/expected.xml). The behaviour is described 
[here](./test/features/OASToAM.feature).

## To-do

- Provide an example of using the generated in a proxy with a ServiceCallout, SharedFlow or 
  TargetEndpoint call
- Describe the best way to handle payloads of different content types
- Test more!

## Disclaimer

This is not a Google product.

