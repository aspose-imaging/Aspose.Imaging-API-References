---
title: "IMaskingSession Klasse"
type: docs
weight: 80
url: /de/python-net/aspose.imaging.masking/imaskingsession/
---

**Summary:** The masking session

**Module:** [aspose.imaging.masking](/imaging/python-net/aspose.imaging.masking/)

**Full Name:** aspose.imaging.masking.IMaskingSession

## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [decompose()](#decompose__1) | Führt die erste grobe Zerlegungsoperation aus |
| [decompose_async()](#decompose_async__2) | Erstellt die asynchrone Aufgabe, die die erste grobe Zerlegungsoperation ausführen kann |
| [improve_decomposition(masking_arguments)](#improve_decomposition_masking_arguments_3) | Führt die Retraining-Dekompositionsoperation aus |
| [improve_decomposition_async(masking_arguments)](#improve_decomposition_async_masking_arguments_4) | Erstellt die asynchrone Aufgabe, die die Retraining-Dekompositionsoperation ausführen kann |
| [save(file_path)](#save_file_path_5) | Speichert den Sitzungszustand in die angegebene Datei. |
| [save(stream)](#save_stream_6) | Speichert den Sitzungszustand in den angegebenen Stream. |


### Method: decompose() {#decompose__1}


```
 decompose() 
```

Führt die erste grobe Zerlegungsoperation aus

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [MaskingResult](/imaging/python-net/aspose.imaging.masking.result/maskingresult/) | Ergebnis der Maskierungsoperation als Array von Segment-Bildanbietern. |


### Method: decompose_async() {#decompose_async__2}


```
 decompose_async() 
```

Erstellt die asynchrone Aufgabe, die die erste grobe Zerlegungsoperation ausführen kann

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [IMaskingAsyncTask](/imaging/python-net/aspose.imaging.masking/imaskingasynctask/) | Die asynchrone Dekompositionsaufgabe |


### Method: improve_decomposition(masking_arguments) {#improve_decomposition_masking_arguments_3}


```
 improve_decomposition(masking_arguments) 
```

Führt die Retraining-Dekompositionsoperation aus

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| masking_arguments | [IMaskingArgs](/imaging/python-net/aspose.imaging.masking.options/imaskingargs/) | Die Maskierungsargumente. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [MaskingResult](/imaging/python-net/aspose.imaging.masking.result/maskingresult/) | Ergebnis der Maskierungsoperation als Array von Segment-Bildanbietern. |


### Method: improve_decomposition_async(masking_arguments) {#improve_decomposition_async_masking_arguments_4}


```
 improve_decomposition_async(masking_arguments) 
```

Erstellt die asynchrone Aufgabe, die die Retraining-Dekompositionsoperation ausführen kann

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| masking_arguments | [IMaskingArgs](/imaging/python-net/aspose.imaging.masking.options/imaskingargs/) | Die Maskierungsargumente. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [IMaskingAsyncTask](/imaging/python-net/aspose.imaging.masking/imaskingasynctask/) | Die asynchrone Dekompositionsaufgabe |


### Method: save(file_path) {#save_file_path_5}


```
 save(file_path) 
```

Speichert den Sitzungszustand in die angegebene Datei.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_path | string | Der Dateipfad. |

### Method: save(stream) {#save_stream_6}


```
 save(stream) 
```

Speichert den Sitzungszustand in den angegebenen Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Stream | _io.BufferedRandom | Der Stream. |

