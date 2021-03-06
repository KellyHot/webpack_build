#Test Repository

## INSTALLATION

Для запуска проекта необходимо:

- Установить [node.js](https://nodejs.org/en/).

- Открыть консоль/терминал от имени администратора, перейти в папку с проектом и выполнить команду установки нужных пакетов/библиотек (npm install);
    ```sh
    $ npm install
    ```

- Выполнять команду, после чего сайт автоматические откроется в вашем браузере;
    ```sh
    $ npm run dev
    ```

- Сборка проекта;
    ```sh
    $ npm run build
    ```

## TEST

Чтобы не возникло казусов, перед отправкой убедитесь, что все тесты проходят без ошибок.

- Проверка JavaScript с помощью eslint и правилами от Airbnb;
    ```sh
    $ npm run eslint
    ```

- Проверка Styles с помощью stylelint и правилами от Webstandards&htmlacademy;
    ```sh
    $ npm run stylelint
    ```

- Проверка Template с помощью puglint и собсвенныеми правилами основываясь на докментиции pug и логики;
    ```sh
    $ npm run puglint
    ```
