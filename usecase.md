# Пересылка

**Акторы**

- Пользователь
- Сервис передачи сообщений
- Получатель сообщений
- Приложения

**Цель:** Как пользователь я хочу иметь возможность пересылать полученные сообщения, чтобы делиться ими с друзьями. 

**Предусловия:** Получено сообщение.

**Сценарий:**

1. Пользователь выбирает сообщение/я.
2. Пользователь нажимает кнопку пересылки.
3. Появляется меню выбора адресата.
4. Пользователь выбирает кому переслать сообщения.
5. Пользователь подтверждает пересылку. Если пользователь не подтвердил пересылку, сценарий заканчивается.
6. Приложение отправляет ивент о отправке сообщений на сервер.
6. Сервер отправляет ивент приложениям получателей о входящем сообщении.
7. Приложения получателей проигрывают уведомлений о новых сообщениях.

**Результат**

- Выбранные пользователи получили новые сообщения.

**Исключения**

- Пользователь не выбрал кому переслать сообщения.
- Пользователь снял выделение с сообщений.


