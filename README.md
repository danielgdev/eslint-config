# @danielgdev/eslint-config

## Usage

### Install

```bash
pnpm add -D eslint @danielgdev/eslint-config
```

### Config `.eslintrc`

```json
{
  "extends": [
    "@danielgdev"
  ]
}
```

### Config `.eslintignore`

```txt
dist
public
```

### Add script for package.json

For example:

```json
{
  "scripts": {
    "lint": "eslint \"**/*.{vue,ts,js}\""
  }
}
```

### Config VSCode auto fix

Create `.vscode/settings.json`

```json
{
  "prettier.enable": false,
  "editor.codeActionsOnSave": {
    "source.fixAll.eslint": true
  }
}
```
