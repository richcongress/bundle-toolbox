# Changelog

## 1.1.1

- Remove useless dependencies, that could produce some Composer issues.
- Move from Travis to Github Actions

## 1.1.0

- Add `AbstractCompilerPass::checkMandatoryServices` to quickly checks if the services listed in th e`MANDATORY_SERVICES` constant exists in the container.
- Add `AbstractConfiguration::getKey` and `AbstractConfiguration::get` to easily retrieve a configuration. It allows also more traceability of the configuration usage.

## 1.0.0

- Add `AbstractCompilerPass`
- Add `AbstractConfiguration`
- Add `AbstractExtension`
- Add `AbstractBundle`
