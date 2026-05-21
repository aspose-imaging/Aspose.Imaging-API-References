---
title: "الفئة EmfPlusPenOptionalData"
second_title: "Aspose.Imaging for .NET API Reference"
description: "Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects.EmfPlusPenOptionalData class. كائن EmfPlusPenOptionalData يحدد بيانات اختيارية لقلم رسومي."
type: docs
weight: 5800
url: /ar/net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/
---
## EmfPlusPenOptionalData class

كائن EmfPlusPenOptionalData يحدد البيانات الاختيارية لقلم رسومي

```csharp
public sealed class EmfPlusPenOptionalData : EmfPlusStructureObjectType
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfPlusPenOptionalData](emfpluspenoptionaldata/)() | المنشئ الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [CompoundLineData](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/compoundlinedata/) { get; set; } | يحصل أو يعيّن كائن EmfPlusCompoundLineData اختياري (القسم 2.2.2.9) الذي يحدد مصفوفة من القيم العشرية التي تعرف الخط المركب للقلم، والذي يتكون من خطوط متوازية ومسافات. يجب أن يكون هذا الحقل موجودًا إذا تم تعيين علامة PenDataCompoundLine في حقل PenDataFlags لكائن EmfPlusPenData. |
| [CustomEndCapData](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/customendcapdata/) { get; set; } | يحصل أو يعيّن كائن EmfPlusCustomEndCapData اختياري (القسم 2.2.2.11) الذي يحدد شكل النهاية المخصصة، وهو الشكل المستخدم في نهاية الخط المرسوم بهذا القلم. يمكن أن يكون أيًا من الأشكال المختلفة، مثل مربع أو دائرة أو ماسة. يجب أن يكون هذا الحقل موجودًا إذا تم تعيين علامة PenDataCustomEndCap في حقل PenDataFlags لكائن EmfPlusPenData. |
| [CustomStartCapData](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/customstartcapdata/) { get; set; } | يحصل أو يعيّن كائن EmfPlusCustomStartCapData اختياري (القسم 2.2.15) الذي يحدد شكل البداية المخصصة، وهو الشكل المستخدم في بداية الخط المرسوم بهذا القلم. يمكن أن يكون أيًا من الأشكال المختلفة، مثل مربع أو دائرة أو ماسة. يجب أن يكون هذا الحقل موجودًا إذا تم تعيين علامة PenDataCustomStartCap في حقل PenDataFlags لكائن EmfPlusPenData. |
| [DashedLineCapType](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/dashedlinecaptype/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا موقّعًا 32-بت اختياري يحدد الشكل لكلا طرفي كل شَرطَة في خط متقطّع. يجب أن يكون هذا الحقل موجودًا إذا تم تعيين علامة PenDataDashedLineCap في حقل PenDataFlags لكائن EmfPlusPenData، ويجب أن تكون القيمة معرفة في تعداد DashedLineCapType (القسم 2.1.1.10). |
| [DashedLineData](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/dashedlinedata/) { get; set; } | يحصل أو يعيّن كائن EmfPlusDashedLineData اختياري (القسم 2.2.2.16) الذي يحدد أطوال الشرط والفراغات في خط متقطّع مخصص. يجب أن يكون هذا الحقل موجودًا إذا تم تعيين علامة PenDataDashedLine في حقل PenDataFlags لكائن EmfPlusPenData. |
| [DashOffset](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/dashoffset/) { get; set; } | يحصل أو يعيّن قيمة عائمة اختيارية 32‑بت تحدد المسافة من بداية الخط إلى بداية الفراغ الأول في نمط الخط المتقطع. يجب أن يكون هذا الحقل موجودًا إذا تم تعيين علم PenDataDashedLineOffset في حقل PenDataFlags لكائن EmfPlusPenData. |
| [EndCap](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/endcap/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا موقعًا اختياريًا 32‑بت يحدد الشكل لنهاية الخط في حقل CustomEndCapData. يجب أن يكون هذا الحقل موجودًا إذا تم تعيين علم PenDataEndCap في حقل PenDataFlags لكائن EmfPlusPenData، ويجب أن تكون القيمة معرفة في تعداد LineCapType. |
| [Join](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/join/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا موقعًا اختياريًا 32‑بت يحدد طريقة ربط خطين يرسمهما القلم نفسه وتلتقي نهايتهما. يجب أن يكون هذا الحقل موجودًا إذا تم تعيين علم PenDataJoin في حقل PenDataFlags لكائن EmfPlusPenData، ويجب أن تكون القيمة معرفة في تعداد LineJoinType (القسم 2.1.1.19). |
| [LineStyle](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/linestyle/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا موقعًا اختياريًا 32‑بت يحدد النمط المستخدم للخطوط المرسومة بهذا القلم. يجب أن يكون هذا الحقل موجودًا إذا تم تعيين علم PenDataLineStyle في حقل PenDataFlags لكائن EmfPlusPenData، ويجب أن تكون القيمة معرفة في تعداد LineStyle (القسم 2.1.1.20). |
| [MiterLimit](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/miterlimit/) { get; set; } | يحصل أو يعيّن قيمة عائمة اختيارية 32‑بت تحدد حد القطع المائل (miter limit)، وهو النسبة القصوى المسموح بها بين طول القطع المائل وعرض الخط. طول القطع المائل هو المسافة من تقاطع جدران الخط من داخل الوصلة إلى تقاطع جدران الخط من خارج الوصلة. يمكن أن يكون طول القطع المائل كبيرًا عندما تكون الزاوية بين خطين صغيرة. يجب أن يكون هذا الحقل موجودًا إذا تم تعيين علم PenDataMiterLimit في حقل PenDataFlags لكائن EmfPlusPenData. |
| [PenAlignment](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/penalignment/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا موقعًا اختياريًا 32‑بت يحدد توزيع عرض القلم بالنسبة لإحداثيات الخط المرسوم. يجب أن يكون هذا الحقل موجودًا إذا تم تعيين علم PenDataNonCenter في حقل PenDataFlags لكائن EmfPlusPenData، ويجب أن تكون القيمة معرفة في تعداد PenAlignment (القسم 2.1.1.24). |
| [StartCap](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/startcap/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا موقعًا اختياريًا 32‑بت يحدد الشكل لبداية الخط في حقل CustomStartCapData. يجب أن يكون هذا الحقل موجودًا إذا تم تعيين علم PenDataStartCap في حقل PenDataFlags لكائن EmfPlusPenData، ويجب أن تكون القيمة معرفة في تعداد LineCapType (القسم 2.1.1.18). |
| [TransformMatrix](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/transformmatrix/) { get; set; } | يحصل أو يعيّن كائن EmfPlusTransformMatrix اختياري (القسم 2.2.2.47) يحدد تحويل الفضاء العالمي إلى فضاء الجهاز للقلم. يجب أن يكون هذا الحقل موجودًا إذا تم تعيين علم PenDataTransform في حقل PenDataFlags لكائن EmfPlusPenData. |

### انظر أيضًا

* class [EmfPlusStructureObjectType](../emfplusstructureobjecttype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../aspose.imaging.fileformats.emf.emfplus.objects/)
* assembly [Aspose.Imaging](../../)


