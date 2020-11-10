# Uikit

## Установка
```
npm install git+ssh://git@git.webestudio.ru:7999/tm/uikit.git 
```

## Подключение стилей для использования тем в проектах на vue.js:
1. Импортируйте пакет в файле `App.vue` в блоке стилей:

   ```html
   <style lang="scss">
    @import 'uikit';
    ...
   ```

2. В директории `frontend/src/styles/` в файле `index.scss` самой верхней строчкой импортируйте файл с палеткой доступных цветов:
    ```css
    @import '../../node_modules/uikit/src/styles/palette.scss';
    ```
