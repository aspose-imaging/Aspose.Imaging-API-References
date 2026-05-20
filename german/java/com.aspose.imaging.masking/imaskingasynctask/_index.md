---
title: "IMaskingAsyncTask"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Stellt die asynchrone Maskierungsaufgabe dar."
type: docs
weight: 11
url: /de/java/com.aspose.imaging.masking/imaskingasynctask/
---
**All Implemented Interfaces:**
[com.aspose.imaging.asynctask.IAsyncTask](../../com.aspose.imaging.asynctask/iasynctask)
```
public interface IMaskingAsyncTask extends IAsyncTask
```

Stellt die asynchrone Maskierungsaufgabe dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getMaskingResult()](#getMaskingResult--) | Gibt das Ergebnis der Maskierungsoperation zurück |
| [getErrorString()](#getErrorString--) | Gibt einen Fehler der Maskierungsoperation zurück |
### getMaskingResult() {#getMaskingResult--}
```
public abstract MaskingResult getMaskingResult()
```


Gibt das Ergebnis der Maskierungsoperation zurück

**Returns:**
[MaskingResult](../../com.aspose.imaging.masking.result/maskingresult) - The result of this task.
### getErrorString() {#getErrorString--}
```
public abstract String getErrorString()
```


Gibt einen Fehler der Maskierungsoperation zurück

**Returns:**
java.lang.String - Der Aufgabenfehler.
