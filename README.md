# LR6
Лабораторная работа №6


## Цель лабораторной работы:
Изучение базовых возможностей системного управления версиями, опыт работы с Git Api, опыт работы с локальным и удаленным репозиторием.


## Ход работы


### Операции


$ git log --pretty=format:"%h - %ad -%an: %s" --date=short

8d191ad - 2023-11-17 -Nataxtare: The file is changed

1f11455 - 2023-11-17 -Nataxtare: Resolved the conflict

4b37555 - 2023-11-17 -Nataxtare: Add files via upload

921f53b - 2020-11-21 -Kurtyanik: Обновление информации

0f9f50d - 2020-11-21 -Kurtyanik: Заполнил файл

c08a654 - 2020-11-21 -Kurtyanik: Файл создан пустым

3c6e913 - 2020-11-21 -Kurtyanik: Initial commit


### Лог команды

cd labop

git clone https://github.com/Nataxtare/LR6

cd LR6

git pull

git log --all

git log -n 1

git merge origin/branch1

git status

cat mergefile.txt

git add .

git commit -m «Разрешил конфликт»

git push origin -d Branch1

git add .

git commit -m «Файл был изменен»

git add .

git commit -m «Файл был изменен снова»

git reset --hard HEAD^

git checkout -b new_branch

git log --pretty=format:"%h - %ad - %an: %s" --date=short

git add .

git commit -m "Окончательный"

git push origin new_branch


### Изображения


Переход в папку labop

![s1](https://github.com/Nataxtare/LR6/blob/master/imgs/1.png)

Клонирование репозитория

Переход в каталог LR6, который был создан после клонирования репозитория

![s2](https://github.com/Nataxtare/LR6/blob/master/imgs/2.png)

Получение обновлений из удаленного репозитория

Просмотр истории коммитов в репозитории

![s3](https://github.com/Nataxtare/LR6/blob/master/imgs/3.png)

Просмотр последнего коммита

Слияние изменений из удаленной ветки ветки 1 в текущую ветку

Проверка состояния рабочего каталога

Просмотр корректировки файлов

![s4](https://github.com/Nataxtare/LR6/blob/master/imgs/5.png)

Добавление всех измененных файлов

Фиксация изменений в локальном репозитории

Отмена последнего коммита и удаление всех изменений

Создание и переключение на новую ветку new_branch

Добавление всех измененных файлов

Фиксация первых этапов работы и второго

Просмотр истории коммитов в кратком формате

Добавление всех измененных файлов

Фиксация конечных изменений

Отправка изменений в новую ветку new_branch

![s6](https://github.com/Nataxtare/LR6/blob/master/imgs/6.png)


## Вывод:
Я изучила базовые возможности системы управления версиями, получила опыт работы с Git Api и опыт работы с локальным и удаленным репозиторием.



