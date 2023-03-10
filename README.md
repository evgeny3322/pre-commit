## О проекте

Проект представляет собой административную панель, для контролирования работы ресторана.

Основные функции проекта:
 - Ведение статистики по заказам
 - Отображение работы ресторана в режиме реального времени (заказы, кухня, доставка).
 - Ведение списка сотрудников
 - Ведение списка заказов
 - Контроль бронирования столиков
 - Контроль над выполнением заказов
 - Отслеживание статуса доставок
 - Формирование меню
 - Учет количества продукции

## Запуск проекта

1. Клонируем проект ```git clone https://github.com/progitpro/platform-front.git```
2. Устанавливаем зависимости ```npm install```
3. Запускаем проект ```npm start```

## Дизайн проекта

https://www.figma.com/file/SomEc4Ummmxxq1yIjIDAmU/Spoon-Restaurant-SAAS-Dashboard?node-id=86%3A170

## Правила работы с git

1. Получая новую задачу создаем под неё ветку от dev.
  - 1.1 Переходим на ветку dev ```git checkout dev```
  - 1.2 Получаем и мержим в ветку последние изменения ```git pull origin dev``` или просто ```git pull```
  - 1.3 Создаем ветку от ветки dev ```git checkout -b <название новой ветки>```
  - 1.4 Название новой ветки должно быть коротким и одновременно отражать суть задачи. Если задача направлена на добавление чего-то нового, в назание ветки указываем префикс ```feature/```. Например, получили задачу ```Добавить левое меню на страницу ордеров```, название ветки можно задать такое: ```feature/orders-left-menu```

2. После создания ветки начинаем проводить работу.

3. По окончанию работ создаем commit с вашими изменениями ```git add .``` -> ```git commit -m "Краткое описание проведенных работ"```

4. После создания commit, получаем новые изменения из ветки dev (пока вы работали, в ветке dev что-то могло измениться). Выполняем команду ```git pull origin dev```. Эта команда смержит в вашу ветку актуальные изменения из ветки dev.

5. Если после мержа ветки dev у вас возникли какие-либо конфликты, решайте их и снова делайте commit (пункт 3).

6. После всех шагов выше выполняете команду ```git push```, если вашей ветки еще нет в репозитории, git предложит вам иную команду, которая позволит создать ветку в удаленном репозитории, в таком случае выполняем её.
  
