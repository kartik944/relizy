# Migration guide

From @maz-ui/changelogen-monorepo 4.3.1 to relizy 0.1.0

## Environment variables

- `CHANGELOGEN_TOKENS_GITHUB` -> `RELIZY_TOKENS_GITHUB`
- `CHANGELOGEN_TOKENS_GITLAB` -> `RELIZY_TOKENS_GITLAB`

## Configuration File

- `changelog.config.ts` -> `relizy.config.ts`
- `changelog.config.js` -> `relizy.config.js`
- `changelog.config.json` -> `relizy.config.json`
- `changelog.config.yaml` -> `relizy.config.yaml`
- `changelog.config.toml` -> `relizy.config.toml`

## CLI

- `changelog` -> `relizy`
- `changelog --config changelog release` -> `relizy --config changelog release`

## Configuration Changes

### monorepo

Because Relizy is working now working with standalone packages, the `monorepo` option is not needed anymore.

If you using relizy in the some folder of your package, you don't need to specify a monorepo config.
By default relizy will use the package.json of the current folder.

### bump

#### `bump.yes`

Before the default value was `true`, now it is `false`.

### changelog

#### `changelog.includeCommitBody`

Before the default value was `false`, now it is `true`.
