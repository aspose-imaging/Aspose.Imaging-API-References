---
title: "الفئة EmfPlusDrawArc"
second_title: "Aspose.Imaging for .NET API Reference"
description: "Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusDrawArc الفئة. السجل EmfPlusDrawArc يحدد رسم قوس إهليلج"
type: docs
weight: 6020
url: /ar/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawarc/
---
## EmfPlusDrawArc class

سجل EmfPlusDrawArc يحدد رسم قوس من إهليلج.

```csharp
public sealed class EmfPlusDrawArc : EmfPlusDrawingRecordType
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfPlusDrawArc](emfplusdrawarc/)(EmfPlusRecord) | يقوم بإنشاء نسخة جديدة من الفئة `EmfPlusDrawArc`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| override [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawarc/datasize/) { get; set; } | يحصل أو يعيّن حجم البيانات. عدد صحيح غير موقع 32‑بت يحدد عدد البايتات المتراصة على 32‑بت للبيانات الخاصة بالسجل التي تلي ذلك. لهذا النوع من السجلات، يجب أن تكون القيمة واحدة من القيم التالية: 0x00000010 إذا كان بت C مضبوطًا في حقل Flags. 0x00000018 إذا كان بت C غير مضبوط في حقل Flags. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 16‑بت يحتوي على معلومات لبعض السجلات حول كيفية تنفيذ العملية وعلى بنية السجل. |
| [ObjectId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawarc/objectid/) { get; set; } | يحصل أو يعيّن معرف الكائن. فهرس كائن EmfPlusPen (القسم 2.2.1.7) في جدول كائنات EMF+ لرسم القوس. يجب أن تكون القيمة بين 0 و 63 شاملًا. |
| [RectangleData](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawarc/rectangledata/) { get; set; } | يحصل أو يعيّن بيانات المستطيل إما كائن EmfPlusRect أو EmfPlusRectF يحدد صندوق الحد للإهليلج المتوازي مع القوس. هذا المستطيل يحدد موضع القوس وحجمه وشكله. نوع الكائن في هذا الحقل يُحدد بقيمة حقل Flags. |
| [RectFloat](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawarc/rectfloat/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كانت البيانات تحتوي على سجلات EmfPlusRectF أو EmfPlusRect. هذا البت يحدد ما إذا كانت البيانات في حقل RectData مضغوطة. إذا كان مضبوطًا، يحتوي RectData على كائن EmfPlusRect (القسم 2.2.2.38). إذا كان غير مضبوط، يحتوي RectData على كائن EmfPlusRectF (القسم 2.2.2.39). |
| override [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawarc/size/) { get; set; } | يحصل أو يعيّن الحجم. عدد صحيح غير موقع 32‑بت يحدد عدد البايتات المتراصة على 32‑بت في السجل بالكامل، بما في ذلك رأس السجل الذي يبلغ 12 بايتًا والبيانات الخاصة بالسجل. لهذا النوع من السجلات، يجب أن تكون القيمة واحدة من القيم التالية: 0x0000001C إذا كان بت C مضبوطًا في حقل Flags. 0x00000024 إذا كان بت C غير مضبوط في حقل Flags. |
| [StartAngle](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawarc/startangle/) { get; set; } | يحصل أو يعيّن زاوية البداية قيمة عائمة 32‑بت غير سالبة تحدد الزاوية بين محور x والنقطة البداية للقوس. أي قيمة مقبولة، ولكن يجب تفسيرها modulo 360، بحيث تكون النتيجة ضمن النطاق من 0.0 شاملًا إلى 360.0 حصريًا. |
| [SweepAngle](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawarc/sweepangle/) { get; set; } | يحصل أو يعيّن زاوية المسح قيمة عائمة 32‑بت تحدد مدى القوس المراد رسمه، كزاوية بالدرجات تُقاس من النقطة البداية المحددة بقيمة StartAngle. أي قيمة مقبولة، ولكن يجب حصرها بين -360.0 و 360.0 شاملًا. القيمة الموجبة تشير إلى أن المسح يُعرف باتجاه عقارب الساعة، والقيمة السالبة تشير إلى أن المسح يُعرف باتجاه عكس عقارب الساعة. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | يحصل على عدد صحيح غير موقع 16‑بت يحدد نوع السجل. |

### انظر أيضًا

* class [EmfPlusDrawingRecordType](../emfplusdrawingrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)


