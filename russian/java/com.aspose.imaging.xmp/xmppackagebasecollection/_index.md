---
title: "XmpPackageBaseCollection"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Представляет коллекцию XmpPackage."
type: docs
weight: 20
url: /ru/java/com.aspose.imaging.xmp/xmppackagebasecollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public final class XmpPackageBaseCollection implements System.Collections.Generic.IGenericEnumerable<XmpPackage>
```

Представляет коллекцию `XmpPackage`.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [XmpPackageBaseCollection()](#XmpPackageBaseCollection--) | Инициализирует новый экземпляр класса `XmpPackageBaseCollection`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getCount()](#getCount--) | Получает количество элементов в коллекции. |
| [add(XmpPackage package_)](#add-com.aspose.imaging.xmp.XmpPackage-) | Добавляет новый экземпляр `XmpPackage`. |
| [remove(XmpPackage package_)](#remove-com.aspose.imaging.xmp.XmpPackage-) | Удаляет указанный пакет XMP. |
| [getPackages()](#getPackages--) | Получить массив `XmpPackage`. |
| [getPackage(String namespaceUri)](#getPackage-java.lang.String-) | Получает `XmpPackage` по его namespaceURI. |
| [clear()](#clear--) | Очищает все `XmpPackage` в коллекции. |
| [iterator()](#iterator--) | Возвращает перечислитель, который перебирает коллекцию. |
### XmpPackageBaseCollection() {#XmpPackageBaseCollection--}
```
public XmpPackageBaseCollection()
```


Инициализирует новый экземпляр класса `XmpPackageBaseCollection`.

### getCount() {#getCount--}
```
public int getCount()
```


Получает количество элементов в коллекции.

Значение: количество элементов в коллекции.

**Returns:**
int
### add(XmpPackage package_) {#add-com.aspose.imaging.xmp.XmpPackage-}
```
public void add(XmpPackage package_)
```


Добавляет новый экземпляр `XmpPackage`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| package_ | [XmpPackage](../../com.aspose.imaging.xmp/xmppackage) | XMP пакет\_ для добавления. |

### remove(XmpPackage package_) {#remove-com.aspose.imaging.xmp.XmpPackage-}
```
public void remove(XmpPackage package_)
```


Удаляет указанный пакет XMP.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| package_ | [XmpPackage](../../com.aspose.imaging.xmp/xmppackage) | XMP пакет\_ для удаления. |

### getPackages() {#getPackages--}
```
public XmpPackage[] getPackages()
```


Получить массив `XmpPackage`.

**Returns:**
com.aspose.imaging.xmp.XmpPackage[] - Возвращает массив пакетов XMP.
### getPackage(String namespaceUri) {#getPackage-java.lang.String-}
```
public XmpPackage getPackage(String namespaceUri)
```


Получает `XmpPackage` по его namespaceURI.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| namespaceUri | java.lang.String | URI пространства имён для получения пакет\_. |

**Returns:**
[XmpPackage](../../com.aspose.imaging.xmp/xmppackage) - Returns XMP package\_ for specified namespace Uri.
### clear() {#clear--}
```
public void clear()
```


Очищает все `XmpPackage` в коллекции.

### iterator() {#iterator--}
```
public System.Collections.Generic.List.Enumerator<XmpPackage> iterator()
```


Возвращает перечислитель, который перебирает коллекцию.

**Returns:**
com.aspose.ms.System.Collections.Generic.List.Enumerator<com.aspose.imaging.xmp.XmpPackage> - Объект `System.Collections.IEnumerator`, который можно использовать для перебора элементов коллекции.
