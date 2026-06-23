---
title: "EmfLogPen"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "كائن LogPen يحدد عرض النمط ولون القلم المنطقي."
type: docs
weight: 27
url: /ar/java/com.aspose.imaging.fileformats.emf.emf.objects/emflogpen/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfBasePen](../../com.aspose.imaging.fileformats.emf.emf.objects/emfbasepen)
```
public final class EmfLogPen extends EmfBasePen
```

كائن LogPen يحدد النمط والعرض واللون لقلم منطقي.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfLogPen()](#EmfLogPen--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getPenStyle()](#getPenStyle--) | يحصل أو يضبط عددًا صحيحًا غير موقع 32‑بت يحدد PenStyle. |
| [setPenStyle(int value)](#setPenStyle-int-) | يحصل أو يضبط عددًا صحيحًا غير موقع 32‑بت يحدد PenStyle. |
| [getWidth()](#getWidth--) | يحصل أو يضبط كائن WMF PointL ([MS-WMF] القسم 2.2.2.15) الذي يحدد عرض القلم بقيمة الحقل x. |
| [setWidth(Point value)](#setWidth-com.aspose.imaging.Point-) | يحصل أو يضبط كائن WMF PointL ([MS-WMF] القسم 2.2.2.15) الذي يحدد عرض القلم بقيمة الحقل x. |
| [getAffectWidth()](#getAffectWidth--) | يحصل أو يضبط عرض التأثير. |
| [setAffectWidth(int value)](#setAffectWidth-int-) | يحصل أو يضبط عرض التأثير. |
| [getArgb32ColorRef()](#getArgb32ColorRef--) | يحصل أو يضبط كائن WMF ColorRef ([MS-WMF] القسم 2.2.2.8) الذي يحدد قيمة لون القلم. |
| [setArgb32ColorRef(int value)](#setArgb32ColorRef-int-) | يحصل أو يضبط كائن WMF ColorRef ([MS-WMF] القسم 2.2.2.8) الذي يحدد قيمة لون القلم. |
### EmfLogPen() {#EmfLogPen--}
```
public EmfLogPen()
```


### getPenStyle() {#getPenStyle--}
```
public int getPenStyle()
```


يحصل أو يضبط عددًا صحيحًا غير موقع 32‑بت يحدد PenStyle. يجب أن تكون القيمة معرفة من جدول تعداد PenStyle، المحدد في القسم 2.1.25.

**Returns:**
int
### setPenStyle(int value) {#setPenStyle-int-}
```
public void setPenStyle(int value)
```


يحصل أو يضبط عددًا صحيحًا غير موقع 32‑بت يحدد PenStyle. يجب أن تكون القيمة معرفة من جدول تعداد PenStyle، المحدد في القسم 2.1.25.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getWidth() {#getWidth--}
```
public Point getWidth()
```


يحصل أو يعيّن كائن WMF PointL ([MS-WMF] القسم 2.2.2.15) الذي يحدد عرض القلم بقيمة الحقل x الخاص به. يجب تجاهل قيمة الحقل y.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setWidth(Point value) {#setWidth-com.aspose.imaging.Point-}
```
public void setWidth(Point value)
```


يحصل أو يعيّن كائن WMF PointL ([MS-WMF] القسم 2.2.2.15) الذي يحدد عرض القلم بقيمة الحقل x الخاص به. يجب تجاهل قيمة الحقل y.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getAffectWidth() {#getAffectWidth--}
```
public int getAffectWidth()
```


يحصل أو يضبط عرض التأثير.

القيمة: عرض التأثير.

**Returns:**
int
### setAffectWidth(int value) {#setAffectWidth-int-}
```
public void setAffectWidth(int value)
```


يحصل أو يضبط عرض التأثير.

القيمة: عرض التأثير.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getArgb32ColorRef() {#getArgb32ColorRef--}
```
public int getArgb32ColorRef()
```


يحصل أو يضبط كائن WMF ColorRef ([MS-WMF] القسم 2.2.2.8) الذي يحدد قيمة لون القلم.

القيمة: لون ARGB 32‑بت

**Returns:**
int
### setArgb32ColorRef(int value) {#setArgb32ColorRef-int-}
```
public void setArgb32ColorRef(int value)
```


يحصل أو يضبط كائن WMF ColorRef ([MS-WMF] القسم 2.2.2.8) الذي يحدد قيمة لون القلم.

القيمة: لون ARGB 32‑بت

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

