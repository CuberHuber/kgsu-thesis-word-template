# Умная библиография (список источников)
Инструкция по применению системы библиографии Zotero и стиля цитирования по ГОСТу.

----------
## Содержание
1. [Введение](#Введение)
2. [Зависимости](#Зависимости)
3. [Особенности](#Особенности)
4. [Установка](#Установка)
5. [Использование](#Использование)

-------
## Введение
Этот кастомный стиль сделан для помощи в оформлении списка литературы и цитирования при помощи системы Zotero.
За основу взялся стиль от автора [Романа Распопова](https://github.com/romanraspopov/GOST-styles-for-Zotero), который был доработан.
Для подробного ознакомления с особенностями заполнения полей для каждого типа библиографии рекомендуется прочитать инструкции в [репозитории](https://github.com/romanraspopov/GOST-styles-for-Zotero) автора базового стиля.

## Зависимости
Далее описаны шаги, которые необходимо выполнить перед продолжением ознакомления с инструкцией:
1. Ознакомится с [Zotero](https://www.zotero.org/download/) и установить ее на свой пк
2. Добавить расширение Zotero в свой браузер и MS Word

## Особенности
1. Стиль не имеет нумерации (это нужно для того, чтобы можно было настроить ее в редакторе).
2. Поддержка Русского и Английского языков при формировании WEB источника (`[Электронный ресурс]` для русского источника и `[Electronic source]` для английского источника, соответственно).

### Пример автосгенерированно библиографии
```text
Дик Д.И. Дипломное проектирование : учебное пособие / Д.И. Дик. – Курган: Издательство Курганского государственного университета, 2018. – 148 с.
Saporta G. Practical Fraud Prevention / G. Saporta, S. Maraney Google-Books-ID: CZ1kEAAAQBAJ. – O’Reilly Media, Inc., 2022. – 397 с.
DM32.2. The GQL Manifesto / DM32.2. – 2018.
Object Management Group. Unified Modeling Language v2.5.1 / Object Management Group. – 2017.
Payment Card Industry Security Standards Council. Payment Card Industry Data Security Standard v3.2.1 / Payment Card Industry Security Standards Council. – 2018.
Visa, a trusted leader in digital payments [Electronic source]. – URL: https://usa.visa.com/ (access date: 10.05.2024).
Концептуальное обоснование проекта, Классы и характеристики пользователей - Автоматизация деятельности отдела продаж в логистической компании [Электронный ресурс]. – URL: https://vuzlit.com/789804/kontseptualnoe_obosnovanie_proekta (дата обращения: 12.06.2024).
```

## Установка

### Шаг 1: Скачать стиль

1. Перейди в [GitHub репозиторий](https://github.com/CuberHuber/kgsu-thesis-word-template).
2. Шажми на кнопку `Code` и выбери `Download ZIP`.
3. Распаку архив на пк и найди файлы с расширением `.csl`.

### Шаг 2: Добавление стиля в Zotero

1. Открой Zotero.
2. Выбери `Edit` > `Preferences` (на Windows) или `Zotero` > `Preferences` (на macOS).
3. Выбери `Cite` tab.
4. Нажми на `Styles` tab.
5. Нажми на кнопку `+`.
6. Проследуй в распакованный архив и выбери файл стиля (`.csl` файл).
7. Нажми `Open` для добавление стиля в Zotero.

## Использование

1. Открой свою библиотеку Zotero.
2. Выбери элементы для цитирования.
3. ПКМ по элементу и выбери `Create Bibliography from Items`.
4. Выбери кастомный стиль по названию.
5. Выбери формат вывода (RTF, HTML или в буфер обмена).
6. Нажми `OK` для генерации библиографии.