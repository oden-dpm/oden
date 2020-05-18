# 🍢 Oden
## Deno Package Manager

Oden is a package manager for the Deno runtime.

## Goals for first POC
- Read dependencies from json configuration in `odenfile` 
- Download dependencies to `vendor` directory
- Create an import map in `vendor/imports.json` for vendored dependencies
- Create locked dependencies tree in `odenlockfile`
- Read application entrypoint and allowed functionality from `odenfile` or `odenlockfile`
- Provide command to run application using configured entrypoint and allowed functionality, using the generated `vendor/imports.json` file
