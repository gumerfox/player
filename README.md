# Музыкальный плеер. Пет-проект.

Имеется: 

    проигрывание mp3 трека по клику на музыкальную карточку.           
    пауза трека.
    остановка трека.
    кнопки следующего/предыдущего трека.
    перемотка трека.
    изменение громкости трека.
    добавление треков в избранное.
    поиск треков по совпадению запроса.
    
Краткий ввод:
    
    1. Приложение делает fetch запрос на API которое находится по адресу "https://rattle-knotty-jeep.glitch.me/"
    2. mp3 треки и постеры хранятся на сервере
    3. Сервер отдаёт JSON с данными о треках
    4. По запросу /api/music?{search=""} происходит поиск трека по исполнителю и названию
    5. Для того чтобы дождаться ответа от сервера добавлен прелоадер.

Зависимости: 

    Нет зависимостей.
    

Запуск:

    1. npm i
    2. gulp
    3. gulp build - для билд сборки (опционально)
            
    
GitHub Pages: 

