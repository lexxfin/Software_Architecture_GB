## E2E (End-to-End) тесты для системы управления роботом-пылесосом:
### Сценарий 1: Запуск и навигация
- Шаг 1: Запустить приложение управления роботом-пылесосом.
- Шаг 2: Выбрать комнату для уборки.
- Шаг 3: Запустить процесс уборки.
- Шаг 4: Проверить, что робот начинает движение.
- Шаг 5: Подождать завершения уборки.
- Шаг 6: Убедиться, что робот вернулся на базу после завершения уборки.

### Сценарий 2: Обработка препятствий
- Шаг 1: Разместить препятствие на пути робота.
- Шаг 2: Запустить уборку в помещении с препятствием.
- Шаг 3: Проверить, что робот успешно обнаруживает и обходит препятствие.
- Шаг 4: Завершить уборку и убедиться, что робот возвращается на базу.

### Сценарий 3: Зарядка
- Шаг 1: Проверить уровень заряда аккумулятора.
- Шаг 2: Запустить уборку с низким зарядом аккумулятора.
- Шаг 3: Убедиться, что робот автоматически возвращается на базу для зарядки при низком заряде.
- Шаг 4: Подождать, пока робот заряжается.
- Шаг 5: Убедиться, что робот возобновляет уборку после зарядки.

## Приёмочные тесты (UAT) для сценариев Use case:
### Сценарий 1: Управление через мобильное приложение
- Тестирование подключения: Убедиться, что мобильное приложение успешно подключается к роботу.
- Тестирование управления: Проверить функциональность управления роботом через мобильное приложение (запуск, остановка, выбор комнаты).
- Тестирование уведомлений: Проверить, что приложение корректно уведомляет пользователя о статусе уборки и состоянии робота.
### Сценарий 2: Планирование уборки
- Тестирование расписания: Убедиться, что робот следует расписанию уборки, если оно установлено.
- Тестирование настройки расписания: Проверить, что пользователь может легко настроить расписание уборки через приложение.
### Сценарий 3: Обновление программного обеспечения
- Тестирование наличия обновлений: Убедиться, что робот корректно оповещает о наличии новых обновлений ПО.
- Тестирование процесса обновления: Проверить, что обновление происходит без сбоев и не влияет на текущую работу робота.
### Сценарий 4: Работа с несколькими комнатами
- Тестирование выбора комнаты: Проверить, что пользователь может выбрать конкретную комнату для уборки.
- Тестирование уборки в нескольких комнатах: Убедиться, что робот эффективно убирает в нескольких комнатах согласно указаниям пользователя.