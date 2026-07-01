---
title: "الطبقة"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يمثل طبقة نص Photoshop."
type: docs
weight: 11
url: /ar/java/com.aspose.imaging.xmp.schemas.photoshop/layer/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.xmp.types.XmpTypeBase](../../com.aspose.imaging.xmp.types/xmptypebase)

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable
```
public class Layer extends XmpTypeBase implements System.IEquatable<Layer>
```

يمثل طبقة نص Photoshop.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [Layer(String layerName, String layerText)](#Layer-java.lang.String-java.lang.String-) | يقوم بتهيئة نسخة جديدة من الفئة `Layer`. |
| [Layer()](#Layer--) | يقوم بتهيئة نسخة جديدة من الفئة `Layer`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getName()](#getName--) | يحصل أو يضبط اسم طبقة النص. |
| [setName(String value)](#setName-java.lang.String-) | يحصل أو يضبط اسم طبقة النص. |
| [getText()](#getText--) | يحصل أو يضبط محتوى النص للطبقة. |
| [setText(String value)](#setText-java.lang.String-) | يحصل أو يضبط محتوى النص للطبقة. |
| [getXmpRepresentation()](#getXmpRepresentation--) | يرجع القيمة المحتواة كسلسلة بصيغة XMP. |
| [equals(Object obj)](#equals-java.lang.Object-) | يحدد ما إذا كان `System.Object` المحدد يساوي هذه النسخة. |
| [isEquals(Layer other)](#isEquals-com.aspose.imaging.xmp.schemas.photoshop.Layer-) | يشير إلى ما إذا كان الكائن الحالي يساوي كائنًا آخر من نفس النوع. |
| [hashCode()](#hashCode--) | يعيد قيمة تجزئة (hash code) لهذا الكائن. |
### Layer(String layerName, String layerText) {#Layer-java.lang.String-java.lang.String-}
```
public Layer(String layerName, String layerText)
```


يقوم بتهيئة نسخة جديدة من الفئة `Layer`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| layerName | java.lang.String | اسم الطبقة. |
| layerText | java.lang.String | نص الطبقة. |

### Layer() {#Layer--}
```
public Layer()
```


يقوم بتهيئة نسخة جديدة من الفئة `Layer`.

### getName() {#getName--}
```
public String getName()
```


يحصل أو يضبط اسم طبقة النص.

القيمة: اسم طبقة النص.

**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


يحصل أو يضبط اسم طبقة النص.

القيمة: اسم طبقة النص.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getText() {#getText--}
```
public String getText()
```


يحصل أو يضبط محتوى النص للطبقة.

القيمة: محتوى النص للطبقة.

**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


يحصل أو يضبط محتوى النص للطبقة.

القيمة: محتوى النص للطبقة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


يرجع القيمة المحتواة كسلسلة بصيغة XMP.

**Returns:**
java.lang.String - يرجع القيمة المحتواة كسلسلة بصيغة XMP.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


يحدد ما إذا كان `System.Object` المحدد يساوي هذه النسخة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| obj | java.lang.Object | الـ `System.Object` للمقارنة مع هذه الحالة. |

**Returns:**
منطقي - `true` إذا كان الـ `System.Object` المحدد يساوي هذه الحالة؛ وإلا، `false`.
### isEquals(Layer other) {#isEquals-com.aspose.imaging.xmp.schemas.photoshop.Layer-}
```
public boolean isEquals(Layer other)
```


يشير إلى ما إذا كان الكائن الحالي يساوي كائنًا آخر من نفس النوع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| other | [Layer](../../com.aspose.imaging.xmp.schemas.photoshop/layer) | كائن للمقارنة مع هذا الكائن. |

**Returns:**
boolean - true إذا كان الكائن الحالي يساوي المعامل `other`؛ وإلا false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


يعيد قيمة تجزئة (hash code) لهذا الكائن.

**Returns:**
int - قيمة تجزئة (hash code) لهذا الكائن، مناسبة للاستخدام في خوارزميات التجزئة وهياكل البيانات مثل جدول التجزئة.
