---
title: "XmpElementBase"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Представляет базовый элемент xmp, содержащий атрибуты."
type: docs
weight: 16
url: /ru/java/com.aspose.imaging.xmp/xmpelementbase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable
```
public abstract class XmpElementBase implements System.IEquatable<XmpElementBase>
```

Представляет базовый элемент xmp, содержащий атрибуты.
## Методы

| Метод | Описание |
| --- | --- |
| [addAttribute(String attribute, String value)](#addAttribute-java.lang.String-java.lang.String-) | Добавляет атрибут. |
| [getAttribute(String attribute)](#getAttribute-java.lang.String-) | Получает атрибут. |
| [clearAttributes()](#clearAttributes--) | Удаляет все атрибуты. |
| [isEquals(XmpElementBase other)](#isEquals-com.aspose.imaging.xmp.XmpElementBase-) | Указывает, равен ли текущий объект другому объекту того же типа. |
| [equals(Object obj)](#equals-java.lang.Object-) | Определяет, равен ли указанный `Object` этому экземпляру. |
| [hashCode()](#hashCode--) | Возвращает хеш-код для этого экземпляра. |
### addAttribute(String attribute, String value) {#addAttribute-java.lang.String-java.lang.String-}
```
public void addAttribute(String attribute, String value)
```


Добавляет атрибут.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| атрибут | java.lang.String | Атрибут. |
| value | java.lang.String | Значение. |

### getAttribute(String attribute) {#getAttribute-java.lang.String-}
```
public String getAttribute(String attribute)
```


Получает атрибут.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| атрибут | java.lang.String | Атрибут. |

**Returns:**
java.lang.String - Возвращает атрибут для указанного имени атрибута.
### clearAttributes() {#clearAttributes--}
```
public void clearAttributes()
```


Удаляет все атрибуты.

### isEquals(XmpElementBase other) {#isEquals-com.aspose.imaging.xmp.XmpElementBase-}
```
public boolean isEquals(XmpElementBase other)
```


Указывает, равен ли текущий объект другому объекту того же типа.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| other | [XmpElementBase](../../com.aspose.imaging.xmp/xmpelementbase) | Объект для сравнения с этим объектом. |

**Returns:**
boolean - true, если текущий объект равен параметру `other`; в противном случае false.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Определяет, равен ли указанный `Object` этому экземпляру.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | java.lang.Object | Объект `Object` для сравнения с этим экземпляром. |

**Returns:**
логический тип - `true`, если указанный `Object` равен этому экземпляру; иначе `false`.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Возвращает хеш-код для этого экземпляра.

**Returns:**
int — хеш-код для этого экземпляра, пригодный для использования в алгоритмах хеширования и структурах данных, таких как хеш-таблица.
