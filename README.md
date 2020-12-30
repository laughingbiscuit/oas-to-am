# OpenAPI Specification to Assign Message
A simple tool to generate an Assign Message policy from a JSON OpenAPI Spec.

## Dependencies

- jq
- libxml2-utils

## Current Behaviour

Takes the OAS spec [here](./test/features/fixtures/petstore.json), parses it to
generate [this](./test/features/fixtures/expected.xml). The behaviour is described 
[here](./test/features/OASToAM.feature).

## To-do

- Provide an example of using the generated in a proxy with a ServiceCallout, SharedFlow or 
  TargetEndpoint call
- Describe the best way to handle payloads of different content types
- Improve JSON payload handling if possible
- Test more!

## Why?

- Now it is very easy to use out of the box Apigee policies to set the variables needed.
- It is also easy to take an OpenAPI spec from a tool like OpenLegacy and kickstart the integration with Apigee

## Disclaimer

This is not a Google product.

