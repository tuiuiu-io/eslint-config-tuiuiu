# eslint-config-tuiuiu

The package provides tuiuiu's .eslintrc as an extensible shared config.

## Usage

Our default export contains all of our ESLint rules, including Airbnb's config 
(which has ECMAScript 6 and React). It requires `eslint`, 
`eslint-plugin-import`, `eslint-plugin-react`, and `eslint-plugin-jsx-a11y`.

1. Run `npm install eslint eslint-config-tuiuiu eslint-plugin-import eslint-plugin-react eslint-plugin-jsx-a11y --save-dev`
2. Add `"extends": "tuiuiu"` to your `.eslintrc`
