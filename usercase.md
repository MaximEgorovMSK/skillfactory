### Use Case № 1 Регистрация пользователя на сайте

*Цель: Регистрация пользователя на сайте*

**Действующие лица:** 
- Неавторизованный пользователь
- Система

**Предусловия:**
- Неавторизованный пользователь зашел на сайт


**Основной поток:**
1. Неавторизованный пользователь зашел на сайт
2. Неавторизованный пользователь переходит на страницу авторизации
3. Неавторизованный пользователь вводит email
4. Система отправляет пользователю email с проверочным кодом
5. Неавторизованный пользователь подтверждает email
6. Неавторизованный пользователь вводит номер телефона
7. Система отправляет пользователю sms с проверочным кодом
8. Неавторизованный пользователь подтверждает номер телефона
9. Неавторизованный пользователь вводит пароль

**Постусловие:**
- Пользователь зарегистрирован

**Исключения:**
``Введенный пользователем email уже зарегистрирован в системе. Пользователю отражено сообщение, что введенный email уже зарегистрирован в системе``
``Пользователем введен неверный проверочный код. Система позволяет запросить повторный код через 60 секунд``

### изменение для альтернативной ветки2
еще одно изменения для альтернативной ветки
### изменение для мердж конфликта 2


