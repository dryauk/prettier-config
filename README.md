# @dryauk/prettier-config

[Prettier](https://prettier.io/) shareable config.

## Install

```bash
yarn add -D @dryauk/prettier-config
```

## Usage

The shareable config can be configured in your `package.json`.

```json
{
  "prettier": "@dryauk/prettier-config"
}
```

If you don’t want to use `package.json`, you can use any of the [supported extensions](https://prettier.io/docs/en/configuration.html) to export a string, e.g. `.prettierrc`:

```json
"@company/prettier-config"
```
