---
title: "EmfLogFont"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "كائن LogFont يحدد السمات الأساسية لخط منطقي."
type: docs
weight: 22
url: /ar/java/com.aspose.imaging.fileformats.emf.emf.objects/emflogfont/
---
**Inheritance:**
java.lang.Object، [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject)، [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public class EmfLogFont extends EmfObject
```

كائن LogFont يحدد السمات الأساسية لخط منطقي.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfLogFont()](#EmfLogFont--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getHeight()](#getHeight--) | يحصل أو يعيّن عددًا صحيحًا موقّع 32‑بت يحدد الارتفاع، بوحدات منطقية، لخلية حرف الخط أو الحرف نفسه. |
| [setHeight(int value)](#setHeight-int-) | يحصل أو يعيّن عددًا صحيحًا موقّع 32‑بت يحدد الارتفاع، بوحدات منطقية، لخلية حرف الخط أو الحرف نفسه. |
| [getWidth()](#getWidth--) | يحصل أو يعيّن عددًا صحيحًا موقّع 32‑بت يحدد العرض المتوسط، بوحدات منطقية، للأحرف في الخط. |
| [setWidth(int value)](#setWidth-int-) | يحصل أو يعيّن عددًا صحيحًا موقّع 32‑بت يحدد العرض المتوسط، بوحدات منطقية، للأحرف في الخط. |
| [getEscapement()](#getEscapement--) | يحصل أو يعيّن عددًا صحيحًا موقّع 32‑بت يحدد الزاوية، بعشرات الدرجات، بين متجه الإزاحة ومحور x للجهاز. |
| [setEscapement(int value)](#setEscapement-int-) | يحصل أو يعيّن عددًا صحيحًا موقّع 32‑بت يحدد الزاوية، بعشرات الدرجات، بين متجه الإزاحة ومحور x للجهاز. |
| [getOrientation()](#getOrientation--) | يحصل أو يعيّن عددًا صحيحًا موقّع 32‑بت يحدد الزاوية، بعشرات الدرجات، بين خط أساس كل حرف ومحور x للجهاز. |
| [setOrientation(int value)](#setOrientation-int-) | يحصل أو يعيّن عددًا صحيحًا موقّع 32‑بت يحدد الزاوية، بعشرات الدرجات، بين خط أساس كل حرف ومحور x للجهاز. |
| [getWeight()](#getWeight--) | يحصل أو يعيّن عددًا صحيحًا موقّع 32‑بت يحدد وزن الخط في النطاق من صفر إلى 1000. |
| [setWeight(int value)](#setWeight-int-) | يحصل أو يعيّن عددًا صحيحًا موقّع 32‑بت يحدد وزن الخط في النطاق من صفر إلى 1000. |
| [getItalic()](#getItalic--) | يحصل أو يعيّن عددًا صحيحًا غير موقّع 8‑بت يحدد خطًا مائلًا إذا كان قيمته 0x01؛ وإلا، يجب أن تكون قيمته 0x00. |
| [setItalic(byte value)](#setItalic-byte-) | يحصل أو يعيّن عددًا صحيحًا غير موقّع 8‑بت يحدد خطًا مائلًا إذا كان قيمته 0x01؛ وإلا، يجب أن تكون قيمته 0x00. |
| [getUnderline()](#getUnderline--) | يحصل أو يعيّن عددًا صحيحًا غير موقّع 8‑بت يحدد خطًا تحته خط إذا كان قيمته 0x01؛ وإلا، يجب أن تكون قيمته 0x00. |
| [setUnderline(byte value)](#setUnderline-byte-) | يحصل أو يعيّن عددًا صحيحًا غير موقّع 8‑بت يحدد خطًا تحته خط إذا كان قيمته 0x01؛ وإلا، يجب أن تكون قيمته 0x00. |
| [getStrikeout()](#getStrikeout--) | يحصل أو يعيّن عددًا صحيحًا غير موقّع 8‑بت يحدد خطًا مشطوبًا إذا كان قيمته 0x01؛ وإلا، يجب أن تكون قيمته 0x00. |
| [setStrikeout(byte value)](#setStrikeout-byte-) | يحصل أو يعيّن عددًا صحيحًا غير موقّع 8‑بت يحدد خطًا مشطوبًا إذا كان قيمته 0x01؛ وإلا، يجب أن تكون قيمته 0x00. |
| [getCharSet()](#getCharSet--) | يحصل أو يعيّن عددًا صحيحًا غير موقع 8 بت يحدد مجموعة رموز الأحرف. |
| [setCharSet(byte value)](#setCharSet-byte-) | يحصل أو يعيّن عددًا صحيحًا غير موقع 8 بت يحدد مجموعة رموز الأحرف. |
| [getOutPrecision()](#getOutPrecision--) | يحصل أو يعيّن عددًا صحيحًا غير موقع 8 بت يحدد دقة الإخراج. |
| [setOutPrecision(byte value)](#setOutPrecision-byte-) | يحصل أو يعيّن عددًا صحيحًا غير موقع 8 بت يحدد دقة الإخراج. |
| [getClipPrecision()](#getClipPrecision--) | يحصل أو يعيّن عددًا صحيحًا غير موقع 8 بت يحدد دقة القص. |
| [setClipPrecision(byte value)](#setClipPrecision-byte-) | يحصل أو يعيّن عددًا صحيحًا غير موقع 8 بت يحدد دقة القص. |
| [getQuality()](#getQuality--) | يحصل أو يعيّن عددًا صحيحًا غير موقع 8 بت يحدد جودة الإخراج. |
| [setQuality(byte value)](#setQuality-byte-) | يحصل أو يعيّن عددًا صحيحًا غير موقع 8 بت يحدد جودة الإخراج. |
| [getPitchAndFamily()](#getPitchAndFamily--) | يحصل أو يعيّن كائن WMF PitchAndFamily ([MS-WMF] القسم 2.2.2.14) يحدد درجة الصوت وعائلة الخط. |
| [setPitchAndFamily(WmfPitchAndFamily value)](#setPitchAndFamily-com.aspose.imaging.fileformats.wmf.objects.WmfPitchAndFamily-) | يحصل أو يعيّن كائن WMF PitchAndFamily ([MS-WMF] القسم 2.2.2.14) يحدد درجة الصوت وعائلة الخط. |
| [getFacename()](#getFacename--) | يحصل أو يعيّن اسم الوجه (64 بايت): سلسلة لا تتجاوز 32 حرف يونيكود تحدد اسم نوع الخط. |
| [setFacename(String value)](#setFacename-java.lang.String-) | يحصل أو يعيّن اسم الوجه (64 بايت): سلسلة لا تتجاوز 32 حرف يونيكود تحدد اسم نوع الخط. |
### EmfLogFont() {#EmfLogFont--}
```
public EmfLogFont()
```


### getHeight() {#getHeight--}
```
public int getHeight()
```


يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بت يحدد الارتفاع، بوحدات منطقية، لخلية حرف الخط أو الحرف. قيمة ارتفاع الحرف، المعروفة أيضًا باسم حجم الـ em، هي قيمة ارتفاع خلية الحرف مطروحًا منها قيمة المسافة الداخلية. يجب على مخطط الخط تفسير القيمة المحددة في حقل Height بالطريقة التالية.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public void setHeight(int value)
```


يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بت يحدد الارتفاع، بوحدات منطقية، لخلية حرف الخط أو الحرف. قيمة ارتفاع الحرف، المعروفة أيضًا باسم حجم الـ em، هي قيمة ارتفاع خلية الحرف مطروحًا منها قيمة المسافة الداخلية. يجب على مخطط الخط تفسير القيمة المحددة في حقل Height بالطريقة التالية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getWidth() {#getWidth--}
```
public int getWidth()
```


يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بت يحدد العرض المتوسط، بوحدات منطقية، للأحرف في الخط. إذا كانت قيمة حقل Width صفرًا، يجب حساب قيمة مناسبة من قيم LogFont الأخرى للعثور على خط يطابق نسبة الأبعاد التي يقصدها المصمم.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public void setWidth(int value)
```


يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بت يحدد العرض المتوسط، بوحدات منطقية، للأحرف في الخط. إذا كانت قيمة حقل Width صفرًا، يجب حساب قيمة مناسبة من قيم LogFont الأخرى للعثور على خط يطابق نسبة الأبعاد التي يقصدها المصمم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getEscapement() {#getEscapement--}
```
public int getEscapement()
```


يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بت يحدد الزاوية، بعشرات الدرجات، بين متجه الإخلاء ومحور x للجهاز. متجه الإخلاء موازٍ للخط الأساسي لسطر النص.

**Returns:**
int
### setEscapement(int value) {#setEscapement-int-}
```
public void setEscapement(int value)
```


يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بت يحدد الزاوية، بعشرات الدرجات، بين متجه الإخلاء ومحور x للجهاز. متجه الإخلاء موازٍ للخط الأساسي لسطر النص.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getOrientation() {#getOrientation--}
```
public int getOrientation()
```


يحصل أو يعيّن عددًا صحيحًا موقّع 32‑بت يحدد الزاوية، بعشرات الدرجات، بين خط أساس كل حرف ومحور x للجهاز.

**Returns:**
int
### setOrientation(int value) {#setOrientation-int-}
```
public void setOrientation(int value)
```


يحصل أو يعيّن عددًا صحيحًا موقّع 32‑بت يحدد الزاوية، بعشرات الدرجات، بين خط أساس كل حرف ومحور x للجهاز.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getWeight() {#getWeight--}
```
public int getWeight()
```


يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بت يحدد وزن الخط في النطاق من صفر إلى 1000. على سبيل المثال، 400 هو عادي و700 هو عريض. إذا كانت هذه القيمة صفرًا، يمكن استخدام وزن افتراضي.

**Returns:**
int
### setWeight(int value) {#setWeight-int-}
```
public void setWeight(int value)
```


يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بت يحدد وزن الخط في النطاق من صفر إلى 1000. على سبيل المثال، 400 هو عادي و700 هو عريض. إذا كانت هذه القيمة صفرًا، يمكن استخدام وزن افتراضي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getItalic() {#getItalic--}
```
public byte getItalic()
```


يحصل أو يعيّن عددًا صحيحًا غير موقّع 8‑بت يحدد خطًا مائلًا إذا كان قيمته 0x01؛ وإلا، يجب أن تكون قيمته 0x00.

**Returns:**
byte
### setItalic(byte value) {#setItalic-byte-}
```
public void setItalic(byte value)
```


يحصل أو يعيّن عددًا صحيحًا غير موقّع 8‑بت يحدد خطًا مائلًا إذا كان قيمته 0x01؛ وإلا، يجب أن تكون قيمته 0x00.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getUnderline() {#getUnderline--}
```
public byte getUnderline()
```


يحصل أو يعيّن عددًا صحيحًا غير موقّع 8‑بت يحدد خطًا تحته خط إذا كان قيمته 0x01؛ وإلا، يجب أن تكون قيمته 0x00.

**Returns:**
byte
### setUnderline(byte value) {#setUnderline-byte-}
```
public void setUnderline(byte value)
```


يحصل أو يعيّن عددًا صحيحًا غير موقّع 8‑بت يحدد خطًا تحته خط إذا كان قيمته 0x01؛ وإلا، يجب أن تكون قيمته 0x00.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getStrikeout() {#getStrikeout--}
```
public byte getStrikeout()
```


يحصل أو يعيّن عددًا صحيحًا غير موقّع 8‑بت يحدد خطًا مشطوبًا إذا كان قيمته 0x01؛ وإلا، يجب أن تكون قيمته 0x00.

**Returns:**
byte
### setStrikeout(byte value) {#setStrikeout-byte-}
```
public void setStrikeout(byte value)
```


يحصل أو يعيّن عددًا صحيحًا غير موقّع 8‑بت يحدد خطًا مشطوبًا إذا كان قيمته 0x01؛ وإلا، يجب أن تكون قيمته 0x00.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getCharSet() {#getCharSet--}
```
public byte getCharSet()
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 8 بت يحدد مجموعة رموز الأحرف. يجب أن تكون قيمة من تعداد WMF CharacterSet ([MS-WMF] القسم 2.1.1.5). إذا كانت مجموعة الأحرف غير معروفة، يجب على معالجة ملف الميتا عدم محاولة ترجمة أو تفسير السلاسل التي تُعرض بهذا الخط.

**Returns:**
byte
### setCharSet(byte value) {#setCharSet-byte-}
```
public void setCharSet(byte value)
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 8 بت يحدد مجموعة رموز الأحرف. يجب أن تكون قيمة من تعداد WMF CharacterSet ([MS-WMF] القسم 2.1.1.5). إذا كانت مجموعة الأحرف غير معروفة، يجب على معالجة ملف الميتا عدم محاولة ترجمة أو تفسير السلاسل التي تُعرض بهذا الخط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getOutPrecision() {#getOutPrecision--}
```
public byte getOutPrecision()
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 8 بت يحدد دقة الإخراج. تحدد دقة الإخراج مدى قرب تطابق الخط مع الارتفاع والعرض واتجاه الحرف والإخلاء والدرجة ونوع الخط المطلوب. يجب أن تكون قيمة من تعداد WMF OutPrecision.

**Returns:**
byte
### setOutPrecision(byte value) {#setOutPrecision-byte-}
```
public void setOutPrecision(byte value)
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 8 بت يحدد دقة الإخراج. تحدد دقة الإخراج مدى قرب تطابق الخط مع الارتفاع والعرض واتجاه الحرف والإخلاء والدرجة ونوع الخط المطلوب. يجب أن تكون قيمة من تعداد WMF OutPrecision.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getClipPrecision() {#getClipPrecision--}
```
public byte getClipPrecision()
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 8 بت يحدد دقة القص. تحدد دقة القص طريقة قص الأحرف التي تقع جزئيًا خارج منطقة القص. يمكن أن تكون واحدة أو أكثر من أعلام WMF ClipPrecision.

**Returns:**
byte
### setClipPrecision(byte value) {#setClipPrecision-byte-}
```
public void setClipPrecision(byte value)
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 8 بت يحدد دقة القص. تحدد دقة القص طريقة قص الأحرف التي تقع جزئيًا خارج منطقة القص. يمكن أن تكون واحدة أو أكثر من أعلام WMF ClipPrecision.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getQuality() {#getQuality--}
```
public byte getQuality()
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 8 بت يحدد جودة الإخراج. تحدد جودة الإخراج مدى قرب محاولة مطابقة خصائص الخط المنطقي مع خصائص خط فعلي مادي. يجب أن تكون إحدى القيم في تعداد WMF FontQuality ([MS-WMF] القسم 2.1.1.10).

**Returns:**
byte
### setQuality(byte value) {#setQuality-byte-}
```
public void setQuality(byte value)
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 8 بت يحدد جودة الإخراج. تحدد جودة الإخراج مدى قرب محاولة مطابقة خصائص الخط المنطقي مع خصائص خط فعلي مادي. يجب أن تكون إحدى القيم في تعداد WMF FontQuality ([MS-WMF] القسم 2.1.1.10).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getPitchAndFamily() {#getPitchAndFamily--}
```
public WmfPitchAndFamily getPitchAndFamily()
```


يحصل أو يعيّن كائن WMF PitchAndFamily ([MS-WMF] القسم 2.2.2.14) يحدد درجة الصوت وعائلة الخط. تصف عائلات الخط مظهر الخط بشكل عام. تُستخدم لتحديد خط عندما لا يكون نوع الخط المحدد متاحًا.

**Returns:**
[WmfPitchAndFamily](../../com.aspose.imaging.fileformats.wmf.objects/wmfpitchandfamily)
### setPitchAndFamily(WmfPitchAndFamily value) {#setPitchAndFamily-com.aspose.imaging.fileformats.wmf.objects.WmfPitchAndFamily-}
```
public void setPitchAndFamily(WmfPitchAndFamily value)
```


يحصل أو يعيّن كائن WMF PitchAndFamily ([MS-WMF] القسم 2.2.2.14) يحدد درجة الصوت وعائلة الخط. تصف عائلات الخط مظهر الخط بشكل عام. تُستخدم لتحديد خط عندما لا يكون نوع الخط المحدد متاحًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [WmfPitchAndFamily](../../com.aspose.imaging.fileformats.wmf.objects/wmfpitchandfamily) |  |

### getFacename() {#getFacename--}
```
public String getFacename()
```


يحصل أو يعيّن اسم الوجه (64 بايت): سلسلة لا تتجاوز 32 حرف يونيكود تحدد اسم نوع الخط. إذا كان طول هذه السلسلة أقل من 32 حرفًا، يجب وجود NULL نهائي، وبعده يجب تجاهل باقي الحقل.

**Returns:**
java.lang.String
### setFacename(String value) {#setFacename-java.lang.String-}
```
public void setFacename(String value)
```


يحصل أو يعيّن اسم الوجه (64 بايت): سلسلة لا تتجاوز 32 حرف يونيكود تحدد اسم نوع الخط. إذا كان طول هذه السلسلة أقل من 32 حرفًا، يجب وجود NULL نهائي، وبعده يجب تجاهل باقي الحقل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

