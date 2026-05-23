---
title: "PhotoshopPackage Класс"
type: docs
weight: 20
url: /ru/python-net/aspose.imaging.xmp.schemas.photoshop/photoshoppackage/
---

**Summary:** Represents Adobe Photoshop namespace.

**Module:** [aspose.imaging.xmp.schemas.photoshop](/imaging/python-net/aspose.imaging.xmp.schemas.photoshop/)

**Full Name:** aspose.imaging.xmp.schemas.photoshop.PhotoshopPackage

**Inheritance:** IXmlValue, XmpPackage

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [PhotoshopPackage()](#PhotoshopPackage__1) | Инициализирует новый экземпляр [PhotoshopPackage](/imaging/python-net/aspose.imaging.xmp.schemas.photoshop/photoshoppackage/) класса. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| URGENCY_MAX [статический] | int | r | Максимальное значение срочности. |
| URGENCY_MIN [статический] | int | r | Минимальное значение срочности. |
| count | int | r | Получает количество ключей XMP. |
| namespace_uri | string | r | Получает URI пространства имён. |
| prefix | string | r | Получает префикс. |
| xml_namespace | string | r | Получает XML‑пространство имён. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_value(key, value)](#add_value_key_value_1) | Добавляет строковое свойство. |
| [add_value(key, value)](#add_value_key_value_2) | Добавляет строковое свойство. |
| clear() | Очищает этот экземпляр. |
| [contains_key(key)](#contains_key_key_3) | Определяет, содержит ли эта коллекция указанный ключ. |
| [get_prop_value(key)](#get_prop_value_key_4) | Получает объект с указанным ключом. |
| [get_xml_value()](#get_xml_value__5) | Преобразует значение XMP в XML‑представление. |
| [remove(key)](#remove_key_6) | Удаляет значение с указанным ключом. |
| [set_authors_position(authors_position)](#set_authors_position_authors_position_7) | Устанавливает позицию автора. |
| [set_caption_writer(caption_writer)](#set_caption_writer_caption_writer_8) | Устанавливает автора подписи. |
| [set_category(category)](#set_category_category_9) | Устанавливает категорию. |
| [set_city(city)](#set_city_city_10) | Устанавливает город. |
| [set_color_mode(color_mode)](#set_color_mode_color_mode_11) | Устанавливает режим цвета. |
| [set_country(country)](#set_country_country_12) | Устанавливает страну. |
| [set_created_date(created_date)](#set_created_date_created_date_13) | Устанавливает дату создания. |
| [set_credit(credit)](#set_credit_credit_14) | Устанавливает кредит. |
| [set_document_ancestors(ancestors)](#set_document_ancestors_ancestors_15) | Устанавливает предков документа. |
| [set_headline(headline)](#set_headline_headline_16) | Устанавливает заголовок. |
| [set_history(history)](#set_history_history_17) | Устанавливает историю. |
| [set_icc_profile(icc_profile)](#set_icc_profile_icc_profile_18) | Устанавливает icc профиль. |
| [set_instructions(instructions)](#set_instructions_instructions_19) | Устанавливает инструкции. |
| [set_prop_value(key, value)](#set_prop_value_key_value_20) | Получает или задаёт объект с указанным ключом. |
| [set_source(source)](#set_source_source_21) | Устанавливает источник. |
| [set_state(state)](#set_state_state_22) | Устанавливает штат. |
| [set_supplemental_categories(supplemental_categories)](#set_supplemental_categories_supplemental_categories_23) | Устанавливает дополнительные категории. |
| [set_transmission_reference(transmission_reference)](#set_transmission_reference_transmission_reference_24) | Устанавливает ссылку передачи. |
| [set_urgency(urgency)](#set_urgency_urgency_25) | Устанавливает срочность. |
| [set_value(key, value)](#set_value_key_value_26) | Устанавливает значение. |
| [set_value(key, value)](#set_value_key_value_27) | Устанавливает значение. |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_28) | Устанавливает значение типа XMP. |
| [try_get_value(key, value)](#try_get_value_key_value_29) | Получает значение по _key_. |


### Constructor: PhotoshopPackage() {#PhotoshopPackage__1}


```
 PhotoshopPackage() 
```

Инициализирует новый экземпляр [PhotoshopPackage](/imaging/python-net/aspose.imaging.xmp.schemas.photoshop/photoshoppackage/) класса.

### Method: add_value(key, value) {#add_value_key_value_1}


```
 add_value(key, value) 
```

Добавляет строковое свойство.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| key | string | Строковое представление ключа, которое идентифицируется добавленным значением. |
| значение | string | Строковое значение. |

### Method: add_value(key, value) {#add_value_key_value_2}


```
 add_value(key, value) 
```

Добавляет строковое свойство.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| key | string | Строковое представление ключа, которое идентифицируется добавленным значением. |
| значение | System.Object | Строковое значение. |

### Method: contains_key(key) {#contains_key_key_3}


```
 contains_key(key) 
```

Определяет, содержит ли эта коллекция указанный ключ.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| key | string | Ключ для проверки. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | **True** если объект содержит указанный ключ; иначе, **False**. |


### Method: get_prop_value(key) {#get_prop_value_key_4}


```
 get_prop_value(key) 
```

Получает объект с указанным ключом.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| key | string | Ключ, идентифицирующий значение. |

**Returns**

| Тип | Описание |
| :- | :- |
| System.Object | Возвращает объект с указанным ключом. |


### Method: get_xml_value() {#get_xml_value__5}


```
 get_xml_value() 
```

Преобразует значение XMP в XML‑представление.

**Returns**

| Тип | Описание |
| :- | :- |
| string | Возвращает значение XMP, преобразованное в представление XML. |


### Method: remove(key) {#remove_key_6}


```
 remove(key) 
```

Удаляет значение с указанным ключом.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| key | string | Строковое представление ключа, связанного с удалённым значением. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | Возвращает true, если значение с указанным ключом было удалено. |


### Method: set_authors_position(authors_position) {#set_authors_position_authors_position_7}


```
 set_authors_position(authors_position) 
```

Устанавливает позицию автора.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| authors_position | string | Позиция авторов. |

### Method: set_caption_writer(caption_writer) {#set_caption_writer_caption_writer_8}


```
 set_caption_writer(caption_writer) 
```

Устанавливает автора подписи.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| caption_writer | string | Автор подписи. |

### Method: set_category(category) {#set_category_category_9}


```
 set_category(category) 
```

Устанавливает категорию.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| category | string | Категория. |

### Method: set_city(city) {#set_city_city_10}


```
 set_city(city) 
```

Устанавливает город.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| city | string | Название города. |

### Method: set_color_mode(color_mode) {#set_color_mode_color_mode_11}


```
 set_color_mode(color_mode) 
```

Устанавливает режим цвета.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| color_mode | [ColorMode](/imaging/python-net/aspose.imaging.xmp.schemas.photoshop/colormode/) | Режим цвета. |

### Method: set_country(country) {#set_country_country_12}


```
 set_country(country) 
```

Устанавливает страну.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| country | string | Страна. |

### Method: set_created_date(created_date) {#set_created_date_created_date_13}


```
 set_created_date(created_date) 
```

Устанавливает дату создания.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| created_date | System.DateTime | Дата создания. |

### Method: set_credit(credit) {#set_credit_credit_14}


```
 set_credit(credit) 
```

Устанавливает кредит.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| credit | string | Кредит. |

### Method: set_document_ancestors(ancestors) {#set_document_ancestors_ancestors_15}


```
 set_document_ancestors(ancestors) 
```

Устанавливает предков документа.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| ancestors | string[] | Предки. |

### Method: set_headline(headline) {#set_headline_headline_16}


```
 set_headline(headline) 
```

Устанавливает заголовок.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| headline | string | Заголовок. |

### Method: set_history(history) {#set_history_history_17}


```
 set_history(history) 
```

Устанавливает историю.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| history | string | История. |

### Method: set_icc_profile(icc_profile) {#set_icc_profile_icc_profile_18}


```
 set_icc_profile(icc_profile) 
```

Устанавливает icc профиль.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| icc_profile | string | ICC‑профиль. |

### Method: set_instructions(instructions) {#set_instructions_instructions_19}


```
 set_instructions(instructions) 
```

Устанавливает инструкции.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| instructions | string | Инструкции. |

### Method: set_prop_value(key, value) {#set_prop_value_key_value_20}


```
 set_prop_value(key, value) 
```

Получает или задаёт объект с указанным ключом.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| key | string | Ключ, идентифицирующий значение. |
| значение | System.Object | Объект с указанным ключом. |

### Method: set_source(source) {#set_source_source_21}


```
 set_source(source) 
```

Устанавливает источник.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| источник | string | Источник. |

### Method: set_state(state) {#set_state_state_22}


```
 set_state(state) 
```

Устанавливает штат.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| состояние | string | Состояние. |

### Method: set_supplemental_categories(supplemental_categories) {#set_supplemental_categories_supplemental_categories_23}


```
 set_supplemental_categories(supplemental_categories) 
```

Устанавливает дополнительные категории.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| дополнительные_категории | string[] | Дополнительные категории. |

### Method: set_transmission_reference(transmission_reference) {#set_transmission_reference_transmission_reference_24}


```
 set_transmission_reference(transmission_reference) 
```

Устанавливает ссылку передачи.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| ссылка_на_передачу | string | Ссылка на передачу. |

### Method: set_urgency(urgency) {#set_urgency_urgency_25}


```
 set_urgency(urgency) 
```

Устанавливает срочность.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| срочность | int | Срочность. |

### Method: set_value(key, value) {#set_value_key_value_26}


```
 set_value(key, value) 
```

Устанавливает значение.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| key | string | Строковое представление ключа, которое идентифицируется добавленным значением. |
| value | [IXmlValue](/imaging/python-net/aspose.imaging.xmp/ixmlvalue/) | Значение для добавления. |

### Method: set_value(key, value) {#set_value_key_value_27}


```
 set_value(key, value) 
```

Устанавливает значение.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| key | string | Строковое представление ключа, которое идентифицируется добавленным значением. |
| value | [IXmpType](/imaging/python-net/aspose.imaging.xmp.types/ixmptype/) | Значение для добавления. |

### Method: set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_28}


```
 set_xmp_type_value(key, value) 
```

Устанавливает значение типа XMP.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| key | string | Строковое представление ключа, связанного с установленным значением. |
| value | [XmpTypeBase](/imaging/python-net/aspose.imaging.xmp.types/xmptypebase/) | Значение для установки. |

### Method: try_get_value(key, value) {#try_get_value_key_value_29}


```
 try_get_value(key, value) 
```

Получает значение по _key_.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| key | string | Ключ элемента XMP. |
| значение | System.Object | Значение XMP. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | **True**, если содержит _key_; иначе **False**. |


