---
title: FileStreamContainer
second_title: Aspose.Imaging لمرجع NET API
description: مساعد لمعالجة دفق الملفات.
type: docs
weight: 9300
url: /ar/net/aspose.imaging/filestreamcontainer/
---
## FileStreamContainer class

مساعد لمعالجة دفق الملفات.

```csharp
public sealed class FileStreamContainer : StreamContainer
```

## الخصائص

| اسم | وصف |
| --- | --- |
| virtual [CanRead](../../aspose.imaging/streamcontainer/canread) { get; } | يحصل على قيمة تشير إلى ما إذا كان التدفق يدعم القراءة. |
| virtual [CanSeek](../../aspose.imaging/streamcontainer/canseek) { get; } | يحصل على قيمة تشير إلى ما إذا كان الدفق يدعم البحث. |
| virtual [CanWrite](../../aspose.imaging/streamcontainer/canwrite) { get; } | يحصل على قيمة تشير إلى ما إذا كان الدفق يدعم الكتابة. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا المثيل قد تم التخلص منه. |
| [FilePath](../../aspose.imaging/filestreamcontainer/filepath) { get; } | يحصل على مسار الملف. |
| [IsCreated](../../aspose.imaging/filestreamcontainer/iscreated) { get; } | يحصل على قيمة تشير إلى ما إذا كان قد تم إنشاء الدفق بشكل صريح. |
| virtual [IsStreamDisposedOnClose](../../aspose.imaging/streamcontainer/isstreamdisposedonclose) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا الدفق سيتم التخلص منه عند الإغلاق. |
| [IsTemporal](../../aspose.imaging/filestreamcontainer/istemporal) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كان الدفق مؤقتًا. |
| virtual [Length](../../aspose.imaging/streamcontainer/length) { get; set; } | الحصول على طول الدفق بالبايت أو تحديده. هذه القيمة أقل منLength من خلال موضع دفق البداية الذي تم تمريره في مُنشئ StreamContainer. |
| virtual [Position](../../aspose.imaging/streamcontainer/position) { get; set; } | الحصول على أو تحديد الموضع الحالي ضمن الدفق. تمثل هذه القيمة الإزاحة من موضع دفق البداية الذي تم تمريره في مُنشئ StreamContainer. |
| virtual [Stream](../../aspose.imaging/streamcontainer/stream) { get; } | يحصل على دفق البيانات. |
| [SyncRoot](../../aspose.imaging/streamcontainer/syncroot) { get; } | الحصول على كائن يمكن استخدامه لمزامنة الوصول إلى المورد المتزامن. |

## طُرق

