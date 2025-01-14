[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://github.com/victorizbitskiy/zru_number_validation/blob/main/LICENSE)
![ABAP 7.4+](https://img.shields.io/badge/ABAP-7.4%2B-brightgreen)

<img src="https://github.com/victorizbitskiy/abapTechDocu/blob/main/logo/logo.png" height="100px"/>\
<a href="https://www.flaticon.com/authors/itim2101">Designed by itim2101/Flaticon</a>

**В процессе разработки...**  

Переводы:
- [:ru: На английском языке](https://github.com/victorizbitskiy/abapTechDocu) 

## `abapTechDocu`
Инструмент, который поможет вам создать техническую документацию на разработку.

# Оглавление
1. [Что это такое?](#что-это-такое?)
2. [Для чего это нужно?](#для-чего-это-нужно)
3. [Установка](#установка)
4. [Использование](#использование)

## Что это такое?
Это классический отчет (report), который собирает и отображает информацию о созданных/измененных в процессе разработки объектах.

## Для чего это нужно?
Часто при создании технической документации требуется указать объекты, созданные или измененные в системе. Делать это вручную - долго и утомительно, 
поэтому я хотел найти способ автоматизировать это. Я нашел инструмент для создания <a href="https://github.com/victorizbitskiy/CUSTTOOL"> настроечной </a> документации, 
но не нашел инструмента, который бы автоматизировал сбор информации о созданных объектах разработки. Поэтому я создал его сам.

## Установка
Для установки используйте [abapGit](http://www.abapgit.org).

## Использование
Просто  запустите отчет **`ztechdocu`** и укажите на селекционном экране транспортные запросы.
В результате вы получите список всех существующих объектов из запроса с описанием. Например, как здесь:

![result](https://github.com/victorizbitskiy/abapTechDocu/blob/main/docs/img/example_1.png)

Далее можно, например, выгрузить эти данные в файл.
