## Дипломный проект. Задание 1: Юнит-тесты

### Автотесты для проверки программы заказа бургера в Stellar Burgers

### Структура проекта

- `praktikum` - пакет, содержащий код программы
- `tests` - пакет, содержащий тесты, разделенные по классам. 

#### а именно:

- `test_bun.py`: (тесты: `test_get_name, test_get_price` ),
- `test_burger_.py`: (тесты: `test_set_bun, test_add_ingredient, test_remove_ingredient, test_move_ingredient, test_get_price, test_get_receipt` ), 
- `test_database.py`: (тесты: `test_available_buns, test_available_ingredients`), 
- `test_ingridient.py`:(тесты: `test_get_name, test_get_price` ).


Процент покрытия 100% (отчет в `htmlcov/index.html`)

### Запуск автотестов

**Установка зависимостей**

> `$ pip install -r requirements.txt`

**Запуск автотестов и создание HTML-отчета о покрытии**

>  `$ pytest --cov=praktikum --cov-report=html`
