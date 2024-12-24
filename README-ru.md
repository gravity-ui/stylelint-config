# @gravity-ui/stylelint-config

## Установка

```
npm install --save-dev stylelint postcss @gravity-ui/stylelint-config
```

## Использование

В корне проекта создайте файл `.stylelintrc` и добавьте в него следующий код:

```json
{
  "extends": "@gravity-ui/stylelint-config"
}
```

### Prettier

При использовании инструмента Prettier дополните корневую конфигурацию следующими правилами:

```json
{
  "extends": ["@gravity-ui/stylelint-config", "@gravity-ui/stylelint-config/prettier"]
}
```

### Порядок

Для задания порядка отображения свойств в CSS-файлах дополните корневую конфигурацию следующими правилами:

```json
{
  "extends": ["@gravity-ui/stylelint-config", "@gravity-ui/stylelint-config/order"]
}
```
