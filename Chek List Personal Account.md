# Чек-лист "Вход в личный кабинет"/ Web  
## Вход по e-mail  
### Классы эквивалентности  

#### 1 класс  
Проверка: Зарегистрированный логин + Правильный пароль  
Тип сценария: Позитивный  
Комментарий: Логин зарегистрированного пользователя с подходящим паролем (Логин: zvo22140@nezid.com, Пароль: azr6nm)  
Ожидаемый результат: Успешный вход в личный кабинет. Открывается страница "Мой профиль" с данными пользователя  

#### 2 класс  
Проверка: Зарегистрированный логин + Неправильный пароль  
Тип сценария: Негативный  
Комментарий: Логин зарегистрированного пользователя с неподходящим паролем (Логин: zvo22140@nezid.com, Пароль: azr6nm9)  
Ожидаемый результат: Появляется сообщение "Не удается войти. Пожалуйста, проверьте правильность написания почты и пароля"  

#### 3 класс  
Проверка: Незарегистрированный логин + Любой пароль  
Тип сценария: Негативный  
Комментарий: Логин незарегистрированного пользователя с любым паролем (Логин: z9v4o22140@nezid.com, Пароль: azr6nm9)   
Ожидаемый результат: Появляется сообщение "Не удается войти. Пожалуйста, проверьте правильность написания почты и пароля"
