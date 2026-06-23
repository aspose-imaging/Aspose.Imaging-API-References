---
title: "IMaskingAsyncTask"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يمثل مهمة القناع غير المتزامنة."
type: docs
weight: 11
url: /ar/java/com.aspose.imaging.masking/imaskingasynctask/
---
**All Implemented Interfaces:**
[com.aspose.imaging.asynctask.IAsyncTask](../../com.aspose.imaging.asynctask/iasynctask)
```
public interface IMaskingAsyncTask extends IAsyncTask
```

يمثل مهمة القناع غير المتزامنة.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getMaskingResult()](#getMaskingResult--) | يرجع نتيجة عملية القناع |
| [getErrorString()](#getErrorString--) | يرجع خطأً في عملية القناع |
### getMaskingResult() {#getMaskingResult--}
```
public abstract MaskingResult getMaskingResult()
```


يرجع نتيجة عملية القناع

**Returns:**
[MaskingResult](../../com.aspose.imaging.masking.result/maskingresult) - The result of this task.
### getErrorString() {#getErrorString--}
```
public abstract String getErrorString()
```


يرجع خطأً في عملية القناع

**Returns:**
java.lang.String - خطأ المهمة.
