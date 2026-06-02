---
title: "EmfColorAdjustment"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "كائن ColorAdjustment يحدد القيم لتعديل الألوان في صور البت المصدرية أثناء عمليات النقل بت-بلوك."
type: docs
weight: 12
url: /ar/java/com.aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public final class EmfColorAdjustment extends EmfObject
```

كائن ColorAdjustment يحدد القيم لتعديل الألوان في صور البت المصدرية أثناء عمليات النقل بت-بلوك.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfColorAdjustment()](#EmfColorAdjustment--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getSize()](#getSize--) | يحصل أو يعيّن عددًا صحيحًا غير موقعًا 16 بت يحدد حجم هذا الكائن بالبايت. |
| [setSize(short value)](#setSize-short-) | يحصل أو يعيّن عددًا صحيحًا غير موقعًا 16 بت يحدد حجم هذا الكائن بالبايت. |
| [getValues()](#getValues--) | يحصل أو يعيّن عددًا صحيحًا غير موقعًا 16 بت يحدد طريقة إعداد صورة الإخراج. |
| [setValues(int value)](#setValues-int-) | يحصل أو يعيّن عددًا صحيحًا غير موقعًا 16 بت يحدد طريقة إعداد صورة الإخراج. |
| [getIlluminantIndex()](#getIlluminantIndex--) | يحصل أو يعيّن عددًا صحيحًا غير موقعًا 16 بت يحدد نوع مصدر الضوء القياسي الذي تُعرض تحته الصورة، من تعداد Illuminant (القسم 2.1.19). |
| [setIlluminantIndex(int value)](#setIlluminantIndex-int-) | يحصل أو يعيّن عددًا صحيحًا غير موقعًا 16 بت يحدد نوع مصدر الضوء القياسي الذي تُعرض تحته الصورة، من تعداد Illuminant (القسم 2.1.19). |
| [getRedGamma()](#getRedGamma--) | يحصل أو يعيّن عددًا صحيحًا غير موقعًا 16 بت يحدد قيمة تصحيح غاما للدرجة n للون الأحمر الأساسي في ألوان المصدر. |
| [setRedGamma(short value)](#setRedGamma-short-) | يحصل أو يعيّن عددًا صحيحًا غير موقعًا 16 بت يحدد قيمة تصحيح غاما للدرجة n للون الأحمر الأساسي في ألوان المصدر. |
| [getGreenGamma()](#getGreenGamma--) | يحصل أو يعيّن عددًا صحيحًا غير موقعًا 16 بت يحدد قيمة تصحيح غاما للدرجة n للون الأخضر الأساسي في ألوان المصدر. |
| [setGreenGamma(short value)](#setGreenGamma-short-) | يحصل أو يعيّن عددًا صحيحًا غير موقعًا 16 بت يحدد قيمة تصحيح غاما للدرجة n للون الأخضر الأساسي في ألوان المصدر. |
| [getBlueGamma()](#getBlueGamma--) | يحصل أو يعيّن عددًا صحيحًا غير موقعًا 16 بت يحدد قيمة تصحيح غاما للدرجة n للون الأزرق الأساسي في ألوان المصدر. |
| [setBlueGamma(short value)](#setBlueGamma-short-) | يحصل أو يعيّن عددًا صحيحًا غير موقعًا 16 بت يحدد قيمة تصحيح غاما للدرجة n للون الأزرق الأساسي في ألوان المصدر. |
| [getReferenceBlack()](#getReferenceBlack--) | يحصل أو يعيّن عددًا صحيحًا غير موقعًا 16 بت يحدد المرجع الأسود لألوان المصدر. |
| [setReferenceBlack(short value)](#setReferenceBlack-short-) | يحصل أو يعيّن عددًا صحيحًا غير موقعًا 16 بت يحدد المرجع الأسود لألوان المصدر. |
| [getReferenceWhite()](#getReferenceWhite--) | يحصل أو يعيّن عددًا صحيحًا غير موقعًا 16 بت يحدد المرجع الأبيض لألوان المصدر. |
| [setReferenceWhite(short value)](#setReferenceWhite-short-) | يحصل أو يعيّن عددًا صحيحًا غير موقعًا 16 بت يحدد المرجع الأبيض لألوان المصدر. |
| [getContrast()](#getContrast--) | يحصل أو يعيّن عددًا صحيحًا موقعًا 16 بت يحدد مقدار التباين الذي سيُطبق على كائن المصدر. |
| [setContrast(short value)](#setContrast-short-) | يحصل أو يعيّن عددًا صحيحًا موقعًا 16 بت يحدد مقدار التباين الذي سيُطبق على كائن المصدر. |
| [getBrightness()](#getBrightness--) | يحصل أو يعيّن عددًا صحيحًا موقعًا 16‑بت يحدد مقدار السطوع الذي سيُطبق على الكائن المصدر. |
| [setBrightness(short value)](#setBrightness-short-) | يحصل أو يعيّن عددًا صحيحًا موقعًا 16‑بت يحدد مقدار السطوع الذي سيُطبق على الكائن المصدر. |
| [getColorfullness()](#getColorfullness--) | يحصل أو يعيّن عددًا صحيحًا موقعًا 16‑بت يحدد مقدار التشبع اللوني الذي سيُطبق على الكائن المصدر. |
| [setColorfullness(short value)](#setColorfullness-short-) | يحصل أو يعيّن عددًا صحيحًا موقعًا 16‑بت يحدد مقدار التشبع اللوني الذي سيُطبق على الكائن المصدر. |
| [getRedGreenTint()](#getRedGreenTint--) | يحصل أو يعيّن عددًا صحيحًا موقعًا 16‑بت يحدد مقدار تعديل الصبغة الحمراء أو الخضراء الذي سيُطبق على الكائن المصدر. |
| [setRedGreenTint(short value)](#setRedGreenTint-short-) | يحصل أو يعيّن عددًا صحيحًا موقعًا 16‑بت يحدد مقدار تعديل الصبغة الحمراء أو الخضراء الذي سيُطبق على الكائن المصدر. |
### EmfColorAdjustment() {#EmfColorAdjustment--}
```
public EmfColorAdjustment()
```


### getSize() {#getSize--}
```
public short getSize()
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 16‑بت يحدد الحجم بالبايت لهذا الكائن. يجب أن يكون هذا 0x0018.

