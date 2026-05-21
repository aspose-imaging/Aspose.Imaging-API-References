---
title: "EmfPlusHatchBrushData"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Объект EmfPlusHatchBrushData задает штриховой узор для графической кисти."
type: docs
weight: 45
url: /ru/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplushatchbrushdata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseBrushData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasebrushdata)
```
public final class EmfPlusHatchBrushData extends EmfPlusBaseBrushData
```

Объект EmfPlusHatchBrushData задает штриховой узор для графической кисти.

Графические кисти задаются объектами `EmfPlusBrush` (раздел 2.2.1.1). Кисть штриховки рисует фон и наносит шаблон из линий, точек, тире, квадратов и перекрестных штрихов над этим фоном. Кисть штриховки определяет два цвета: один для фона и один для шаблона над фоном. Цвет фона называется цветом фона, а цвет шаблона — цветом переднего плана.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfPlusHatchBrushData()](#EmfPlusHatchBrushData--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getBackArgb32Color()](#getBackArgb32Color--) | Получает или задает 32-битный объект EmfPlusArgb, который определяет цвет, используемый для закраски фона шаблона штриховки. |
| [setBackArgb32Color(int value)](#setBackArgb32Color-int-) | Получает или задает 32-битный объект EmfPlusArgb, который определяет цвет, используемый для закраски фона шаблона штриховки. |
| [getForeArgb32Color()](#getForeArgb32Color--) | Получает или задает 32-битный объект EmfPlusArgb, который определяет цвет, используемый для рисования линий шаблона штриховки. |
| [setForeArgb32Color(int value)](#setForeArgb32Color-int-) | Получает или задает 32-битный объект EmfPlusArgb, который определяет цвет, используемый для рисования линий шаблона штриховки. |
| [getHatchStyle()](#getHatchStyle--) | Получает или задает 32-битное беззнаковое целое, которое определяет стиль штриховки кисти. |
| [setHatchStyle(int value)](#setHatchStyle-int-) | Получает или задает 32-битное беззнаковое целое, которое определяет стиль штриховки кисти. |
### EmfPlusHatchBrushData() {#EmfPlusHatchBrushData--}
```
public EmfPlusHatchBrushData()
```


### getBackArgb32Color() {#getBackArgb32Color--}
```
public int getBackArgb32Color()
```


Получает или задает 32-битный объект EmfPlusArgb, который определяет цвет, используемый для закраски фона шаблона штриховки.

**Returns:**
int
### setBackArgb32Color(int value) {#setBackArgb32Color-int-}
```
public void setBackArgb32Color(int value)
```


Получает или задает 32-битный объект EmfPlusArgb, который определяет цвет, используемый для закраски фона шаблона штриховки.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getForeArgb32Color() {#getForeArgb32Color--}
```
public int getForeArgb32Color()
```


Получает или задает 32-битный объект EmfPlusArgb, который определяет цвет, используемый для рисования линий шаблона штриховки.

**Returns:**
int
### setForeArgb32Color(int value) {#setForeArgb32Color-int-}
```
public void setForeArgb32Color(int value)
```


Получает или задает 32-битный объект EmfPlusArgb, который определяет цвет, используемый для рисования линий шаблона штриховки.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getHatchStyle() {#getHatchStyle--}
```
public int getHatchStyle()
```


Получает или задает 32-битное беззнаковое целое, которое определяет стиль штриховки кисти. Оно ДОЛЖНО быть определено в перечислении `EmfPlusHatchStyle`.

**Returns:**
int
### setHatchStyle(int value) {#setHatchStyle-int-}
```
public void setHatchStyle(int value)
```


Получает или задает 32-битное беззнаковое целое, которое определяет стиль штриховки кисти. Оно ДОЛЖНО быть определено в перечислении `EmfPlusHatchStyle`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

