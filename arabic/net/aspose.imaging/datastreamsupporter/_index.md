---
title: "الفئة DataStreamSupporter"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.DataStreamSupporter. حاوية تدفق البيانات"
type: docs
weight: 820
url: /ar/net/aspose.imaging/datastreamsupporter/
---
## DataStreamSupporter class

حاوية تدفق البيانات.

```csharp
public abstract class DataStreamSupporter : DisposableObject
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer/) { get; } | الحصول على تدفق بيانات الكائن. |
| [Disposed](../../aspose.imaging/disposableobject/disposed/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا المثال تم التخلص منه. |
| abstract [IsCached](../../aspose.imaging/datastreamsupporter/iscached/) { get; } | يحصل على قيمة تشير إلى ما إذا كانت بيانات الكائن مخزنة مؤقتًا حاليًا ولا يلزم قراءة البيانات. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| abstract [CacheData](../../aspose.imaging/datastreamsupporter/cachedata/)() | يقوم بتخزين البيانات مؤقتًا ويضمن عدم تحميل بيانات إضافية من الـ [`DataStreamContainer`](./datastreamcontainer/). |
| [Dispose](../../aspose.imaging/disposableobject/dispose/)() | يتخلص من المثيل الحالي. |
| virtual [Save](../../aspose.imaging/datastreamsupporter/save/#save)() | يحفظ بيانات الكائن إلى الـ `DataStreamSupporter` الحالي. |
| [Save](../../aspose.imaging/datastreamsupporter/save/#save_1)(Stream) | يحفظ بيانات الكائن إلى الدفق المحدد. |
| virtual [Save](../../aspose.imaging/datastreamsupporter/save/#save_2)(string) | يحفظ بيانات الكائن إلى موقع الملف المحدد. |
| virtual [Save](../../aspose.imaging/datastreamsupporter/save/#save_3)(string, bool) | يحفظ بيانات الكائن إلى موقع الملف المحدد. |

### انظر أيضًا

* class [DisposableObject](../disposableobject/)
* namespace [Aspose.Imaging](../../aspose.imaging/)
* assembly [Aspose.Imaging](../../)


