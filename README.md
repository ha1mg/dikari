# game&over

### О чем?
Темой итогового проекта является разработка бот-сервиса на платформе Telegram с использования языка программирования Python. 
Основными функциями бот-сервиса является вывод информации о погоде, основанной на введенной локации, а также вывод информации о количестве новых заражений коронавирусом,
основываясь на выбранной стране.

### В проекте используются 
- библиотека для создания бот-сервисов telebot
- api pyowm для получения данных о погоде  
- api COVID19py для получения данных о коронавирусе.

### Авторы
- Созданием main.py, а также weather.py, в котором реализована функция вывода информациии о погоде занимался Локтюшин Егор.
- Созданием covid.py, в котором реализована функция вывода ифнормации по коронавирусу. А также созданием кнопок для возврата в главное меню, занимался Яковлев Вадим.
### Начало работы
1. Установить библиотеку telebot
>pip install pyTelegramBotAPI
2. Установить api pyowm
>pip install pyowm
3. Установить api COVID19py
>pip install COVID19Py
4. Запустить main.py 
5. В Telegram ввести в поиске @kispybot 
6. Отправитиь бот-сервису сообщение "/start"

