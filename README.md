Это форк пакета (appzcoder/laravel-admin)[https://github.com/appzcoder/laravel-admin]

В этом пакете удалены следующие:
1) удален CRUD таблиц users, permission, roles
2) удалены все миграции
3) удалена генерация стандартного Auth который завязан на работу с Eloquent
4) удалено меню по работе с таблицами из пункта 1, так же все routes

Для установки добавляем в composer.json
```"wowkaster/laravel-admin": "dev-master"```



Этот проект нужен для работы с SSO.
Пользователи храняться не локально а за пределами приложения.
