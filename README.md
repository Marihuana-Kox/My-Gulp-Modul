# Начало работы
1 Скачиваете репозмиторий git clone git@github.com:Marihuana-Kox/My-Gulp-Modul.git .
2 Установка npm install может еще понадобится установка Gulp - npm install gulp
1 Скачиваете репозмиторий
git clone git@github.com:Marihuana-Kox/My-Gulp-Modul.git .
2 Установка npm install может еще понадобится установка Gulp
3 Запускаете Gulp 
4 Выбираете default

Задачи Gulp:
    gulp : запустить задачу gulp по умолчанию (sass, js, watch, браузерсинк) для веб-разработки;
    build : собрать проект в папку dist (очистка, оптимизация образа, удаление ненужных файлов);
    Deploy : развертывание проекта на сервере из папки dist через FTP ;
    rsync : развертывание проекта на сервере из папки dist через RSYNC ;
    Clearcache : очистить весь кэш gulp.
    
Правила работы со стартовым HTML-шаблоном
    Все HTML-файлы должны иметь такое же начальное содержимое, как и в app/index.html ;
    Чтобы установить новую JS-библиотеку, просто запустите в терминале команду « bower i имя-плагина ». Библиотеки автоматически помещаются в папку app/libs . В системе должен быть установлен Bower (npm i -g Bower). Затем поместите все пути к библиотекам JS в задачу js() (gulpfile.js);
    Все пользовательские JS расположены в app/js/common.js ;
    Все переменные Sass помещены в app/sass/_vars.sass ;
    Все шрифты помещены в app/sass/_fonts.sass с помощью примеси «_mixins/font-face».
    Все медиа-запросы Bootstrap помещаются в app/sass/_media.sass ;
    Все CSS-стили JS-библиотек размещены в app/sass/_libs.sass ;
И все!
Пишите свой код в директории app
