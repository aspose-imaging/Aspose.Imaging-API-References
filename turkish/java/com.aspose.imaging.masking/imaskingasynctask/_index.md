---
title: "IMaskingAsyncTask"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Maskeleme asenkron görevini temsil eder."
type: docs
weight: 11
url: /tr/java/com.aspose.imaging.masking/imaskingasynctask/
---
**All Implemented Interfaces:**
[com.aspose.imaging.asynctask.IAsyncTask](../../com.aspose.imaging.asynctask/iasynctask)
```
public interface IMaskingAsyncTask extends IAsyncTask
```

Maskeleme asenkron görevini temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getMaskingResult()](#getMaskingResult--) | Maskeleme işleminin sonucunu döndürür |
| [getErrorString()](#getErrorString--) | Maskeleme işleminin hatasını döndürür |
### getMaskingResult() {#getMaskingResult--}
```
public abstract MaskingResult getMaskingResult()
```


Maskeleme işleminin sonucunu döndürür

**Returns:**
[MaskingResult](../../com.aspose.imaging.masking.result/maskingresult) - The result of this task.
### getErrorString() {#getErrorString--}
```
public abstract String getErrorString()
```


Maskeleme işleminin hatasını döndürür

**Returns:**
java.lang.String - Görev hatası.
