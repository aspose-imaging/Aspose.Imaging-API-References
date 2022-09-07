---
title: EmfPlusPenOptionalData
second_title: Aspose.Imaging لمرجع NET API
description: يحدد كائن EmfPlusPenOptionalData البيانات الاختيارية لقلم رسومات
type: docs
weight: 5680
url: /ar/net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/
---
## EmfPlusPenOptionalData class

يحدد كائن EmfPlusPenOptionalData البيانات الاختيارية لقلم رسومات

```csharp
public sealed class EmfPlusPenOptionalData : EmfPlusStructureObjectType
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [EmfPlusPenOptionalData](emfpluspenoptionaldata)() | Default_Constructor |

## الخصائص

| اسم | وصف |
| --- | --- |
| [CompoundLineData](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/compoundlinedata) { get; set; } | الحصول على كائن EmfPlusCompoundLineData الاختياري أو تعيينه (القسم 2.2.2.9) الذي يحدد مصفوفة من قيم الفاصلة العائمة التي تحدد الخط المركب للقلم ، والذي يتكون من خطوط متوازية ومسافات. يجب أن يكون هذا الحقل موجودًا إذا تم تعيين علامة PenDataCompoundLine في الحقل PenDataFlags لكائن EmfPlusPenData |
| [CustomEndCapData](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/customendcapdata) { get; set; } | الحصول على كائن EmfPlusCustomEndCapData الاختياري أو تعيينه (القسم 2.2.2.11) الذي يحدد شكل الحرف النهائي المخصص ، وهو الشكل الذي يجب استخدامه في نهاية الخط المرسوم باستخدام هذا القلم. يمكن أن يكون أيًا من الأشكال المختلفة ، مثل المربع أو الدائرة أو الماس. يجب أن يكون هذا الحقل موجودًا في حالة تعيين علامة PenDataCustomEndCap في حقل PenDataFlags الخاص بالكائن EmfPlusPenData |
| [CustomStartCapData](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/customstartcapdata) { get; set; } | الحصول على كائن EmfPlusCustomStartCapData الاختياري أو تعيينه (القسم 2.2.2.15) الذي يحدد الشكل المخصص لبدء الأحرف الاستهلالية ، وهو الشكل الذي يجب استخدامه في بداية الخط المرسوم باستخدام هذا القلم. يمكن أن يكون أي من أشكال مختلفة ، مثل المربع أو الدائرة أو المعين. يجب أن يكون هذا الحقل موجودًا إذا تم تعيين علامة PenDataCustomStartCap في حقل PenDataFlags الخاص بالكائن EmfPlusPenData |
| [DashedLineCapType](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/dashedlinecaptype) { get; set; } | الحصول على أو تعيين عدد صحيح اختياري ذو إشارة 32 بت يحدد شكل طرفي كل شرطة في سطر متقطع. يجب أن يكون هذا الحقل موجودًا إذا تم تعيين علامة PenDataDashedLineCap في الحقل PenDataFlags لكائن EmfPlusPenData ، ويجب تحديد قيمة في تعداد DashedLineCapType (القسم 2.1.1.10) . |
| [DashedLineData](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/dashedlinedata) { get; set; } | الحصول على كائن EmfPlusDashedLineData الاختياري أو تعيينه (القسم 2.2.2.16) الذي يحدد أطوال الشرطات والمسافات في خط متقطع مخصص. يجب أن يكون هذا الحقل موجودًا إذا تم تعيين علامة PenDataDashedLine في حقل PenDataFlags للكائن EmfPlusPenData . |
| [DashOffset](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/dashoffset) { get; set; } | الحصول على أو تعيين قيمة اختيارية للفاصلة العائمة 32 بت تحدد مسافة من بداية السطر إلى بداية المساحة الأولى في نمط خط متقطع. يجب أن يكون هذا الحقل موجودًا إذا تم تعيين علامة PenDataDashedLineOffset في الحقل PenDataFlags لكائن EmfPlusPenData. |
| [EndCap](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/endcap) { get; set; } | الحصول على أو تعيين عدد صحيح اختياري ذو إشارة 32 بت يحدد الشكل لنهاية السطر في الحقل CustomEndCapData. يجب أن يكون هذا الحقل موجودًا إذا تم تعيين علامة PenDataEndCap في الحقل PenDataFlags لكائن EmfPlusPenData ، ويجب تحديد القيمة في LineCapType enumeration |
| [Join](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/join) { get; set; } | الحصول على أو تعيين عدد صحيح اختياري ذو إشارة 32 بت يحدد كيفية ربط سطرين يتم رسمهما بواسطة القلم نفسه وتلتقي نهاياتهما. يجب أن يكون هذا الحقل موجودًا إذا تم تعيين علامة PenDataJoin في حقل PenDataFlags الخاص بكائن EmfPlusPenData ، ويجب تحديد قيمة في تعداد LineJoinType (القسم 2.1.1.19) . |
| [LineStyle](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/linestyle) { get; set; } | الحصول على أو تعيين عدد صحيح اختياري ذو إشارة 32 بت يحدد النمط المستخدم للخطوط المرسومة باستخدام كائن القلم هذا. يجب أن يكون هذا الحقل موجودًا إذا تم تعيين علامة PenDataLineStyle في الحقل PenDataFlags لكائن EmfPlusPenData ، ويجب تحديد قيمة في تعداد LineStyle (القسم 2.1.1.20) . |
| [MiterLimit](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/miterlimit) { get; set; } | الحصول على أو تعيين قيمة اختيارية للفاصلة العائمة ذات 32 بت تحدد حد ميتري ، وهو الحد الأقصى المسموح به لطول ميتري إلى عرض الخط. طول ميتري هو المسافة من تقاطع لجدران الخط على الوصلة الداخلية إلى تقاطع جدران الخط خارج الوصلة. يمكن أن يكون طول ميتري كبيرًا عندما تكون الزاوية بين خطين صغيرة. يجب أن يكون هذا الحقل موجودًا إذا تم تعيين علامة PenDataMiterLimit في الحقل PenDataFlags لكائن EmfPlusPenData. |
| [PenAlignment](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/penalignment) { get; set; } | الحصول على أو تعيين عدد صحيح اختياري ذو إشارة 32 بت يحدد توزيع لعرض القلم فيما يتعلق بالإحداثيات للخط المرسوم. يجب أن يكون هذا الحقل موجودًا إذا تم تعيين علامة PenDataNonCenter في الحقل PenDataFlags لكائن EmfPlusPenData ، ويجب تحديد القيمة في تعداد PenAlignment (القسم 2.1.1.24) . |
| [StartCap](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/startcap) { get; set; } | الحصول على أو تعيين عدد صحيح اختياري ذو إشارة 32 بت يحدد الشكل لـ بداية سطر في الحقل CustomStartCapData. يجب أن يكون هذا الحقل موجودًا إذا تم تعيين علامة PenDataStartCap في حقل PenDataFlags لكائن EmfPlusPenData ، ويجب تحديد قيمة في تعداد LineCapType (القسم 2.1.1.18) . |
| [TransformMatrix](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/transformmatrix) { get; set; } | الحصول على أو تعيين كائن EmfPlusTransformMatrix اختياري (القسم 2.2.2.47) الذي يحدد مساحة عالمية لتحويل مساحة الجهاز لـ القلم. يجب أن يكون هذا الحقل موجودًا إذا تم تعيين علامة PenDataTransform في حقل PenDataFlags للكائن EmfPlusPenData. |

### أنظر أيضا

* class [EmfPlusStructureObjectType](../emfplusstructureobjecttype)
* مساحة الاسم [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../aspose.imaging.fileformats.emf.emfplus.objects)
* المجسم [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
