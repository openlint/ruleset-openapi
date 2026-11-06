# OpenLint OpenAPI ruleset

Ruleset package for OpenAPI (v3.2-v2.0) documents.

Install the package and extend it directly:

```sh
npm install --save-dev @openlint/ruleset-openapi
```

```yaml
extends: "@openlint/ruleset-openapi"
```

This ruleset is based on `spectral:oas` for compatibility, but removes the following rules that had more to do with vendor-specific requirements than OpenAPI compatibility:

- `contact-properties`
- `info-contact`
- `info-description`
- `info-license`
- `license-url`
- `openapi-tags-alphabetical`
- `operation-singular-tag`
- `operation-tags`
- `tag-description`

These can be found in [@openlint/ruleset-documentation](https://github.com/openlint/ruleset-documentation) instead.
