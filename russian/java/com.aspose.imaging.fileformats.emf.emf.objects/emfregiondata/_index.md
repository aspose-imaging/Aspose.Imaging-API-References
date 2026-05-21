---
title: "EmfRegionData"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Объект RegionData определяет данные, описывающие регион, состоящий из неперекрывающихся прямоугольников."
type: docs
weight: 33
url: /ru/java/com.aspose.imaging.fileformats.emf.emf.objects/emfregiondata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public final class EmfRegionData extends EmfObject
```

Объект RegionData указывает данные, определяющие регион, состоящий из неперекрывающихся прямоугольников.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfRegionData()](#EmfRegionData--) | Инициализирует новый экземпляр класса `EmfRegionData`. |
| [EmfRegionData(Rectangle rectangle)](#EmfRegionData-com.aspose.imaging.Rectangle-) | Инициализирует новый экземпляр класса `EmfRegionData`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getRegionDataHeader()](#getRegionDataHeader--) | Получает объект RegionDataHeader размером 256 бит, описывающий следующие данные. |
| [setRegionDataHeader(EmfRegionDataHeader value)](#setRegionDataHeader-com.aspose.imaging.fileformats.emf.emf.objects.EmfRegionDataHeader-) | Устанавливает объект RegionDataHeader размером 256 бит, описывающий следующие данные. |
| [getData()](#getData--) | Получает массив объектов WMF RectL ([MS-WMF] раздел 2.2.2.19); объекты объединяются для создания региона |
| [setData(Rectangle[] value)](#setData-com.aspose.imaging.Rectangle---) | Устанавливает массив объектов WMF RectL ([MS-WMF] раздел 2.2.2.19); объекты объединяются для создания региона |
### EmfRegionData() {#EmfRegionData--}
```
public EmfRegionData()
```


Инициализирует новый экземпляр класса `EmfRegionData`.

### EmfRegionData(Rectangle rectangle) {#EmfRegionData-com.aspose.imaging.Rectangle-}
```
public EmfRegionData(Rectangle rectangle)
```


Инициализирует новый экземпляр класса `EmfRegionData`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Прямоугольник. |

### getRegionDataHeader() {#getRegionDataHeader--}
```
public EmfRegionDataHeader getRegionDataHeader()
```


Получает объект RegionDataHeader размером 256 бит, описывающий следующие данные.

**Returns:**
[EmfRegionDataHeader](../../com.aspose.imaging.fileformats.emf.emf.objects/emfregiondataheader)
### setRegionDataHeader(EmfRegionDataHeader value) {#setRegionDataHeader-com.aspose.imaging.fileformats.emf.emf.objects.EmfRegionDataHeader-}
```
public void setRegionDataHeader(EmfRegionDataHeader value)
```


Устанавливает объект RegionDataHeader размером 256 бит, описывающий следующие данные.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [EmfRegionDataHeader](../../com.aspose.imaging.fileformats.emf.emf.objects/emfregiondataheader) |  |

### getData() {#getData--}
```
public Rectangle[] getData()
```


Получает массив объектов WMF RectL ([MS-WMF] раздел 2.2.2.19); объекты объединяются для создания региона

**Returns:**
com.aspose.imaging.Rectangle[]
### setData(Rectangle[] value) {#setData-com.aspose.imaging.Rectangle---}
```
public void setData(Rectangle[] value)
```


Устанавливает массив объектов WMF RectL ([MS-WMF] раздел 2.2.2.19); объекты объединяются для создания региона

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Rectangle\[\]](../../com.aspose.imaging/rectangle) |  |

