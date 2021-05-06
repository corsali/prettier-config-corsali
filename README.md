# @corsali/prettier-config

Corsali prettier config.

## Usage

1. Add the package to dev dependencies:

```sh
$ npm i -D @corsali/prettier-config
```

2. Add a `prettier` entry to `package.json`

```json
# package.json

{
  ...
  "prettier": "@corsali/prettier-config"
  ...
}
```

## Development

1. In this repository:

   1. `npm link` (may need to be run as root).
   2. Update version in `package.json`.

2. In another project where the rule is used:
   1. `npm link @corsali/prettier-config`.
   2. Update the installed version in `package.json`.
