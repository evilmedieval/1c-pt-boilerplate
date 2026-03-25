# Настройки отладки для 1C Platform Tools. Ключи и значения для launch.json

"rootProject": "Путь к корневому проекту. Например: '${workspaceFolder}/src/cf'",

"extensions": "Массив путей к расширениям. Например: '${workspaceFolder}/src/cfe'",

"platformPath": "Путь к платформе 1С. Например: 'C:/Program Files/1cv8'",

"platformVersion": "Версия платформы 1С. Например: '8.3.23.2040'",

"autoAttachTypes": "Массив типов для автоматического подключения. Например: ['Client', 'ManagedClient']",

Доступные значения: Client (Толстый клиент), ManagedClient (Тонкий клиент), WebClient, Server, OData, HttpService, WebService и др.
Пример: ["Client", "ManagedClient", "Server"]

# В случае, если у вас есть какие-либо расширения, то их нужно указать в массиве extensions. Например: 

"extensions": [
				"${workspaceFolder}/src/cfe"
			],

# Настройка отладочного сервера и его порта

"debugServerHost": "localhost",
"debugServerPort": 1550,
