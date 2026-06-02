---
title: "الفئة StreamContainer"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.StreamContainer. تمثل حاوية التدفق التي تحتوي على التدفق وتوفر روتينات معالجة التدفق"
type: docs
weight: 11720
url: /ar/net/aspose.imaging/streamcontainer/
---
## StreamContainer class

يمثل حاوية تدفق تحتوي على التدفق وتوفر روتينات معالجة التدفق.

```csharp
public class StreamContainer : DisposableObject
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [StreamContainer](streamcontainer/#constructor)(Stream) | يُنشئ مثيلًا جديدًا للفئة `StreamContainer`. |
| [StreamContainer](streamcontainer/#constructor_1)(Stream, bool) | يُنشئ مثيلًا جديدًا للفئة `StreamContainer`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| virtual [CanRead](../../aspose.imaging/streamcontainer/canread/) { get; } | يحصل على قيمة تشير إلى ما إذا كان التدفق يدعم القراءة. |
| virtual [CanSeek](../../aspose.imaging/streamcontainer/canseek/) { get; } | يحصل على قيمة تشير إلى ما إذا كان التدفق يدعم السعي. |
| virtual [CanWrite](../../aspose.imaging/streamcontainer/canwrite/) { get; } | يحصل على قيمة تشير إلى ما إذا كان التدفق يدعم الكتابة. |
| [Disposed](../../aspose.imaging/disposableobject/disposed/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا المثال تم التخلص منه. |
| virtual [IsStreamDisposedOnClose](../../aspose.imaging/streamcontainer/isstreamdisposedonclose/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا التدفق يتم التخلص منه عند الإغلاق. |
| virtual [Length](../../aspose.imaging/streamcontainer/length/) { get; set; } | يحصل أو يعيّن طول التدفق بالبايت. هذه القيمة أقل من الطول بمقدار موضع بدء التدفق الممرّر في مُنشئ StreamContainer. |
| virtual [Position](../../aspose.imaging/streamcontainer/position/) { get; set; } | يحصل أو يعيّن الموضع الحالي داخل الدفق. تمثل هذه القيمة الإزاحة من موضع بدء الدفق الذي تم تمريره في مُنشئ StreamContainer. |
| virtual [Stream](../../aspose.imaging/streamcontainer/stream/) { get; } | يحصل على دفق البيانات. |
| [SyncRoot](../../aspose.imaging/streamcontainer/syncroot/) { get; } | يحصل على كائن يمكن استخدامه لمزامنة الوصول إلى المورد المتزامن. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Dispose](../../aspose.imaging/disposableobject/dispose/)() | يتخلص من المثيل الحالي. |
| virtual [Flush](../../aspose.imaging/streamcontainer/flush/)() | يمسح جميع المخازن المؤقتة لهذا الدفق ويتسبب في كتابة أي بيانات مخزنة مؤقتًا إلى الجهاز الأساسي. |
| virtual [Read](../../aspose.imaging/streamcontainer/read/#read)(byte[]) | يقرأ بايتات لملء المخزن المؤقت للبايتات المحدد. |
| virtual [Read](../../aspose.imaging/streamcontainer/read/#read_1)(byte[], int, int) | يقرأ تسلسلًا من البايتات من الدفق الحالي ويقّدم الموضع داخل الدفق بعدد البايتات المقروءة. |
| virtual [ReadByte](../../aspose.imaging/streamcontainer/readbyte/)() | يقرأ بايتًا من الدفق ويقّدم الموضع داخل الدفق بايتًا واحدًا، أو يُعيد -1 إذا كان عند نهاية الدفق. |
| virtual [Save](../../aspose.imaging/streamcontainer/save/#save)(Stream) | يحفظ (ينسخ) بيانات التدفق إلى التدفق المحدد. يستخدم حجم المخزن المؤقت الافتراضي [`ReadWriteBytesCount`](./readwritebytescount/) وقيمة تدفق [`Length`](./length/). |
| virtual [Save](../../aspose.imaging/streamcontainer/save/#save_3)(string) | يحفظ (ينسخ) بيانات التدفق إلى التدفق المحدد. يستخدم حجم المخزن المؤقت الافتراضي [`ReadWriteBytesCount`](./readwritebytescount/) وقيمة تدفق [`Length`](./length/). |
| virtual [Save](../../aspose.imaging/streamcontainer/save/#save_1)(Stream, int) | يحفظ (ينسخ) جميع بيانات التدفق إلى التدفق المحدد. يستخدم قيمة تدفق [`Length`](./length/). |
| virtual [Save](../../aspose.imaging/streamcontainer/save/#save_4)(string, int) | يحفظ (ينسخ) بيانات التدفق إلى التدفق المحدد. يستخدم قيمة تدفق [`Length`](./length/). |
| virtual [Save](../../aspose.imaging/streamcontainer/save/#save_2)(Stream, int, long) | يحفظ (ينسخ) بيانات الدفق إلى الدفق المحدد. |
| virtual [Save](../../aspose.imaging/streamcontainer/save/#save_5)(string, int, long) | يحفظ (ينسخ) بيانات الدفق إلى الدفق المحدد. |
| virtual [Seek](../../aspose.imaging/streamcontainer/seek/)(long, SeekOrigin) | يعيّن الموضع داخل الدفق الحالي. |
| virtual [SeekBegin](../../aspose.imaging/streamcontainer/seekbegin/)() | يعيّن موضع الدفق إلى بداية الدفق. تمثل هذه القيمة الإزاحة من موضع بدء الدفق الذي تم تمريره في مُنشئ StreamContainer. |
| virtual [ToBytes](../../aspose.imaging/streamcontainer/tobytes/#tobytes)() | يحوّل بيانات الدفق إلى مصفوفة Byte. |
| virtual [ToBytes](../../aspose.imaging/streamcontainer/tobytes/#tobytes_1)(long, long) | يحوّل بيانات الدفق إلى مصفوفة Byte. |
| virtual [Write](../../aspose.imaging/streamcontainer/write/#write)(byte[]) | يكتب جميع البايتات المحددة إلى الدفق. |
| virtual [Write](../../aspose.imaging/streamcontainer/write/#write_1)(byte[], int, int) | يكتب تسلسلًا من البايتات إلى الدفق الحالي ويقّدم الموضع الحالي داخل هذا الدفق بعدد البايتات المكتوبة. |
| virtual [WriteByte](../../aspose.imaging/streamcontainer/writebyte/)(byte) | يكتب بايتًا إلى الموضع الحالي في الدفق ويقّدم الموضع داخل الدفق بايتًا واحدًا. |
| virtual [WriteTo](../../aspose.imaging/streamcontainer/writeto/#writeto)(StreamContainer) | ينسخ البيانات المحتواة إلى `StreamContainer` آخر. |
| virtual [WriteTo](../../aspose.imaging/streamcontainer/writeto/#writeto_1)(StreamContainer, long) | ينسخ البيانات المحتواة إلى `StreamContainer` آخر. |
| [explicit operator](../../aspose.imaging/streamcontainer/op_explicit/) | ينفذ تحويلًا صريحًا من `StreamContainer` إلى Stream. |

## الحقول

| الاسم | الوصف |
| --- | --- |
| const [ReadWriteBytesCount](../../aspose.imaging/streamcontainer/readwritebytescount/) | يحدد عدد البايتات للقراءة والكتابة عند القراءة المتسلسلة. |

### انظر أيضًا

* class [DisposableObject](../disposableobject/)
* namespace [Aspose.Imaging](../../aspose.imaging/)
* assembly [Aspose.Imaging](../../)


