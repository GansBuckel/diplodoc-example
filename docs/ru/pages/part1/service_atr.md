# Служебные характеристики

Служебные характеристики имеют зарезервированные номера, обрабатываются головным модулем ПК «ГИС Нева» специальным образом и не требуют описания в Классификаторе.

Использование номеров служебных характеристик в пользовательских классификаторах для объектов карты нецелесообразно, так как может привести к непредсказуемым последствиям.

Для служебных характеристик зарезервирован диапазон номеров от 900 до 1023. К служебным характеристикам не относятся характеристики метаданных паспорта карты (номенклатура, имя карты, масштаб и т.п.). Номера паспортных характеристик могут использоваться в пользовательских классификаторах.

Часть служебных характеристик используется при организации хранения информации цифровых карт объектной модели во внешней объектно-ориентированной базе данных пространственных объектов (БДПО).

В представленной ниже таблице содержится список и описание служебных характеристик. Для типов данных характеристик используются следующие обозначения:

К – комплексный (составной) тип (в графе типа данных в скобках указаны номера внутренних атрибутов)
Т– текстовая строка
Ц – длинное целое число
Ч – дробное число
Б – байт

| Номер | Акроним | Наименование                                          | Тип<br>данных | Описание применения                                                                                                                                                                                                                        |
|:-----:|:-------:|-------------------------------------------------------|:-------------:|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 994   | extID   | Значения  глобальных идентификаторов других объектов | Т             | Содержит значение глобального идентификатора (GUID) другого объекта. Атрибут является реализацией специальной связи между объектами. Используется для предъявления другого объекта в центре экрана по указанному в атрибуте значению GUID. |
| 995   |  —      | Признак выгруженного объекта из базы данных           | Б             | Всем объектам, выгружаемым из БДПО, головной модуль присваивает автоматически значение характеристики =1. Атрибут используется для загрузки объектов обратно в базу данных.                                                                |
| 996   | guIDs   | История глобальных идентификаторов объектов          | К (999)       | Комплексный атрибут, объединяющий значения глобальных идентификаторов объекта, накапливаемые при операциях сшивки и деления объекта.                                                                                                       |
| 998   | mapID   | Идентификатор карты                                   | Т             | Глобальный уникальный идентификатор, присваиваемый цифровой карте.                                                                                                                                                                         |
| 999   | guID    | Глобальный уникальный идентификатор объекта           | Т             | Обязательно присваивается объекту карты перед выгрузкой в БДПО или другие цифровые карты. Присваивается объектам-связям, комплексным и координированным атрибутам.                                                                         |
| 1000  | —       | Внутренний локальный идентификатор объекта            | Ц             | Является уникальным значением в пределах карты. Присваивается всем объектам карты при их создании. Не присваивается специальным объектам (внутренние контуры, связи, координированные и комплексные атрибуты).                            |
| 1000  | locID   | Внешний локальный идентификатор объекта               | К (1000,&nbsp;998)  | Комплексный атрибут, объединяющий непосредственно значения локальных идентификаторов объектов и идентификаторов соответствующих им карт.                                                                                                   |
| 1001  | valID   | Значение локального идентификатора                    | Ц             | Значение локального идентификатора во внешнем локальном идентификаторе и в объекте-связи для ответного объекта.                                                                                                                            |
| 1002  |  —      | Признак исходного/ целевого объекта в связи           | Б             | В объекте связи указывает признак исходного/целевого объекта. Принимает значения: 1 – данный объект исходный в связи, 2 – данный объект целевой в связи.                                                                                   |
| 1003  |  —      | Тип связи                                             | Б             | В объекте-связи указывает тип связи. Принимает значения: 1- ассоциация, 2 – агрегация, 3 – композиция.                                                                                                                                     |

