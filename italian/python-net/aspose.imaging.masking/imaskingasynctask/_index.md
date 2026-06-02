---
title: "IMaskingAsyncTask Classe"
type: docs
weight: 60
url: /it/python-net/aspose.imaging.masking/imaskingasynctask/
---

**Summary:** Represents the masking async task.

**Module:** [aspose.imaging.masking](/imaging/python-net/aspose.imaging.masking/)

**Full Name:** aspose.imaging.masking.IMaskingAsyncTask

**Inheritance:** IAsyncTask

## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| is_busy | bool | r | Restituisce un valore che indica se questa attività è attualmente in esecuzione. |
| is_canceled | bool | r | Restituisce un valore che indica se questa attività è stata annullata. |
| is_faulted | bool | r | Restituisce un valore che indica se questa attività ha generato un errore. |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| abort() | Interrompe questa attività.<br/>            L'attività viene completata immediatamente, con il rischio di non liberare le risorse non gestite interne. |
| cancel() | Annulla questa attività.<br/>            L'attività viene completata in modo sicuro mediante l'arresto controllato dell'algoritmo. |
| [get_error()](#get_error__1) | Restituisce un errore dell'operazione di mascheramento |
| [get_masking_result()](#get_masking_result__2) | Restituisce il risultato dell'operazione di mascheramento |
| run_async() | Esegue questa attività. |
| wait_on_done() | Attende fino al completamento dell'attività. |


### Method: get_error() {#get_error__1}


```
 get_error() 
```

Restituisce un errore dell'operazione di mascheramento

**Returns**

| Tipo | Descrizione |
| :- | :- |
| string | L'errore dell'attività. |


### Method: get_masking_result() {#get_masking_result__2}


```
 get_masking_result() 
```

Restituisce il risultato dell'operazione di mascheramento

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [MaskingResult](/imaging/python-net/aspose.imaging.masking.result/maskingresult/) | Il risultato di questa attività. |


