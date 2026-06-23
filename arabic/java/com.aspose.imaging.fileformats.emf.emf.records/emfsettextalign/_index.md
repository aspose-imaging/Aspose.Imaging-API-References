---
title: "EmfSetTextAlign"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "سجل EMR_SETTEXTALIGN يحدد محاذاة النص."
type: docs
weight: 139
url: /ar/java/com.aspose.imaging.fileformats.emf.emf.records/emfsettextalign/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfSetTextAlign extends EmfStateRecordType
```

السجل EMR\_SETTEXTALIGN يحدد محاذاة النص.

تستخدم سجلات EMR\_SMALLTEXTOUT و EMR\_EXTTEXTOUTA و EMR\_EXTTEXTOUTW قيم محاذاة النص لتحديد موضع سلسلة نصية على وسيلة الإخراج. تحدد القيم العلاقة بين نقطة مرجعية ومستطيل يحد النص. تكون النقطة المرجعية إما الموضع الحالي أو نقطة تُمرّر إلى سجل إخراج النص. المستطيل الذي يحد النص يتكوّن من خلايا الأحرف في سلسلة النص.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfSetTextAlign(EmfRecord source)](#EmfSetTextAlign-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | يُنشئ مثيلًا جديدًا من الفئة `EmfSetTextAlign`. |
| [EmfSetTextAlign()](#EmfSetTextAlign--) | يُنشئ مثيلًا جديدًا من الفئة `EmfSetTextAlign`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getTextAlignmentMode()](#getTextAlignmentMode--) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد محاذاة النص باستخدام قناع من أعلام محاذاة النص. |
| [setTextAlignmentMode(int value)](#setTextAlignmentMode-int-) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد محاذاة النص باستخدام قناع من أعلام محاذاة النص. |
### EmfSetTextAlign(EmfRecord source) {#EmfSetTextAlign-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetTextAlign(EmfRecord source)
```


يُنشئ مثيلًا جديدًا من الفئة `EmfSetTextAlign`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | المصدر. |

### EmfSetTextAlign() {#EmfSetTextAlign--}
```
public EmfSetTextAlign()
```


يُنشئ مثيلًا جديدًا من الفئة `EmfSetTextAlign`.

### getTextAlignmentMode() {#getTextAlignmentMode--}
```
public int getTextAlignmentMode()
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد محاذاة النص باستخدام قناع من علامات محاذاة النص. تكون هذه إما `Wmf.Consts.WmfTextAlignmentModeFlags` ([MS-WMF] القسم 2.1.2.3) للنص ذو الخط الأساسي الأفقي، أو `Wmf.Consts.WmfVerticalTextAlignmentModeFlags` ([MS-WMF] القسم 2.1.2.4) للنص ذو الخط الأساسي العمودي. يمكن اختيار قيمة واحدة فقط من تلك التي تؤثر على المحاذاة الأفقية والعمودية.

**Returns:**
int
### setTextAlignmentMode(int value) {#setTextAlignmentMode-int-}
```
public void setTextAlignmentMode(int value)
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد محاذاة النص باستخدام قناع من علامات محاذاة النص. تكون هذه إما `Wmf.Consts.WmfTextAlignmentModeFlags` ([MS-WMF] القسم 2.1.2.3) للنص ذو الخط الأساسي الأفقي، أو `Wmf.Consts.WmfVerticalTextAlignmentModeFlags` ([MS-WMF] القسم 2.1.2.4) للنص ذو الخط الأساسي العمودي. يمكن اختيار قيمة واحدة فقط من تلك التي تؤثر على المحاذاة الأفقية والعمودية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

