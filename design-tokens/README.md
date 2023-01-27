# Compound Design Tokens

Home to the design tokens.

## Supported platforms

| Platform   | Themes                     | Support |
| ---------- | -------------------------- | ------- |
| CSS        | Light, dark, high contrast | ✅      |
| JavaScript | Light, dark, high contrast | ✅      |
| iOS        |                            | 🚧      |
| Android    |                            | 🚧      |

## Development

The tokens are defined under the `tokens/` folder and are synced from [tokens.studio](https://tokens.studio/).
They are then transformed to the supported platforms using [Style Dictionary](https://amzn.github.io/style-dictionary/).

All consumable tokens are generated under `assets/`. Generate them by running

```
yarn build
```
