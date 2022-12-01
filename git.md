* git config --global user.name <имя пользователя>
* git config --global user.email <email пользователя>
* git init - инициализация репозитория
* git add - добавление нового файла и изменения (git будет отслеживать эти изменения)
* git status - статус репозитория
* git commit -m "сообщение" - добавление комита.
* git log - просмотр комитов в репозитории
* git branch - посмотреть список веток в репозитории 
* git branch -d <название ветки> удалить ветку 
* git branch <Название ветки> создать новую ветку 
* git checkout <название ветки> переход к другой ветки
* git reset - команда отменяет комита или проиндексированного файла/происходит откат изменений в несохранённые изменения 
* git revert - откат к предыдущему комиту и сохранение
* git merge <branch> - команда обьединения ветки. Выполняется из главной ветки . куда необходимо вливать ветку.
* git clone <url адрес> - клонирование удалённого репозитория
* git push - отправка локального репозитория на удалённый.
* git pull - загрузка изменений с удалённого репозитория и локального репозитория
* 
# Инструкция по работе с Markdown

## Заголовки 
 в зависимости от кол-ва решёток перед текстом 

# h1 

###### h6  

## Шрифт 
__Жирный__

**Тоже жирный**

*Курсив*

_Тоже курсив_

~~Зачеркнутый~~

~~__*жирный курсив зачёркнутый*__~~

## Списки
  * Добавляем звёздочку для ненумерованного списка 
  - Или минус 
  1. Для нумерованного списка просто ставим цифры

## Картинка 
 Добавляем картинку в папку с git и пишем в следующих полях текст и имя файла картинки 
 
 Например : 

![какая то игра](arc.jpg)

## Ссылка
 Для создания ссылки необходимо в квадратные скобки разместить текст ссылки , а в круглые url-адрес.
 
 Например: [Кинопоиск](https://www.kinopoisk.ru/)

## Цитата 
 Для того что бы добавить цитату необходимо перед ней поставить обратную скобку (>)

Например: 

> цитата
>> вложенная цитата
>>> вложения можно делать и со списками)

## Таблица

|  таблица | дефисы  | 
| --------- | ------ |
| выравннивают | и разделяют |
| столбец | невидно |
 