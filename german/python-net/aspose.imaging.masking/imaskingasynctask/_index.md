---
title: "IMaskingAsyncTask Klasse"
type: docs
weight: 60
url: /de/python-net/aspose.imaging.masking/imaskingasynctask/
---

**Summary:** Represents the masking async task.

**Module:** [aspose.imaging.masking](/imaging/python-net/aspose.imaging.masking/)

**Full Name:** aspose.imaging.masking.IMaskingAsyncTask

**Inheritance:** IAsyncTask

## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| is_busy | bool | r | Gibt einen Wert zurück, der angibt, ob diese Aufgabe gerade ausgeführt wird. |
| is_canceled | bool | r | Gibt einen Wert zurück, der angibt, ob diese Aufgabe abgebrochen wurde. |
| is_faulted | bool | r | Gibt einen Wert zurück, der angibt, ob diese Aufgabe fehlerhaft war. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| abort() | Bricht diese Aufgabe ab.<br/>            Die Aufgabe wird sofort abgeschlossen, mit dem Risiko, interne nicht verwaltete Ressourcen nicht freizugeben. |
| cancel() | Bricht diese Aufgabe ab.<br/>            Die Aufgabe wird sicher abgeschlossen, indem der Algorithmus kontrolliert gestoppt wird. |
| [get_error()](#get_error__1) | Gibt einen Fehler der Maskierungsoperation zurück |
| [get_masking_result()](#get_masking_result__2) | Gibt das Ergebnis der Maskierungsoperation zurück |
| run_async() | Führt diese Aufgabe aus. |
| wait_on_done() | Wartet, bis die Aufgabe beendet ist. |


### Method: get_error() {#get_error__1}


```
 get_error() 
```

Gibt einen Fehler der Maskierungsoperation zurück

**Returns**

| Typ | Beschreibung |
| :- | :- |
| string | Der Aufgabenfehler. |


### Method: get_masking_result() {#get_masking_result__2}


```
 get_masking_result() 
```

Gibt das Ergebnis der Maskierungsoperation zurück

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [MaskingResult](/imaging/python-net/aspose.imaging.masking.result/maskingresult/) | Das Ergebnis dieser Aufgabe. |


