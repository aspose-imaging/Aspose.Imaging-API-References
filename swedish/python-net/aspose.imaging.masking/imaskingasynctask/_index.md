---
title: "IMaskingAsyncTask klass"
type: docs
weight: 60
url: /sv/python-net/aspose.imaging.masking/imaskingasynctask/
---

**Summary:** Represents the masking async task.

**Module:** [aspose.imaging.masking](/imaging/python-net/aspose.imaging.masking/)

**Full Name:** aspose.imaging.masking.IMaskingAsyncTask

**Inheritance:** IAsyncTask

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| is_busy | bool | r | Hämtar ett värde som indikerar om den här uppgiften för närvarande körs. |
| is_canceled | bool | r | Hämtar ett värde som indikerar om den här uppgiften avbröts. |
| is_faulted | bool | r | Hämtar ett värde som indikerar om den här uppgiften misslyckades. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| abort() | Avbryter den här uppgiften.<br/>            Uppgiften avslutas omedelbart, med risken att interna ohanterade resurser inte frigörs. |
| cancel() | Avbryter den här uppgiften.<br/>            Uppgiften avslutas säkert genom kontrollerad stoppning av algoritmen. |
| [get_error()](#get_error__1) | Returnerar ett fel för maskeringsoperationen |
| [get_masking_result()](#get_masking_result__2) | Returnerar resultatet av maskeringsoperationen |
| run_async() | Kör den här uppgiften. |
| wait_on_done() | Väntar tills uppgiften är klar. |


### Method: get_error() {#get_error__1}


```
 get_error() 
```

Returnerar ett fel för maskeringsoperationen

**Returns**

| Typ | Beskrivning |
| :- | :- |
| string | Uppgiftsfelet. |


### Method: get_masking_result() {#get_masking_result__2}


```
 get_masking_result() 
```

Returnerar resultatet av maskeringsoperationen

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [MaskingResult](/imaging/python-net/aspose.imaging.masking.result/maskingresult/) | Resultatet av denna uppgift. |


