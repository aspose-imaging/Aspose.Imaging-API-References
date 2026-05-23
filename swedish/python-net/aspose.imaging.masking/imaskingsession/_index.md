---
title: "IMaskingSession klass"
type: docs
weight: 80
url: /sv/python-net/aspose.imaging.masking/imaskingsession/
---

**Summary:** The masking session

**Module:** [aspose.imaging.masking](/imaging/python-net/aspose.imaging.masking/)

**Full Name:** aspose.imaging.masking.IMaskingSession

## **Methods**
| **Name** | **Description** |
| :- | :- |
| [decompose()](#decompose__1) | Utför den första grova dekomponeringsoperationen |
| [decompose_async()](#decompose_async__2) | Skapar den asynkrona uppgiften som kan utföra den första grova dekomponeringsoperationen |
| [improve_decomposition(masking_arguments)](#improve_decomposition_masking_arguments_3) | Utför återträning av dekomponeringsoperation |
| [improve_decomposition_async(masking_arguments)](#improve_decomposition_async_masking_arguments_4) | Skapar den asynkrona uppgiften som kan utföra återträning av dekomponeringsoperation |
| [save(file_path)](#save_file_path_5) | Sparar sessionsstatus till den angivna filen. |
| [save(stream)](#save_stream_6) | Spara sessionsstatus till den angivna strömmen. |


### Method: decompose() {#decompose__1}


```
 decompose() 
```

Utför den första grova dekomponeringsoperationen

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [MaskingResult](/imaging/python-net/aspose.imaging.masking.result/maskingresult/) | Resultat av maskeringsoperation som en array av segmentbildsleverantörer. |


### Method: decompose_async() {#decompose_async__2}


```
 decompose_async() 
```

Skapar den asynkrona uppgiften som kan utföra den första grova dekomponeringsoperationen

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [IMaskingAsyncTask](/imaging/python-net/aspose.imaging.masking/imaskingasynctask/) | Den asynkrona dekomponeringsuppgiften |


### Method: improve_decomposition(masking_arguments) {#improve_decomposition_masking_arguments_3}


```
 improve_decomposition(masking_arguments) 
```

Utför återträning av dekomponeringsoperation

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| masking_arguments | [IMaskingArgs](/imaging/python-net/aspose.imaging.masking.options/imaskingargs/) | Maskeringsargumenten. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [MaskingResult](/imaging/python-net/aspose.imaging.masking.result/maskingresult/) | Resultat av maskeringsoperation som en array av segmentbildsleverantörer. |


### Method: improve_decomposition_async(masking_arguments) {#improve_decomposition_async_masking_arguments_4}


```
 improve_decomposition_async(masking_arguments) 
```

Skapar den asynkrona uppgiften som kan utföra återträning av dekomponeringsoperation

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| masking_arguments | [IMaskingArgs](/imaging/python-net/aspose.imaging.masking.options/imaskingargs/) | Maskeringsargumenten. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [IMaskingAsyncTask](/imaging/python-net/aspose.imaging.masking/imaskingasynctask/) | Den asynkrona dekomponeringsuppgiften |


### Method: save(file_path) {#save_file_path_5}


```
 save(file_path) 
```

Sparar sessionsstatus till den angivna filen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_path | string | Filsökvägen. |

### Method: save(stream) {#save_stream_6}


```
 save(stream) 
```

Spara sessionsstatus till den angivna strömmen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| ström | _io.BufferedRandom | Strömmen. |

