---
title: "IAsyncTask"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "المهمة غير المتزامنة."
type: docs
weight: 16
url: /ar/java/com.aspose.imaging.asynctask/iasynctask/
---
**All Implemented Interfaces:**
com.aspose.ms.System.IAsyncResult, com.aspose.ms.System.IDisposable
```
public interface IAsyncTask extends System.IAsyncResult, System.IDisposable
```

المهمة غير المتزامنة.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getProgressEventHandler()](#getProgressEventHandler--) | يحصل على معالج حدث التقدم للمهمة غير المتزامنة. |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.imaging.ProgressEventHandler-) | يضبط معالج حدث التقدم للمهمة غير المتزامنة. |
| [isBusy()](#isBusy--) | يحصل على قيمة تشير إلى ما إذا كانت هذه المهمة قيد التشغيل حاليًا. |
| [isCanceled()](#isCanceled--) | يحصل على قيمة تشير إلى ما إذا تم إلغاء هذه المهمة. |
| [isFaulted()](#isFaulted--) | يحصل على قيمة تشير إلى ما إذا كانت هذه المهمة قد فشلت. |
| [getError()](#getError--) | يحصل على خطأ المهمة المتاح بعد إكمال المهمة. |
| [getResult()](#getResult--) | يحصل على نتيجة هذه المهمة. |
| [runAsync()](#runAsync--) | يشغّل هذه المهمة. |
| [runAsync(int priority)](#runAsync-int-) | يشغّل هذه المهمة. |
| [cancel()](#cancel--) | يلغي هذه المهمة. |
| [abort()](#abort--) | يوقف هذه المهمة. |
| [setCompleteCallback(CompleteCallback completeCallback)](#setCompleteCallback-com.aspose.imaging.asynctask.CompleteCallback-) | يضبط المفوض للنداء الكامل. |
### getProgressEventHandler() {#getProgressEventHandler--}
```
public abstract ProgressEventHandler getProgressEventHandler()
```


يحصل على معالج حدث التقدم للمهمة غير المتزامنة.

القيمة: معالج حدث التقدم للمهمة غير المتزامنة.

**Returns:**
[ProgressEventHandler](../../com.aspose.imaging/progresseventhandler) - the progress event handler of the asynchronous task.
### setProgressEventHandler(ProgressEventHandler value) {#setProgressEventHandler-com.aspose.imaging.ProgressEventHandler-}
```
public abstract void setProgressEventHandler(ProgressEventHandler value)
```


يضبط معالج حدث التقدم للمهمة غير المتزامنة.

القيمة: معالج حدث التقدم للمهمة غير المتزامنة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [ProgressEventHandler](../../com.aspose.imaging/progresseventhandler) | معالج حدث التقدم للمهمة غير المتزامنة. |

### isBusy() {#isBusy--}
```
public abstract boolean isBusy()
```


يحصل على قيمة تشير إلى ما إذا كانت هذه المهمة قيد التشغيل حاليًا.

القيمة: `true` إذا كانت هذه المهمة قيد التشغيل حاليًا؛ وإلا `false`.

**Returns:**
منطقي - قيمة تشير إلى ما إذا كانت هذه المهمة قيد التشغيل حاليًا.
### isCanceled() {#isCanceled--}
```
public abstract boolean isCanceled()
```


يحصل على قيمة تشير إلى ما إذا تم إلغاء هذه المهمة.

القيمة: `true` إذا تم إلغاء هذه المهمة؛ وإلا `false`.

**Returns:**
boolean - قيمة تشير إلى ما إذا تم إلغاء هذه المهمة.
### isFaulted() {#isFaulted--}
```
public abstract boolean isFaulted()
```


يحصل على قيمة تشير إلى ما إذا كانت هذه المهمة قد فشلت.

القيمة: `true` إذا كانت هذه المهمة معطوبة؛ وإلا `false`.

**Returns:**
boolean - قيمة تشير إلى ما إذا كانت هذه المهمة معطوبة.
### getError() {#getError--}
```
public abstract Throwable getError()
```


يحصل على خطأ المهمة المتاح بعد إكمال المهمة.

القيمة: خطأ المهمة.

**Returns:**
java.lang.Throwable - خطأ المهمة المتاح بعد إكمال المهمة.
### getResult() {#getResult--}
```
public abstract Object getResult()
```


يحصل على نتيجة هذه المهمة.

القيمة: نتيجة هذه المهمة.

**Returns:**
java.lang.Object - نتيجة هذه المهمة.
### runAsync() {#runAsync--}
```
public abstract void runAsync()
```


يشغّل هذه المهمة.

### runAsync(int priority) {#runAsync-int-}
```
public abstract void runAsync(int priority)
```


يشغّل هذه المهمة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الأولوية | int | أولوية الخيط. |

### cancel() {#cancel--}
```
public abstract void cancel()
```


يلغي هذه المهمة. تُكمل المهمة بأمان عبر إيقاف الخوارزمية بشكل مُتحكم.

### abort() {#abort--}
```
public abstract void abort()
```


يُجهض هذه المهمة. تُكمل المهمة فورًا، مع خطر عدم تحرير الموارد الداخلية غير المُدارة.

### setCompleteCallback(CompleteCallback completeCallback) {#setCompleteCallback-com.aspose.imaging.asynctask.CompleteCallback-}
```
public abstract void setCompleteCallback(CompleteCallback completeCallback)
```


يضبط المفوض للنداء الكامل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| completeCallback | [CompleteCallback](../../com.aspose.imaging.asynctask/completecallback) | دالة رد النداء عند الإكمال. |