**Returns:**
short
### setSize(short value) {#setSize-short-}
```
public void setSize(short value)
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 16‑بت يحدد الحجم بالبايت لهذا الكائن. يجب أن يكون هذا 0x0018.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | short |  |

### getValues() {#getValues--}
```
public int getValues()
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 16‑بت يحدد طريقة إعداد صورة الإخراج. يمكن ضبط هذا الحقل إلى NULL أو إلى أي تركيبة من القيم في تعداد ColorAdjustment (القسم 2.1.5).

**Returns:**
int
### setValues(int value) {#setValues-int-}
```
public void setValues(int value)
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 16‑بت يحدد طريقة إعداد صورة الإخراج. يمكن ضبط هذا الحقل إلى NULL أو إلى أي تركيبة من القيم في تعداد ColorAdjustment (القسم 2.1.5).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getIlluminantIndex() {#getIlluminantIndex--}
```
public int getIlluminantIndex()
```


يحصل أو يعيّن عددًا صحيحًا غير موقعًا 16 بت يحدد نوع مصدر الضوء القياسي الذي تُعرض تحته الصورة، من تعداد Illuminant (القسم 2.1.19).

**Returns:**
int
### setIlluminantIndex(int value) {#setIlluminantIndex-int-}
```
public void setIlluminantIndex(int value)
```


يحصل أو يعيّن عددًا صحيحًا غير موقعًا 16 بت يحدد نوع مصدر الضوء القياسي الذي تُعرض تحته الصورة، من تعداد Illuminant (القسم 2.1.19).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getRedGamma() {#getRedGamma--}
```
public short getRedGamma()
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 16‑بت يحدد قيمة تصحيح غاما للدرجة n للون الأحمر الأساسي في ألوان المصدر. يجب أن تكون هذه القيمة في النطاق من 2,500 إلى 65,000. قيمة 10,000 تعني أنه لا يجوز إجراء تصحيح غاما.

