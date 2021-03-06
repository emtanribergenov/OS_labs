---
# Front matter
lang: ru-RU
title: Основы интерфейса взаимодействия пользователя с системой Linux на уровне
командной строки.
subtitle: ЛР по ОС №5
author: Танрибергенов Эльдар Марсович
group: НПИбд-02-20
---






> Отчёт
>
> о выполнении лабораторной работы № 5.

### Основы интерфейса взаимодействия пользователя с системой Linux на уровне командной строки.



#### Выполнил:

студент группы НПИбд-02-20

Танрибергенов Эльдар Марсович.

Студ. билет № 1032208074

Москва 2021 г.



# Цель работы:

-   Приобретение практических навыков взаимодействия пользователя с
    системой посредством командной строки.

# Задание:

1\. Определите полное имя вашего домашнего каталога. Далее относительно
этого каталога будут выполняться последующие упражнения.

2\. Выполните следующие действия:

2.1. Перейдите в каталог /tmp.

2.2. Выведите на экран содержимое каталога /tmp. Для этого используйте
команду ls с различными опциями. Поясните разницу в выводимой на экран
информации.

2.3. Определите, есть ли в каталоге /var/spool подкаталог с именем cron?

2.4. Перейдите в Ваш домашний каталог и выведите на экран его
содержимое. Определите, кто является владельцем файлов и подкаталогов?

3\. Выполните следующие действия:

3.1. В домашнем каталоге создайте новый каталог с именем newdir.

3.2. В каталоге \~/newdir создайте новый каталог с именем morefun.

3.3. В домашнем каталоге создайте одной командой три новых каталога с
именами letters, memos, misk. Затем удалите эти каталоги одной командой.

3.4. Попробуйте удалить ранее созданный каталог \~/newdir командой rm.
Проверьте, был ли каталог удалён.

3.5. Удалите каталог \~/newdir/morefun из домашнего каталога. Проверьте,
был ли каталог удалён.

4\. С помощью команды man определите, какую опцию команды ls нужно
использовать для просмотра содержимое не только указанного каталога, но
и подкаталогов, входящих в него.

5\. С помощью команды man определите набор опций команды ls, позволяющий
отсортировать по времени последнего изменения выводимый список
содержимого каталога с развёрнутым описанием файлов.

6\. Используйте команду man для просмотра описания следующих команд: cd,
pwd, mkdir, rmdir, rm. Поясните основные опции этих команд.

7\. Используя информацию, полученную при помощи команды history,
выполните модификацию и исполнение нескольких команд из буфера команд.

# Ход работы:

Просмотрел полное имя домашнего каталога, перешёл в каталог /tmp. Вывел
на экран содержимое этого каталога со всеми скрытыми каталогами и
файлами при помощи ls -a

![](https://github.com/emtanribergenov/OS_labs/blob/master/5/screenshots/1.png)

Вывел содержимое этого же каталога с расширенной информацией ls --l.

![](https://github.com/emtanribergenov/OS_labs/blob/master/5/screenshots/2.png)

Вывел содержимое в обратном порядке с подробной информацией,
отсортировав по размеру, отображая размер в удобном для чтения формате.
ls --rlSh

![](https://github.com/emtanribergenov/OS_labs/blob/master/5/screenshots/3.png)

Проверил подкаталог spool в var. Вывел его содержимое с подробной
информацией. Перешёл в дом. каталог и вывел содержание с подробной инфой
с удобным выводом размера. Видно, что владельцем файлов и директорий
являюсь я,
emtanribergenov

![](https://github.com/emtanribergenov/OS_labs/blob/master/5/screenshots/4.png)

Создал каталог newdir , а в нём подкаталог morefun. Проверил.

![](https://github.com/emtanribergenov/OS_labs/blob/master/5/screenshots/5.png)

Создал сразу три каталога одной командой и удалил также одной командой.

![](https://github.com/emtanribergenov/OS_labs/blob/master/5/screenshots/6.png)

Попытался удалить каталог при помощи rm без опций. Не удалось. Удалил
каталог morefun. Получил справку по команде ls. Для вывода содержимого
не только указанного каталога, но и всех входящих в него подкаталогов,
используется опция --R. Проверил.

![](https://github.com/emtanribergenov/OS_labs/blob/master/5/screenshots/7.png)

![](https://github.com/emtanribergenov/OS_labs/blob/master/5/screenshots/8.png)

С помощью команды man определил опцию команды ls, позволяющий
отсортировать по времени последнего изменения выводимый список
содержимого каталога с развёрнутым описанием файлов. Это ls --lt.
Испытал.

![](https://github.com/emtanribergenov/OS_labs/blob/master/5/screenshots/9.png)

Получил справки по командам cd, pwd, mkdir, rmdir, rm. Основные опции я
описал в скринкасте.

![](https://github.com/emtanribergenov/OS_labs/blob/master/5/screenshots/10.png)

Воспользовавшись командой history, модифицировал и запустил несколько
использованных ранее
команд.

![](https://github.com/emtanribergenov/OS_labs/blob/master/5/screenshots/11.png)

![](https://github.com/emtanribergenov/OS_labs/blob/master/5/screenshots/12.png)

# Вывод:

В результате лабораторной работы я приобрёл практические навыки
взаимодействия пользователя с системой посредством командной строки.



# Ответы на вопросы:

1. Текстовый интерфейс, который позволяет вводить команды, выполнять их и просматривать результаты. 
2. pwd. Например: pwd 
3. ls -F. Например: ls -F / 
4.  Скрытые файлы - системные, увидить можно с помощью ls -a
5. rm -R  - удаление файла/каталога, rmdir - удаление пустого каталога
6. history 
7.   !<номер_команды>:s/<что_меняем>/<на_что_меняем>, пример:   !3:s/a/F
8.  можно через " ; " , пример: cd ; ls
9. способ размещения внутри литерала символов окончания литерала, а также непечатаемых и специальных символов. пример: \\n 
10. права доступа, кол-во файлов в каталоге, автор, владелец, дата модификации, размер, время, имя файла
11. который указывает на расположение файла относительно корневого каталога. пример : cd * вместо cd /home/user/*
12. . man, --help, info 
13. tab

