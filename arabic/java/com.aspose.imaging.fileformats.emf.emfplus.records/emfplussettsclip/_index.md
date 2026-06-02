---
title: "EmfPlusSetTsClip"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "سجل EmfPlusSetTSClip يحدد مناطق القص في سياق جهاز الرسومات لخادم الطرفية."
type: docs
weight: 66
url: /ar/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplussettsclip/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusTerminalServerRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusterminalserverrecordtype)
```
public final class EmfPlusSetTsClip extends EmfPlusTerminalServerRecordType
```

سجل EmfPlusSetTSClip يحدد مناطق القص في سياق جهاز الرسومات لخادم الطرفية.

مخطط الضغط للبيانات في هذا السجل يستخدم الخوارزمية التالية. يتم ترميز كل نقطة من كل مستطيل إما بايتًا واحدًا أو بايتين. إذا تم ترميز النقطة بايتًا واحدًا، يجب أن يكون البت العالي (0x80) للبايت مُعيّنًا، وتكون القيمة رقمًا موقعًا ممثلاً بالبتات السبع الأقل. إذا لم يُعيّن البت العالي، تُرمَّز القيمة بايتين، حيث يُرمَّز البايت الأعلى في الـ7 بتات الأقل من البايت الأول، وتُرمَّز قيمة البايت الأقل في البايت الثاني. تُرمَّز كل نقطة كفرق بين النقطة في المستطيل الحالي والنقطة في المستطيل السابق. تُرمَّز النقطة السفلية للمستطيل كفرق بين الإحداثي السفلي والإحداثي العلوي في المستطيل الحالي.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfPlusSetTsClip(EmfPlusRecord source)](#EmfPlusSetTsClip-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | يُهيئ نسخة جديدة من الفئة `EmfPlusSetTsClip`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getCompressed()](#getCompressed--) | يحصل على قيمة تشير إلى ما إذا كان `EmfPlusSetTsClip` مضغوطًا. |
| [getNumRects()](#getNumRects--) | يحصل على عدد rects. |
| [getRects()](#getRects--) | يحصل أو يضبط مصفوفة من مستطيلات NumRects التي تحدد مناطق القص. |
| [setRects(Rectangle[] value)](#setRects-com.aspose.imaging.Rectangle---) | يحصل أو يضبط مصفوفة من مستطيلات NumRects التي تحدد مناطق القص. |
### EmfPlusSetTsClip(EmfPlusRecord source) {#EmfPlusSetTsClip-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusSetTsClip(EmfPlusRecord source)
```


يُهيئ نسخة جديدة من الفئة `EmfPlusSetTsClip`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | المصدر. |

### getCompressed() {#getCompressed--}
```
public boolean getCompressed()
```


يحصل على قيمة تشير إلى ما إذا كان هذا `EmfPlusSetTsClip` مضغوطًا. تحدد هذه البت تنسيق بيانات المستطيلات في حقل rects. إذا تم ضبطه، يتم تعريف كل مستطيل في 4 بايتات. إذا لم يتم ضبطه، يتم تعريف كل مستطيل في 8 بايتات.

القيمة: `true` إذا كانت مضغوطة؛ وإلا `false`.

**Returns:**
boolean
### getNumRects() {#getNumRects--}
```
public short getNumRects()
```


يحصل على عدد rects. يحدد هذا الحقل عدد المستطيلات التي تم تعريفها في حقل rect.

القيمة: عدد rects.

**Returns:**
short
### getRects() {#getRects--}
```
public Rectangle[] getRects()
```


يحصل أو يضبط مصفوفة من مستطيلات NumRects التي تحدد مناطق القص. يتم تحديد تنسيق هذه البيانات بواسطة البت C في حقل Flags.

القيمة: rects.

**Returns:**
com.aspose.imaging.Rectangle[]
### setRects(Rectangle[] value) {#setRects-com.aspose.imaging.Rectangle---}
```
public void setRects(Rectangle[] value)
```


يحصل أو يضبط مصفوفة من مستطيلات NumRects التي تحدد مناطق القص. يتم تحديد تنسيق هذه البيانات بواسطة البت C في حقل Flags.

القيمة: rects.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Rectangle\[\]](../../com.aspose.imaging/rectangle) |  |

