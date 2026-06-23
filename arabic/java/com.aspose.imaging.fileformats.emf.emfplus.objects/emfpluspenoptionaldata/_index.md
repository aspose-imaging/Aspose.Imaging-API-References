---
title: "EmfPlusPenOptionalData"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "كائن EmfPlusPenOptionalData يحدد بيانات اختيارية لقلم رسومي."
type: docs
weight: 65
url: /ar/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/
---
**Inheritance:**
java.lang.Object، [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging/fileformats.emf/metaobject)، [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging/fileformats.emf.emfplus.objects/emfplusobject)، [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging/fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
```
public final class EmfPlusPenOptionalData extends EmfPlusStructureObjectType
```

كائن EmfPlusPenOptionalData يحدد بيانات اختيارية لقلم رسومي.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfPlusPenOptionalData()](#EmfPlusPenOptionalData--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getTransformMatrix()](#getTransformMatrix--) | يحصل أو يعيّن كائن EmfPlusTransformMatrix اختياري (القسم 2.2.2.47) يحدد تحويل من مساحة العالم إلى مساحة الجهاز للقلم. |
| [setTransformMatrix(Matrix value)](#setTransformMatrix-com.aspose.imaging.Matrix-) | يحصل أو يعيّن كائن EmfPlusTransformMatrix اختياري (القسم 2.2.2.47) يحدد تحويل من مساحة العالم إلى مساحة الجهاز للقلم. |
| [getStartCap()](#getStartCap--) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت اختياري يحدد الشكل لبداية الخط في حقل CustomStartCapData. |
| [setStartCap(int value)](#setStartCap-int-) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت اختياري يحدد الشكل لبداية الخط في حقل CustomStartCapData. |
| [getEndCap()](#getEndCap--) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت اختياري يحدد الشكل لنهاية الخط في حقل CustomEndCapData. |
| [setEndCap(int value)](#setEndCap-int-) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت اختياري يحدد الشكل لنهاية الخط في حقل CustomEndCapData. |
| [getJoin()](#getJoin--) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت اختياري يحدد طريقة ربط خطين يُرسمان بالقلم نفسه وتلتقي نهايتهما. |
| [setJoin(int value)](#setJoin-int-) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت اختياري يحدد طريقة ربط خطين يُرسمان بالقلم نفسه وتلتقي نهايتهما. |
| [getMiterLimit()](#getMiterLimit--) | يحصل أو يعيّن قيمة عائمة 32‑بت اختياري تحدد حد المِتر، وهو النسبة القصوى المسموح بها بين طول المِتر وعرض الخط. |
| [setMiterLimit(float value)](#setMiterLimit-float-) | يحصل أو يعيّن قيمة عائمة 32‑بت اختياري تحدد حد المِتر، وهو النسبة القصوى المسموح بها بين طول المِتر وعرض الخط. |
| [getLineStyle()](#getLineStyle--) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت اختياري يحدد النمط المستخدم للخطوط المرسومة بهذا القلم. |
| [setLineStyle(int value)](#setLineStyle-int-) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت اختياري يحدد النمط المستخدم للخطوط المرسومة بهذا القلم. |
| [getDashedLineCapType()](#getDashedLineCapType--) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت اختياري يحدد الشكل لكلا طرفي كل شَرطَة في خط متقطع. |
| [setDashedLineCapType(int value)](#setDashedLineCapType-int-) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت اختياري يحدد الشكل لكلا طرفي كل شَرطَة في خط متقطع. |
| [getDashOffset()](#getDashOffset--) | يحصل أو يعيّن قيمة عائمة 32‑بت اختياري تحدد المسافة من بداية الخط إلى بداية الفراغ الأول في نمط الخط المتقطع. |
| [setDashOffset(float value)](#setDashOffset-float-) | يحصل أو يعيّن قيمة عائمة 32‑بت اختياري تحدد المسافة من بداية الخط إلى بداية الفراغ الأول في نمط الخط المتقطع. |
| [getDashedLineData()](#getDashedLineData--) | يحصل أو يعيّن كائن EmfPlusDashedLineData اختياري (القسم 2.2.2.16) يحدد أطوال الشرط والمسافات في خط متقطع مخصص. |
| [setDashedLineData(EmfPlusDashedLineData value)](#setDashedLineData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusDashedLineData-) | يحصل أو يعيّن كائن EmfPlusDashedLineData اختياري (القسم 2.2.2.16) يحدد أطوال الشرط والمسافات في خط متقطع مخصص. |
| [getPenAlignment()](#getPenAlignment--) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت اختياريًا يحدد توزيع عرض القلم بالنسبة لإحداثيات الخط المرسوم. |
| [setPenAlignment(int value)](#setPenAlignment-int-) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت اختياريًا يحدد توزيع عرض القلم بالنسبة لإحداثيات الخط المرسوم. |
| [getCompoundLineData()](#getCompoundLineData--) | يحصل أو يعيّن كائن EmfPlusCompoundLineData اختياري (القسم 2.2.2.9) يحدد مصفوفة من القيم العشرية التي تعرف الخط المركب للقلم، والذي يتكون من خطوط متوازية وفراغات. |
| [setCompoundLineData(EmfPlusCompoundLineData value)](#setCompoundLineData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCompoundLineData-) | يحصل أو يعيّن كائن EmfPlusCompoundLineData اختياري (القسم 2.2.2.9) يحدد مصفوفة من القيم العشرية التي تعرف الخط المركب للقلم، والذي يتكون من خطوط متوازية وفراغات. |
| [getCustomStartCapData()](#getCustomStartCapData--) | يحصل أو يعيّن كائن EmfPlusCustomStartCapData اختياري (القسم 2.2.2.15) يحدد شكل القمة الابتدائية المخصص، وهو الشكل المستخدم في بداية الخط المرسوم بهذا القلم. |
| [setCustomStartCapData(EmfPlusCustomStartCapData value)](#setCustomStartCapData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCustomStartCapData-) | يحصل أو يعيّن كائن EmfPlusCustomStartCapData اختياري (القسم 2.2.2.15) يحدد شكل القمة الابتدائية المخصص، وهو الشكل المستخدم في بداية الخط المرسوم بهذا القلم. |
| [getCustomEndCapData()](#getCustomEndCapData--) | يحصل أو يعيّن كائن EmfPlusCustomEndCapData اختياري (القسم 2.2.2.11) يحدد شكل القمة النهائية المخصص، وهو الشكل المستخدم في نهاية الخط المرسوم بهذا القلم. |
| [setCustomEndCapData(EmfPlusCustomEndCapData value)](#setCustomEndCapData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCustomEndCapData-) | يحصل أو يعيّن كائن EmfPlusCustomEndCapData اختياري (القسم 2.2.2.11) يحدد شكل القمة النهائية المخصص، وهو الشكل المستخدم في نهاية الخط المرسوم بهذا القلم. |
### EmfPlusPenOptionalData() {#EmfPlusPenOptionalData--}
```
public EmfPlusPenOptionalData()
```


### getTransformMatrix() {#getTransformMatrix--}
```
public Matrix getTransformMatrix()
```


يحصل أو يعيّن كائن EmfPlusTransformMatrix اختياري (القسم 2.2.2.47) يحدد تحويل من مساحة العالم إلى مساحة الجهاز للقلم. يجب أن يكون هذا الحقل موجودًا إذا تم تعيين علم PenDataTransform في حقل PenDataFlags لكائن EmfPlusPenData.

**Returns:**
[Matrix](../../com.aspose.imaging/matrix)
### setTransformMatrix(Matrix value) {#setTransformMatrix-com.aspose.imaging.Matrix-}
```
public void setTransformMatrix(Matrix value)
```


يحصل أو يعيّن كائن EmfPlusTransformMatrix اختياري (القسم 2.2.2.47) يحدد تحويل من مساحة العالم إلى مساحة الجهاز للقلم. يجب أن يكون هذا الحقل موجودًا إذا تم تعيين علم PenDataTransform في حقل PenDataFlags لكائن EmfPlusPenData.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) |  |

### getStartCap() {#getStartCap--}
```
public int getStartCap()
```


يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت اختياريًا يحدد الشكل لبداية الخط في حقل CustomStartCapData. يجب أن يكون هذا الحقل موجودًا إذا تم تعيين علم PenDataStartCap في حقل PenDataFlags لكائن EmfPlusPenData، ويجب أن تكون القيمة معرفة في تعداد LineCapType (القسم 2.1.1.18).

**Returns:**
int
### setStartCap(int value) {#setStartCap-int-}
```
public void setStartCap(int value)
```


يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت اختياريًا يحدد الشكل لبداية الخط في حقل CustomStartCapData. يجب أن يكون هذا الحقل موجودًا إذا تم تعيين علم PenDataStartCap في حقل PenDataFlags لكائن EmfPlusPenData، ويجب أن تكون القيمة معرفة في تعداد LineCapType (القسم 2.1.1.18).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getEndCap() {#getEndCap--}
```
public int getEndCap()
```


يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت اختياريًا يحدد الشكل لنهاية الخط في حقل CustomEndCapData. يجب أن يكون هذا الحقل موجودًا إذا تم تعيين علم PenDataEndCap في حقل PenDataFlags لكائن EmfPlusPenData، ويجب أن تكون القيمة معرفة في تعداد LineCapType.

**Returns:**
int
### setEndCap(int value) {#setEndCap-int-}
```
public void setEndCap(int value)
```


يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت اختياريًا يحدد الشكل لنهاية الخط في حقل CustomEndCapData. يجب أن يكون هذا الحقل موجودًا إذا تم تعيين علم PenDataEndCap في حقل PenDataFlags لكائن EmfPlusPenData، ويجب أن تكون القيمة معرفة في تعداد LineCapType.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getJoin() {#getJoin--}
```
public int getJoin()
```


يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت اختياريًا يحدد طريقة ربط خطين يتم رسمهما بنفس القلم وتلتقي نهايتهما. يجب أن يكون هذا الحقل موجودًا إذا تم تعيين علم PenDataJoin في حقل PenDataFlags لكائن EmfPlusPenData، ويجب أن تكون القيمة معرفة في تعداد LineJoinType (القسم 2.1.1.19).

**Returns:**
int
### setJoin(int value) {#setJoin-int-}
```
public void setJoin(int value)
```


يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت اختياريًا يحدد طريقة ربط خطين يتم رسمهما بنفس القلم وتلتقي نهايتهما. يجب أن يكون هذا الحقل موجودًا إذا تم تعيين علم PenDataJoin في حقل PenDataFlags لكائن EmfPlusPenData، ويجب أن تكون القيمة معرفة في تعداد LineJoinType (القسم 2.1.1.19).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getMiterLimit() {#getMiterLimit--}
```
public float getMiterLimit()
```


يحصل أو يعيّن قيمة عائمة 32‑بت اختياريًا تحدد حد المِتر، وهو النسبة القصوى المسموح بها بين طول المِتر وعرض الخط. طول المِتر هو المسافة من تقاطع جدران الخط من داخل الوصلة إلى تقاطع جدران الخط من خارج الوصلة. يمكن أن يكون طول المِتر كبيرًا عندما تكون الزاوية بين خطين صغيرة. يجب أن يكون هذا الحقل موجودًا إذا تم تعيين علم PenDataMiterLimit في حقل PenDataFlags لكائن EmfPlusPenData.

**Returns:**
float
### setMiterLimit(float value) {#setMiterLimit-float-}
```
public void setMiterLimit(float value)
```


يحصل أو يعيّن قيمة عائمة 32‑بت اختياريًا تحدد حد المِتر، وهو النسبة القصوى المسموح بها بين طول المِتر وعرض الخط. طول المِتر هو المسافة من تقاطع جدران الخط من داخل الوصلة إلى تقاطع جدران الخط من خارج الوصلة. يمكن أن يكون طول المِتر كبيرًا عندما تكون الزاوية بين خطين صغيرة. يجب أن يكون هذا الحقل موجودًا إذا تم تعيين علم PenDataMiterLimit في حقل PenDataFlags لكائن EmfPlusPenData.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getLineStyle() {#getLineStyle--}
```
public int getLineStyle()
```


يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت اختياريًا يحدد النمط المستخدم للخطوط المرسومة بهذا القلم. يجب أن يكون هذا الحقل موجودًا إذا تم تعيين علم PenDataLineStyle في حقل PenDataFlags لكائن EmfPlusPenData، ويجب أن تكون القيمة معرفة في تعداد LineStyle (القسم 2.1.1.20).

**Returns:**
int
### setLineStyle(int value) {#setLineStyle-int-}
```
public void setLineStyle(int value)
```


يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت اختياريًا يحدد النمط المستخدم للخطوط المرسومة بهذا القلم. يجب أن يكون هذا الحقل موجودًا إذا تم تعيين علم PenDataLineStyle في حقل PenDataFlags لكائن EmfPlusPenData، ويجب أن تكون القيمة معرفة في تعداد LineStyle (القسم 2.1.1.20).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getDashedLineCapType() {#getDashedLineCapType--}
```
public int getDashedLineCapType()
```


يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت اختياريًا يحدد الشكل لكلا طرفي كل شرطة في خط متقطع. يجب أن يكون هذا الحقل موجودًا إذا تم تعيين علم PenDataDashedLineCap في حقل PenDataFlags لكائن EmfPlusPenData، ويجب أن تكون القيمة معرفة في تعداد DashedLineCapType (القسم 2.1.1.10).

**Returns:**
int
### setDashedLineCapType(int value) {#setDashedLineCapType-int-}
```
public void setDashedLineCapType(int value)
```


يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت اختياريًا يحدد الشكل لكلا طرفي كل شرطة في خط متقطع. يجب أن يكون هذا الحقل موجودًا إذا تم تعيين علم PenDataDashedLineCap في حقل PenDataFlags لكائن EmfPlusPenData، ويجب أن تكون القيمة معرفة في تعداد DashedLineCapType (القسم 2.1.1.10).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getDashOffset() {#getDashOffset--}
```
public float getDashOffset()
```


يحصل أو يعيّن قيمة عائمة 32‑بت اختياريًا تحدد المسافة من بداية الخط إلى بداية أول فراغ في نمط الخط المتقطع. يجب أن يكون هذا الحقل موجودًا إذا تم تعيين علم PenDataDashedLineOffset في حقل PenDataFlags لكائن EmfPlusPenData.

**Returns:**
float
### setDashOffset(float value) {#setDashOffset-float-}
```
public void setDashOffset(float value)
```


يحصل أو يعيّن قيمة عائمة 32‑بت اختياريًا تحدد المسافة من بداية الخط إلى بداية أول فراغ في نمط الخط المتقطع. يجب أن يكون هذا الحقل موجودًا إذا تم تعيين علم PenDataDashedLineOffset في حقل PenDataFlags لكائن EmfPlusPenData.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getDashedLineData() {#getDashedLineData--}
```
public EmfPlusDashedLineData getDashedLineData()
```


يحصل أو يعيّن كائن EmfPlusDashedLineData اختياري (القسم 2.2.2.16) يحدد أطوال الشرط والمسافات في خط متقطع مخصص. يجب أن يكون هذا الحقل موجودًا إذا تم تعيين علم PenDataDashedLine في حقل PenDataFlags لكائن EmfPlusPenData.

**Returns:**
[EmfPlusDashedLineData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusdashedlinedata)
### setDashedLineData(EmfPlusDashedLineData value) {#setDashedLineData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusDashedLineData-}
```
public void setDashedLineData(EmfPlusDashedLineData value)
```


يحصل أو يعيّن كائن EmfPlusDashedLineData اختياري (القسم 2.2.2.16) يحدد أطوال الشرط والمسافات في خط متقطع مخصص. يجب أن يكون هذا الحقل موجودًا إذا تم تعيين علم PenDataDashedLine في حقل PenDataFlags لكائن EmfPlusPenData.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [EmfPlusDashedLineData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusdashedlinedata) |  |

### getPenAlignment() {#getPenAlignment--}
```
public int getPenAlignment()
```


يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت اختياريًا يحدد توزيع عرض القلم بالنسبة لإحداثيات الخط المرسوم. يجب أن يكون هذا الحقل موجودًا إذا تم تعيين علم PenDataNonCenter في حقل PenDataFlags لكائن EmfPlusPenData، ويجب أن تكون القيمة معرفة في تعداد PenAlignment (القسم 2.1.1.24).

**Returns:**
int
### setPenAlignment(int value) {#setPenAlignment-int-}
```
public void setPenAlignment(int value)
```


يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت اختياريًا يحدد توزيع عرض القلم بالنسبة لإحداثيات الخط المرسوم. يجب أن يكون هذا الحقل موجودًا إذا تم تعيين علم PenDataNonCenter في حقل PenDataFlags لكائن EmfPlusPenData، ويجب أن تكون القيمة معرفة في تعداد PenAlignment (القسم 2.1.1.24).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getCompoundLineData() {#getCompoundLineData--}
```
public EmfPlusCompoundLineData getCompoundLineData()
```


يحصل أو يعيّن كائن EmfPlusCompoundLineData اختياري (القسم 2.2.2.9) يحدد مصفوفة من القيم العشرية التي تعرف الخط المركب للقلم، والذي يتكون من خطوط متوازية وفراغات. يجب أن يكون هذا الحقل موجودًا إذا تم تعيين علم PenDataCompoundLine في حقل PenDataFlags لكائن EmfPlusPenData.

**Returns:**
[EmfPlusCompoundLineData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscompoundlinedata)
### setCompoundLineData(EmfPlusCompoundLineData value) {#setCompoundLineData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCompoundLineData-}
```
public void setCompoundLineData(EmfPlusCompoundLineData value)
```


يحصل أو يعيّن كائن EmfPlusCompoundLineData اختياري (القسم 2.2.2.9) يحدد مصفوفة من القيم العشرية التي تعرف الخط المركب للقلم، والذي يتكون من خطوط متوازية وفراغات. يجب أن يكون هذا الحقل موجودًا إذا تم تعيين علم PenDataCompoundLine في حقل PenDataFlags لكائن EmfPlusPenData.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [EmfPlusCompoundLineData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscompoundlinedata) |  |

### getCustomStartCapData() {#getCustomStartCapData--}
```
public EmfPlusCustomStartCapData getCustomStartCapData()
```


يحصل أو يعيّن كائن EmfPlusCustomStartCapData اختياري (القسم 2.2.2.15) يحدد شكل القمة الابتدائية المخصص، وهو الشكل المستخدم في بداية الخط المرسوم بهذا القلم. يمكن أن يكون أيًا من الأشكال المختلفة، مثل مربع أو دائرة أو ماسة. يجب أن يكون هذا الحقل موجودًا إذا تم تعيين علم PenDataCustomStartCap في حقل PenDataFlags لكائن EmfPlusPenData.

**Returns:**
[EmfPlusCustomStartCapData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomstartcapdata)
### setCustomStartCapData(EmfPlusCustomStartCapData value) {#setCustomStartCapData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCustomStartCapData-}
```
public void setCustomStartCapData(EmfPlusCustomStartCapData value)
```


يحصل أو يعيّن كائن EmfPlusCustomStartCapData اختياري (القسم 2.2.2.15) يحدد شكل القمة الابتدائية المخصص، وهو الشكل المستخدم في بداية الخط المرسوم بهذا القلم. يمكن أن يكون أيًا من الأشكال المختلفة، مثل مربع أو دائرة أو ماسة. يجب أن يكون هذا الحقل موجودًا إذا تم تعيين علم PenDataCustomStartCap في حقل PenDataFlags لكائن EmfPlusPenData.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [EmfPlusCustomStartCapData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomstartcapdata) |  |

### getCustomEndCapData() {#getCustomEndCapData--}
```
public EmfPlusCustomEndCapData getCustomEndCapData()
```


يحصل أو يعيّن كائن EmfPlusCustomEndCapData اختياري (القسم 2.2.2.11) يحدد شكل القمة النهائية المخصص، وهو الشكل المستخدم في نهاية الخط المرسوم بهذا القلم. يمكن أن يكون أيًا من الأشكال المختلفة، مثل مربع أو دائرة أو ماسة. يجب أن يكون هذا الحقل موجودًا إذا تم تعيين علم PenDataCustomEndCap في حقل PenDataFlags لكائن EmfPlusPenData.

**Returns:**
[EmfPlusCustomEndCapData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomendcapdata)
### setCustomEndCapData(EmfPlusCustomEndCapData value) {#setCustomEndCapData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCustomEndCapData-}
```
public void setCustomEndCapData(EmfPlusCustomEndCapData value)
```


يحصل أو يعيّن كائن EmfPlusCustomEndCapData اختياري (القسم 2.2.2.11) يحدد شكل القمة النهائية المخصص، وهو الشكل المستخدم في نهاية الخط المرسوم بهذا القلم. يمكن أن يكون أيًا من الأشكال المختلفة، مثل مربع أو دائرة أو ماسة. يجب أن يكون هذا الحقل موجودًا إذا تم تعيين علم PenDataCustomEndCap في حقل PenDataFlags لكائن EmfPlusPenData.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [EmfPlusCustomEndCapData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomendcapdata) |  |

