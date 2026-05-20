---
title: "EmfLogFont"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "كائن LogFont يحدد السمات الأساسية لخط منطقي."
type: docs
weight: 22
url: /ar/java/com.aspose.imaging.fileformats.emf.emf.objects/emflogfont/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
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
| [getHeight()](#getHeight--) | يحصل أو يعيّن عددًا صحيحًا موقّعًا 32‑بت يحدد الارتفاع، بوحدات منطقية، لخلية حرف الخط أو الحرف. |
| [setHeight(int value)](#setHeight-int-) | يحصل أو يعيّن عددًا صحيحًا موقّعًا 32‑بت يحدد الارتفاع، بوحدات منطقية، لخلية حرف الخط أو الحرف. |
| [getWidth()](#getWidth--) | يحصل أو يعيّن عددًا صحيحًا موقّعًا 32‑بت يحدد العرض المتوسط، بوحدات منطقية، للأحرف في الخط. |
| [setWidth(int value)](#setWidth-int-) | يحصل أو يعيّن عددًا صحيحًا موقّعًا 32‑بت يحدد العرض المتوسط، بوحدات منطقية، للأحرف في الخط. |
| [getEscapement()](#getEscapement--) | يحصل أو يعيّن عددًا صحيحًا موقّعًا 32‑بت يحدد الزاوية، بعشرات الدرجات، بين متجه الإزاحة ومحور x للجهاز. |
| [setEscapement(int value)](#setEscapement-int-) | يحصل أو يعيّن عددًا صحيحًا موقّعًا 32‑بت يحدد الزاوية، بعشرات الدرجات، بين متجه الإزاحة ومحور x للجهاز. |
| [getOrientation()](#getOrientation--) | يحصل أو يعيّن عددًا صحيحًا موقّعًا 32‑بت يحدد الزاوية، بعشرات الدرجات، بين خط أساس كل حرف ومحور x للجهاز. |
| [setOrientation(int value)](#setOrientation-int-) | يحصل أو يعيّن عددًا صحيحًا موقّعًا 32‑بت يحدد الزاوية، بعشرات الدرجات، بين خط أساس كل حرف ومحور x للجهاز. |
| [getWeight()](#getWeight--) | يحصل أو يعيّن عددًا صحيحًا موقّعًا 32‑بت يحدد وزن الخط في النطاق من صفر إلى 1000. |
| [setWeight(int value)](#setWeight-int-) | يحصل أو يعيّن عددًا صحيحًا موقّعًا 32‑بت يحدد وزن الخط في النطاق من صفر إلى 1000. |
| [getItalic()](#getItalic--) | يحصل أو يعيّن عددًا صحيحًا غير موقع 8‑بت يحدد خطًا مائلًا إذا تم تعيينه إلى 0x01؛ وإلا، يجب أن يُعيّن إلى 0x00. |
| [setItalic(byte value)](#setItalic-byte-) | يحصل أو يعيّن عددًا صحيحًا غير موقع 8‑بت يحدد خطًا مائلًا إذا تم تعيينه إلى 0x01؛ وإلا، يجب أن يُعيّن إلى 0x00. |
| [getUnderline()](#getUnderline--) | يحصل أو يعيّن عددًا صحيحًا غير موقع 8‑بت يحدد خطًا مسطرًا إذا تم تعيينه إلى 0x01؛ وإلا، يجب أن يُعيّن إلى 0x00. |
| [setUnderline(byte value)](#setUnderline-byte-) | يحصل أو يعيّن عددًا صحيحًا غير موقع 8‑بت يحدد خطًا مسطرًا إذا تم تعيينه إلى 0x01؛ وإلا، يجب أن يُعيّن إلى 0x00. |
| [getStrikeout()](#getStrikeout--) | يحصل أو يعيّن عددًا صحيحًا غير موقع 8‑بت يحدد خطًا مشطوبًا إذا تم تعيينه إلى 0x01؛ وإلا، يجب أن يُعيّن إلى 0x00. |
| [setStrikeout(byte value)](#setStrikeout-byte-) | يحصل أو يعيّن عددًا صحيحًا غير موقع 8‑بت يحدد خطًا مشطوبًا إذا تم تعيينه إلى 0x01؛ وإلا، يجب أن يُعيّن إلى 0x00. |
| [getCharSet()](#getCharSet--) | يحصل أو يعيّن عددًا صحيحًا غير موقع 8‑بت يحدد مجموعة رموز الأحرف. |
| [setCharSet(byte value)](#setCharSet-byte-) | يحصل أو يعيّن عددًا صحيحًا غير موقع 8‑بت يحدد مجموعة رموز الأحرف. |
| [getOutPrecision()](#getOutPrecision--) | يحصل أو يعيّن عددًا صحيحًا غير موقع 8‑بت يحدد دقة الإخراج. |
| [setOutPrecision(byte value)](#setOutPrecision-byte-) | يحصل أو يعيّن عددًا صحيحًا غير موقع 8‑بت يحدد دقة الإخراج. |
| [getClipPrecision()](#getClipPrecision--) | يحصل أو يعيّن عددًا صحيحًا غير موقع 8‑بت يحدد دقة القص. |
| [setClipPrecision(byte value)](#setClipPrecision-byte-) | يحصل أو يعيّن عددًا صحيحًا غير موقع 8‑بت يحدد دقة القص. |
| [getQuality()](#getQuality--) | يحصل أو يعيّن عددًا صحيحًا غير موقع 8‑بت يحدد جودة الإخراج. |
| [setQuality(byte value)](#setQuality-byte-) | يحصل أو يعيّن عددًا صحيحًا غير موقع 8‑بت يحدد جودة الإخراج. |
| [getPitchAndFamily()](#getPitchAndFamily--) | يحصل أو يعيّن كائن WMF PitchAndFamily ([MS-WMF] القسم 2.2.2.14) الذي يحدد درجة الخط وعائلته. |
| [setPitchAndFamily(WmfPitchAndFamily value)](#setPitchAndFamily-com.aspose.imaging.fileformats.wmf.objects.WmfPitchAndFamily-) | يحصل أو يعيّن كائن WMF PitchAndFamily ([MS-WMF] القسم 2.2.2.14) الذي يحدد درجة الخط وعائلته. |
| [getFacename()](#getFacename--) | يحصل أو يعيّن Facename (64 بايت): سلسلة لا تتجاوز 32 حرف يونيكود التي تحدد اسم الخط. |
| [setFacename(String value)](#setFacename-java.lang.String-) | يحصل أو يعيّن Facename (64 بايت): سلسلة لا تتجاوز 32 حرف يونيكود التي تحدد اسم الخط. |
### EmfLogFont() {#EmfLogFont--}
```
public EmfLogFont()
```


### getHeight() {#getHeight--}
```
public int getHeight()
```


يحصل أو يعيّن عددًا صحيحًا موقّعًا 32‑بت يحدد الارتفاع، بوحدات منطقية، لخلية حرف الخط أو الحرف. قيمة ارتفاع الحرف، المعروفة أيضًا بحجم الـ em، هي قيمة ارتفاع خلية الحرف مطروحًا منها قيمة المسافة الداخلية. يجب على مُعيّن الخط تفسير القيمة المحددة في حقل Height بالطريقة التالية.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public void setHeight(int value)
```


يحصل أو يعيّن عددًا صحيحًا موقّعًا 32‑بت يحدد الارتفاع، بوحدات منطقية، لخلية حرف الخط أو الحرف. قيمة ارتفاع الحرف، المعروفة أيضًا بحجم الـ em، هي قيمة ارتفاع خلية الحرف مطروحًا منها قيمة المسافة الداخلية. يجب على مُعيّن الخط تفسير القيمة المحددة في حقل Height بالطريقة التالية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getWidth() {#getWidth--}
```
public int getWidth()
```


يحصل أو يعيّن عددًا صحيحًا موقّعًا 32‑بت يحدد العرض المتوسط، بوحدات منطقية، للأحرف في الخط. إذا كانت قيمة حقل Width صفرًا، يجب حساب قيمة مناسبة من قيم LogFont الأخرى للعثور على خط يمتلك نسبة الأبعاد التي يقصدها المصمم.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public void setWidth(int value)
```


يحصل أو يعيّن عددًا صحيحًا موقّعًا 32‑بت يحدد العرض المتوسط، بوحدات منطقية، للأحرف في الخط. إذا كانت قيمة حقل Width صفرًا، يجب حساب قيمة مناسبة من قيم LogFont الأخرى للعثور على خط يمتلك نسبة الأبعاد التي يقصدها المصمم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getEscapement() {#getEscapement--}
```
public int getEscapement()
```


يحصل أو يضبط عددًا صحيحًا موقعًا 32 بت يحدد الزاوية، بعشرات الدرجات، بين متجه الإزاحة ومحور x للجهاز. متجه الإزاحة موازٍ لخط الأساس لسطر من النص.

**Returns:**
int
### setEscapement(int value) {#setEscapement-int-}
```
public void setEscapement(int value)
```


يحصل أو يضبط عددًا صحيحًا موقعًا 32 بت يحدد الزاوية، بعشرات الدرجات، بين متجه الإزاحة ومحور x للجهاز. متجه الإزاحة موازٍ لخط الأساس لسطر من النص.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getOrientation() {#getOrientation--}
```
public int getOrientation()
```


يحصل أو يعيّن عددًا صحيحًا موقّعًا 32‑بت يحدد الزاوية، بعشرات الدرجات، بين خط أساس كل حرف ومحور x للجهاز.

**Returns:**
int
### setOrientation(int value) {#setOrientation-int-}
```
public void setOrientation(int value)
```


يحصل أو يعيّن عددًا صحيحًا موقّعًا 32‑بت يحدد الزاوية، بعشرات الدرجات، بين خط أساس كل حرف ومحور x للجهاز.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getWeight() {#getWeight--}
```
public int getWeight()
```


يحصل أو يضبط عددًا صحيحًا موقعًا 32 بت يحدد وزن الخط في النطاق من الصفر إلى 1000. على سبيل المثال، 400 هو عادي و700 هو عريض. إذا كانت هذه القيمة صفرًا، يمكن استخدام وزن افتراضي.

**Returns:**
int
### setWeight(int value) {#setWeight-int-}
```
public void setWeight(int value)
```


يحصل أو يضبط عددًا صحيحًا موقعًا 32 بت يحدد وزن الخط في النطاق من الصفر إلى 1000. على سبيل المثال، 400 هو عادي و700 هو عريض. إذا كانت هذه القيمة صفرًا، يمكن استخدام وزن افتراضي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getItalic() {#getItalic--}
```
public byte getItalic()
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 8‑بت يحدد خطًا مائلًا إذا تم تعيينه إلى 0x01؛ وإلا، يجب أن يُعيّن إلى 0x00.

**Returns:**
byte
### setItalic(byte value) {#setItalic-byte-}
```
public void setItalic(byte value)
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 8‑بت يحدد خطًا مائلًا إذا تم تعيينه إلى 0x01؛ وإلا، يجب أن يُعيّن إلى 0x00.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | byte |  |

### getUnderline() {#getUnderline--}
```
public byte getUnderline()
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 8‑بت يحدد خطًا مسطرًا إذا تم تعيينه إلى 0x01؛ وإلا، يجب أن يُعيّن إلى 0x00.

**Returns:**
byte
### setUnderline(byte value) {#setUnderline-byte-}
```
public void setUnderline(byte value)
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 8‑بت يحدد خطًا مسطرًا إذا تم تعيينه إلى 0x01؛ وإلا، يجب أن يُعيّن إلى 0x00.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | byte |  |

### getStrikeout() {#getStrikeout--}
```
public byte getStrikeout()
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 8‑بت يحدد خطًا مشطوبًا إذا تم تعيينه إلى 0x01؛ وإلا، يجب أن يُعيّن إلى 0x00.

**Returns:**
byte
### setStrikeout(byte value) {#setStrikeout-byte-}
```
public void setStrikeout(byte value)
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 8‑بت يحدد خطًا مشطوبًا إذا تم تعيينه إلى 0x01؛ وإلا، يجب أن يُعيّن إلى 0x00.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | byte |  |

### getCharSet() {#getCharSet--}
```
public byte getCharSet()
```


يحصل أو يضبط عددًا صحيحًا غير موقع 8 بت يحدد مجموعة رموز الحروف. يجب أن يكون قيمة في تعداد WMF CharacterSet ([MS-WMF] القسم 2.1.1.5). إذا كان مجموعة الأحرف غير معروفة، يجب ألا تحاول معالجة ملف الميتا ترجمة أو تفسير السلاسل التي تم عرضها بهذا الخط.

**Returns:**
byte
### setCharSet(byte value) {#setCharSet-byte-}
```
public void setCharSet(byte value)
```


يحصل أو يضبط عددًا صحيحًا غير موقع 8 بت يحدد مجموعة رموز الحروف. يجب أن يكون قيمة في تعداد WMF CharacterSet ([MS-WMF] القسم 2.1.1.5). إذا كان مجموعة الأحرف غير معروفة، يجب ألا تحاول معالجة ملف الميتا ترجمة أو تفسير السلاسل التي تم عرضها بهذا الخط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | byte |  |

### getOutPrecision() {#getOutPrecision--}
```
public byte getOutPrecision()
```


يحصل أو يضبط عددًا صحيحًا غير موقع 8 بت يحدد دقة الإخراج. تحدد دقة الإخراج مدى قرب تطابق الخط مع الارتفاع والعرض والاتجاه والحرف والإزاحة والمسافة ونوع الخط المطلوب. يجب أن تكون قيمة من تعداد WMF OutPrecision.

**Returns:**
byte
### setOutPrecision(byte value) {#setOutPrecision-byte-}
```
public void setOutPrecision(byte value)
```


يحصل أو يضبط عددًا صحيحًا غير موقع 8 بت يحدد دقة الإخراج. تحدد دقة الإخراج مدى قرب تطابق الخط مع الارتفاع والعرض والاتجاه والحرف والإزاحة والمسافة ونوع الخط المطلوب. يجب أن تكون قيمة من تعداد WMF OutPrecision.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | byte |  |

### getClipPrecision() {#getClipPrecision--}
```
public byte getClipPrecision()
```


يحصل أو يضبط عددًا صحيحًا غير موقع 8 بت يحدد دقة القطع. تحدد دقة القطع كيفية قطع الأحرف التي تقع جزئيًا خارج منطقة القطع. يمكن أن تكون واحدة أو أكثر من أعلام WMF ClipPrecision.

**Returns:**
byte
### setClipPrecision(byte value) {#setClipPrecision-byte-}
```
public void setClipPrecision(byte value)
```


يحصل أو يضبط عددًا صحيحًا غير موقع 8 بت يحدد دقة القطع. تحدد دقة القطع كيفية قطع الأحرف التي تقع جزئيًا خارج منطقة القطع. يمكن أن تكون واحدة أو أكثر من أعلام WMF ClipPrecision.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | byte |  |

### getQuality() {#getQuality--}
```
public byte getQuality()
```


يحصل أو يضبط عددًا صحيحًا غير موقع 8 بت يحدد جودة الإخراج. تحدد جودة الإخراج مدى قرب محاولة مطابقة خصائص الخط المنطقي مع خصائص خط فعلي مادي. يجب أن تكون واحدة من القيم في تعداد WMF FontQuality ([MS-WMF] القسم 2.1.1.10).

**Returns:**
byte
### setQuality(byte value) {#setQuality-byte-}
```
public void setQuality(byte value)
```


يحصل أو يضبط عددًا صحيحًا غير موقع 8 بت يحدد جودة الإخراج. تحدد جودة الإخراج مدى قرب محاولة مطابقة خصائص الخط المنطقي مع خصائص خط فعلي مادي. يجب أن تكون واحدة من القيم في تعداد WMF FontQuality ([MS-WMF] القسم 2.1.1.10).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | byte |  |

### getPitchAndFamily() {#getPitchAndFamily--}
```
public WmfPitchAndFamily getPitchAndFamily()
```


يحصل أو يضبط كائن WMF PitchAndFamily ([MS-WMF] القسم 2.2.2.14) يحدد درجة الخط وعائلته. تصف عائلات الخطوط مظهر الخط بشكل عام. تُستخدم لتحديد خط عندما لا يكون نوع الخط المحدد متاحًا.

**Returns:**
[WmfPitchAndFamily](../../com.aspose.imaging.fileformats.wmf.objects/wmfpitchandfamily)
### setPitchAndFamily(WmfPitchAndFamily value) {#setPitchAndFamily-com.aspose.imaging.fileformats.wmf.objects.WmfPitchAndFamily-}
```
public void setPitchAndFamily(WmfPitchAndFamily value)
```


يحصل أو يضبط كائن WMF PitchAndFamily ([MS-WMF] القسم 2.2.2.14) يحدد درجة الخط وعائلته. تصف عائلات الخطوط مظهر الخط بشكل عام. تُستخدم لتحديد خط عندما لا يكون نوع الخط المحدد متاحًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [WmfPitchAndFamily](../../com.aspose.imaging.fileformats.wmf.objects/wmfpitchandfamily) |  |

### getFacename() {#getFacename--}
```
public String getFacename()
```


يحصل أو يضبط اسم الوجه (64 بايت): سلسلة لا تزيد عن 32 حرف يونيكود تحدد اسم نوع الخط. إذا كان طول هذه السلسلة أقل من 32 حرفًا، يجب أن يكون هناك NULL نهائي، وبعده يجب تجاهل باقي الحقل.

**Returns:**
java.lang.String
### setFacename(String value) {#setFacename-java.lang.String-}
```
public void setFacename(String value)
```


يحصل أو يضبط اسم الوجه (64 بايت): سلسلة لا تزيد عن 32 حرف يونيكود تحدد اسم نوع الخط. إذا كان طول هذه السلسلة أقل من 32 حرفًا، يجب أن يكون هناك NULL نهائي، وبعده يجب تجاهل باقي الحقل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

