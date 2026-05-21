---
title: "XmpCollection"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Коллекция элементов XMP."
type: docs
weight: 15
url: /ru/java/com.aspose.imaging.xmp/xmpcollection/
---
**Inheritance:**
java.lang.Object, java.util.AbstractCollection, java.util.AbstractList, java.util.ArrayList

**All Implemented Interfaces:**
[com.aspose.imaging.xmp.types.IXmpType](../../com.aspose.imaging.xmp.types/ixmptype)
```
public class XmpCollection extends ArrayList<IXmpType> implements IXmpType
```

Коллекция элементов XMP.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [XmpCollection()](#XmpCollection--) | Инициализирует новый экземпляр класса [XmpCollection](../../com.aspose.imaging.xmp/xmpcollection). |
## Методы

| Метод | Описание |
| --- | --- |
| [addItem(Object item)](#addItem-java.lang.Object-) | Добавляет новый элемент. |
| [addObject(Object item)](#addObject-java.lang.Object-) | Добавляет элемент данных XMP. |
| [removeAt(int index)](#removeAt-int-) | Удаляет элемент по указанному индексу. |
| [add(IXmpType item)](#add-com.aspose.imaging.xmp.types.IXmpType-) | Добавляет элемент в коллекцию. |
| [copyTo(IXmpType[] array, int arrayIndex)](#copyTo-com.aspose.imaging.xmp.types.IXmpType---int-) | Копирует элементы коллекции в массив, начиная с определённого индекса массива. |
| [getXmpRepresentation()](#getXmpRepresentation--) | Получает строковое значение XMP этого объекта. |
| [getXmlValue()](#getXmlValue--) | Преобразует значение XMP в XML-представление. |
| [toString()](#toString--) | Возвращает XML‑строку, представляющую этот экземпляр. |
### XmpCollection() {#XmpCollection--}
```
public XmpCollection()
```


Инициализирует новый экземпляр класса [XmpCollection](../../com.aspose.imaging.xmp/xmpcollection).

### addItem(Object item) {#addItem-java.lang.Object-}
```
public final void addItem(Object item)
```


Добавляет новый элемент.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| элемент | java.lang.Object | Элемент, который будет добавлен в список элементов. |

### addObject(Object item) {#addObject-java.lang.Object-}
```
public final void addObject(Object item)
```


Добавляет элемент данных XMP.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| элемент | java.lang.Object | Элемент XMP. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Удаляет элемент по указанному индексу.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Нулевой индекс элемента, который нужно удалить. |

### add(IXmpType item) {#add-com.aspose.imaging.xmp.types.IXmpType-}
```
public final boolean add(IXmpType item)
```


Добавляет элемент в коллекцию.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [IXmpType](../../com.aspose.imaging.xmp.types/ixmptype) | Объект, который нужно добавить в коллекцию. |

**Returns:**
boolean
### copyTo(IXmpType[] array, int arrayIndex) {#copyTo-com.aspose.imaging.xmp.types.IXmpType---int-}
```
public final void copyTo(IXmpType[] array, int arrayIndex)
```


Копирует элементы коллекции в массив, начиная с определённого индекса массива.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| array | [IXmpType\[\]](../../com.aspose.imaging.xmp.types/ixmptype) | Одномерный массив, который является получателем элементов, скопированных из коллекции. Массив должен иметь нулевую индексацию. |
| arrayIndex | int | Нулевой индекс в массиве, с которого начинается копирование. |

### getXmpRepresentation() {#getXmpRepresentation--}
```
public final String getXmpRepresentation()
```


Получает строковое значение XMP этого объекта.

**Returns:**
java.lang.String - Возвращает строковое значение в формате XMP.
### getXmlValue() {#getXmlValue--}
```
public final String getXmlValue()
```


Преобразует значение XMP в XML-представление.

**Returns:**
java.lang.String — Возвращает значение XMP, преобразованное в XML-представление.
### toString() {#toString--}
```
public String toString()
```


Возвращает XML‑строку, представляющую этот экземпляр.

**Returns:**
java.lang.String - XML-строка, представляющая этот экземпляр.
