# otus_28
# Динамический веб контент

Домашнее задание
Роль для настройки веб сервера
Варианты стенда
nginx + php-fpm (laravel/wordpress) + python (flask/django) + js(react/angular)
nginx + java (tomcat/jetty/netty) + go + ruby
можно свои комбинации

Реализации на выбор
- на хостовой системе через конфиги в /etc
- деплой через docker-compose

Для усложнения можно попросить проекты у коллег с курсов по разработке

К сдаче примается
vagrant стэнд с проброшенными на локалхост портами
каждый порт на свой сайт
через нжинкс

_________________________________________________________________________________________________________________________

Команда ```vagrant up```поднимает vm, ansible-playbook разворачивает комбинацию 

nginx + php-fpm (laravel) + python (django) + js(react)

Для проверки:


uwsgi/django - http://192.168.10.150:10002/
![Img_alt](https://github.com/Edo1993/otus_28/blob/master/pics/332.png)

php-fpm/laravel - http://192.168.10.150:10001/
![Img_alt](https://github.com/Edo1993/otus_28/blob/master/pics/333.png)

http://192.168.10.150:10001/homework
![Img_alt](https://github.com/Edo1993/otus_28/blob/master/pics/334.png)

nodejs/reactjs - http://192.168.10.150:10003/
![Img_alt](https://github.com/Edo1993/otus_28/blob/master/pics/331.png)
