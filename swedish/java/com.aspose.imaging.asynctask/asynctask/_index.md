---
title: "AsyncTask"
second_title: "Aspose.Imaging för Java API-referens"
description: "Den statiska fabriksklassen för att skapa de asynkrona uppgifterna"
type: docs
weight: 10
url: /sv/java/com.aspose.imaging.asynctask/asynctask/
---
**Inheritance:**
java.lang.Object
```
public final class AsyncTask
```

Den statiska fabriksklassen för att skapa de asynkrona uppgifterna
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [create(AsyncTaskAction taskAction)](#create-com.aspose.imaging.asynctask.AsyncTaskAction-) | Skapar den asynkrona uppgiften utan något resultat. |
| [create(AsyncTaskFunc taskFunc)](#create-com.aspose.imaging.asynctask.AsyncTaskFunc-) | Skapar den asynkrona uppgiften med ett generiskt typresultat. |
### create(AsyncTaskAction taskAction) {#create-com.aspose.imaging.asynctask.AsyncTaskAction-}
```
public static IAsyncTask create(AsyncTaskAction taskAction)
```


Skapar den asynkrona uppgiften utan något resultat.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| taskAction | [AsyncTaskAction](../../com.aspose.imaging.asynctask/asynctaskaction) | Uppgiftens åtgärd. |

**Returns:**
[IAsyncTask](../../com.aspose.imaging.asynctask/iasynctask) - The asynchronous task
### create(AsyncTaskFunc taskFunc) {#create-com.aspose.imaging.asynctask.AsyncTaskFunc-}
```
public static IAsyncTask create(AsyncTaskFunc taskFunc)
```


Skapar den asynkrona uppgiften med ett generiskt typresultat.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| taskFunc | [AsyncTaskFunc](../../com.aspose.imaging.asynctask/asynctaskfunc) | Uppgiftens funktion. |

**Returns:**
[IAsyncTask](../../com.aspose.imaging.asynctask/iasynctask) - The asynchronous task
