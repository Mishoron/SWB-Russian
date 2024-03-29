# SteamWorld: Build Demo [RU Localization]

Это локализатор задачей которого является предоставление наиболее лучшего игрового опыта в прохождении демоверсии игры на родном для многих языке(а говорящих на языка более 200млн+ оценочно).    
Более подробная информация будет предоставлена ниже.

### Оглавление
1. [Что уже переведено?](https://github.com/Mishoron/SWB-Russian#%D1%87%D1%82%D0%BE-%D0%BF%D0%B5%D1%80%D0%B5%D0%B2%D0%B5%D0%B4%D0%B5%D0%BD%D0%BE-%D1%83%D0%B6%D0%B5-%D1%81%D0%B5%D0%B9%D1%87%D0%B0%D1%81)
2. [О локализаторе](https://github.com/Mishoron/SWB-Russian#%D0%BE-%D0%BB%D0%BE%D0%BA%D0%B0%D0%BB%D0%B8%D0%B7%D0%B0%D1%82%D0%BE%D1%80%D0%B5)
3. [Пару слов об игре](https://github.com/Mishoron/SWB-Russian#%D0%BF%D0%B0%D1%80%D1%83-%D1%81%D0%BB%D0%BE%D0%B2-%D0%BE%D0%B1-%D0%B8%D0%B3%D1%80%D0%B5)
4. [Как установить](https://github.com/Mishoron/SWB-Russian#%D0%BA%D0%B0%D0%BA-%D1%83%D1%81%D1%82%D0%B0%D0%BD%D0%BE%D0%B2%D0%B8%D1%82%D1%8C)
5. [Dev log](https://github.com/Mishoron/SWB-Russian#dev-log)
6. [Об исключениях](https://github.com/Mishoron/SWB-Russian#%D0%BE%D0%B1-%D0%B8%D1%81%D0%BA%D0%BB%D1%8E%D1%87%D0%B5%D0%BD%D0%B8%D1%8F%D1%85)

### Что уже переведено?
На текущий момент локализован весь задействованный контент, где это возможно было сделать путем модификации файла, подробнее [ниже](https://github.com/Mishoron/SWB-Russian#об-исключениях).  А именно: туториал, главное меню, меню паузы, интерфейс, описание построек и т.д, но более того начиная с версии pre-release 1.2, переведен и весь оставшийся файл, более подробно [тут](https://github.com/Mishoron/SWB-Russian#dev-log).

### О локализаторе
Сам локализатор работает путем модификации файла локализации, так что все достаточно прозрачно.   
Разработан он, не без помощи технологий перевода, что немного сокращало человеко-часы, однако упор делается на контекстный перевод.   
В дальнейшем после демо проект вряд ли будет поддерживаться, имхо игра получит оффициальную локализацию(по имеющейся информации).   
Все работы связанные с основным переведом осуществлялись двумя энтузиастами, которые являются соавторами этого репозитория.    
Поддержание, редактирование и прочие изменения выполнял я - Script.    
Отдельная благодарность [энтузиасту](https://github.com/duhich167), который согласился помочь и перевести диалоги

*К слову, если обнаружите ошибку/опечатку сообщайте*

### Пару слов об игре
Сама игра является продолжением такой франшизы, как Steamworld, что существует уже более десятилетия(с первой игры).    
Её сюжет предположительно может происходить во время событий SteamWorld: Dig2, собой представляет достаточно простой, но не менее интересный градостроительный симулятор.    
Главной целью сюжетной компании является побег с планеты, которая в последнее время стала сейсмически нестабильной.(Также скорее всего будет и некий режим без сюжета)

### Как установить?
На текущий момент предоставляется лишь один вариант, а именно замена корневого файла локализации:
____
1. Получите модифицированный файл 'YMCA Localization - EN.csv', либо путем скачивания текущей версии с [релизов](https://github.com/Mishoron/SWB-Russian/releases)/[тэгов](https://github.com/Mishoron/SWB-Russian/tags)(наиболее стабильной), либо недоработанной/невыпущенной с [веток](https://github.com/Mishoron/SWB-Russian/branches)(наиболее новой)
2. Зайдите в корневую папку игры `В стиме: Свойства->Установленные файлы->Обзор`
3. Перейдите в папку `SteamWorld Build Demo_Data`, затем в `StreamingAssets` и наконец в `Localization`
4. Замените файл `YMCA Localization - EN.csv`, полученным в пункте 1

Вот и все!      
#### Как Убрать?    
Убрать также довольно просто, достаточно в вашем лаунчере запустить проверку целостности файлов:
1. `ПКМ по игре в библеотеке -> Свойства`
2. Слева выберите `Установленные файлы`
3. И наконец `Проверить целостность файлов демоверсии`

Все вышеперечисленные инструкции подходят лишь для Steam.

### Dev log
Здесь наглядно показано, что переведено, а что ещё нуждается в переводе   
- [x] Обучение, включая шахту( однако некоторые части могут быть не доделаны
- [x] Начальная катсцена(субтитры), сюжетные диалоги
- [x] GUI(исключая части описанные ниже)
- [x] Структуры:название, описание
- [x] Ресурсы:название, описание
- [x] Окно администрирования
- [x] Окно Железнодорожной станции, включая окно трейда и магазина
- [x] Уведомления(в левом вверхнем углу)
- [x] Подсказки во время геймплея
- [x] Предметы:название, описание  
*Дополнение: Начиная с версии pre-release 1.2 переведен весь пропущенный и даже не задействованный контент в демоверсии, также были переработаны ранние переводы для улучшения игрового опыта.*
### Об исключениях
Не все переведено по причине отсутсвия таковой возможности, ибо игра игнорирует некоторые тэги в файле(недоработка разработчиков), а некоторые элементы(такие как экран конца демо и кнопки в начальном меню) вшиты прямо в код, а это в свою очередь означает, что перевести их - нельзя.   
*А полноценная модификация демоверсии игры - в целом нецелесообразна*      
