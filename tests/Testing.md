
# Тестирование приложения "SudokuApp"

## Проверка запланированных действий  

### Аутентификация и учетная запись  

| **Действие** | **Ожидаемый результат** | **Результат** |  
|:---|:---|:---|  
| Ввод корректных данных при входе | Пользователь успешно входит в учетную запись | Вход в аккаунт выполнен |  
| Ввод некорректных данных при входе | Появляется сообщение об ошибке | Сообщение о неверных данных |  
| Регистрация нового пользователя с корректными данными | Учетная запись успешно создается | Пользователь успешно создан |  
| Попытка регистрации с уже существующим логином | Появляется сообщение об ошибке | Сообщение о неправильных данных |  
| Нажатие на кнопку выхода из аккаунта | Пользователь выходит из учетной записи | Выход из аккаунта успешен |  

### Выбор игрового режима  

| **Действие** | **Ожидаемый результат** | **Результат** |  
|:---|:---|:---|  
| Выбор классического судоку | Переход на экран выбора уровня классического судоку | Переход на эран выбора уровня |  
| Выбор судоку с ограничением по времени | Переход на экран выбора уровня судоку с ограничением по времени | Режим установлен |  
| Нажатие кнопки "Информация" на экране выбора режима | Появляется сообщение с описанием режимов | Показ информации |  

### Уровни 

| **Действие** | **Ожидаемый результат** | **Результат** |  
|:---|:---|:---|  
| Начало нового уровня в классическом судоку | Открывается выбранный уровень | Уровень открывается |   
| Попытка открыть несозданный уровень | Отображается сообщение о том, что уровень ещё не создан | Сообщение выводится |  

### Интерфейс профиля  

| **Действие** | **Ожидаемый результат** | **Результат** |  
|:---|:---|:---|  
| Нажатие кнопки "Войти" (неавторизованный пользователь) | Переход на экран входа | Переход на экран входа |  
| Нажатие кнопки "Выйти" (авторизованный пользователь) | Пользователь выходит из учетной записи | Пользователь не в учётной записи |  

### Геймплей  

| **Действие** | **Ожидаемый результат** | **Результат** |  
|:---|:---|:---|  
| Ввод числа в клетку | Число корректно отображается | Число корректно отображается |  
| Попытка ввода некорректного значения | Появляется предупреждение об ошибке | Увелечение счётчика ошибок |  
| Завершение уровня (все клетки заполнены корректно) | Появляется сообщение о завершении уровня | Сообщение о прохождении уровня |  
| Завершение уровня с ошибками | Появляется сообщение с указанием ошибок | Сообщение о том, что уровень не пройден |  

### Проверка производительности  

| **Действие** | **Ожидаемый результат** | **Результат** |  
|:---|:---|:---|  
| Быстрое переключение между экранами | Приложение не зависает, переходы выполняются быстро | Всё работает корректно |  
| Запуск приложения без интернет-соединения | Приложение работает корректно | Приложение работает корректно |  
