# @yandex-cloud/stylelint-config

> ⚠️ Repository moved to @gravity-ui/stylelint-config

## Install
```
$ npm install --save-dev stylelint postcss @yandex-cloud/stylelint-config
```

## Usage
Add `.stylelintrc` file in the project root with the following content:

```json
{
    "extends": "@yandex-cloud/stylelint-config"
}
```

### Prettier
If you are using Prettier, extend root config with the additional rules:

```json
{
    "extends": ["@yandex-cloud/stylelint-config", "@yandex-cloud/stylelint-config/prettier"]
}
```

### Order
If you want to order properties in your css files, extend root config with the additional rules:

```json
{
    "extends": ["@yandex-cloud/stylelint-config", "@yandex-cloud/stylelint-config/order"]
}
```
