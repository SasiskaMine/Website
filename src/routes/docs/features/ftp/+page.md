---
title: Connect to FTP servers
---
 ENG:
Files comes equipped with robust support for connecting to remote FTP and FTPS servers. This feature allows you to seamlessly access any compatible server, explore its directory structure, and perform tasks such as editing, renaming, and deleting files or folders as needed.

## Establishing a connection with FTP servers

To connect to remote servers, use the address bar by entering specific paths. Here's how:

### FTP

Enter the following in the address bar: `ftp://<server_address>:<port>`. For example, if your server address is `ftp.example.com` and you're using the default port, enter `ftp://ftp.example.com:21`. If you don't specify a port, it defaults to port 21.

### FTPS

For a secure connection using FTPS, use this format: `ftps://<server_address>:<port>`. For example, if your server address is `ftps.example.com` and you're using the default port, enter `ftps://ftps.example.com:990`. If you don't specify a port, it defaults to port 990.

When required, Files will prompt you to enter your credentials (username and password) to log in securely.

## Disconnecting from FTP servers

Disconnecting is straightforward: simply close the tab or window, and you'll automatically be disconnected from the server.

## Limitations to be aware of

- **Note:** SFTP is not currently supported.
  RUS:
  Подключение к FTP-серверам

Программа Files предоставляет мощную поддержку для подключения к удалённым FTP- и FTPS-серверам. Эта функция позволяет вам легко получить доступ к любому совместимому серверу, исследовать его структуру каталогов и выполнять такие задачи, как редактирование, переименование и удаление файлов или папок по мере необходимости.

Установление соединения с FTP-серверами

Чтобы подключиться к удалённым серверам, используйте строку адреса, вводя конкретные пути. Вот как это делается:

FTP

Введите следующее в строку адреса: ftp://<адрес_сервера>:<порт>. Например, если адрес вашего сервера ftp.example.com и вы используете стандартный порт, введите ftp://ftp.example.com:21. Если порт не указан, по умолчанию используется порт 21.

FTPS

Для безопасного подключения через FTPS используйте следующий формат: ftps://<адрес_сервера>:<порт>. Например, если адрес вашего сервера ftps.example.com и вы используете стандартный порт, введите ftps://ftps.example.com:990. Если порт не указан, по умолчанию используется порт 990.

При необходимости программа Files попросит вас ввести ваши учётные данные (имя пользователя и пароль) для безопасного входа.

Отключение от FTP-серверов

Отключиться просто: достаточно закрыть вкладку или окно, и вы автоматически отключитесь от сервера.

Ограничения, о которых следует знать

    Примечание: SFTP в настоящее время не поддерживается.
