---
title: SplitStreamContainer
second_title: Aspose.Imaging لمرجع NET API
description: يمثل حاوية الدفق المنقسمة التي تحتوي على الدفق وتوفر إجراءات معالجة الدفق.
type: docs
weight: 11120
url: /ar/net/aspose.imaging/splitstreamcontainer/
---
## SplitStreamContainer class

يمثل حاوية الدفق المنقسمة التي تحتوي على الدفق وتوفر إجراءات معالجة الدفق.

```csharp
public class SplitStreamContainer : StreamContainer
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [SplitStreamContainer](splitstreamcontainer#constructor_1)(Stream) | يقوم بتهيئة مثيل جديد لملف[`SplitStreamContainer`](../splitstreamcontainer) فئة . |
| [SplitStreamContainer](splitstreamcontainer#constructor_2)(Stream, bool) | يقوم بتهيئة مثيل جديد لملف[`SplitStreamContainer`](../splitstreamcontainer) فئة . |
| [SplitStreamContainer](splitstreamcontainer#constructor)(StreamContainer, bool) | يقوم بتهيئة مثيل جديد لملف[`SplitStreamContainer`](../splitstreamcontainer) فئة . |

## الخصائص

| اسم | وصف |
| --- | --- |
| override [CanRead](../../aspose.imaging/splitstreamcontainer/canread) { get; } | يحصل على قيمة تشير إلى ما إذا كان التدفق يدعم القراءة. |
| override [CanSeek](../../aspose.imaging/splitstreamcontainer/canseek) { get; } | يحصل على قيمة تشير إلى ما إذا كان الدفق يدعم البحث. |
| override [CanWrite](../../aspose.imaging/splitstreamcontainer/canwrite) { get; } | يحصل على قيمة تشير إلى ما إذا كان الدفق يدعم الكتابة. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا المثيل قد تم التخلص منه. |
| virtual [IsStreamDisposedOnClose](../../aspose.imaging/streamcontainer/isstreamdisposedonclose) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا الدفق سيتم التخلص منه عند الإغلاق. |
| override [Length](../../aspose.imaging/splitstreamcontainer/length) { get; set; } | الحصول على طول الدفق بالبايت أو تحديده. هذه القيمة أقل منLength من خلال موضع دفق البداية الذي تم تمريره في مُنشئ StreamContainer. |
| override [Position](../../aspose.imaging/splitstreamcontainer/position) { get; set; } | الحصول على أو تحديد الموضع الحالي ضمن الدفق. تمثل هذه القيمة الإزاحة من موضع دفق البداية الذي تم تمريره في مُنشئ StreamContainer. |
| override [Stream](../../aspose.imaging/splitstreamcontainer/stream) { get; } | يحصل على دفق البيانات. |
| [SyncRoot](../../aspose.imaging/splitstreamcontainer/syncroot) { get; } | الحصول على كائن يمكن استخدامه لمزامنة الوصول إلى المورد المتزامن. |

## طُرق

| اسم | وصف |
| --- | --- |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | التخلص من المثيل الحالي . |
| override [Flush](../../aspose.imaging/splitstreamcontainer/flush)() | يمسح كافة المخازن المؤقتة لهذا الدفق ويسبب كتابة أي بيانات مخزنة إلى الجهاز الأساسي. |
| [Insert](../../aspose.imaging/splitstreamcontainer/insert)(int, StreamContainer, bool) | إدراج حاوية التدفق في الموضع المحدد. |
| override [Read](../../aspose.imaging/splitstreamcontainer/read#read)(byte[]) | يقرأ البايت لملء المخزن المؤقت للبايتات المحدد. |
| override [Read](../../aspose.imaging/splitstreamcontainer/read#read_1)(byte[], int, int) | يقرأ تسلسل البايت من الدفق الحالي ويقدم الموضع داخل الدفق بعدد البايت المقروء. |
| override [ReadByte](../../aspose.imaging/splitstreamcontainer/readbyte)() | يقرأ بايت من الدفق ويقدم الموضع داخل الدفق بمقدار بايت واحد ، أو يُرجع -1 إذا كان في نهاية الدفق . |
| virtual [Save](../../aspose.imaging/streamcontainer/save)(Stream) | يحفظ (ينسخ) بيانات الدفق إلى الدفق المحدد. يستخدم حجم المخزن المؤقت الافتراضي[`ReadWriteBytesCount`](../streamcontainer/readwritebytescount) والدفق[`Length`](../streamcontainer/length) القيمة . |
| virtual [Save](../../aspose.imaging/streamcontainer/save)(string) | يحفظ (ينسخ) بيانات الدفق إلى الدفق المحدد. يستخدم حجم المخزن المؤقت الافتراضي[`ReadWriteBytesCount`](../streamcontainer/readwritebytescount) والدفق[`Length`](../streamcontainer/length) القيمة . |
| virtual [Save](../../aspose.imaging/streamcontainer/save)(Stream, int) | يحفظ (ينسخ) جميع بيانات الدفق إلى الدفق المحدد. يستخدم تيار[`Length`](../streamcontainer/length) القيمة . |
| virtual [Save](../../aspose.imaging/streamcontainer/save)(string, int) | يحفظ (ينسخ) بيانات الدفق إلى الدفق المحدد. يستخدم تيار[`Length`](../streamcontainer/length) القيمة . |
| override [Save](../../aspose.imaging/splitstreamcontainer/save#save_2)(Stream, int, long) | يحفظ (ينسخ) بيانات الدفق إلى الدفق المحدد. |
| virtual [Save](../../aspose.imaging/streamcontainer/save)(string, int, long) | يحفظ (ينسخ) بيانات الدفق إلى الدفق المحدد. |
| override [Seek](../../aspose.imaging/splitstreamcontainer/seek)(long, SeekOrigin) | يضبط الموضع ضمن الدفق الحالي. |
| override [SeekBegin](../../aspose.imaging/splitstreamcontainer/seekbegin)() | يضبط موضع الدفق على بداية الدفق. تمثل هذه القيمة الإزاحة من موضع دفق البداية الذي تم تمريره في مُنشئ StreamContainer. |
| override [ToBytes](../../aspose.imaging/splitstreamcontainer/tobytes#tobytes)() | يحول بيانات الدفق إلى ملفByte مجموعة . |
| override [ToBytes](../../aspose.imaging/splitstreamcontainer/tobytes#tobytes_1)(long, long) | يحول بيانات الدفق إلى ملفByte مجموعة . |
| override [Write](../../aspose.imaging/splitstreamcontainer/write#write)(byte[]) | يكتب كل وحدات البايت المحددة في الدفق. |
| override [Write](../../aspose.imaging/splitstreamcontainer/write#write_1)(byte[], int, int) | يكتب تسلسلًا من البايتات إلى الدفق الحالي ويقدم الموضع الحالي ضمن هذا الدفق بعدد البايتات المكتوبة. |
| override [WriteByte](../../aspose.imaging/splitstreamcontainer/writebyte)(byte) | يكتب بايت إلى الموضع الحالي في الدفق ويقدم الموضع داخل الدفق بمقدار بايت واحد. |
| virtual [WriteTo](../../aspose.imaging/streamcontainer/writeto)(StreamContainer) | نسخ البيانات المضمنة إلى آخر[`StreamContainer`](../streamcontainer) . |
| virtual [WriteTo](../../aspose.imaging/streamcontainer/writeto)(StreamContainer, long) | نسخ البيانات المضمنة إلى آخر[`StreamContainer`](../streamcontainer) . |

### أنظر أيضا

* class [StreamContainer](../streamcontainer)
* مساحة الاسم [Aspose.Imaging](../../aspose.imaging)
* المجسم [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
