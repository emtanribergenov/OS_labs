---
# Front matter
lang: ru-RU
title: Знакомство с операционной системой Linux.
subtitle: ЛР по ОС №4
author: Танрибергенов Эльдар Марсович
group: НПИбд-02-20
---



> Отчёт
>
> о выполнении лабораторной работы № 4.

### Знакомство с операционной системой Linux.



#### Выполнил:

студент группы НПИбд-02-20

Танрибергенов Эльдар Марсович.

Студ. билет № 1032208074

Москва 2021 г.



# Цель работы:

-   Познакомиться с операционной системой Linux, получить практические
    навыки работы с консолью и некоторыми графическими менеджерами
    рабочих столов операционной системы.

# Задание:

1\. Ознакомиться с теоретическим материалом.

2\. Загрузить компьютер.

3\. Перейти на текстовую консоль. Сколько текстовых консолей доступно на
вашем компьютере?

4\. Перемещаться между текстовыми консолями. Какие комбинации клавиш
необходимо при этом нажимать?

5\. Зарегистрироваться в текстовой консоли операционной системы. Какой
логин вы при этом использовали? Какие символы отображаются при вводе
пароля?

6\. Завершить консольный сеанс. Какую команду или комбинацию клавиш
необходимо для этого использовать?

7\. Переключиться на графический интерфейс. Какую комбинацию клавиш для
этого необходимо нажать?

8\. Ознакомиться с менеджером рабочих столов. Как называется менеджер,
запускаемый по умолчанию? 9. Поочерёдно зарегистрироваться в разных
графических менеджерах рабочих столов (GNOME, KDE, XFCE) и оконных
менеджерах (Openbox). Продемонстрировать разницу между ними, сделав
снимки экрана (скриншоты). Какие графические менеджеры установлены на
вашем компьютере?

10\. Изучить список установленных программ. Обратить внимание на
предпочтительные программы для разных применений. Запустите поочерёдно
браузер, текстовой редактор, текстовой процессор, эмулятор консоли.
Укажите названия программ.

# Ход работы:

![](https://github.com/emtanribergenov/OS_labs/blob/master/4/screenshots/1.png)

Рис.1. Текстовая консоль

![](https://github.com/emtanribergenov/OS_labs/blob/master/4/screenshots/2.png)

Рис. 2. Вход в систему посредством текстовой консоли.

При вводе пароля никакие символы не отражаются. Использовал логин
соответствующий соглашению об именовании.

В linux существует 6 консолей. В моей операционной системе CentOS 8 одна
из них по умолчанию работает в графическом режиме. Перемещаться можно
нажимая комбинации клавиш Ctrl + Alt + FN, где N -- номер консоли (число
1-6).

Завершаю консольный сеанс командой logout. Можно воспользоваться
комбинацией клавиш Ctrl +
d

![](https://github.com/emtanribergenov/OS_labs/blob/master/4/screenshots/3.png)

Рис. 3. Завершение консольного сеанса.

![](https://github.com/emtanribergenov/OS_labs/blob/master/4/screenshots/4.png)

Рис. 4. Переключение на графический
интерфейс.

Использовал комбинацию клавиш Ctrl + Alt + F7.

![](https://github.com/emtanribergenov/OS_labs/blob/master/4/screenshots/gnome.png)

Рис. 5. Графический менеджер GNOME.

По умолчанию в системе CentOS 8 установлен графический менеджер GNOME.

![](https://github.com/emtanribergenov/OS_labs/blob/master/4/screenshots/Xfce.png)

Рис. 6. Графический менеджер Xfce.

Различия видны невооружённым глазом.

Графический менеджер рабочего стола KDE в моей системе
отсутствует.

![](https://github.com/emtanribergenov/OS_labs/blob/master/4/screenshots/Openbox.png)

Рис. 7. Оконный менеджер Openbox.

Openbox, как я понял, не отображает иконок приложений на рабочем столе
-- вместо этого предоставляется меню, вызываемое нажатием ПКМ. В этом
меню доступны все приложения, утилиты и прочее, установленные на
компьютер.

В моей системе CentOS 8 установлены графические менеджеры GNOME и Xfce.

![](https://github.com/emtanribergenov/OS_labs/blob/master/4/screenshots/ffb.png)

Рис. 8. Браузер Firefox.

![](https://github.com/emtanribergenov/OS_labs/blob/master/4/screenshots/g.png)

Рис. 9. Тектовый редактор Gedit.

![](https://github.com/emtanribergenov/OS_labs/blob/master/4/screenshots/t.png)

Рис. 10. Эмулятор консоли (терминал).

Текстового процессора уже установленного в CentOS 8 нет, а загружать его
я не стал, т.к. не имею нужды.

# Вывод:

В результате лабораторной работы я получил практические навыки работы с
консолью и некоторыми графическими менеджерами рабочих столов
операционной системы.



# Ответы на вопросы:

1. Устройство, используемое для взаимодействия пользователя (или оператора) с компьютером или компьютерной системой. Быстрее. 
2. . название учётной записи пользователя
3. /etc/passwd. В зашифрованном виде
4.  в конфигурационных файлах. 
5. идентификатор 0
6. имеет
7. Все субъекты и объекты компьютерной системы должны быть однозначно идентифицированы 
8. права доступа, дата создания 
9. UID (User ID) - идентификатор пользователя в системе. GID (Group ID) -  идентификационный номер основной группы пользователя.
10.  Запись в файле / etc / passwd. Используется для записи общей информации об учетной записи или ее пользователях, таких как их настоящее имя и номер телефона.
11. Содержит пользовательские данные и пользовательские файлы конфигурации.
12. /home/emtanribergenov 
13. Имеет.
14. Логин, пароль и др инфа о пользователе
15. узнать права доступа
16.  Эмулятор терминала. Виртуальная консоль - консоль в GUI
17. Изначально Getty предназначалась для входа в систему с простых терминалов (dumb terminal). В настоящее время она в основном используется для входа в Linux с консоли.
18. запущенный экземпляр взаимодействия пользователя с системой.
19. инструментарий для управления абстрактными окнами 
20.  GTK+ ;  Qt 