**Returns:**
short
### setRedGamma(short value) {#setRedGamma-short-}
```
public void setRedGamma(short value)
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 16‑بت يحدد قيمة تصحيح غاما للدرجة n للون الأحمر الأساسي في ألوان المصدر. يجب أن تكون هذه القيمة في النطاق من 2,500 إلى 65,000. قيمة 10,000 تعني أنه لا يجوز إجراء تصحيح غاما.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | short |  |

### getGreenGamma() {#getGreenGamma--}
```
public short getGreenGamma()
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 16‑بت يحدد قيمة تصحيح غاما للدرجة n للون الأخضر الأساسي في ألوان المصدر. يجب أن تكون هذه القيمة في النطاق من 2,500 إلى 65,000. قيمة 10,000 تعني أنه لا يجوز إجراء تصحيح غاما.

**Returns:**
short
### setGreenGamma(short value) {#setGreenGamma-short-}
```
public void setGreenGamma(short value)
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 16‑بت يحدد قيمة تصحيح غاما للدرجة n للون الأخضر الأساسي في ألوان المصدر. يجب أن تكون هذه القيمة في النطاق من 2,500 إلى 65,000. قيمة 10,000 تعني أنه لا يجوز إجراء تصحيح غاما.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | short |  |

### getBlueGamma() {#getBlueGamma--}
```
public short getBlueGamma()
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 16‑بت يحدد قيمة تصحيح غاما للدرجة n للون الأزرق الأساسي في ألوان المصدر. يجب أن تكون هذه القيمة في النطاق من 2,500 إلى 65,000. قيمة 10,000 تعني أنه لا يجوز إجراء تصحيح غاما.

**Returns:**
short
### setBlueGamma(short value) {#setBlueGamma-short-}
```
public void setBlueGamma(short value)
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 16‑بت يحدد قيمة تصحيح غاما للدرجة n للون الأزرق الأساسي في ألوان المصدر. يجب أن تكون هذه القيمة في النطاق من 2,500 إلى 65,000. قيمة 10,000 تعني أنه لا يجوز إجراء تصحيح غاما.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | short |  |

### getReferenceBlack() {#getReferenceBlack--}
```
public short getReferenceBlack()
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 16‑بت يحدد المرجع الأسود لألوان المصدر. أي ألوان أغمق من هذا تُعامل كأنها سوداء. يجب أن تكون هذه القيمة في النطاق من صفر إلى 4,000.

**Returns:**
short
### setReferenceBlack(short value) {#setReferenceBlack-short-}
```
public void setReferenceBlack(short value)
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 16‑بت يحدد المرجع الأسود لألوان المصدر. أي ألوان أغمق من هذا تُعامل كأنها سوداء. يجب أن تكون هذه القيمة في النطاق من صفر إلى 4,000.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | short |  |

### getReferenceWhite() {#getReferenceWhite--}
```
public short getReferenceWhite()
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 16‑بت يحدد المرجع الأبيض لألوان المصدر. أي ألوان أفتح من هذا تُعامل كأنها بيضاء. يجب أن تكون هذه القيمة في النطاق من 6,000 إلى 10,000.

