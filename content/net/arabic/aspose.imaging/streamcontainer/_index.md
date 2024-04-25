---
title: StreamContainer
second_title: Aspose.Imaging لمرجع NET API
description: يمثل حاوية الدفق التي تحتوي على الدفق وتوفر إجراءات معالجة الدفق.
type: docs
weight: 11130
url: /ar/aspose.imaging/streamcontainer/
---
## StreamContainer class

يمثل حاوية الدفق التي تحتوي على الدفق وتوفر إجراءات معالجة الدفق.

```csharp
public class StreamContainer : DisposableObject
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [StreamContainer](streamcontainer#constructor)(Stream) | يقوم بتهيئة مثيل جديد لملف[`StreamContainer`](../streamcontainer) فئة . |
| [StreamContainer](streamcontainer#constructor_1)(Stream, bool) | يقوم بتهيئة مثيل جديد لملف[`StreamContainer`](../streamcontainer) فئة . |

## الخصائص

| اسم | وصف |
| --- | --- |
| virtual [CanRead](../../aspose.imaging/streamcontainer/canread) { get; } | يحصل على قيمة تشير إلى ما إذا كان التدفق يدعم القراءة. |
| virtual [CanSeek](../../aspose.imaging/streamcontainer/canseek) { get; } | يحصل على قيمة تشير إلى ما إذا كان الدفق يدعم البحث. |
| virtual [CanWrite](../../aspose.imaging/streamcontainer/canwrite) { get; } | يحصل على قيمة تشير إلى ما إذا كان الدفق يدعم الكتابة. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا المثيل قد تم التخلص منه. |
| virtual [IsStreamDisposedOnClose](../../aspose.imaging/streamcontainer/isstreamdisposedonclose) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا الدفق سيتم التخلص منه عند الإغلاق. |
| virtual [Length](../../aspose.imaging/streamcontainer/length) { get; set; } | الحصول على طول الدفق بالبايت أو تحديده. هذه القيمة أقل منLength من خلال موضع دفق البداية الذي تم تمريره في مُنشئ StreamContainer. |
| virtual [Position](../../aspose.imaging/streamcontainer/position) { get; set; } | الحصول على أو تحديد الموضع الحالي ضمن الدفق. تمثل هذه القيمة الإزاحة من موضع دفق البداية الذي تم تمريره في مُنشئ StreamContainer. |
| virtual [Stream](../../aspose.imaging/streamcontainer/stream) { get; } | يحصل على دفق البيانات. |
| [SyncRoot](../../aspose.imaging/streamcontainer/syncroot) { get; } | الحصول على كائن يمكن استخدامه لمزامنة الوصول إلى المورد المتزامن. |

## طُرق

| اسم | وصف |
| --- | --- |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | التخلص من المثيل الحالي . |
| virtual [Flush](../../aspose.imaging/streamcontainer/flush)() | يمسح كافة المخازن المؤقتة لهذا الدفق ويسبب كتابة أي بيانات مخزنة إلى الجهاز الأساسي. |
| virtual [Read](../../aspose.imaging/streamcontainer/read#read)(byte[]) | يقرأ البايت لملء المخزن المؤقت للبايتات المحدد. |
| virtual [Read](../../aspose.imaging/streamcontainer/read#read_1)(byte[], int, int) | يقرأ تسلسل البايت من الدفق الحالي ويقدم الموضع داخل الدفق بعدد البايت المقروء. |
| virtual [ReadByte](../../aspose.imaging/streamcontainer/readbyte)() | يقرأ بايت من الدفق ويقدم الموضع داخل الدفق بمقدار بايت واحد ، أو يُرجع -1 إذا كان في نهاية الدفق . |
| virtual [Save](../../aspose.imaging/streamcontainer/save#save)(Stream) | يحفظ (ينسخ) بيانات الدفق إلى الدفق المحدد. يستخدم حجم المخزن المؤقت الافتراضي[`ReadWriteBytesCount`](./readwritebytescount) والدفق[`Length`](./length) القيمة . |
| virtual [Save](../../aspose.imaging/streamcontainer/save#save_3)(string) | يحفظ (ينسخ) بيانات الدفق إلى الدفق المحدد. يستخدم حجم المخزن المؤقت الافتراضي[`ReadWriteBytesCount`](./readwritebytescount) والدفق[`Length`](./length) القيمة . |
| virtual [Save](../../aspose.imaging/streamcontainer/save#save_1)(Stream, int) | يحفظ (ينسخ) جميع بيانات الدفق إلى الدفق المحدد. يستخدم تيار[`Length`](./length) القيمة . |
| virtual [Save](../../aspose.imaging/streamcontainer/save#save_4)(string, int) | يحفظ (ينسخ) بيانات الدفق إلى الدفق المحدد. يستخدم تيار[`Length`](./length) القيمة . |
| virtual [Save](../../aspose.imaging/streamcontainer/save#save_2)(Stream, int, long) | يحفظ (ينسخ) بيانات الدفق إلى الدفق المحدد. |
| virtual [Save](../../aspose.imaging/streamcontainer/save#save_5)(string, int, long) | يحفظ (ينسخ) بيانات الدفق إلى الدفق المحدد. |
| virtual [Seek](../../aspose.imaging/streamcontainer/seek)(long, SeekOrigin) | يضبط الموضع ضمن الدفق الحالي. |
| virtual [SeekBegin](../../aspose.imaging/streamcontainer/seekbegin)() | يضبط موضع الدفق على بداية الدفق. تمثل هذه القيمة الإزاحة من موضع دفق البداية الذي تم تمريره في مُنشئ StreamContainer. |
| virtual [ToBytes](../../aspose.imaging/streamcontainer/tobytes#tobytes)() | يحول بيانات الدفق إلى ملفByte مجموعة . |
| virtual [ToBytes](../../aspose.imaging/streamcontainer/tobytes#tobytes_1)(long, long) | يحول بيانات الدفق إلى ملفByte مجموعة . |
| virtual [Write](../../aspose.imaging/streamcontainer/write#write)(byte[]) | يكتب كل وحدات البايت المحددة في الدفق. |
| virtual [Write](../../aspose.imaging/streamcontainer/write#write_1)(byte[], int, int) | يكتب تسلسلًا من البايتات إلى الدفق الحالي ويقدم الموضع الحالي ضمن هذا الدفق بعدد البايتات المكتوبة. |
| virtual [WriteByte](../../aspose.imaging/streamcontainer/writebyte)(byte) | يكتب بايت إلى الموضع الحالي في الدفق ويقدم الموضع داخل الدفق بمقدار بايت واحد. |
| virtual [WriteTo](../../aspose.imaging/streamcontainer/writeto#writeto)(StreamContainer) | نسخ البيانات المضمنة إلى آخر[`StreamContainer`](../streamcontainer) . |
| virtual [WriteTo](../../aspose.imaging/streamcontainer/writeto#writeto_1)(StreamContainer, long) | نسخ البيانات المضمنة إلى آخر[`StreamContainer`](../streamcontainer) . |
| [explicit operator](../../aspose.imaging/streamcontainer/op_explicit) | يقوم بإجراء تحويل صريح من[`StreamContainer`](../streamcontainer) إلىStream . |

## مجالات

| اسم | وصف |
| --- | --- |
| const [ReadWriteBytesCount](../../aspose.imaging/streamcontainer/readwritebytescount) | تحديد عدد وحدات البايت للقراءة والكتابة عند القراءة بالتسلسل. |

### أنظر أيضا

* class [DisposableObject](../disposableobject)
* مساحة الاسم [Aspose.Imaging](../../aspose.imaging)
* المجسم [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
