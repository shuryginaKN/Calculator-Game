# Игра "Калькулятор" (Calculator Game)

<<<<<<< HEAD
=======

>>>>>>> fc22ba25c41e8884e346472efe61a5ce44b87ec8
## Описание игры

Игроку показывается случайное арифметическое выражение с операциями +, -, *, содержащее четыре операнда (например 35+16*2-4), которое нужно вычислить и записать ответ. После этого программа должна вывести соответствующее сообщение и правильный ответ.

<<<<<<< HEAD
Веб-приложение сохраняет информацию об игроках, датах игр, предложенных выражениях, их правильных значениях и введенных пользователями ответах в базе данных. Также реализована возможность просмотра истории игр.
Игра разработана на языке PHP с использованием Composer для управления зависимостями, а также с помощью REST API взаимодействуя с базой данных SQLite на сервере. Backend приложения реализовать с помощью PHP-микрофреймворка Slim.

## Установка и запуск
=======
## Установка
>>>>>>> fc22ba25c41e8884e346472efe61a5ce44b87ec8

### Локальная установка
1. Клонируйте репозиторий:
   ```bash
<<<<<<< HEAD
    git clone https://github.com/shuryginaKN/Calculator-Game.git
=======
    git clone https://github.com/shuryginaKN/PHP_SHurygina_KN.git
>>>>>>> fc22ba25c41e8884e346472efe61a5ce44b87ec8
    ```

2. Перейдите в каталог проекта:
   ```bash
<<<<<<< HEAD
   cd Calculator-Game
=======
   cd C:\...\calculator
>>>>>>> fc22ba25c41e8884e346472efe61a5ce44b87ec8
   ```

3. Установите зависимости через Composer:
    ```bash
    composer install
    ```

<<<<<<< HEAD
4. Запуск локального сервера:
    ```bash
    php -S localhost:3000 -t public
    ```
5. Откройте в браузере:
    ```bash
    http://localhost:3000/
    ```

## Структура проекта
```
Task03/
├── db/
│   └── database.sqlite         # Файл базы данных SQLite
├── public/
│   └── index.php               # Главная страница веб-приложения (маршрутизация Slim)
│   └── index.html              # Фронтенд (HTML, JavaScript)
│   └── styles.css              # Стили
├── src/
│   ├── GameController.php      # Обработчики REST API (логика работы с запросами) 
│   ├── Database.php            # Работа с базой данных SQLite
│   ├── Game.php                # Логика игры
├── vendor/
├── composer.json               # Файл конфигурации Composer
└── README.md                   # Описание проекта
```

### Как играть
1. Откройте http://localhost:3000/ и решите предложенный пример.
2. Введите свой ответ и нажмите "Ответить".
3. Программа покажет, правильно ли решен пример, и сохранит результат в базе данных.
4. Для просмотра истории игр нажмите на кнопку "Посмотреть результаты".

## Требования
- PHP 7.4 или выше
- Встроенный сервер PHP
- SQLite

## Автор
- shuryginaKN
- [Репозиторий на GitHub](https://github.com/shuryginaKN/Calculator-Game.git)
=======
4. Запустите игру:
    ```bash
    php bin/calculator
    ```


### Установка через Packagist
1. Убедитесь, что Composer установлен глобально.
2. Установите игру:
    ```bash
    composer global require ks561/cold-hot
    ```

3. Запустите игру из командной строки:
    ```bash
   calculator
   ```

## Ссылки
- [Packagist пакет calculator](https://packagist.org/packages/ks561/calculator)
- [Репозиторий на GitHub](https://github.com/shuryginaKN/calculator)
>>>>>>> fc22ba25c41e8884e346472efe61a5ce44b87ec8
