# BaseMind ESLint Config NextJS

This is an extensive ESLint configurations for NextJS based projects. Its compatible with ESLint >=9.

## Usage

In an ´eslint.config.mjs´ file:

```javascript
import eslintConfigBasemind from "@basemind/eslint-config-next";

export default eslintConfigBasemind;
```

Or

```javascript
import eslintConfigBasemind from "@basemind/eslint-config-next";

export default [
  ...eslintConfigBasemind,
  // other configurations below, for example:
  {
    rules: {
      "@typescript-eslint/no-unsafe-member-access": "off",
    },
  },
];
```
