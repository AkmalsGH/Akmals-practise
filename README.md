# Akmals-practise-28.1

Итоговый проект по автоматизации тестирования: 

1- conftest.py содержит весь необходимый код для отлова неудачных тестовых случаев и создания скриншота страницы в случае, если какой-либо тестовый пример не сработает.

2- pages/base_page.py содержит реализацию шаблона PageObject для Python.

3- pages/auth_page.py страница авторизации для работы с автотестами.

4- pages/config_page.py страница регистрации для работы с автотестами.

5- pages/elements_page.py содержит вспомогательный класс для определения веб-элементов на веб-страницах.

6- tests_rt.py содержит тесты для Ростелекома ( https://b2c.passport.rt.ru/ )

Как запустить тесты?

1- Установите требования: pip install -r requirements.txt

2- Загрузите Selenium WebDriver с https://chromedriver.chromium.org/downloads (выберите версию, совместимую с вашей платформой и браузером)

3- Запустите тесты: pytest -v --driver Chrome --driver-path /chromedriver tests_rostelecom.py