| اسم | وصف |
| --- | --- |
| static [CreateFileStream](../../aspose.imaging/filestreamcontainer/createfilestream)(string, bool) | إنشاء دفق ملف جديد. |
| static [OpenFileStream](../../aspose.imaging/filestreamcontainer/openfilestream)(string) | يفتح تدفق ملف موجود. إذا لم يكن دفق الملف موجودًا ، فسيتم طرح الاستثناء المناسب. |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | التخلص من المثيل الحالي . |
| virtual [Flush](../../aspose.imaging/streamcontainer/flush)() | يمسح كافة المخازن المؤقتة لهذا الدفق ويسبب كتابة أي بيانات مخزنة إلى الجهاز الأساسي. |
| virtual [Read](../../aspose.imaging/streamcontainer/read)(byte[]) | يقرأ البايت لملء المخزن المؤقت للبايتات المحدد. |
| virtual [Read](../../aspose.imaging/streamcontainer/read)(byte[], int, int) | يقرأ تسلسل البايت من الدفق الحالي ويقدم الموضع داخل الدفق بعدد البايت المقروء. |
| virtual [ReadByte](../../aspose.imaging/streamcontainer/readbyte)() | يقرأ بايت من الدفق ويقدم الموضع داخل الدفق بمقدار بايت واحد ، أو يُرجع -1 إذا كان في نهاية الدفق . |
| virtual [Save](../../aspose.imaging/streamcontainer/save)(Stream) | يحفظ (ينسخ) بيانات الدفق إلى الدفق المحدد. يستخدم حجم المخزن المؤقت الافتراضي[`ReadWriteBytesCount`](../streamcontainer/readwritebytescount) والدفق[`Length`](../streamcontainer/length) القيمة . |
| virtual [Save](../../aspose.imaging/streamcontainer/save)(string) | يحفظ (ينسخ) بيانات الدفق إلى الدفق المحدد. يستخدم حجم المخزن المؤقت الافتراضي[`ReadWriteBytesCount`](../streamcontainer/readwritebytescount) والدفق[`Length`](../streamcontainer/length) القيمة . |
| virtual [Save](../../aspose.imaging/streamcontainer/save)(Stream, int) | يحفظ (ينسخ) جميع بيانات الدفق إلى الدفق المحدد. يستخدم تيار[`Length`](../streamcontainer/length) القيمة . |
| virtual [Save](../../aspose.imaging/streamcontainer/save)(string, int) | يحفظ (ينسخ) بيانات الدفق إلى الدفق المحدد. يستخدم تيار[`Length`](../streamcontainer/length) القيمة . |
| virtual [Save](../../aspose.imaging/streamcontainer/save)(Stream, int, long) | يحفظ (ينسخ) بيانات الدفق إلى الدفق المحدد. |
| virtual [Save](../../aspose.imaging/streamcontainer/save)(string, int, long) | يحفظ (ينسخ) بيانات الدفق إلى الدفق المحدد. |
| virtual [Seek](../../aspose.imaging/streamcontainer/seek)(long, SeekOrigin) | يضبط الموضع ضمن الدفق الحالي. |
| virtual [SeekBegin](../../aspose.imaging/streamcontainer/seekbegin)() | يضبط موضع الدفق على بداية الدفق. تمثل هذه القيمة الإزاحة من موضع دفق البداية الذي تم تمريره في مُنشئ StreamContainer. |
| virtual [ToBytes](../../aspose.imaging/streamcontainer/tobytes)() | يحول بيانات الدفق إلى ملفByte مجموعة . |
| virtual [ToBytes](../../aspose.imaging/streamcontainer/tobytes)(long, long) | يحول بيانات الدفق إلى ملفByte مجموعة . |
| virtual [Write](../../aspose.imaging/streamcontainer/write)(byte[]) | يكتب كل وحدات البايت المحددة في الدفق. |
| virtual [Write](../../aspose.imaging/streamcontainer/write)(byte[], int, int) | يكتب تسلسلًا من البايتات إلى الدفق الحالي ويقدم الموضع الحالي ضمن هذا الدفق بعدد البايتات المكتوبة. |
| virtual [WriteByte](../../aspose.imaging/streamcontainer/writebyte)(byte) | يكتب بايت إلى الموضع الحالي في الدفق ويقدم الموضع داخل الدفق بمقدار بايت واحد. |
| virtual [WriteTo](../../aspose.imaging/streamcontainer/writeto)(StreamContainer) | نسخ البيانات المضمنة إلى آخر[`StreamContainer`](../streamcontainer) . |
| virtual [WriteTo](../../aspose.imaging/streamcontainer/writeto)(StreamContainer, long) | نسخ البيانات المضمنة إلى آخر[`StreamContainer`](../streamcontainer) . |
| [explicit operator](../../aspose.imaging/filestreamcontainer/op_explicit#op_explicit_1) | يقوم بإجراء تحويل صريح من[`FileStreamContainer`](../filestreamcontainer) إلىStream . (2 operators) |

### أنظر أيضا

* class [StreamContainer](../streamcontainer)
* مساحة الاسم [Aspose.Imaging](../../aspose.imaging)
* المجسم [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
