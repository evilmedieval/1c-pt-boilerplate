# Настройки отладки для 1C Platform Tools. Ключи и значения для launch.json

"_comment_rootProject": "Путь к корневому проекту. Например: '${workspaceFolder}/src/cf'",

"_comment_extensions": "Массив путей к расширениям. Например: '${workspaceFolder}/src/cfe'",

"_comment_platformPath": "Путь к платформе 1С. Например: 'C:/Program Files/1cv8'",

"_comment_platformVersion": "Версия платформы 1С. Например: '8.3.23.2040'",

"_comment_autoAttachTypes": "Массив типов для автоматического подключения. Например: ['Client', 'ManagedClient']",

Доступные значения: Client (Толстый клиент), ManagedClient (Тонкий клиент), WebClient, Server, OData, HttpService, WebService и др.
Пример: ["Client", "ManagedClient", "Server"]

# В случае, если у вас есть какие-либо расширения, то их нужно указать в массиве extensions. Например: 

"extensions": [
				"${workspaceFolder}/src/cfe"
			],

# Настройка отладочного сервера и его порта

"debugServerHost": "localhost",
"debugServerPort": 1550,
