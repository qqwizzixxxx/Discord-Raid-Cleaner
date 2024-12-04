### ENGLISH


# Changelog

## [3.1.0] - 2024-04-12
### Added
- **`!Permissions`** - Shows all role permissions.
- **`!Serverinfo`** - Displays information about the server.
- **`!User  info <User  Name>`** - Retrieves and displays information about a user, such as their ID, join date, and roles.
- **`!Roleinfo <role name>`** - Retrieves information about a specific role, including its permissions and members.
- **`!Channelinfo <channel name>`** - Retrieves information about a specific channel, including its type, topic, and member count.
- **`!Membercount`** - Retrieves the total number of members in the server.
- **`!Serverowner`** - Retrieves information about the server owner.
- **`!Botinfo`** - Retrieves information about the bot itself, including its name, ID, and creation date.
- **`!Invite`** - Generates an invite link for the bot to join another server.
- **`!Avatar <Username>`** - Retrieves the avatar URL of a user or the bot.
- **`!Banner <Username>`** - Retrieves the banner URL of a user or the bot.
- **`!addRole`** - Allows users with the `manage_roles` permission to add a specified role to a user by their username.

### Changed
- **Command Case Insensitivity** - Implemented a custom command handler to allow users to invoke commands in any case (e.g., `!avatar`, `!Avatar`, `!AVATAR`).

### Fixed
- **Error Handling** - Added error handling for command not found scenarios, allowing the bot to recognize commands typed in different cases. Improved user feedback for commands that fail due to missing members or roles.


### RUSSIAN


# Журнал изменений

## [3.1.0] - 2024-04-12
### Добавлено
- **`!Permissions`** - Показывает все разрешения ролей.
- **`!Serverinfo`** - Отображает информацию о сервере.
- **`!User   info <Имя пользователя>`** - Извлекает и отображает информацию о пользователе, такую как его ID, дата присоединения и роли.
- **`!Roleinfo <имя роли>`** - Извлекает информацию о конкретной роли, включая ее разрешения и участников.
- **`!Channelinfo <имя канала>`** - Извлекает информацию о конкретном канале, включая его тип, тему и количество участников.
- **`!Membercount`** - Извлекает общее количество участников на сервере.
- **`!Serverowner`** - Извлекает информацию о владельце сервера.
- **`!Botinfo`** - Извлекает информацию о самом боте, включая его имя, ID и дату создания.
- **`!Invite`** - Генерирует ссылку-приглашение для бота, чтобы он мог присоединиться к другому серверу.
- **`!Avatar <Имя пользователя>`** - Извлекает URL-адрес аватара пользователя или бота.
- **`!Banner <Имя пользователя>`** - Извлекает URL-адрес баннера пользователя или бота.
- **`!addRole`** - Позволяет пользователям с разрешением `manage_roles` добавлять указанную роль пользователю по его имени.

### Изменено
- **Нечувствительность к регистру команд** - Реализована пользовательская обработка команд, позволяющая пользователям вызывать команды в любом регистре (например, `!avatar`, `!Avatar`, `!AVATAR`).

### Исправлено
- **Обработка ошибок** - Добавлена обработка ошибок для сценариев, когда команда не найдена, позволяющая боту распознавать команды, введенные в разных регистрах. Улучшена обратная связь для команд, которые не срабатывают из-за отсутствия участников или ролей.
