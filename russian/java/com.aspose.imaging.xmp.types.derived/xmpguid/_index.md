---
title: "XmpGuid"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Представляет глобальный уникальный идентификатор XMP."
type: docs
weight: 14
url: /ru/java/com.aspose.imaging.xmp.types.derived/xmpguid/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.xmp.types.XmpTypeBase](../../com.aspose.imaging.xmp.types/xmptypebase)
```
public final class XmpGuid extends XmpTypeBase
```

Представляет глобальный уникальный идентификатор XMP.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [XmpGuid(String value)](#XmpGuid-java.lang.String-) | Инициализирует новый экземпляр класса `XmpGuid`. |
| [XmpGuid(UUID guid)](#XmpGuid-java.util.UUID-) | Инициализирует новый экземпляр класса `XmpGuid`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getPrefix()](#getPrefix--) | Получает или задает префикс, например uuid. |
| [setPrefix(String value)](#setPrefix-java.lang.String-) | Получает или задает префикс, например uuid. |
| [getValue()](#getValue--) | Получает или задает значение. |
| [setValue(UUID value)](#setValue-java.util.UUID-) | Получает или задает значение. |
| [getXmpRepresentation()](#getXmpRepresentation--) | Получает строковое значение в формате XMP. |
### XmpGuid(String value) {#XmpGuid-java.lang.String-}
```
public XmpGuid(String value)
```


Инициализирует новый экземпляр класса `XmpGuid`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Значение. |

### XmpGuid(UUID guid) {#XmpGuid-java.util.UUID-}
```
public XmpGuid(UUID guid)
```


Инициализирует новый экземпляр класса `XmpGuid`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| guid | java.util.UUID | Уникальный идентификатор. |

### getPrefix() {#getPrefix--}
```
public String getPrefix()
```


Получает или задает префикс, например uuid.

Значение: Префикс, например uuid.

**Returns:**
java.lang.String
### setPrefix(String value) {#setPrefix-java.lang.String-}
```
public void setPrefix(String value)
```


Получает или задает префикс, например uuid.

Значение: Префикс, например uuid.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getValue() {#getValue--}
```
public UUID getValue()
```


Получает или задает значение.

Значение: Значение.

**Returns:**
java.util.UUID
### setValue(UUID value) {#setValue-java.util.UUID-}
```
public void setValue(UUID value)
```


Получает или задает значение.

Значение: Значение.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.util.UUID |  |

### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


Получает строковое значение в формате XMP.

**Returns:**
java.lang.String - Возвращает строковое значение в формате XMP.
