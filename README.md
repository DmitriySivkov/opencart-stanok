# Разработка stankom

Включи докер, подними контейнеры (docker-compose up)

**Экспорт БД:**

_В терминале поочереди вводи две команды_

**ЗАКОНЧИЛ РАБОТУ**
1) make mysql
2) make dump

После этого в папке /dump появится свежий дамп БД.

Не забудь сложить его в гит
(гит-коммит + гит-пуш)

**Импорт БД:**

Обновись из гита - выполни "git pull"

_В терминале поочереди вводи две команды_

**НАЧАЛ РАБОТУ**
1) make mysql
2) make import **АНДРЕЙ ТЫ УВЕРЕН?!**

После этого БД заменится на свежий дамп

**Работа с файлами:**

После изменений в файловой системе проекта не забудь сложить в гит
(гит-коммит + гит-пуш)

**ПОСЛЕ РАЗРАБОТКИ ИЗМЕНИТЬ СТАТУС ТОВАРОВ**

В таблице oc_product сделать status=0 следующим товарам:

айдишники товаров: 89, 100, 102, 104, 106, 281, 327, 291, 292, 294, 295, 329, 326, 320, 324, 335, 334, 340, 354, 376, 357, 377, 372, 384, 449, 459






**ПРОЧЕЕ**

Добавить "Не является публичной афертой в подвал"

Добавить редиректы и проверить ссылки

Выключить все товары из категории плазменные станки, токарные станки, обрабатывающие центры

Правки XML техникса:
<file path="catalog/controller/product/product.php"> - строка 5456

В инструкции пользователю рассказать как добавлять фильтры на товар и категорию, через вкладки фильтр
атрибуты больше не работают

Поправить генерацию sitemap

поиск по слову //прибраться

Якоря поправить в странице о компании
И также ссылки на новости и контакты, ну и в карте внизу
information.php 51 строка