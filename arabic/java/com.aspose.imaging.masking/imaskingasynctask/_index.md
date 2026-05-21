---
title: "IMaskingAsyncTask"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يمثل مهمة التمويه async."
type: docs
weight: 11
url: /ar/java/com.aspose.imaging.masking/imaskingasynctask/
---
**All Implemented Interfaces:**
[com.aspose.imaging.asynctask.IAsyncTask](../../com.aspose.imaging.asynctask/iasynctask)
```
public interface IMaskingAsyncTask extends IAsyncTask
```

يمثل مهمة التمويه async.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getMaskingResult()](#getMaskingResult--) | يعيد نتيجة عملية التمويه |
| [getErrorString()](#getErrorString--) | يعيد خطأً في عملية التمويه |
### getMaskingResult() {#getMaskingResult--}
```
public abstract MaskingResult getMaskingResult()
```


يعيد نتيجة عملية التمويه

**Returns:**
[MaskingResult](../../com.aspose.imaging.masking.result/maskingresult) - The result of this task.
### getErrorString() {#getErrorString--}
```
public abstract String getErrorString()
```


يعيد خطأً في عملية التمويه

**Returns:**
java.lang.String - خطأ المهمة.
