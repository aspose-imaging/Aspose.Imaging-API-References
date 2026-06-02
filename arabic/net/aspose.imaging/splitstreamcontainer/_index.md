---
title: "الفئة SplitStreamContainer"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.SplitStreamContainer. تمثل حاوية تدفق مقسمة تحتوي على التدفق وتوفر روتينات معالجة التدفق"
type: docs
weight: 11710
url: /ar/net/aspose.imaging/splitstreamcontainer/
---
## SplitStreamContainer class

يمثل حاوية تدفق مقسمة تحتوي على التدفق وتوفر روتينات معالجة التدفق.

```csharp
public class SplitStreamContainer : StreamContainer
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [SplitStreamContainer](splitstreamcontainer/#constructor_1)(Stream) | ينشئ مثيلاً جديداً للفئة `SplitStreamContainer`. |
| [SplitStreamContainer](splitstreamcontainer/#constructor_2)(Stream, bool) | ينشئ مثيلاً جديداً للفئة `SplitStreamContainer`. |
| [SplitStreamContainer](splitstreamcontainer/#constructor)(StreamContainer, bool) | ينشئ مثيلاً جديداً للفئة `SplitStreamContainer`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| override [CanRead](../../aspose.imaging/splitstreamcontainer/canread/) { get; } | يحصل على قيمة تشير إلى ما إذا كان التدفق يدعم القراءة. |
| override [CanSeek](../../aspose.imaging/splitstreamcontainer/canseek/) { get; } | يحصل على قيمة تشير إلى ما إذا كان التدفق يدعم السعي. |
| override [CanWrite](../../aspose.imaging/splitstreamcontainer/canwrite/) { get; } | يحصل على قيمة تشير إلى ما إذا كان التدفق يدعم الكتابة. |
| [Disposed](../../aspose.imaging/disposableobject/disposed/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا المثال تم التخلص منه. |
| virtual [IsStreamDisposedOnClose](../../aspose.imaging/streamcontainer/isstreamdisposedonclose/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا التدفق يتم التخلص منه عند الإغلاق. |
| override [Length](../../aspose.imaging/splitstreamcontainer/length/) { get; set; } | يحصل أو يعيّن طول التدفق بالبايت. هذه القيمة أقل من الطول بمقدار موضع بدء التدفق الممرّر في مُنشئ StreamContainer. |
| override [Position](../../aspose.imaging/splitstreamcontainer/position/) { get; set; } | يحصل أو يعيّن الموضع الحالي داخل الدفق. تمثل هذه القيمة الإزاحة من موضع بدء الدفق الذي تم تمريره في مُنشئ StreamContainer. |
| override [Stream](../../aspose.imaging/splitstreamcontainer/stream/) { get; } | يحصل على دفق البيانات. |
| [SyncRoot](../../aspose.imaging/splitstreamcontainer/syncroot/) { get; } | يحصل على كائن يمكن استخدامه لمزامنة الوصول إلى المورد المتزامن. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Dispose](../../aspose.imaging/disposableobject/dispose/)() | يتخلص من المثيل الحالي. |
| override [Flush](../../aspose.imaging/splitstreamcontainer/flush/)() | يمسح جميع المخازن المؤقتة لهذا الدفق ويتسبب في كتابة أي بيانات مخزنة مؤقتًا إلى الجهاز الأساسي. |
| [Insert](../../aspose.imaging/splitstreamcontainer/insert/)(int, StreamContainer, bool) | يدرج حاوية الدفق في الموضع المحدد. |
| override [Read](../../aspose.imaging/splitstreamcontainer/read/#read)(byte[]) | يقرأ بايتات لملء المخزن المؤقت للبايتات المحدد. |
| override [Read](../../aspose.imaging/splitstreamcontainer/read/#read_1)(byte[], int, int) | يقرأ تسلسلًا من البايتات من الدفق الحالي ويقّدم الموضع داخل الدفق بعدد البايتات المقروءة. |
| override [ReadByte](../../aspose.imaging/splitstreamcontainer/readbyte/)() | يقرأ بايتًا من الدفق ويقّدم الموضع داخل الدفق بايتًا واحدًا، أو يُعيد -1 إذا كان عند نهاية الدفق. |
| virtual [Save](../../aspose.imaging/streamcontainer/save/)(Stream) | يحفظ (ينسخ) بيانات الدفق إلى الدفق المحدد. يستخدم حجم المخزن المؤقت الافتراضي [`ReadWriteBytesCount`](../streamcontainer/readwritebytescount/) وقيمة الدفق [`Length`](../streamcontainer/length/). |
| virtual [Save](../../aspose.imaging/streamcontainer/save/)(string) | يحفظ (ينسخ) بيانات الدفق إلى الدفق المحدد. يستخدم حجم المخزن المؤقت الافتراضي [`ReadWriteBytesCount`](../streamcontainer/readwritebytescount/) وقيمة الدفق [`Length`](../streamcontainer/length/). |
| virtual [Save](../../aspose.imaging/streamcontainer/save/)(Stream, int) | يحفظ (ينسخ) جميع بيانات الدفق إلى الدفق المحدد. يستخدم قيمة الدفق [`Length`](../streamcontainer/length/). |
| virtual [Save](../../aspose.imaging/streamcontainer/save/)(string, int) | يحفظ (ينسخ) بيانات الدفق إلى الدفق المحدد. يستخدم قيمة الدفق [`Length`](../streamcontainer/length/). |
| override [Save](../../aspose.imaging/splitstreamcontainer/save/#save_2)(Stream, int, long) | يحفظ (ينسخ) بيانات الدفق إلى الدفق المحدد. |
| virtual [Save](../../aspose.imaging/streamcontainer/save/)(string, int, long) | يحفظ (ينسخ) بيانات الدفق إلى الدفق المحدد. |
| override [Seek](../../aspose.imaging/splitstreamcontainer/seek/)(long, SeekOrigin) | يعيّن الموضع داخل الدفق الحالي. |
| override [SeekBegin](../../aspose.imaging/splitstreamcontainer/seekbegin/)() | يعيّن موضع الدفق إلى بداية الدفق. تمثل هذه القيمة الإزاحة من موضع بدء الدفق الذي تم تمريره في مُنشئ StreamContainer. |
| override [ToBytes](../../aspose.imaging/splitstreamcontainer/tobytes/#tobytes)() | يحوّل بيانات الدفق إلى مصفوفة Byte. |
| override [ToBytes](../../aspose.imaging/splitstreamcontainer/tobytes/#tobytes_1)(long, long) | يحوّل بيانات الدفق إلى مصفوفة Byte. |
| override [Write](../../aspose.imaging/splitstreamcontainer/write/#write)(byte[]) | يكتب جميع البايتات المحددة إلى الدفق. |
| override [Write](../../aspose.imaging/splitstreamcontainer/write/#write_1)(byte[], int, int) | يكتب تسلسلًا من البايتات إلى الدفق الحالي ويقّدم الموضع الحالي داخل هذا الدفق بعدد البايتات المكتوبة. |
| override [WriteByte](../../aspose.imaging/splitstreamcontainer/writebyte/)(byte) | يكتب بايتًا إلى الموضع الحالي في الدفق ويقّدم الموضع داخل الدفق بايتًا واحدًا. |
| virtual [WriteTo](../../aspose.imaging/streamcontainer/writeto/)(StreamContainer) | ينسخ البيانات المحتواة إلى [`StreamContainer`](../streamcontainer/). |
| virtual [WriteTo](../../aspose.imaging/streamcontainer/writeto/)(StreamContainer, long) | ينسخ البيانات المحتواة إلى [`StreamContainer`](../streamcontainer/). |

### انظر أيضًا

* class [StreamContainer](../streamcontainer/)
* namespace [Aspose.Imaging](../../aspose.imaging/)
* assembly [Aspose.Imaging](../../)


