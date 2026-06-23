---
title: "WmfLogColorSpace"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "كائن LogColorSpace يحدد مساحة ألوان منطقية لسياق جهاز التشغيل والتي يمكن أن تكون اسم ملف تعريف ألوان بأحرف ASCII."
type: docs
weight: 44
url: /ar/java/com.aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject)
```
public class WmfLogColorSpace extends MetaObject
```

كائن LogColorSpace يحدد مساحة ألوان منطقية لسياق جهاز التشغيل، ويمكن أن يكون اسم ملف تعريف الألوان بحروف ASCII.

يتم استخدام حقول Endpoints و GammaRed و GammaGreen و GammaBlue لتحديد مساحة ألوان منطقية. حقل Endpoints هو كائن CIEXYZTriple يحتوي على قيم x و y و z لنقطة النهاية RGB لمساحة اللون. العلاقة بين قيم الثلاثية X,Y,Z وقيم اللون x,y,z تُعبر كما يلي. x = X/(X+Y+Z) y = Y/(X+Y+Z) z = Z/(X+Y+Z) تحتوي حقول GammaRed و GammaGreen و GammaBlue على قيم بتنسيق "8.8 fixed point"، وهو تقنية لتمثيل الأعداد غير الصحيحة. كل قيمة تتكون من مقدار 8 بت موسع بالصفر يليه جزء 8 بت، مع إزاحة الـ 16 بت المجمعة إلى اليسار بمقدار 8 بت. وبالتالي، في 32 بت، القيمة الحقيقية N.F هي 00000000nnnnnnnnffffffff00000000، حيث "nnnnnnnn" و "ffffffff" تمثيلات ثنائية لـ N و F على التوالي. على سبيل المثال، للعدد الحقيقي 10.5، سيكون nnnnnnnn هو 00001010 (ثنائي 10) و ffffffff هو 00000101 (ثنائي 5)، والقيمة الثنائية الكاملة 32‑بت ستكون 00000000000010100000010100000000، وهي القيمة الست عشرية 0x0A50.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [WmfLogColorSpace()](#WmfLogColorSpace--) |  |
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
| [getFilename()](#getFilename--) | يحصل أو يضبط سلسلة أحرف ASCII اختيارية تحدد اسم ملف يحتوي على ملف تعريف ألوان. |
| [setFilename(String value)](#setFilename-java.lang.String-) | يحصل أو يضبط سلسلة أحرف ASCII اختيارية تحدد اسم ملف يحتوي على ملف تعريف ألوان. |
### WmfLogColorSpace() {#WmfLogColorSpace--}
```
public WmfLogColorSpace()
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


يحصل أو يضبط سلسلة أحرف ASCII اختيارية تحدد اسم ملف يحتوي على ملف تعريف ألوان. إذا تم تحديد اسم ملف، وكان حقل `ColorSpaceType` مضبوطًا على LCS\\_CALIBRATED\\_RGB، يجب تجاهل الحقول الأخرى في هذه البنية.

**Returns:**
java.lang.String
### setFilename(String value) {#setFilename-java.lang.String-}
```
public void setFilename(String value)
```


يحصل أو يضبط سلسلة أحرف ASCII اختيارية تحدد اسم ملف يحتوي على ملف تعريف ألوان. إذا تم تحديد اسم ملف، وكان حقل `ColorSpaceType` مضبوطًا على LCS\\_CALIBRATED\\_RGB، يجب تجاهل الحقول الأخرى في هذه البنية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

