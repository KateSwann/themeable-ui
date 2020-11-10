# Uikit

## Установка
```
npm install --save themeable-ui
```

## Подключение стилей для использования тем в проектах на vue.js:
1. Импортируйте пакет в файле `App.vue` в блоке стилей:

   ```html
   <style lang="scss">
    @import 'themeable-ui';
    ...
   ```

2. В директории `frontend/src/styles/` в файле `index.scss` самой верхней строчкой импортируйте файл с палеткой доступных цветов:
    ```css
    @import 'themeable-ui/src/styles/palette.scss';
    ```
