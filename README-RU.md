[![Static Badge](https://img.shields.io/badge/Telegram-Channel-Link?style=for-the-badge&logo=Telegram&logoColor=white&logoSize=auto&color=blue)](https://t.me/+jJhUfsfFCn4zZDk0)      [![Static Badge](https://img.shields.io/badge/Telegram-Bot%20Link-Link?style=for-the-badge&logo=Telegram&logoColor=white&logoSize=auto&color=blue)](https://t.me/major/start?startapp=339631649)

![demo](https://github.com/user-attachments/assets/94ab0cfd-07d2-449d-ae41-1a1807402e3e)



## Recommendation before use

# 🔥🔥 PYTHON version must be 3.10 🔥🔥

> 🇪🇳 README in english available [here](README)

## Функционал  
|                               Функционал                               | Поддерживается |
|:----------------------------------------------------------------------:|:--------------:|
|                            Многопоточность                             |       ✅        | 
|                        Привязка прокси к сессии                        |       ✅        | 
|                   Авто Реферальство ваших аккаунтов                    |       ✅        |
| Авто выполнение заданий, которые можно выполнить обычному пользователю |       ✅        |
|                         Автоматическая рулетка                         |       ✅        |
| Авто Hold Coins  					                       |     ✅     |
| Авто Swipe Coins                   				       |     ✅     |
| Авто Puzzle Pavel                        				   |     ✅     |
|                     Автоматичесие ежедневная стрики                   |       ✅        |
|                      Поддержка pyrogram .session                       |       ✅        |
|             Поддержка Telethon версии (в ветке telethon)               |       ✅        |


## [Настройки](https://github.com/GravelFire/MajorBot/blob/main/.env-example/)
|        Настройки        |                                      Описание                                       |
|:-----------------------:|:-----------------------------------------------------------------------------------:|
|  **API_ID / API_HASH**  | Данные платформы, с которой будет запущена сессия Telegram (по умолчанию - android) |
| **TASKS_WITH_JOIN_CHANNEL** | Выполнять ли задания с присоединением к каналам (True / False)                  |
|    **HOLD_COIN**        |                         Количество монет в Hold Coin (напр. [585, 600])             |
|    **SWIPE_COIN**       |                         Количество монет в Swipe Coin (напр. [2000, 3000])          |
| **REF_ID**              | Ваш идентификатор реферала после startapp= (Ваш идентификатор telegram) 			|
| **SQUAD_ID**            | Ваш идентификатор сквада в которые будут заходить боты (напр. 2237841784)           |
| **USE_RANDOM_DELAY_IN_RUN**  | Использовать ли рандомную задержку при запуске (True / False)  	            |
| **RANDOM_DELAY_IN_RUN**      | Рандомная задержка при запуске (напр. [0, 15])    	                            |
| **FAKE_USER AGENT**     | Использовать поддельный пользовательский агент для сеансов (True / False) 			|
| **SLEEP_TIME**          | Задержка перед следующим кругом (например, [1800, 3600]) 							|
| **USE_PROXY_FROM_FILE** |       Использовать ли прокси из файла `bot/config/proxies.txt` (True / False)       |

## Быстрый старт 📚

Для быстрой установки и последующего запуска - запустите файл run.bat на Windows или run.sh на Линукс

## Предварительные условия
Прежде чем начать, убедитесь, что у вас установлено следующее:
- [Python](https://www.python.org/downloads/) **версии 3.10**

## Получение API ключей
1. Перейдите на сайт [my.telegram.org](https://my.telegram.org) и войдите в систему, используя свой номер телефона.
2. Выберите **"API development tools"** и заполните форму для регистрации нового приложения.
3. Запишите `API_ID` и `API_HASH` в файле `.env`, предоставленные после регистрации вашего приложения.

## Установка
Вы можете скачать [**Репозиторий**](https://github.com/GravelFire/MajorBot) клонированием на вашу систему и установкой необходимых зависимостей:
```shell
git clone https://github.com/GravelFire/MajorBot.git
cd MajorBot
```

Затем для автоматической установки введите:

Windows:
```shell
run.bat
```

Linux:
```shell
run.sh
```

# Linux ручная установка
```shell
python3 -m venv venv
source venv/bin/activate
pip3 install -r requirements.txt
cp .env-example .env
nano .env  # Здесь вы обязательно должны указать ваши API_ID и API_HASH , остальное берется по умолчанию
python3 main.py
```

Также для быстрого запуска вы можете использовать аргументы, например:
```shell
~/MajorBot >>> python3 main.py --action (1/2)
# Or
~/MajorBot >>> python3 main.py -a (1/2)

# 1 - Запускает кликер
# 2 - Создает сессию
```


# Windows ручная установка
```shell
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
copy .env-example .env
# Указываете ваши API_ID и API_HASH, остальное берется по умолчанию
python main.py
```

Также для быстрого запуска вы можете использовать аргументы, например:
```shell
~/MajorBot >>> python main.py --action (1/2)
# Или
~/MajorBot >>> python main.py -a (1/2)

# 1 - Запускает кликер
# 2 - Создает сессию
```
