---
title: "الواجهة IAsyncTask"
second_title: "Aspose.Imaging for .NET API Reference"
description: "واجهة Aspose.Imaging.AsyncTask.IAsyncTask. المهمة غير المتزامنة"
type: docs
weight: 100
url: /ar/net/aspose.imaging.asynctask/iasynctask/
---
## IAsyncTask interface

المهمة غير المتزامنة.

```csharp
public interface IAsyncTask : IAsyncResult, IDisposable
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Error](../../aspose.imaging.asynctask/iasynctask/error/) { get; } | يحصل على خطأ المهمة المتاح بعد إكمال المهمة. |
| [IsBusy](../../aspose.imaging.asynctask/iasynctask/isbusy/) { get; } | يحصل على قيمة تشير إلى ما إذا كانت هذه المهمة قيد التشغيل حاليًا. |
| [IsCanceled](../../aspose.imaging.asynctask/iasynctask/iscanceled/) { get; } | يحصل على قيمة تشير إلى ما إذا تم إلغاء هذه المهمة. |
| [IsFaulted](../../aspose.imaging.asynctask/iasynctask/isfaulted/) { get; } | يحصل على قيمة تشير إلى ما إذا كانت هذه المهمة قد حدث فيها خطأ. |
| [ProgressEventHandler](../../aspose.imaging.asynctask/iasynctask/progresseventhandler/) { get; set; } | يحصل أو يضبط معالج حدث التقدم للمهمة غير المتزامنة. |
| [Result](../../aspose.imaging.asynctask/iasynctask/result/) { get; } | يحصل على نتيجة هذه المهمة. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Abort](../../aspose.imaging.asynctask/iasynctask/abort/)() | يوقف هذه المهمة. تُكمل المهمة فورًا، مع خطر عدم تحرير الموارد الداخلية غير المدارة. |
| [Cancel](../../aspose.imaging.asynctask/iasynctask/cancel/)() | يلغي هذه المهمة. تُكمل المهمة بأمان عبر إيقاف الخوارزمية بشكل مُتحكم. |
| [RunAsync](../../aspose.imaging.asynctask/iasynctask/runasync/#runasync)() | يشغل هذه المهمة. |
| [RunAsync](../../aspose.imaging.asynctask/iasynctask/runasync/#runasync_1)(ThreadPriority) | يشغل هذه المهمة. |
| [SetCompleteCallback](../../aspose.imaging.asynctask/iasynctask/setcompletecallback/)(CompleteCallback) | يضبط المندوب الندائي للانتهاء. |

### انظر أيضًا

* namespace [Aspose.Imaging.AsyncTask](../../aspose.imaging.asynctask/)
* assembly [Aspose.Imaging](../../)


