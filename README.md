# Bootstrap TypeScript

Use for default TypeScript projects

## Init project

```
yarn init -y
```

## Add some dev dependencies

```
yarn add -D typescript jest ts-jest @types/node @types/jest
```

## Add to the package.json

```json
"scripts": {
    "start": "tsc && node dist/index.js",
    "test": "jest"
}
```