---
title: "XmpBasicPackage"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Представляет базовое пространство имён XMP."
type: docs
weight: 10
url: /ru/java/com.aspose.imaging.xmp.schemas.xmpbaseschema/xmpbasicpackage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.xmp.XmpPackage](../../com.aspose.imaging.xmp/xmppackage)
```
public class XmpBasicPackage extends XmpPackage
```

Представляет базовое пространство имён XMP.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [XmpBasicPackage()](#XmpBasicPackage--) | Инициализирует новый экземпляр класса `XmpBasicPackage`. |
| [XmpBasicPackage(String prefix, String namespaceUri)](#XmpBasicPackage-java.lang.String-java.lang.String-) | Инициализирует новый экземпляр класса `XmpBasicPackage`. |
## Поля

| Поле | Описание |
| --- | --- |
| [RATING_REJECTED](#RATING-REJECTED) | Оценка отклонённого значения. |
| [RATING_MIN](#RATING-MIN) | Минимальное значение оценки. |
| [RATING_MAX](#RATING-MAX) | Максимальное значение оценки. |
## Методы

| Метод | Описание |
| --- | --- |
| [setLabel(String label)](#setLabel-java.lang.String-) | Устанавливает метку. |
| [addValue(String key, String value)](#addValue-java.lang.String-java.lang.String-) | Добавляет строковое свойство. |
| [setCreatedDate(Date createdDate)](#setCreatedDate-java.util.Date-) | Добавляет дату создания ресурса. |
| [setCreatedDate(String createdDate)](#setCreatedDate-java.lang.String-) | Добавляет дату создания ресурса. |
| [setCreatorTool(String creatorTool)](#setCreatorTool-java.lang.String-) | Устанавливает инструмент создателя. |
| [setIdentifier(String[] identifier)](#setIdentifier-java.lang.String---) | Устанавливает идентификатор. |
| [setMetadataDate(Date metadataDate)](#setMetadataDate-java.util.Date-) | Добавляет дату последнего изменения метаданных. |
| [setMetadataDate(String metadataDate)](#setMetadataDate-java.lang.String-) | Добавляет дату последнего изменения метаданных. |
| [setModifyDate(Date modifiedDate)](#setModifyDate-java.util.Date-) | Добавляет дату последнего изменения ресурса. |
| [setModifyDate(String modifiedDate)](#setModifyDate-java.lang.String-) | Добавляет дату последнего изменения ресурса. |
| [setRating(int choice)](#setRating-int-) | Устанавливает оценку. |
### XmpBasicPackage() {#XmpBasicPackage--}
```
public XmpBasicPackage()
```


Инициализирует новый экземпляр класса `XmpBasicPackage`.

### XmpBasicPackage(String prefix, String namespaceUri) {#XmpBasicPackage-java.lang.String-java.lang.String-}
```
public XmpBasicPackage(String prefix, String namespaceUri)
```


Инициализирует новый экземпляр класса `XmpBasicPackage`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| префикс | java.lang.String | Префикс. |
| namespaceUri | java.lang.String | URI пространства имён. |

### RATING_REJECTED {#RATING-REJECTED}
```
public static final int RATING_REJECTED
```


Оценка отклонённого значения.

### RATING_MIN {#RATING-MIN}
```
public static final int RATING_MIN
```


Минимальное значение оценки.

### RATING_MAX {#RATING-MAX}
```
public static final int RATING_MAX
```


Максимальное значение оценки.

### setLabel(String label) {#setLabel-java.lang.String-}
```
public void setLabel(String label)
```


Устанавливает метку.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| метка | java.lang.String | Эта метка. |

### addValue(String key, String value) {#addValue-java.lang.String-java.lang.String-}
```
public void addValue(String key, String value)
```


Добавляет строковое свойство.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| ключ | java.lang.String | Строковое представление ключа, идентифицированного добавленным значением. |
| value | java.lang.String | Строковое значение. |

### setCreatedDate(Date createdDate) {#setCreatedDate-java.util.Date-}
```
public void setCreatedDate(Date createdDate)
```


Добавляет дату создания ресурса.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| createdDate | java.util.Date | Дата создания. |

### setCreatedDate(String createdDate) {#setCreatedDate-java.lang.String-}
```
public void setCreatedDate(String createdDate)
```


Добавляет дату создания ресурса.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| createdDate | java.lang.String | Дата создания. |

### setCreatorTool(String creatorTool) {#setCreatorTool-java.lang.String-}
```
public void setCreatorTool(String creatorTool)
```


Устанавливает инструмент создателя.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| creatorTool | java.lang.String | Название инструмента. |

### setIdentifier(String[] identifier) {#setIdentifier-java.lang.String---}
```
public void setIdentifier(String[] identifier)
```


Устанавливает идентификатор.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| identifier | java.lang.String[] | Идентификатор. |

### setMetadataDate(Date metadataDate) {#setMetadataDate-java.util.Date-}
```
public void setMetadataDate(Date metadataDate)
```


Добавляет дату последнего изменения метаданных.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| metadataDate | java.util.Date | Дата метаданных. |

### setMetadataDate(String metadataDate) {#setMetadataDate-java.lang.String-}
```
public void setMetadataDate(String metadataDate)
```


Добавляет дату последнего изменения метаданных.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| metadataDate | java.lang.String | Дата метаданных. |

### setModifyDate(Date modifiedDate) {#setModifyDate-java.util.Date-}
```
public void setModifyDate(Date modifiedDate)
```


Добавляет дату последнего изменения ресурса.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| modifiedDate | java.util.Date | Дата последнего изменения. |

### setModifyDate(String modifiedDate) {#setModifyDate-java.lang.String-}
```
public void setModifyDate(String modifiedDate)
```


Добавляет дату последнего изменения ресурса.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| modifiedDate | java.lang.String | Дата последнего изменения. |

### setRating(int choice) {#setRating-int-}
```
public void setRating(int choice)
```


Устанавливает оценку.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| choice | int | От -1 до 5 |

