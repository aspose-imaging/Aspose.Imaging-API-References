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

يستخدم مخطط الضغط للبيانات في هذا السجل الخوارزمية التالية. يتم ترميز كل نقطة من كل مستطيل إما بايتًا واحدًا أو بايتين. إذا تم ترميز النقطة بايتًا واحدًا، يجب تعيين البت العالي (0x80) للبايت، وتكون القيمة عددًا موقعًا ممثلاً بالبتات السبع الأقل. إذا لم يتم تعيين البت العالي، فإن القيمة تُرمّز ببايتين، حيث يتم ترميز البايت الأعلى في البتات السبع الأقل من البايت الأول، ويتم ترميز قيمة البايت الأقل في البايت الثاني. يتم ترميز كل نقطة كفرق بين النقطة في المستطيل الحالي والنقطة في المستطيل السابق. يتم ترميز النقطة السفلية للمستطيل كفرق بين الإحداثي السفلي والإحداثي العلوي في المستطيل الحالي.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfPlusSetTsClip(EmfPlusRecord source)](#EmfPlusSetTsClip-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | ينشئ مثيلًا جديدًا من الفئة `EmfPlusSetTsClip`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getCompressed()](#getCompressed--) | يحصل على قيمة تشير إلى ما إذا كان هذا `EmfPlusSetTsClip` مضغوطًا. |
| [getNumRects()](#getNumRects--) | يحصل على عدد المستطيلات. |
| [getRects()](#getRects--) | يحصل أو يعيّن مصفوفة من مستطيلات NumRects التي تحدد مناطق القص. |
| [setRects(Rectangle[] value)](#setRects-com.aspose.imaging.Rectangle---) | يحصل أو يعيّن مصفوفة من مستطيلات NumRects التي تحدد مناطق القص. |
### EmfPlusSetTsClip(EmfPlusRecord source) {#EmfPlusSetTsClip-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusSetTsClip(EmfPlusRecord source)
```


ينشئ مثيلًا جديدًا من الفئة `EmfPlusSetTsClip`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | المصدر. |

### getCompressed() {#getCompressed--}
```
public boolean getCompressed()
```


يحصل على قيمة تشير إلى ما إذا كان هذا `EmfPlusSetTsClip` مضغوطًا. يحدد هذا البت تنسيق بيانات المستطيلات في حقل rects. إذا كان مضبوطًا، يتم تعريف كل مستطيل في 4 بايتات. إذا كان غير مضبوط، يتم تعريف كل مستطيل في 8 بايتات.

القيمة: `true` إذا كان مضغوطًا؛ وإلا `false`.

**Returns:**
boolean
### getNumRects() {#getNumRects--}
```
public short getNumRects()
```


يحصل على عدد المستطيلات. يحدد هذا الحقل عدد المستطيلات التي تم تعريفها في حقل rect.

القيمة: عدد المستطيلات.

**Returns:**
قصير
### getRects() {#getRects--}
```
public Rectangle[] getRects()
```


يحصل أو يعيّن مصفوفة من مستطيلات NumRects التي تحدد مناطق القص. يتم تحديد تنسيق هذه البيانات بواسطة البت C في حقل Flags.

القيمة: المستطيلات.

**Returns:**
com.aspose.imaging.Rectangle[]
### setRects(Rectangle[] value) {#setRects-com.aspose.imaging.Rectangle---}
```
public void setRects(Rectangle[] value)
```


يحصل أو يعيّن مصفوفة من مستطيلات NumRects التي تحدد مناطق القص. يتم تحديد تنسيق هذه البيانات بواسطة البت C في حقل Flags.

القيمة: المستطيلات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Rectangle\[\]](../../com.aspose.imaging/rectangle) |  |

