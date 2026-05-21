---
title: "XmpBoolean"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Представляет базовый тип Boolean XMP."
type: docs
weight: 10
url: /ru/java/com.aspose.imaging.xmp.types.basic/xmpboolean/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.xmp.types.XmpTypeBase](../../com.aspose.imaging.xmp.types/xmptypebase)
```
public final class XmpBoolean extends XmpTypeBase
```

Представляет базовый тип Boolean XMP.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [XmpBoolean(boolean value)](#XmpBoolean-boolean-) | Инициализирует новый экземпляр класса `XmpBoolean` на основе логического значения. |
| [XmpBoolean()](#XmpBoolean--) | Инициализирует новый экземпляр класса `XmpBoolean` со значением по умолчанию. |
| [XmpBoolean(String value)](#XmpBoolean-java.lang.String-) | Инициализирует новый экземпляр класса `XmpBoolean`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getValue()](#getValue--) | Получает или задает значение, указывающее, является ли этот `XmpBoolean` значением. |
| [setValue(boolean value)](#setValue-boolean-) | Получает или задает значение, указывающее, является ли этот `XmpBoolean` значением. |
| [getXmpRepresentation()](#getXmpRepresentation--) | Возвращает строковое значение в формате XMP. |
### XmpBoolean(boolean value) {#XmpBoolean-boolean-}
```
public XmpBoolean(boolean value)
```


Инициализирует новый экземпляр класса `XmpBoolean` на основе логического значения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | Логическое значение. Допустимые значения: True или False. |

### XmpBoolean() {#XmpBoolean--}
```
public XmpBoolean()
```


Инициализирует новый экземпляр класса `XmpBoolean` со значением по умолчанию.

### XmpBoolean(String value) {#XmpBoolean-java.lang.String-}
```
public XmpBoolean(String value)
```


Инициализирует новый экземпляр класса `XmpBoolean`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Значение. |

### getValue() {#getValue--}
```
public boolean getValue()
```


Получает или задает значение, указывающее, является ли этот `XmpBoolean` значением.

Значение: `true`, если значение; иначе `false`.

**Returns:**
boolean
### setValue(boolean value) {#setValue-boolean-}
```
public void setValue(boolean value)
```


Получает или задает значение, указывающее, является ли этот `XmpBoolean` значением.

Значение: `true`, если значение; иначе `false`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


Возвращает строковое значение в формате XMP.

**Returns:**
java.lang.String - Возвращает строку, содержащую представление xmp.
