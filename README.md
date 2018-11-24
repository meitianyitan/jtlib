# jtlib
Run react project by integrate webpack.

## Install

```bash
npm i jtlib -D
```

## Add `jtlib` to package.json

```json
"jtlib": {
  "entrys": [
    "docs/index.tsx"
  ],
  "dlls": [
    "react",
    "react-dom"
  ],
  "production": {
    "path": "built",
    "filename": "bundle.js"
  }
}
```

## Or add `jtlib.config.json` in root dir

```json
{
  "entrys": [
    "docs/index.tsx"
  ],
  "dlls": [
    "react",
    "react-dom"
  ]
}
```

## start dev server

```bash
jtlib develop
```

## production build

```bash
jtlib production
```

## test

```bash
jtlib test
```