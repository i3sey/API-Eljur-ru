API-Eljur-ru - Python библиотека предназначенная для легкой работы разработчикам с информацией от Eljur.ru
Внимание! С родительским/учительским аккаунтом API может работать некорректно.

---

На данный момент существует 7 модулей, из которых полностью завершены 6*:
P.S: звездочка означает, что большая часть модуля завершена.

Authorization:
- register (Регистрация пользователя eljur.ru. // Не завершено)
- login (Подключение к пользователю eljur.ru)
- recover (Восстановление пароля пользователя eljur.ru. через почту)

Profile:
- getProfile (Получение информации о пользователе)

Security:
- changePassword (Изменение пароля в личном кабинете пользователя)

Settings:
- changeSing (Изменение подписи в новых сообщениях пользователя)
- switcher (Переключение настраиваиваемых функций в настройках)

Message:
- schoolList (Получение тех, кому можем отправить сообщение)
- sendMessage (Отправка сообщения по ID пользователя)
- getMessages (Получение сообщений пользователя)
- deleteMessages (Удаление сообщения у пользователя)
- recoverMessages (Возвращает сообщение из Корзины)

Journal: // Не завершено
- journal (Получение страницы дневника с расписанием и оценками)

Portfolio*:
- reportCard (Получение списка оценок пользователя)
- attendance (Получение пропущенных дней пользователя // Не завершено)
- finalGrades (Получение четвертных оценок пользователя)

---
TODO:
- Доделать Journal
- Сделать example папку с примерами работы API
