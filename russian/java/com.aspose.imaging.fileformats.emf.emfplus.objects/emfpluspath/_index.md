---
title: "EmfPlusPath"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Объект EmfPlusPath задает серию линейных и криволинейных сегментов, образующих графический путь."
type: docs
weight: 58
url: /ru/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspath/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusGraphicsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsobjecttype)
```
public final class EmfPlusPath extends EmfPlusGraphicsObjectType
```

Объект EmfPlusPath указывает серию линейных и криволинейных сегментов, образующих графический путь. Порядок точек данных Безье: начальная точка, контрольная точка 1, контрольная точка 2 и конечная точка. Для получения дополнительной информации см. [MSDN - DrawBeziers].
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfPlusPath()](#EmfPlusPath--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getPathPointFlags()](#getPathPointFlags--) | Получает или задает количество точек пути. 32-битное беззнаковое целое, которое указывает, как интерпретировать точки и связанные типы точек, определённые этим объектом. |
| [setPathPointFlags(short value)](#setPathPointFlags-short-) | Получает или задает количество точек пути. 32-битное беззнаковое целое, которое указывает, как интерпретировать точки и связанные типы точек, определённые этим объектом. |
| [getPathPoints()](#getPathPoints--) | Получает или задает массив точек пути. Массив из PathPointCount точек, определяющих путь. |
| [setPathPoints(PointF[] value)](#setPathPoints-com.aspose.imaging.PointF---) | Получает или задает массив точек пути. Массив из PathPointCount точек, определяющих путь. |
| [getPathPointTypes()](#getPathPointTypes--) | Получает или задает массив, который указывает, как точки в поле PathPoints используются для построения пути. |
| [setPathPointTypes(EmfPlusBasePointType[] value)](#setPathPointTypes-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBasePointType---) | Получает или задает массив, который указывает, как точки в поле PathPoints используются для построения пути. |
### EmfPlusPath() {#EmfPlusPath--}
```
public EmfPlusPath()
```


### getPathPointFlags() {#getPathPointFlags--}
```
public short getPathPointFlags()
```


Получает или задает количество точек пути. 32-битное беззнаковое целое, которое указывает, как интерпретировать точки и связанные типы точек, определённые этим объектом.

**Returns:**
short
### setPathPointFlags(short value) {#setPathPointFlags-short-}
```
public void setPathPointFlags(short value)
```


Получает или задает количество точек пути. 32-битное беззнаковое целое, которое указывает, как интерпретировать точки и связанные типы точек, определённые этим объектом.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | short |  |

### getPathPoints() {#getPathPoints--}
```
public PointF[] getPathPoints()
```


Получает или задает массив точек пути. Массив из PathPointCount точек, определяющих путь. Тип объектов в этом массиве задаётся полем PathPointFlags следующим образом: если установлен флаг P, точки являются относительными позициями, задаваемыми объектами EmfPlusPointR (раздел 2.2.2.37). Если флаг P сброшен и установлен флаг C, точки являются абсолютными позициями, задаваемыми объектами EmfPlusPoint (раздел 2.2.2.35). Если флаг P и флаг C сброшены, точки являются абсолютными позициями, задаваемыми объектами EmfPlusPointF (раздел 2.2.2.36).

**Returns:**
com.aspose.imaging.PointF[]
### setPathPoints(PointF[] value) {#setPathPoints-com.aspose.imaging.PointF---}
```
public void setPathPoints(PointF[] value)
```


Получает или задает массив точек пути. Массив из PathPointCount точек, определяющих путь. Тип объектов в этом массиве задаётся полем PathPointFlags следующим образом: если установлен флаг P, точки являются относительными позициями, задаваемыми объектами EmfPlusPointR (раздел 2.2.2.37). Если флаг P сброшен и установлен флаг C, точки являются абсолютными позициями, задаваемыми объектами EmfPlusPoint (раздел 2.2.2.35). Если флаг P и флаг C сброшены, точки являются абсолютными позициями, задаваемыми объектами EmfPlusPointF (раздел 2.2.2.36).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.imaging/pointf) |  |

### getPathPointTypes() {#getPathPointTypes--}
```
public EmfPlusBasePointType[] getPathPointTypes()
```


Получает или задает массив, который указывает, как точки в поле PathPoints используются для построения пути. Тип объектов в этом массиве задаётся флагом R в поле PathPointFlags.

Значение: типы точек пути.

**Returns:**
com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBasePointType[]
### setPathPointTypes(EmfPlusBasePointType[] value) {#setPathPointTypes-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBasePointType---}
```
public void setPathPointTypes(EmfPlusBasePointType[] value)
```


Получает или задает массив, который указывает, как точки в поле PathPoints используются для построения пути. Тип объектов в этом массиве задаётся флагом R в поле PathPointFlags.

Значение: типы точек пути.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [EmfPlusBasePointType\[\]](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasepointtype) |  |

