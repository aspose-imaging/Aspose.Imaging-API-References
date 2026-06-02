---
title: "AsyncTask"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Die statische Fabrikklasse zum Erstellen der asynchronen Aufgaben"
type: docs
weight: 10
url: /de/java/com.aspose.imaging.asynctask/asynctask/
---
**Inheritance:**
java.lang.Object
```
public final class AsyncTask
```

Die statische Fabrikklasse zum Erstellen der asynchronen Aufgaben
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [create(AsyncTaskAction taskAction)](#create-com.aspose.imaging.asynctask.AsyncTaskAction-) | Erstellt die asynchrone Aufgabe ohne Ergebnis. |
| [create(AsyncTaskFunc taskFunc)](#create-com.aspose.imaging.asynctask.AsyncTaskFunc-) | Erstellt die asynchrone Aufgabe mit generischem Typ Ergebnis. |
### create(AsyncTaskAction taskAction) {#create-com.aspose.imaging.asynctask.AsyncTaskAction-}
```
public static IAsyncTask create(AsyncTaskAction taskAction)
```


Erstellt die asynchrone Aufgabe ohne Ergebnis.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| taskAction | [AsyncTaskAction](../../com.aspose.imaging.asynctask/asynctaskaction) | Die Aufgabenaktion. |

**Returns:**
[IAsyncTask](../../com.aspose.imaging.asynctask/iasynctask) - The asynchronous task
### create(AsyncTaskFunc taskFunc) {#create-com.aspose.imaging.asynctask.AsyncTaskFunc-}
```
public static IAsyncTask create(AsyncTaskFunc taskFunc)
```


Erstellt die asynchrone Aufgabe mit generischem Typ Ergebnis.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| taskFunc | [AsyncTaskFunc](../../com.aspose.imaging.asynctask/asynctaskfunc) | Die Aufgabenfunktion. |

**Returns:**
[IAsyncTask](../../com.aspose.imaging.asynctask/iasynctask) - The asynchronous task
