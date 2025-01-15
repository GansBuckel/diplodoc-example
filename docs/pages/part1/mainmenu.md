# Часть 1<br>Общее описание 

 ОБЩАЯ ИНФОРМАЦИЯ .......................................................... 4
1.1
Назначение .............................................................................................................................................. 4
1.2
Аппаратные и системные требования ............................................................................................... 4
1.3
Состав....................................................................................................................................................... 4
1.3.1
Базовые программные средства ........................................................................................................ 4
1.3.2
Классификатор цифровой карты ....................................................................................................... 5
1.3.2.1
Картографическая модель ........................................................................................................... 5
1.3.2.2
Объектная модель ........................................................................................................................ 5
1.3.2.3
Структура и содержание Классификатора ................................................................................ 6
1.4
Правила размещения на компьютере ................................................................................................ 8
1.4.1
Основная папка ................................................................................................................................... 8
1.4.2
Рабочая папка ..................................................................................................................................... 8
1.4.3
Размещение программных и технологических файлов .................................................................. 8
1.5
Установка ПК и запуск головного программного модуля ........................................................... 10
2 ОСНОВНЫЕ ПОНЯТИЯ ......................................................... 11
2.1
Цифровая карта ................................................................................................................................... 11
2.2
Типы цифровых карт .......................................................................................................................... 11
2.3
Структурная модель карты ............................................................................................................... 11
2.3.1
Иерархическое дерево карты........................................................................................................... 11
2.3.2
Корневой объект и паспорт карты .................................................................................................. 12
2.3.3
Слои карты ........................................................................................................................................ 13
2.3.3.1
Общее описание слоя ................................................................................................................ 13
2.3.3.2
Создание слоёв и управление слоями карты ........................................................................... 13
2.3.4
Объекты карты.................................................................................................................................. 14
2.4
Объект цифровой карты .................................................................................................................... 15
2.4.1
Виды объектов .................................................................................................................................. 17
2.4.1.1
Пространственный объект (геообъект) .................................................................................... 18
2.4.1.1.1
Объект типа «Знак» ........................................................................................................... 19
2.4.1.1.2
Объект типа «Линия» ........................................................................................................ 19
2.4.1.1.3
Объект типа «Область»..................................................................................................... 20
2.4.1.1.4
Объект «Без метрики» ...................................................................................................... 20
2.4.1.2
Объект «Меню» ......................................................................................................................... 21
2.4.1.3
Объект «Координированный атрибут» .................................................................................... 21
2.4.1.4
Объект «Подпись» ..................................................................................................................... 22
2.4.1.5
Объект «Информация» .............................................................................................................. 23
2.4.2
Локальная и глобальная идентификация объекта ......................................................................... 23
2.4.3
Атрибутивное описание ................................................................................................................... 24
2.4.3.1
Простые атрибуты ..................................................................................................................... 24
2.4.3.2
Атрибуты перечислимого типа ................................................................................................ 25
2.4.3.3
Множественность и обязательность значений атрибутов...................................................... 28
2.4.3.4
Ограничения на значения атрибутов или сочетания значений.............................................. 28
2.4.3.5
Составной/комплексный атрибут ............................................................................................. 29
2.4.3.6
Использование атрибутов из таблиц внешних баз данных .................................................... 30
2.4.4
Координатное описание объектов .................................................................................................. 33
2.4.4.1
Картографическое «спагетти» .................................................................................................. 33
2.4.4.2
Цепочно-узловая структура ...................................................................................................... 33
2.4.4.3
Z-координаты в метрике объекта ............................................................................................. 34
2.4.4.4
Основное и дополнительное координатное описание объекта ............................................. 34
2.4.4.5
Специальные типы координатного описания линий и областей ........................................... 34
2.4.4.6
Специальный тип объекта – «массив глубин» ........................................................................ 35
2.4.5
Описание и установление отношений (связей) между объектами .............................................. 35
2.4.5.1
Связи между объектами в картографической модели ............................................................ 35
2.4.5.2
Отношения и связи между объектами в объектной модели .................................................. 35
2.4.5.3
Координатное описание связи между объектами ................................................................... 37
2.4.6
Кодовые обозначения видов и типов объектов ............................................................................. 38
2.5
Привязка карты к местности ............................................................................................................ 38
2.6
Проект карт и активная карта .......................................................................................................... 39
2.7
Правила описания условных логических выражений ................................................................. 41
2.7.1
Вычисляемые переменные и функции ........................................................................................... 41
2.7.1.1
Переменные для свойств объекта ............................................................................................. 42
2.7.1.2
Переменные и функции для свойств атрибутов...................................................................... 42
3
2.7.1.3
Контекстный анализ содержимого текстовых атрибутов ...................................................... 43
2.7.1.4
Логические утверждения для атрибутов перечислимого типа и атрибутов-связей с
внешней базой данных ........................................................................................................................................... 44
2.7.1.5
Логические утверждения для комплексных атрибутов .......................................................... 45
2.7.1.6
Функции для свойств связей между объектами ...................................................................... 47
2.8
Описание метаданных ........................................................................................................................ 47
2.9
Служебные характеристики .............................................................................................................. 49
3 ОСНОВНОЕ МЕНЮ ГОЛОВНОГО ПРОГРАММНОГО
МОДУЛЯ .................................................................................................... 52
3.1
Заголовок ............................................................................................................................................... 52
3.2
Функциональное меню ....................................................................................................................... 52
3.2.1
Настройка вызова программных приложений ............................................................................... 52
3.3
Панель инструментов редактирования ........................................................................................... 54
3.4
Информационная строка .................................................................................................................... 55
4 ПРИЛОЖЕНИЕ 1. ТЕРМИНЫ И ОПРЕДЕЛЕНИЯ .......... 57
5 ПРИЛОЖЕНИЕ 2. ПРАВИЛА ЧТЕНИЯ UML-
ДИАГРАММ .............................................................................................. 59