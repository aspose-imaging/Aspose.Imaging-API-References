---
title: "WmfLogColorSpaceW"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "كائن LogColorSpaceW يحدد مساحة ألوان منطقية يمكن تعريفها بملف تعريف ألوان يحمل اسمًا مكوّنًا من أحرف يونيكود 16-بت."
type: docs
weight: 45
url: /ar/java/com.aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject)
```
public class WmfLogColorSpaceW extends MetaObject
```

كائن LogColorSpaceW يحدد مساحة ألوان منطقية، يمكن تعريفها بملف تعريف ألوان يحمل اسمًا مكوّنًا من أحرف Unicode 16-بت.

انظر كائن `WmfLogColorSpace` (القسم 2.2.2.11) للحصول على تفاصيل إضافية حول تفسير قيم الحقول لهذا الكائن.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [WmfLogColorSpaceW()](#WmfLogColorSpaceW--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getSignature()](#getSignature--) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32-بت يحدد `signature` لكائنات مساحة الألوان؛ يجب تعيينه إلى القيمة 0x50534F43، وهي ترميز ASCII للسلسلة \"PSOC\". |
| [setSignature(int value)](#setSignature-int-) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32-بت يحدد `signature` لكائنات مساحة الألوان؛ يجب تعيينه إلى القيمة 0x50534F43، وهي ترميز ASCII للسلسلة \"PSOC\". |
| [getVersion()](#getVersion--) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32-بت يحدد رقم `version`؛ يجب أن يكون 0x00000400. |
| [setVersion(int value)](#setVersion-int-) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32-بت يحدد رقم `version`؛ يجب أن يكون 0x00000400. |
| [getSize()](#getSize--) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32-بت يحدد `size` لهذا الكائن، بالبايت. |
| [setSize(int value)](#setSize-int-) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32-بت يحدد `size` لهذا الكائن، بالبايت. |
| [getColorSpaceType()](#getColorSpaceType--) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32-بت يحدد نوع مساحة اللون. |
| [setColorSpaceType(int value)](#setColorSpaceType-int-) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32-بت يحدد نوع مساحة اللون. |
| [getIntent()](#getIntent--) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32-بت يحدد نية تخطيط النطاق اللوني. |
| [setIntent(int value)](#setIntent-int-) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32-بت يحدد نية تخطيط النطاق اللوني. |
| [getEndpoints()](#getEndpoints--) | يحصل أو يعيّن كائن CIEXYZTriple (القسم 2.2.2.7) يحدد إحداثيات اللون CIE x, y, و z للثلاث ألوان التي تتطابق مع `endpoints` RGB لمساحة اللون المنطقية المرتبطة بالصورة النقطية. |
| [setEndpoints(WmfCieXyzTriple value)](#setEndpoints-com.aspose.imaging.fileformats.wmf.objects.WmfCieXyzTriple-) | يحصل أو يعيّن كائن CIEXYZTriple (القسم 2.2.2.7) يحدد إحداثيات اللون CIE x, y, و z للثلاث ألوان التي تتطابق مع `endpoints` RGB لمساحة اللون المنطقية المرتبطة بالصورة النقطية. |
| [getGammaRed()](#getGammaRed--) | يحصل أو يعيّن قيمة ثابتة 32-بت تحدد منحنى الاستجابة المظللة للأحمر. |
| [setGammaRed(int value)](#setGammaRed-int-) | يحصل أو يعيّن قيمة ثابتة 32-بت تحدد منحنى الاستجابة المظللة للأحمر. |
| [getGammaGreen()](#getGammaGreen--) | يحصل أو يعيّن قيمة ثابتة 32-بت تحدد منحنى الاستجابة المظللة للأخضر. |
| [setGammaGreen(int value)](#setGammaGreen-int-) | يحصل أو يعيّن قيمة ثابتة 32-بت تحدد منحنى الاستجابة المظللة للأخضر. |
| [getGammaBlue()](#getGammaBlue--) | يحصل أو يعيّن قيمة ثابتة 32-بت تحدد منحنى الاستجابة المظللة للأزرق. |
| [setGammaBlue(int value)](#setGammaBlue-int-) | يحصل أو يعيّن قيمة ثابتة 32-بت تحدد منحنى الاستجابة المظللة للأزرق. |
| [getFilename()](#getFilename--) | يحصل أو يعيّن سلسلة أحرف يونيكود UTF16-LE منتهية بصفر اختيارية، تحدد اسم ملف يحتوي على تعريف ألوان. |
| [setFilename(String value)](#setFilename-java.lang.String-) | يحصل أو يعيّن سلسلة أحرف يونيكود UTF16-LE منتهية بصفر اختيارية، تحدد اسم ملف يحتوي على تعريف ألوان. |
### WmfLogColorSpaceW() {#WmfLogColorSpaceW--}
```
public WmfLogColorSpaceW()
```


### getSignature() {#getSignature--}
```
public int getSignature()
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32-بت يحدد `signature` لكائنات مساحة الألوان؛ يجب تعيينه إلى القيمة 0x50534F43، وهي ترميز ASCII للسلسلة \"PSOC\".

**Returns:**
int
### setSignature(int value) {#setSignature-int-}
```
public void setSignature(int value)
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32-بت يحدد `signature` لكائنات مساحة الألوان؛ يجب تعيينه إلى القيمة 0x50534F43، وهي ترميز ASCII للسلسلة \"PSOC\".

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getVersion() {#getVersion--}
```
public int getVersion()
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32-بت يحدد رقم `version`؛ يجب أن يكون 0x00000400.

**Returns:**
int
### setVersion(int value) {#setVersion-int-}
```
public void setVersion(int value)
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32-بت يحدد رقم `version`؛ يجب أن يكون 0x00000400.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getSize() {#getSize--}
```
public int getSize()
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32-بت يحدد `size` لهذا الكائن، بالبايت.

**Returns:**
int
### setSize(int value) {#setSize-int-}
```
public void setSize(int value)
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32-بت يحدد `size` لهذا الكائن، بالبايت.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getColorSpaceType() {#getColorSpaceType--}
```
public int getColorSpaceType()
```


يحصل أو يعيّن عددًا صحيحًا موقعًا 32-بت يحدد نوع مساحة اللون. يجب تعريفه في تعداد LogicalColorSpace (القسم 2.1.1.14). إذا كانت هذه القيمة LCS\_sRGB أو LCS\_WINDOWS\_COLOR\_SPACE، يجب استخدام مساحة اللون sRGB.

**Returns:**
int
### setColorSpaceType(int value) {#setColorSpaceType-int-}
```
public void setColorSpaceType(int value)
```


يحصل أو يعيّن عددًا صحيحًا موقعًا 32-بت يحدد نوع مساحة اللون. يجب تعريفه في تعداد LogicalColorSpace (القسم 2.1.1.14). إذا كانت هذه القيمة LCS\_sRGB أو LCS\_WINDOWS\_COLOR\_SPACE، يجب استخدام مساحة اللون sRGB.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getIntent() {#getIntent--}
```
public int getIntent()
```


يحصل أو يعيّن عددًا صحيحًا موقعًا 32-بت يحدد نية تخطيط النطاق اللوني. يجب تعريفه في تعداد GamutMappingIntent (القسم 2.1.1.11).

**Returns:**
int
### setIntent(int value) {#setIntent-int-}
```
public void setIntent(int value)
```


يحصل أو يعيّن عددًا صحيحًا موقعًا 32-بت يحدد نية تخطيط النطاق اللوني. يجب تعريفه في تعداد GamutMappingIntent (القسم 2.1.1.11).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getEndpoints() {#getEndpoints--}
```
public WmfCieXyzTriple getEndpoints()
```


يحصل أو يعيّن كائن CIEXYZTriple (القسم 2.2.2.7) يحدد إحداثيات اللون CIE x, y, و z للثلاث ألوان التي تتطابق مع `endpoints` RGB لمساحة اللون المنطقية المرتبطة بالصورة النقطية. إذا لم يحدد حقل `ColorSpaceType` القيمة LCS\_CALIBRATED\_RGB، يجب تجاهل هذا الحقل.

**Returns:**
[WmfCieXyzTriple](../../com.aspose.imaging.fileformats.wmf.objects/wmfciexyztriple)
### setEndpoints(WmfCieXyzTriple value) {#setEndpoints-com.aspose.imaging.fileformats.wmf.objects.WmfCieXyzTriple-}
```
public void setEndpoints(WmfCieXyzTriple value)
```


يحصل أو يعيّن كائن CIEXYZTriple (القسم 2.2.2.7) يحدد إحداثيات اللون CIE x, y, و z للثلاث ألوان التي تتطابق مع `endpoints` RGB لمساحة اللون المنطقية المرتبطة بالصورة النقطية. إذا لم يحدد حقل `ColorSpaceType` القيمة LCS\_CALIBRATED\_RGB، يجب تجاهل هذا الحقل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [WmfCieXyzTriple](../../com.aspose.imaging.fileformats.wmf.objects/wmfciexyztriple) |  |

### getGammaRed() {#getGammaRed--}
```
public int getGammaRed()
```


يحصل أو يعيّن قيمة ثابتة 32-بت تحدد منحنى الاستجابة المظللة للأحمر. إذا لم يحدد حقل `ColorSpaceType` القيمة LCS\_CALIBRATED\_RGB، يجب تجاهل هذا الحقل.

**Returns:**
int
### setGammaRed(int value) {#setGammaRed-int-}
```
public void setGammaRed(int value)
```


يحصل أو يعيّن قيمة ثابتة 32-بت تحدد منحنى الاستجابة المظللة للأحمر. إذا لم يحدد حقل `ColorSpaceType` القيمة LCS\_CALIBRATED\_RGB، يجب تجاهل هذا الحقل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getGammaGreen() {#getGammaGreen--}
```
public int getGammaGreen()
```


يحصل أو يعيّن قيمة ثابتة 32-بت تحدد منحنى الاستجابة المظللة للأخضر. إذا لم يحدد حقل `ColorSpaceType` القيمة LCS\_CALIBRATED\_RGB، يجب تجاهل هذا الحقل.

**Returns:**
int
### setGammaGreen(int value) {#setGammaGreen-int-}
```
public void setGammaGreen(int value)
```


يحصل أو يعيّن قيمة ثابتة 32-بت تحدد منحنى الاستجابة المظللة للأخضر. إذا لم يحدد حقل `ColorSpaceType` القيمة LCS\_CALIBRATED\_RGB، يجب تجاهل هذا الحقل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getGammaBlue() {#getGammaBlue--}
```
public int getGammaBlue()
```


يحصل أو يعيّن قيمة ثابتة 32-بت تحدد منحنى الاستجابة المظللة للأزرق. إذا لم يحدد حقل `ColorSpaceType` القيمة LCS\_CALIBRATED\_RGB، يجب تجاهل هذا الحقل.

**Returns:**
int
### setGammaBlue(int value) {#setGammaBlue-int-}
```
public void setGammaBlue(int value)
```


يحصل أو يعيّن قيمة ثابتة 32-بت تحدد منحنى الاستجابة المظللة للأزرق. إذا لم يحدد حقل `ColorSpaceType` القيمة LCS\_CALIBRATED\_RGB، يجب تجاهل هذا الحقل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getFilename() {#getFilename--}
```
public String getFilename()
```


يحصل أو يضبط سلسلة أحرف يونيكود UTF16-LE منتهية بصفر، اختيارية، والتي تحدد اسم ملف يحتوي على ملف تعريف ألوان. إذا تم تحديد اسم ملف، وكان حقل `ColorSpaceType` مضبوطًا على LCS\\_CALIBRATED\\_RGB، يجب تجاهل الحقول الأخرى في هذه البنية.

**Returns:**
java.lang.String
### setFilename(String value) {#setFilename-java.lang.String-}
```
public void setFilename(String value)
```


يحصل أو يضبط سلسلة أحرف يونيكود UTF16-LE منتهية بصفر، اختيارية، والتي تحدد اسم ملف يحتوي على ملف تعريف ألوان. إذا تم تحديد اسم ملف، وكان حقل `ColorSpaceType` مضبوطًا على LCS\\_CALIBRATED\\_RGB، يجب تجاهل الحقول الأخرى في هذه البنية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

