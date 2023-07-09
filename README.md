# Malven Co. ESLint Config for Typescript 
Malven Co. Javascript coding standards for Typescript projects using [ESLint](http://eslint.org)

---

## How to Use

```
npm i -D eslint @malven/eslint-config @malven/eslint-config-typescript @typescript-eslint/parser @typescript-eslint/eslint-plugin typescript
```

### In your global or project-specific .eslintrc

```json
// in .eslintrc

{
  "parser": "@typescript-eslint/parser",
  "extends": [
    "@malven",
    "@malven/typescript"
  ]
}
```
