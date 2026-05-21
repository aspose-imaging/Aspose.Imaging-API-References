---
title: "EmfLogPen"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Объект LogPen определяет стиль, ширину и цвет логического пера."
type: docs
weight: 27
url: /ru/java/com.aspose.imaging.fileformats.emf.emf.objects/emflogpen/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfBasePen](../../com.aspose.imaging.fileformats.emf.emf.objects/emfbasepen)
```
public final class EmfLogPen extends EmfBasePen
```

Объект LogPen определяет стиль, ширину и цвет логического пера.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfLogPen()](#EmfLogPen--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getPenStyle()](#getPenStyle--) | Получает или задает 32-битное беззнаковое целое, которое определяет PenStyle. |
| [setPenStyle(int value)](#setPenStyle-int-) | Получает или задает 32-битное беззнаковое целое, которое определяет PenStyle. |
| [getWidth()](#getWidth--) | Получает или задает объект WMF PointL ([MS-WMF] раздел 2.2.2.15), который определяет ширину пера по значению его поля x. |
| [setWidth(Point value)](#setWidth-com.aspose.imaging.Point-) | Получает или задает объект WMF PointL ([MS-WMF] раздел 2.2.2.15), который определяет ширину пера по значению его поля x. |
| [getAffectWidth()](#getAffectWidth--) | Получает или задает ширину эффекта. |
| [setAffectWidth(int value)](#setAffectWidth-int-) | Получает или задает ширину эффекта. |
| [getArgb32ColorRef()](#getArgb32ColorRef--) | Получает или задает объект WMF ColorRef ([MS-WMF] раздел 2.2.2.8), который определяет значение цвета пера. |
| [setArgb32ColorRef(int value)](#setArgb32ColorRef-int-) | Получает или задает объект WMF ColorRef ([MS-WMF] раздел 2.2.2.8), который определяет значение цвета пера. |
### EmfLogPen() {#EmfLogPen--}
```
public EmfLogPen()
```


### getPenStyle() {#getPenStyle--}
```
public int getPenStyle()
```


Получает или задает 32-битное беззнаковое целое, которое определяет PenStyle. Значение ДОЛЖНО быть определено из таблицы перечисления PenStyle, указанной в разделе 2.1.25.

**Returns:**
int
### setPenStyle(int value) {#setPenStyle-int-}
```
public void setPenStyle(int value)
```


Получает или задает 32-битное беззнаковое целое, которое определяет PenStyle. Значение ДОЛЖНО быть определено из таблицы перечисления PenStyle, указанной в разделе 2.1.25.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getWidth() {#getWidth--}
```
public Point getWidth()
```


Получает или задает объект WMF PointL ([MS-WMF] раздел 2.2.2.15), который определяет ширину пера по значению его поля x. Значение его поля y ДОЛЖНО игнорироваться.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setWidth(Point value) {#setWidth-com.aspose.imaging.Point-}
```
public void setWidth(Point value)
```


Получает или задает объект WMF PointL ([MS-WMF] раздел 2.2.2.15), который определяет ширину пера по значению его поля x. Значение его поля y ДОЛЖНО игнорироваться.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getAffectWidth() {#getAffectWidth--}
```
public int getAffectWidth()
```


Получает или задает ширину эффекта.

Значение: Ширина эффекта.

**Returns:**
int
### setAffectWidth(int value) {#setAffectWidth-int-}
```
public void setAffectWidth(int value)
```


Получает или задает ширину эффекта.

Значение: Ширина эффекта.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getArgb32ColorRef() {#getArgb32ColorRef--}
```
public int getArgb32ColorRef()
```


Получает или задает объект WMF ColorRef ([MS-WMF] раздел 2.2.2.8), который определяет значение цвета пера.

Значение: 32-битный цвет ARGB

**Returns:**
int
### setArgb32ColorRef(int value) {#setArgb32ColorRef-int-}
```
public void setArgb32ColorRef(int value)
```


Получает или задает объект WMF ColorRef ([MS-WMF] раздел 2.2.2.8), который определяет значение цвета пера.

Значение: 32-битный цвет ARGB

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

