# eslint-config-untile-react

Untile-flavored React ESLint config. Extends [`eslint-config-untile`](https://github.com/untile/eslint-config-untile).

## Installation

```sh
$ npm install eslint @untile/eslint-config-untile-react --save-dev
```

## Usage

Create an `.eslintrc.yml` file with the following:

```yaml
extends: @untile/eslint-config-untile-react
```

Add the following `script` to your `package.json`:

```json
{
  "scripts": {
    "lint": "eslint ."
  }
}
```

and run the linter with:

```sh
$ npm run lint
```

## Releases

Be sure to have configured `GITHUB_TOKEN` in your globals.

```bash
npm version [<new version> | major | minor | patch] -m "Release %s"
git push origin master && git push --tags
```
