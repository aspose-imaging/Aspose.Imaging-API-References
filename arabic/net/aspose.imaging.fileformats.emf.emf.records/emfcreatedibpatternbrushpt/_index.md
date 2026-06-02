---
title: "الفئة EmfCreateDibPatternBrushPt"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfCreateDibPatternBrushPt. سجل EMR_CREATEDIBPATTERNBRUSHPT يعرّف فرشاة نمطية لعمليات الرسومات. يتم تحديد النمط بواسطة DIB."
type: docs
weight: 3590
url: /ar/net/aspose.imaging.fileformats.emf.emf.records/emfcreatedibpatternbrushpt/
---
## EmfCreateDibPatternBrushPt class

سجل EMR_CREATEDIBPATTERNBRUSHPT يعرف فرشاة نمطية لعمليات الرسوم. النمط محدد بواسطة DIB.

```csharp
public sealed class EmfCreateDibPatternBrushPt : EmfObjectCreationRecordType
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfCreateDibPatternBrushPt](emfcreatedibpatternbrushpt/#constructor)() | ينشئ مثيلًا جديدًا للفئة `EmfCreateDibPatternBrushPt`. |
| [EmfCreateDibPatternBrushPt](emfcreatedibpatternbrushpt/#constructor_1)(EmfRecord) | ينشئ مثيلًا جديدًا للفئة `EmfCreateDibPatternBrushPt`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [BitmapBuffer](../../aspose.imaging.fileformats.emf.emf.records/emfcreatedibpatternbrushpt/bitmapbuffer/) { get; set; } | يحصل أو يضبط مخزنًا يحتوي على DIB مضغوط على شكل كائن WMF DeviceIndependentBitmap ([MS-WMF] القسم 2.2.2.9). لا يلزم أن يكون متجاورًا مع الجزء الثابت من سجل EMR_CREATEDIBPATTERNBRUSHPT. |
| [IhBrush](../../aspose.imaging.fileformats.emf.emf.records/emfcreatedibpatternbrushpt/ihbrush/) { get; set; } | يحصل أو يضبط عددًا صحيحًا غير موقع 32 بت يحدد فهرس كائن فرشاة النمط في جدول كائنات EMF (القسم 3.1.1.1). يجب حفظ هذا الفهرس حتى يمكن إعادة استخدام هذا الكائن أو تعديله. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | يحصل أو يعيّن حجم السجل |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | يحصل أو يعيّن النوع. |
| [Usage](../../aspose.imaging.fileformats.emf.emf.records/emfcreatedibpatternbrushpt/usage/) { get; set; } | يحصل أو يضبط عددًا صحيحًا غير موقع 32 بت يحدد كيفية تفسير القيم في جدول الألوان في رأس DIB. يجب أن تكون هذه القيمة ضمن تعداد DIBColors (القسم 2.1.9). |

## ملاحظات

يمكن اختيار كائن فرشاة النمط المحدد بواسطة هذا السجل في سياق جهاز التشغيل بواسطة سجل EMR_SELECTOBJECT (القسم 2.3.8.5)، الذي يحدد فرشاة النمط التي ستُستخدم في عمليات الرسومات اللاحقة.

### انظر أيضًا

* class [EmfObjectCreationRecordType](../emfobjectcreationrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


