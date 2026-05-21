---
title: "IMaskingAsyncTask"
second_title: "Aspose.Imaging för Java API-referens"
description: "Representerar den asynkrona maskeringsuppgiften."
type: docs
weight: 11
url: /sv/java/com.aspose.imaging.masking/imaskingasynctask/
---
**All Implemented Interfaces:**
[com.aspose.imaging.asynctask.IAsyncTask](../../com.aspose.imaging.asynctask/iasynctask)
```
public interface IMaskingAsyncTask extends IAsyncTask
```

Representerar den asynkrona maskeringsuppgiften.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getMaskingResult()](#getMaskingResult--) | Returnerar resultatet av maskeringsoperationen |
| [getErrorString()](#getErrorString--) | Returnerar ett fel i maskeringsoperationen |
### getMaskingResult() {#getMaskingResult--}
```
public abstract MaskingResult getMaskingResult()
```


Returnerar resultatet av maskeringsoperationen

**Returns:**
[MaskingResult](../../com.aspose.imaging.masking.result/maskingresult) - The result of this task.
### getErrorString() {#getErrorString--}
```
public abstract String getErrorString()
```


Returnerar ett fel i maskeringsoperationen

**Returns:**
java.lang.String - Uppgiftsfelet.
