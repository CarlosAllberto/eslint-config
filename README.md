# Configuração ESLint baseado na rocketseat

## Whats included?

- Standard config base;
- React plugin;
- React Hooks plugin;
- JSX a11y plugin;
- Prettier;

## Setup
Install dependencies:
```
npm i -D eslint @carlosallberto/eslint-config
```

### React (with Next.js)

Inside `.eslintrc.json`
```
{
  "extends": [
    "@carlosallberto/eslint-config/next", 
    "next/core-web-vitals"
  ]
}
```

### React (without Next.js)

Inside `.eslintrc.json`
```
{
  "extends": "@carlosallberto/eslint-config/react"
}
```

### Node.js

Inside `.eslintrc.json`
```
{
  "extends": "@carlosallberto/eslint-config/node"
}
```
