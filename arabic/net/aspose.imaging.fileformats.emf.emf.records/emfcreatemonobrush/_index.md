---
title: "الفئة EmfCreateMonoBrush"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfCreateMonoBrush. سجل EMR_CREATEMONOBRUSH يعرّف فرشاة نمط أحادية اللون لعمليات الرسوميات. يتم تحديد النمط بواسطة DIB أحادي اللون."
type: docs
weight: 3600
url: /ar/net/aspose.imaging.fileformats.emf.emf.records/emfcreatemonobrush/
---
## EmfCreateMonoBrush class

سجل EMR_CREATEMONOBRUSH يعرف فرشاة نمط أحادية اللون لعمليات الرسوم. النمط محدد بواسطة DIB أحادي اللون.

```csharp
public sealed class EmfCreateMonoBrush : EmfObjectCreationRecordType
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfCreateMonoBrush](emfcreatemonobrush/)(EmfRecord) | يُهيّئ مثيلًا جديدًا من الفئة `EmfCreateMonoBrush`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [BitmapBuffer](../../aspose.imaging.fileformats.emf.emf.records/emfcreatemonobrush/bitmapbuffer/) { get; set; } | يحصل أو يضبط مخزنًا يحتوي على DIB مضغوط على شكل كائن WMF DeviceIndependentBitmap ([MS-WMF] القسم 2.2.2.9). لا يلزم أن يكون متجاورًا مع الجزء الثابت من سجل EMR_CREATEDIBPATTERNBRUSHPT. |
| [IhBrush](../../aspose.imaging.fileformats.emf.emf.records/emfcreatemonobrush/ihbrush/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقعًا 32‑بت يحدد فهرس كائن فرشاة النمط أحادي اللون في جدول كائنات EMF (القسم 3.1.1.1). يجب حفظ هذا الفهرس لكي يمكن إعادة استخدام هذا الكائن أو تعديلّه. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | يحصل أو يعيّن حجم السجل |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | يحصل أو يعيّن النوع. |
| [Usage](../../aspose.imaging.fileformats.emf.emf.records/emfcreatemonobrush/usage/) { get; set; } | يحصل أو يضبط عددًا صحيحًا غير موقع 32 بت يحدد كيفية تفسير القيم في جدول الألوان في رأس DIB. يجب أن تكون هذه القيمة ضمن تعداد DIBColors (القسم 2.1.9). |

### انظر أيضًا

* class [EmfObjectCreationRecordType](../emfobjectcreationrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


