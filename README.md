## HomeWork D5_7_NewsPaper

Начальная страница: http://127.0.0.1:8000/

#### Реализовано два способа входа и регистрации:   
1. Для входа через Google и почту, через "Login" и "Sign-up" в шапке или использовать редактирование новости,
после чего перенаправит вас (пакет allauth), если вы не вошли.  
2. "Login" и "Sign-up" в футере справа (не видно, необходимо навести мышку), для входа и регистрации через пользователей.

### Задание
#### Давайте обобщим все действия, которые вы должны выполнить для модификации приложения:

1. В классе-представлении редактирования новости добавить проверку аутентификации.
2. Выполнить необходимые настройки пакета allauth в файле конфигурации.
3. В файле конфигурации определить адрес для перенаправления на страницу входа в систему и адрес перенаправления после успешного входа.
4. Реализовать шаблон с формой входа в систему и выполнить настройку конфигурации URL.
5. Реализовать шаблон страницы регистрации пользователей.
6. Реализовать возможность регистрации через Google-аккаунт.
7. Создать группы common и authors.
8. Реализовать автоматическое добавление новых пользователей в группу common.
9. Создать возможность стать автором (быть добавленным в группу authors).
10. Для группы authors предоставить права создания и редактирования объектов модели Post (новостей и статей).
11. В классах-представлениях добавления и редактирования новостей и статей добавить проверку прав доступа.
12. Исходный код залить в git-репозиторий.

