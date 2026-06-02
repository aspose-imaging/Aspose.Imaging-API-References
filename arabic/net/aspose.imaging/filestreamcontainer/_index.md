---
title: "الفئة FileStreamContainer"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.FileStreamContainer. أداة مساعدة لمعالجة تدفق الملفات"
type: docs
weight: 9480
url: /ar/net/aspose.imaging/filestreamcontainer/
---
## FileStreamContainer class

مساعدة لمعالجة تدفق الملفات.

```csharp
public sealed class FileStreamContainer : StreamContainer
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| virtual [CanRead](../../aspose.imaging/streamcontainer/canread/) { get; } | يحصل على قيمة تشير إلى ما إذا كان التدفق يدعم القراءة. |
| virtual [CanSeek](../../aspose.imaging/streamcontainer/canseek/) { get; } | يحصل على قيمة تشير إلى ما إذا كان التدفق يدعم السعي. |
| virtual [CanWrite](../../aspose.imaging/streamcontainer/canwrite/) { get; } | يحصل على قيمة تشير إلى ما إذا كان التدفق يدعم الكتابة. |
| [Disposed](../../aspose.imaging/disposableobject/disposed/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا المثال تم التخلص منه. |
| [FilePath](../../aspose.imaging/filestreamcontainer/filepath/) { get; } | يحصل على مسار الملف. |
| [IsCreated](../../aspose.imaging/filestreamcontainer/iscreated/) { get; } | يحصل على قيمة تشير إلى ما إذا تم إنشاء التدفق صراحةً. |
| virtual [IsStreamDisposedOnClose](../../aspose.imaging/streamcontainer/isstreamdisposedonclose/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا التدفق يتم التخلص منه عند الإغلاق. |
| [IsTemporal](../../aspose.imaging/filestreamcontainer/istemporal/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان التدفق مؤقتًا. |
| virtual [Length](../../aspose.imaging/streamcontainer/length/) { get; set; } | يحصل أو يعيّن طول التدفق بالبايت. هذه القيمة أقل من الطول بمقدار موضع بدء التدفق الممرّر في مُنشئ StreamContainer. |
| virtual [Position](../../aspose.imaging/streamcontainer/position/) { get; set; } | يحصل أو يعيّن الموضع الحالي داخل الدفق. تمثل هذه القيمة الإزاحة من موضع بدء الدفق الذي تم تمريره في مُنشئ StreamContainer. |
| virtual [Stream](../../aspose.imaging/streamcontainer/stream/) { get; } | يحصل على دفق البيانات. |
| [SyncRoot](../../aspose.imaging/streamcontainer/syncroot/) { get; } | يحصل على كائن يمكن استخدامه لمزامنة الوصول إلى المورد المتزامن. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [CreateFileStream](../../aspose.imaging/filestreamcontainer/createfilestream/)(string, bool) | ينشئ تدفق ملفات جديد. |
| static [OpenFileStream](../../aspose.imaging/filestreamcontainer/openfilestream/)(string) | يفتح تدفق ملفات موجود. إذا لم يكن تدفق الملفات موجودًا يتم رمي الاستثناء المناسب. |
| [Dispose](../../aspose.imaging/disposableobject/dispose/)() | يتخلص من المثيل الحالي. |
| virtual [Flush](../../aspose.imaging/streamcontainer/flush/)() | يمسح جميع المخازن المؤقتة لهذا الدفق ويتسبب في كتابة أي بيانات مخزنة مؤقتًا إلى الجهاز الأساسي. |
| virtual [Read](../../aspose.imaging/streamcontainer/read/)(byte[]) | يقرأ بايتات لملء المخزن المؤقت للبايتات المحدد. |
| virtual [Read](../../aspose.imaging/streamcontainer/read/)(byte[], int, int) | يقرأ تسلسلًا من البايتات من الدفق الحالي ويقّدم الموضع داخل الدفق بعدد البايتات المقروءة. |
| virtual [ReadByte](../../aspose.imaging/streamcontainer/readbyte/)() | يقرأ بايتًا من الدفق ويقّدم الموضع داخل الدفق بايتًا واحدًا، أو يُعيد -1 إذا كان عند نهاية الدفق. |
| virtual [Save](../../aspose.imaging/streamcontainer/save/)(Stream) | يحفظ (ينسخ) بيانات الدفق إلى الدفق المحدد. يستخدم حجم المخزن المؤقت الافتراضي [`ReadWriteBytesCount`](../streamcontainer/readwritebytescount/) وقيمة الدفق [`Length`](../streamcontainer/length/). |
| virtual [Save](../../aspose.imaging/streamcontainer/save/)(string) | يحفظ (ينسخ) بيانات الدفق إلى الدفق المحدد. يستخدم حجم المخزن المؤقت الافتراضي [`ReadWriteBytesCount`](../streamcontainer/readwritebytescount/) وقيمة الدفق [`Length`](../streamcontainer/length/). |
| virtual [Save](../../aspose.imaging/streamcontainer/save/)(Stream, int) | يحفظ (ينسخ) جميع بيانات الدفق إلى الدفق المحدد. يستخدم قيمة الدفق [`Length`](../streamcontainer/length/). |
| virtual [Save](../../aspose.imaging/streamcontainer/save/)(string, int) | يحفظ (ينسخ) بيانات الدفق إلى الدفق المحدد. يستخدم قيمة الدفق [`Length`](../streamcontainer/length/). |
| virtual [Save](../../aspose.imaging/streamcontainer/save/)(Stream, int, long) | يحفظ (ينسخ) بيانات الدفق إلى الدفق المحدد. |
| virtual [Save](../../aspose.imaging/streamcontainer/save/)(string, int, long) | يحفظ (ينسخ) بيانات الدفق إلى الدفق المحدد. |
| virtual [Seek](../../aspose.imaging/streamcontainer/seek/)(long, SeekOrigin) | يعيّن الموضع داخل الدفق الحالي. |
| virtual [SeekBegin](../../aspose.imaging/streamcontainer/seekbegin/)() | يعيّن موضع الدفق إلى بداية الدفق. تمثل هذه القيمة الإزاحة من موضع بدء الدفق الذي تم تمريره في مُنشئ StreamContainer. |
| virtual [ToBytes](../../aspose.imaging/streamcontainer/tobytes/)() | يحوّل بيانات الدفق إلى مصفوفة Byte. |
| virtual [ToBytes](../../aspose.imaging/streamcontainer/tobytes/)(long, long) | يحوّل بيانات الدفق إلى مصفوفة Byte. |
| virtual [Write](../../aspose.imaging/streamcontainer/write/)(byte[]) | يكتب جميع البايتات المحددة إلى الدفق. |
| virtual [Write](../../aspose.imaging/streamcontainer/write/)(byte[], int, int) | يكتب تسلسلًا من البايتات إلى الدفق الحالي ويقّدم الموضع الحالي داخل هذا الدفق بعدد البايتات المكتوبة. |
| virtual [WriteByte](../../aspose.imaging/streamcontainer/writebyte/)(byte) | يكتب بايتًا إلى الموضع الحالي في الدفق ويقّدم الموضع داخل الدفق بايتًا واحدًا. |
| virtual [WriteTo](../../aspose.imaging/streamcontainer/writeto/)(StreamContainer) | ينسخ البيانات المحتواة إلى [`StreamContainer`](../streamcontainer/). |
| virtual [WriteTo](../../aspose.imaging/streamcontainer/writeto/)(StreamContainer, long) | ينسخ البيانات المحتواة إلى [`StreamContainer`](../streamcontainer/). |
| [explicit operator](../../aspose.imaging/filestreamcontainer/op_explicit/#op_explicit_1) | يُجري تحويلًا صريحًا من `FileStreamContainer` إلى Stream. (عاملان) |

### انظر أيضًا

* class [StreamContainer](../streamcontainer/)
* namespace [Aspose.Imaging](../../aspose.imaging/)
* assembly [Aspose.Imaging](../../)


