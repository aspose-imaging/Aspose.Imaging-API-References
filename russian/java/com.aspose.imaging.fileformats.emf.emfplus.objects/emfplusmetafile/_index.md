---
title: "EmfPlusMetafile"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Объект EmfPlusMetafileData задает метафайл, содержащий графическое изображение."
type: docs
weight: 55
url: /ru/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusmetafile/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseImageData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbaseimagedata)
```
public final class EmfPlusMetafile extends EmfPlusBaseImageData
```

Объект EmfPlusMetafileData задает метафайл, содержащий графическое изображение.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfPlusMetafile()](#EmfPlusMetafile--) | Инициализирует новый экземпляр класса `EmfPlusMetafile`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getType()](#getType--) | Получает или задает 32-битное беззнаковое целое число, которое определяет тип метафайла, встроенного в поле MetafileData. |
| [setType(int value)](#setType-int-) | Получает или задает 32-битное беззнаковое целое число, которое определяет тип метафайла, встроенного в поле MetafileData. |
| [getMetafileDataSize()](#getMetafileDataSize--) | Получает или задает 32-битное беззнаковое целое число, которое определяет размер в байтах данных метафайла в поле MetafileData. |
| [setMetafileDataSize(int value)](#setMetafileDataSize-int-) | Получает или задает 32-битное беззнаковое целое число, которое определяет размер в байтах данных метафайла в поле MetafileData. |
| [getMetafileData()](#getMetafileData--) | Получает или задает переменной длины данные, которые определяют встроенный метафайл. |
| [setMetafileData(byte[] value)](#setMetafileData-byte---) | Получает или задает переменной длины данные, которые определяют встроенный метафайл. |
### EmfPlusMetafile() {#EmfPlusMetafile--}
```
public EmfPlusMetafile()
```


Инициализирует новый экземпляр класса `EmfPlusMetafile`.

### getType() {#getType--}
```
public int getType()
```


Получает или задает 32-битное беззнаковое целое число, которое определяет тип метафайла, встроенного в поле MetafileData. Это значение ДОЛЖНО быть определено в перечислении MetafileDataType (раздел 2.1.1.21).

**Returns:**
int
### setType(int value) {#setType-int-}
```
public void setType(int value)
```


Получает или задает 32-битное беззнаковое целое число, которое определяет тип метафайла, встроенного в поле MetafileData. Это значение ДОЛЖНО быть определено в перечислении MetafileDataType (раздел 2.1.1.21).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getMetafileDataSize() {#getMetafileDataSize--}
```
public int getMetafileDataSize()
```


Получает или задает 32-битное беззнаковое целое число, которое определяет размер в байтах данных метафайла в поле MetafileData.

**Returns:**
int
### setMetafileDataSize(int value) {#setMetafileDataSize-int-}
```
public void setMetafileDataSize(int value)
```


Получает или задает 32-битное беззнаковое целое число, которое определяет размер в байтах данных метафайла в поле MetafileData.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getMetafileData() {#getMetafileData--}
```
public byte[] getMetafileData()
```


Получает или задает переменной длины данные, которые определяют встроенный метафайл. Содержание и формат данных могут различаться для каждого типа метафайла.

Графические изображения задаются объектами EmfPlusImage (раздел 2.2.1.4). Объект EmfPlusMetafile ДОЛЖЕН присутствовать в поле ImageData объекта EmfPlusImage, если в его поле Type указано ImageTypeMetafile. Этот объект является универсальным и используется для различных типов данных, включая: WMF метафайл [MS-WMF]; WMF метафайл, который может быть размещён; EMF метафайл [MS-EMF]; EMF+ метафайл, который определяет графические операции только с записями EMF+; и EMF+ метафайл, который определяет графические операции как с записями EMF+, так и с записями EMF. См. раздел 2.2.2 для спецификации дополнительных структурных объектов.

**Returns:**
byte[]
### setMetafileData(byte[] value) {#setMetafileData-byte---}
```
public void setMetafileData(byte[] value)
```


Получает или задает переменной длины данные, которые определяют встроенный метафайл. Содержание и формат данных могут различаться для каждого типа метафайла.

Графические изображения задаются объектами EmfPlusImage (раздел 2.2.1.4). Объект EmfPlusMetafile ДОЛЖЕН присутствовать в поле ImageData объекта EmfPlusImage, если в его поле Type указано ImageTypeMetafile. Этот объект является универсальным и используется для различных типов данных, включая: WMF метафайл [MS-WMF]; WMF метафайл, который может быть размещён; EMF метафайл [MS-EMF]; EMF+ метафайл, который определяет графические операции только с записями EMF+; и EMF+ метафайл, который определяет графические операции как с записями EMF+, так и с записями EMF. См. раздел 2.2.2 для спецификации дополнительных структурных объектов.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte[] |  |

