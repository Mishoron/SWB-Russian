# SteamWorld: Build Demo [RU Localization]

Это локализатор задачей которого является предоставление наиболее лучшего игрового опыта в прохождении демо-версии игры на родном для многих языке(а носителей языка более 200млн+ оценочно).    
Более подробная информация будет предоставлена ниже.

### Оглавление
1. [Что переведено уже сейчас?](https://github.com/Mishoron/SWB-Russian#%D1%87%D1%82%D0%BE-%D0%BF%D0%B5%D1%80%D0%B5%D0%B2%D0%B5%D0%B4%D0%B5%D0%BD%D0%BE-%D1%83%D0%B6%D0%B5-%D1%81%D0%B5%D0%B9%D1%87%D0%B0%D1%81)
2. [О локализаторе](https://github.com/Mishoron/SWB-Russian#%D0%BE-%D0%BB%D0%BE%D0%BA%D0%B0%D0%BB%D0%B8%D0%B7%D0%B0%D1%82%D0%BE%D1%80%D0%B5)
3. [Пару слов об игре](https://github.com/Mishoron/SWB-Russian#%D0%BF%D0%B0%D1%80%D1%83-%D1%81%D0%BB%D0%BE%D0%B2-%D0%BE%D0%B1-%D0%B8%D0%B3%D1%80%D0%B5)
4. [Как установить](https://github.com/Mishoron/SWB-Russian#%D0%BA%D0%B0%D0%BA-%D1%83%D1%81%D1%82%D0%B0%D0%BD%D0%BE%D0%B2%D0%B8%D1%82%D1%8C)
5. [Dev log](https://github.com/Mishoron/SWB-Russian#dev-log)
6. [Об исключениях](https://github.com/Mishoron/SWB-Russian#%D0%BE%D0%B1-%D0%B8%D1%81%D0%BA%D0%BB%D1%8E%D1%87%D0%B5%D0%BD%D0%B8%D1%8F%D1%85)

### Что переведено уже сейчас?
На текущий момент локализован(с исключениями, смотреть оглавление): туториал, главное меню, меню паузы, большая часть интерфейса, описание построек и всего задействованного контента, но есть исключения смотрите тут.

### О локализаторе
Сам локализатор работает путем модификации файла локализации, так что все достаточно прозрачно.   
Разработан он, не без помощи технологий перевода, что немного сокращало человеко-часы, однако упор делается на контекстный перевод.   
В дальнейшем после демо проект вряд ли будет поддерживаться, имхо игра получит оффициальную локализацию(по очевидным догадкам).   
Все работы связанные с переведом осуществлялись двумя энтузиастами, которые являются соавторами этого репозитория.

*К слову, если обнаружите ошибку/опечатку сообщайте*

### Пару слов об игре
Сама игра является продолжением такой франшизы, как Steamworld, что существует уже более десятилетия(с первой игры).    
Её сюжет предположительно может происходить во время событий SteamWorld: Dig2, собой представляет достаточно простой, но не менее интересный градостроительный симулятор.    
Главной целью сюжетной компании является побег с планеты, которая в последнее время стала сейсмически нестабильной.(Также скорее всего будет и некий режим без сюжета, но это лишь предположение)

### Как установить?
На текущий момент предоставляется лишь один вариант, а именно замена корневого файла локализации:
____
1. Получите модифицированный файл 'YMCA Localization - EN.csv', либо путем скачивания текущей версии с гита(наиболее новой), либо релизной(наиболее стабильной)
2. Зайдите в корневую папку игры `В стиме: Свойства->Локальный файлы->Обзор`
3. Перейдите в папку `SteamWorld Build Demo_Data`, затем в `StreamingAssets` и наконец в `Localization`
4. Замените файл `YMCA Localization - EN.csv`, полученным в пункте 1
Вот и все!    
Убрать её можно также довольно просто, достаточно в вашем лаунчере запустить проверку целостности файлов(В Steam именно так)

### Dev log
Здесь наглядно показано, что переведено, а что ещё нуждается в переводе   
- [x] Обучение, включая шахту( однако некоторые части могут быть не доделаны
- [x] Начальная катсцена(субтитры), сюжетные диалоги
- [x] GUI(исключая части описанные ниже)
- [x] Структуры:название, описание
- [x] Ресурсы:название, описание
- [x] Окно администрирования
- [x] Окно Железнодорожной станции, включая окно трейда и магазина
- [ ] Уведомления(в левом вверхнем углу)
- [ ] Подсказки во время геймплея
- [ ] Предметы:название, описание
### Об исключениях
Не все переведено по причине отсутсвия технической возможности, модификации этого в игре, так что да некоторые кнопки, надписи и финальный экран демо не переводим.   
*Ну что поделать, а полноценный мод в целом нецелесообразен*      
