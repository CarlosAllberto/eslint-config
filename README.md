# ESLint config

## Whats included?

- Standard config base;
- React plugin;
- React Hooks plugin;
- JSX a11y plugin;
- Prettier;

## Setup

### React (with Next.js)

Install dependencies:
```
npm i -D eslint eslint-config-carlosallberto
```
Inside `.eslintrc.json`
```
{
  "extends": [
    "eslint-config-carlosallberto/next", 
    "next/core-web-vitals"
  ]
}
```

### React (without Next.js)

Install dependencies:
```
npm i -D eslint eslint-config-carlosallberto
```
Inside `.eslintrc.json`
```
{
  "extends": "eslint-config-carlosallberto/react"
}
```

### Node.js

Install dependencies:
```
npm i -D eslint eslint-config-carlosallberto
```
Inside `.eslintrc.json`
```
{
  "extends": "eslint-config-carlosallberto/node"
}
```
