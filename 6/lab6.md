---
# Front matter
lang: ru-RU
title: Анализ файловой системы Linux. Команды для работы с файлами и каталогами
subtitle: ЛР по ОС №6
author: Танрибергенов Эльдар Марсович
group: НПИбд-02-20
---




> Отчёт
>
> о выполнении лабораторной работы № 6.

### Анализ файловой системы Linux. Команды для работы с файлами и каталогами



#### Выполнил:

студент группы НПИбд-02-20

Танрибергенов Эльдар Марсович.

Студ. билет № 1032208074

Москва 2021 г.



# Цель работы:

-   Ознакомление с файловой системой Linux, её структурой, именами и
    содержанием каталогов. Приобретение практических навыков по
    применению команд для работы с файлами и каталогами, по управлению
    процессами (и работами), по проверке использования диска и
    обслуживанию файловой системы.

# Задание:

1\. Выполните все примеры, приведённые в первой части описания
лабораторной работы.

2\. Выполните следующие действия, зафиксировав в отчёте по лабораторной
работе используемые при этом команды и результаты их выполнения:

2.1. Скопируйте файл /usr/include/sys/io.h в домашний каталог и назовите
его equipment. Если файла io.h нет, то используйте любой другой файл в
каталоге /usr/include/sys/ вместо него.

2.2. В домашнем каталоге создайте директорию \~/ski.plases.

2.3. Переместите файл equipment в каталог \~/ski.plases.

2.4. Переименуйте файл \~/ski.plases/equipment в
\~/ski.plases/equiplist.

2.5. Создайте в домашнем каталоге файл abc1 и скопируйте его в каталог
\~/ski.plases, назовите его equiplist2.

2.6. Создайте каталог с именем equipment в каталоге \~/ski.plases.

2.7. Переместите файлы \~/ski.plases/equiplist и equiplist2 в каталог
\~/ski.plases/equipment.

2.8. Создайте и переместите каталог \~/newdir в каталог \~/ski.plases и
назовите его plans.

3\. Определите опции команды chmod, необходимые для того, чтобы присвоить
перечисленным ниже файлам выделенные права доступа, считая, что в начале
таких прав нет:

3.1. drwxr\--r\-- \... australia

3.2. drwx\--x\--x \... play

3.3. -r-xr\--r\-- \... my\_os

3.4. -rw-rw-r\-- \... feathers При необходимости создайте нужные файлы.

4\. Проделайте приведённые ниже упражнения, записывая в отчёт по
лабораторной работе используемые при этом команды:

4.1. Просмотрите содержимое файла /etc/password.

4.2. Скопируйте файл \~/feathers в файл \~/file.old.

4.3. Переместите файл \~/file.old в каталог \~/play.

4.4. Скопируйте каталог \~/play в каталог \~/fun.

4.5. Переместите каталог \~/fun в каталог \~/play и назовите его games.

4.6. Лишите владельца файла \~/feathers права на чтение.

4.7. Что произойдёт, если вы попытаетесь просмотреть файл \~/feathers
командой cat?

4.8. Что произойдёт, если вы попытаетесь скопировать файл \~/feathers?

4.9. Дайте владельцу файла \~/feathers право на чтение.

4.10. Лишите владельца каталога \~/play права на выполнение.

4.11. Перейдите в каталог \~/play. Что произошло?

4.12. Дайте владельцу каталога \~/play право на выполнение.

5\. Прочитайте man по командам mount, fsck, mkfs, kill и кратко их
охарактеризуйте, приведя примеры.

# Ход работы:

![](https://github.com/emtanribergenov/OS_labs/blob/master/6/screenshots/1.png)

![](https://github.com/emtanribergenov/OS_labs/blob/master/6/screenshots/2.png)

![](https://github.com/emtanribergenov/OS_labs/blob/master/6/screenshots/3.png)

![](https://github.com/emtanribergenov/OS_labs/blob/master/6/screenshots/4.png)

![](https://github.com/emtanribergenov/OS_labs/blob/master/6/screenshots/5.png)

![](https://github.com/emtanribergenov/OS_labs/blob/master/6/screenshots/6.png)

![](https://github.com/emtanribergenov/OS_labs/blob/master/6/screenshots/7.png)

![](https://github.com/emtanribergenov/OS_labs/blob/master/6/screenshots/8.png)



После присвоения прав к обозначенным файлам провёл проверку путём вывода
подробной информации по файлам и каталогам посредством команды ls --l.
Всем файлам были правильно присвоены указанные в л.р. права.

![](https://github.com/emtanribergenov/OS_labs/blob/master/6/screenshots/9.png)

![](https://github.com/emtanribergenov/OS_labs/blob/master/6/screenshots/10.png)

![](https://github.com/emtanribergenov/OS_labs/blob/master/6/screenshots/11.png)



Конечно, после лишения владельца файла feathers на чтение просмотр
содержимого этого файла и его копирование невозможно.

Также, после лишения права владельца на выполнения каталога play
перемещение в данный каталог
невозможно.

![](https://github.com/emtanribergenov/OS_labs/blob/master/6/screenshots/12.png)

Из справок по данным командам стало известно:

-   mount служит для присоединения файловой системы с какого-либо
    устройства к большому файловому дереву.

-   fsck служит для проверки и починки файловой системы Linux

-   mkfs служит для создания файловой системы Linux

-   kill служит для «уничтожения» завершения процесса

# Вывод:

В результате лабораторной работы я ознакомился с файловой системой
Linux, её структурой, именами и содержанием каталогов. Приобрёл
практические навыки по применению команд для работы с файлами и
каталогами, по управлению процессами (и работами), по проверке
использования диска и обслуживанию файловой системы.



# Ответы на вопросы:

1. **XFS** - это высокопроизводительная файловая система. Рассчитана на файлы большого размера, и поддерживала диски до 2 Терабайт. Из преимуществ файловой системы можно отметить высокую скорость работы с большими файлами, отложенное выделение места, увеличение разделов на лету и незначительный размер служебной информации. XFS - журналируемая файловая система, однако в отличие от ext, в журнал записываются только изменения метаданных. Она используется по умолчанию в дистрибутивах на основе Red Hat. Из недостатков - это невозможность уменьшения размера, сложность восстановления данных и риск потери файлов при записи, если будет неожиданное отключение питания, поскольку большинство данных находится в памяти.

   Другие файловые системы, такие как **NTFS, FAT, HFS** могут использоваться в Linux, но корневая файловая система linux на них не устанавливается, поскольку они для этого не предназначены.

2.  Файловая система в Linux определяет организацию расположения файлов, по сути представляя собой иерархическую структуру «дерева»: начинается с корневого каталога «/» и разрастается ветвями в зависимости от работы системы.. 

3.  создать новую запись в каталоге, указывающую на индексный узел файла; увеличить счетчик связей в индексном узле. 

4. насильственное прерывание операций ввода-вывода, выполняемых непосредственно с диском, нарушения работы дискового кэша

5.  Файловая система создается при форматировании дисков 

6.  cat - выводит в стандартный вывод

7. копирование 

8.  mv - переименование источника в DEST или перемещение в каталог. 

9.  Чтобы получить доступ к файлам в Linux, используются разрешения. Эти разрешения назначаются трем объектам: файлу, группе и всем остальным. Используется команда chmod

