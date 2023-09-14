---
## Front matter
lang: ru-RU
title: Презентация по защите лабораторной работы №3
subtitle: По предмету Математическое моделирование
author:
  - Максимов А. А.
institute:
  - Российский университет дружбы народов, Москва, Россия
date: 18 февраля 2023

## i18n babel
babel-lang: russian
babel-otherlangs: english

## Formatting pdf
toc: false
toc-title: Содержание
slide_level: 2
aspectratio: 169
section-titles: true
theme: metropolis
header-includes:
 - \metroset{progressbar=frametitle,sectionpage=progressbar,numbering=fraction}
 - '\makeatletter'
 - '\beamer@ignorenonframefalse'
 - '\makeatother'
---

# Информация

## Докладчик

:::::::::::::: {.columns align=center}
::: {.column width="70%"}

  * Максимов Алексей Александрович
  * профессор кафедры прикладной информатики и теории вероятностей
  * Российский университет дружбы народов
  * <https://github.com/Leximus555/study_2022-2023_mathmod/edit/master/labs>

:::
::::::::::::::

## Задача

Выполнить задания по созданию виртуальной машины.

## Ход работы

# Выполнение лабораторной работы
### Выполняем базовые настроки и создаем виртальную машину(репизиторий)

1. Установка имени
2. Памяти (20 гБ) динамический виртуальный диск
3. Образа машины
4. Оперативной памяти (2 гБ)
5. Создание репозитория


![image](image/1.PNG)

### Применяем начальные настройки машины
1. дату и время
2. Язык
3. Раскладку клавиатуры
4. Подключение к сети
5. Отключаем RDUMP


![image](image/2.PNG)

6. Пароль
7. Пользователя

![image](image/3.PNG)

### Устанавливаем драйвера для гостевой ОС

![image](image/4.PNG)

### Пробуем найти требемую информацию с помощью команды dmesg | grep -i "..."

![image](image/5.PNG)

## Вывод 

Поработали с Julia и OpenModelica и решили задачу.

