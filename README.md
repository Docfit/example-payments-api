# Example Payments API

A small refunds API used to show [DocFit](https://docfit.dev) at work. The code and its OpenAPI file live here; the docs live in a separate repository, [Docfit/example-payments-docs](https://github.com/Docfit/example-payments-docs).

When a pull request merges here, DocFit reads the change, updates the docs pages that are now wrong, builds and checks them, and opens a docs pull request in the docs repository, linked from the merged pull request.

## Layout

- `src/api/refunds/`: create, get, list and cancel refunds
- `src/webhooks/`: the refund webhook event
- `openapi/spec.yaml`: the OpenAPI description
