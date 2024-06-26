# Супер новый проект

![Laravel](https://laravel.com/img/logotype.min.svg)

## Документация

:boom: Используя клавиши <kbd>CTRL</kbd> + <kbd>C</kbd> и <kbd>CTRL</kbd> + <kbd>V</kbd> необходимо выполнить установку

	1. composer require antefil/parser
 
	2. php artisan vendor:publish --provider='Antefil\Parser\Providers\PostServiceProvider'

	3. php artisan migrate

Для проверки установки можно перейти по адресу https://site.ru/checking_install_packages
	
<table>
    <tr>
        <th>Шаг 1</th>
        <th>Шаг 2</th>
    </tr>
    <tr>
        <td>Ячейка 1.1</td>
        <td>Ячейка 2.1</td>
    </tr>
    <tr>
        <td>Ячейка 1.2</td>
        <td>Ячейка 2.2</td>
    </tr>
</table>

:sob: Удаление: необходимо выполнить следущее шаги
	
	- Удалить запись "antefil/parser": "^1.0", в файле composer.json в корне вашего сайта
	- Выполнить команду: composer update
	- Выполнить команду: php artisan migrate:rollback если выполняли ранее команду php artisan migrate.
	- Удалить файл /config/social.php
	- Удалить файлы в /database/migrations имеющие в названии create_parser
	- Удалить папку в /resources/views/vendor/parser