**Returns:**
short
### setReferenceWhite(short value) {#setReferenceWhite-short-}
```
public void setReferenceWhite(short value)
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 16‑بت يحدد المرجع الأبيض لألوان المصدر. أي ألوان أفتح من هذا تُعامل كأنها بيضاء. يجب أن تكون هذه القيمة في النطاق من 6,000 إلى 10,000.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | short |  |

### getContrast() {#getContrast--}
```
public short getContrast()
```


يحصل أو يعيّن عددًا صحيحًا موقعًا 16‑بت يحدد مقدار التباين الذي سيُطبق على الكائن المصدر. يجب أن تكون هذه القيمة في النطاق من –100 إلى 100. قيمة الصفر تعني أنه لا يجوز إجراء تعديل التباين.

**Returns:**
short
### setContrast(short value) {#setContrast-short-}
```
public void setContrast(short value)
```


يحصل أو يعيّن عددًا صحيحًا موقعًا 16‑بت يحدد مقدار التباين الذي سيُطبق على الكائن المصدر. يجب أن تكون هذه القيمة في النطاق من –100 إلى 100. قيمة الصفر تعني أنه لا يجوز إجراء تعديل التباين.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | short |  |

### getBrightness() {#getBrightness--}
```
public short getBrightness()
```


يحصل أو يعيّن عددًا صحيحًا موقعًا 16‑بت يحدد مقدار السطوع الذي سيُطبق على الكائن المصدر. يجب أن تكون هذه القيمة في النطاق من –100 إلى 100. قيمة الصفر تعني أنه لا يجوز إجراء تعديل السطوع.

**Returns:**
short
### setBrightness(short value) {#setBrightness-short-}
```
public void setBrightness(short value)
```


يحصل أو يعيّن عددًا صحيحًا موقعًا 16‑بت يحدد مقدار السطوع الذي سيُطبق على الكائن المصدر. يجب أن تكون هذه القيمة في النطاق من –100 إلى 100. قيمة الصفر تعني أنه لا يجوز إجراء تعديل السطوع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | short |  |

### getColorfullness() {#getColorfullness--}
```
public short getColorfullness()
```


يحصل أو يعيّن عددًا صحيحًا موقعًا 16‑بت يحدد مقدار التشبع اللوني الذي سيُطبق على الكائن المصدر. يجب أن تكون هذه القيمة في النطاق من –100 إلى 100. قيمة الصفر تعني أنه لا يجوز إجراء تعديل التشبع اللوني.

**Returns:**
short
### setColorfullness(short value) {#setColorfullness-short-}
```
public void setColorfullness(short value)
```


يحصل أو يعيّن عددًا صحيحًا موقعًا 16‑بت يحدد مقدار التشبع اللوني الذي سيُطبق على الكائن المصدر. يجب أن تكون هذه القيمة في النطاق من –100 إلى 100. قيمة الصفر تعني أنه لا يجوز إجراء تعديل التشبع اللوني.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | short |  |

### getRedGreenTint() {#getRedGreenTint--}
```
public short getRedGreenTint()
```


يحصل أو يعيّن عددًا صحيحًا موقعًا 16‑بت يحدد مقدار تعديل الصبغة الحمراء أو الخضراء الذي سيُطبق على الكائن المصدر. يجب أن تكون هذه القيمة في النطاق من –100 إلى 100. الأعداد الموجبة تعدل نحو الأحمر والأعداد السالبة نحو الأخضر. قيمة الصفر تعني أنه لا يجوز إجراء تعديل الصبغة.

**Returns:**
short
### setRedGreenTint(short value) {#setRedGreenTint-short-}
```
public void setRedGreenTint(short value)
```


يحصل أو يعيّن عددًا صحيحًا موقعًا 16‑بت يحدد مقدار تعديل الصبغة الحمراء أو الخضراء الذي سيُطبق على الكائن المصدر. يجب أن تكون هذه القيمة في النطاق من –100 إلى 100. الأعداد الموجبة تعدل نحو الأحمر والأعداد السالبة نحو الأخضر. قيمة الصفر تعني أنه لا يجوز إجراء تعديل الصبغة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | short |  |

