Итоговый проект SkillFactory для проведения тестирования по проекту "Новый интерфейс авторизации в личном кабинете" от заказчика Ростелеком Информационные Технологии"

Автоматизированное ui-тестирование https://b2c.passport.rt.ru/
____

+ Файл с Тестированием требований, Тест-кейсам и Баг-репортами https://docs.google.com/spreadsheets/d/1xGqDuOkohyhbi9e-0vDX15dbj3E_O8AOANhxRZauLUA/edit?usp=sharing

1. В папке pages в файле base_page.py находится конструктор webdriver и общие для всех тестируемых страниц методы.

2. В папке pages в файлах auth_page.py, change_pass_page.py, reg_page.py находятся методы проверок: файл auth_page.py содержит методы проверок формы авторизации; файл change_pass_page.py содержит методы проверок формы восстановления пароля; файл reg_page.py содержит методы проверок формы регистрации.

3. В папке pages в файле "locators.py находятся все локаторы.

4. В папке tests в файлах test_auth_page.py, test_change_pass_page.py, test_reg_page.py находятся тесты. Все тесты помечены номером, совпадающим с номером тест-кейса в файле.
5. В корне проекта в файле conftest.py находится фикстура с функцией открытия и закрытия браузера. 

6. В корне проекта в файле settings.py находятся методы и переменные для параметризации тестов

7. В корне проекта в файле pytest.ini зарегистрированы метки маркировок тестов.

8. В корне проекта в файле requirements.py описаны используемые библиотеки.

9. В корне проекта файл драйвера chromedriver.exe
