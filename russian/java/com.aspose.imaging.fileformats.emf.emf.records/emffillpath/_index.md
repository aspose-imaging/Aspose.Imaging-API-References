---
title: "EmfFillPath"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись EMR_FILLPATH закрывает все открытые фигуры в текущем пути и заполняет внутреннее пространство пути, используя текущую кисть и режим заполнения полигонов."
type: docs
weight: 58
url: /ru/java/com.aspose.imaging.fileformats.emf.emf.records/emffillpath/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfFillPath extends EmfDrawingRecordType
```

Запись EMR\_FILLPATH закрывает все открытые фигуры в текущем пути и заполняет внутреннюю часть пути, используя текущую кисть и режим заполнения полигонов.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfFillPath(EmfRecord source)](#EmfFillPath-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Инициализирует новый экземпляр класса `EmfFillPath`. |
| [EmfFillPath()](#EmfFillPath--) | Инициализирует новый экземпляр класса `EmfFillPath`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getBounds()](#getBounds--) | Получает или задает 128-битный объект WMF RectL, указанный в разделе [MS-WMF] 2.2.2.19, который определяет ограничивающий прямоугольник в единицах устройства. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Получает или задает 128-битный объект WMF RectL, указанный в разделе [MS-WMF] 2.2.2.19, который определяет ограничивающий прямоугольник в единицах устройства. |
### EmfFillPath(EmfRecord source) {#EmfFillPath-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfFillPath(EmfRecord source)
```


Инициализирует новый экземпляр класса `EmfFillPath`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Источник. |

### EmfFillPath() {#EmfFillPath--}
```
public EmfFillPath()
```


Инициализирует новый экземпляр класса `EmfFillPath`.

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


Получает или задает 128-битный объект WMF RectL, указанный в разделе [MS-WMF] 2.2.2.19, который определяет ограничивающий прямоугольник в единицах устройства.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


Получает или задает 128-битный объект WMF RectL, указанный в разделе [MS-WMF] 2.2.2.19, который определяет ограничивающий прямоугольник в единицах устройства.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

