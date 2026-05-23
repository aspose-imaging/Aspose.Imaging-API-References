---
title: "IAsyncTask Klasse"
type: docs
weight: 30
url: /de/python-net/aspose.imaging.asynctask/iasynctask/
---

**Summary:** The asynchronous task.

**Module:** [aspose.imaging.asynctask](/imaging/python-net/aspose.imaging.asynctask/)

**Full Name:** aspose.imaging.asynctask.IAsyncTask

## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| is_busy | bool | r | Gibt einen Wert zurück, der angibt, ob diese Aufgabe gerade ausgeführt wird. |
| is_canceled | bool | r | Gibt einen Wert zurück, der angibt, ob diese Aufgabe abgebrochen wurde. |
| is_faulted | bool | r | Gibt einen Wert zurück, der angibt, ob diese Aufgabe fehlerhaft war. |
| result | System.Object | r | Gibt das Ergebnis dieser Aufgabe zurück. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| abort() | Bricht diese Aufgabe ab.<br/>            Die Aufgabe wird sofort abgeschlossen, mit dem Risiko, interne nicht verwaltete Ressourcen nicht freizugeben. |
| cancel() | Bricht diese Aufgabe ab.<br/>            Die Aufgabe wird sicher abgeschlossen, indem der Algorithmus kontrolliert gestoppt wird. |
| run_async() | Führt diese Aufgabe aus. |
| wait_on_done() | Wartet, bis die Aufgabe beendet ist. |


