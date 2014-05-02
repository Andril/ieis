#Сайт института  Э и ИБ  -  СНУЯЭ и П

<a href="https://travis-ci.org/Samael500/ieis"><img src="https://travis-ci.org/Samael500/ieis.svg" data-bindattr-78="78" title="Build Status Images"></a>

Web site of the Institute of  Environmental and Information Security,<br>
Sevastopol University of Nuclear Energy and Industry.

###Зависимости

* python-pip
* python-virtualenv
* git

```bash
$ apt-get install <зависимость>
```

###Виртуальное окружение

######Установка
```bash
# 1. перейти в каталог проекта
$ cd ~/snunei/ieis
# 2. создать директорию виртуального окружения
$ mkdir venv
# 3. создать виртуальное окружение
$ virtualenv --no-site-packages --prompt="(ieis)" venv
```
######Работа
```bash
$ . venv/bin/activate  # запуск
$ deactivate           # остановка
```

###Установка и запуск проекта

```bash
$ make pipinstall  # установка зависимостей
$ make runserver   # запуск dev сервера
```
