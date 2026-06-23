---
title: "EmfPlusPath"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "كائن EmfPlusPath يحدد سلسلة من مقاطع الخط والمنحنى التي تشكل مسارًا رسوميًا."
type: docs
weight: 58
url: /ar/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspath/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusGraphicsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsobjecttype)
```
public final class EmfPlusPath extends EmfPlusGraphicsObjectType
```

كائن EmfPlusPath يحدد سلسلة من مقاطع الخط والمنحنى التي تشكل مسارًا رسوميًا. ترتيب نقاط بيانات بيزيير هو نقطة البداية، نقطة التحكم 1، نقطة التحكم 2، ونقطة النهاية. لمزيد من المعلومات راجع[MSDN - DrawBeziers].
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfPlusPath()](#EmfPlusPath--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getPathPointFlags()](#getPathPointFlags--) | يحصل أو يعيّن Path points count عدد صحيح غير موقع 32-بت يحدد كيفية تفسير النقاط وأنواع النقاط المرتبطة التي تم تعريفها بواسطة هذا الكائن |
| [setPathPointFlags(short value)](#setPathPointFlags-short-) | يحصل أو يعيّن Path points count عدد صحيح غير موقع 32-بت يحدد كيفية تفسير النقاط وأنواع النقاط المرتبطة التي تم تعريفها بواسطة هذا الكائن |
| [getPathPoints()](#getPathPoints--) | يحصل أو يعيّن array of path points مصفوفة من نقاط PathPointCount التي تحدد المسار. |
| [setPathPoints(PointF[] value)](#setPathPoints-com.aspose.imaging.PointF---) | يحصل أو يعيّن array of path points مصفوفة من نقاط PathPointCount التي تحدد المسار. |
| [getPathPointTypes()](#getPathPointTypes--) | يحصل أو يعيّن مصفوفة تحدد كيفية استخدام النقاط في حقل PathPoints لرسم المسار. |
| [setPathPointTypes(EmfPlusBasePointType[] value)](#setPathPointTypes-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBasePointType---) | يحصل أو يعيّن مصفوفة تحدد كيفية استخدام النقاط في حقل PathPoints لرسم المسار. |
### EmfPlusPath() {#EmfPlusPath--}
```
public EmfPlusPath()
```


### getPathPointFlags() {#getPathPointFlags--}
```
public short getPathPointFlags()
```


يحصل أو يعيّن Path points count عدد صحيح غير موقع 32-بت يحدد كيفية تفسير النقاط وأنواع النقاط المرتبطة التي تم تعريفها بواسطة هذا الكائن

**Returns:**
قصير
### setPathPointFlags(short value) {#setPathPointFlags-short-}
```
public void setPathPointFlags(short value)
```


يحصل أو يعيّن Path points count عدد صحيح غير موقع 32-بت يحدد كيفية تفسير النقاط وأنواع النقاط المرتبطة التي تم تعريفها بواسطة هذا الكائن

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | قصير |  |

### getPathPoints() {#getPathPoints--}
```
public PointF[] getPathPoints()
```


يحصل أو يعيّن array of path points مصفوفة من نقاط PathPointCount التي تحدد المسار. نوع الكائنات في هذه المصفوفة يتم تحديده بواسطة حقل PathPointFlags، كما يلي: إذا كان علم P مفعلاً، تكون النقاط مواقع نسبية يتم تحديدها بواسطة كائنات EmfPlusPointR (القسم 2.2.2.37). إذا كان علم P غير مفعّل وعلم C مفعلاً، تكون النقاط مواقع مطلقة يتم تحديدها بواسطة كائنات EmfPlusPoint (القسم 2.2.2.35). إذا كان علم P غير مفعّل وعلم C غير مفعّل، تكون النقاط مواقع مطلقة يتم تحديدها بواسطة كائنات EmfPlusPointF (القسم 2.2.2.36).

**Returns:**
com.aspose.imaging.PointF[]
### setPathPoints(PointF[] value) {#setPathPoints-com.aspose.imaging.PointF---}
```
public void setPathPoints(PointF[] value)
```


يحصل أو يعيّن array of path points مصفوفة من نقاط PathPointCount التي تحدد المسار. نوع الكائنات في هذه المصفوفة يتم تحديده بواسطة حقل PathPointFlags، كما يلي: إذا كان علم P مفعلاً، تكون النقاط مواقع نسبية يتم تحديدها بواسطة كائنات EmfPlusPointR (القسم 2.2.2.37). إذا كان علم P غير مفعّل وعلم C مفعلاً، تكون النقاط مواقع مطلقة يتم تحديدها بواسطة كائنات EmfPlusPoint (القسم 2.2.2.35). إذا كان علم P غير مفعّل وعلم C غير مفعّل، تكون النقاط مواقع مطلقة يتم تحديدها بواسطة كائنات EmfPlusPointF (القسم 2.2.2.36).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.imaging/pointf) |  |

### getPathPointTypes() {#getPathPointTypes--}
```
public EmfPlusBasePointType[] getPathPointTypes()
```


يحصل أو يعيّن مصفوفة تحدد كيفية استخدام النقاط في حقل PathPoints لرسم المسار. نوع الكائنات في هذه المصفوفة يتم تحديده بواسطة علم R في حقل PathPointFlags

القيمة: أنواع نقاط المسار.

**Returns:**
com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBasePointType[]
### setPathPointTypes(EmfPlusBasePointType[] value) {#setPathPointTypes-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBasePointType---}
```
public void setPathPointTypes(EmfPlusBasePointType[] value)
```


يحصل أو يعيّن مصفوفة تحدد كيفية استخدام النقاط في حقل PathPoints لرسم المسار. نوع الكائنات في هذه المصفوفة يتم تحديده بواسطة علم R في حقل PathPointFlags

القيمة: أنواع نقاط المسار.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [EmfPlusBasePointType\[\]](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasepointtype) |  |

