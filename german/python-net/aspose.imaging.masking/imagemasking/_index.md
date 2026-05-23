---
title: "ImageMasking Klasse"
type: docs
weight: 90
url: /de/python-net/aspose.imaging.masking/imagemasking/
---

**Summary:** Provides image masking operations

**Module:** [aspose.imaging.masking](/imaging/python-net/aspose.imaging.masking/)

**Full Name:** aspose.imaging.masking.ImageMasking

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [ImageMasking(source_image)](#ImageMasking_source_image_1) | Initialisiert eine neue Instanz der [ImageMasking](/imaging/python-net/aspose.imaging.masking/imagematching/) Klasse. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [apply_mask(target_image, mask, masking_options)](#apply_mask_target_image_mask_masking_options_1) | Wendet die Maske auf das angegebene Quellbild an. |
| [create_session(options)](#create_session_options_2) | Erstellt die Maskierungssitzung, die Retraining-Dekompositionsoperationen ausführen kann. |
| [decompose(options)](#decompose_options_3) | Führt die Dekompositionsoperation unter Verwendung der angegebenen Maskierungsoptionen aus |
| [decompose_async(options)](#decompose_async_options_4) | Erstellt die asynchrone Dekompositionsaufgabe unter Verwendung der angegebenen Maskierungsoptionen. |
| [load_session(file_path)](#load_session_file_path_5) | Lädt die Sitzung aus der angegebenen Datei. |
| [load_session(stream)](#load_session_stream_6) | Lädt die Sitzung aus dem angegebenen Stream. |
| [load_session_from_stream(stream)](#load_session_from_stream_stream_7) | Lädt die Sitzung aus dem angegebenen Stream. |


### Constructor: ImageMasking(source_image) {#ImageMasking_source_image_1}


```
 ImageMasking(source_image) 
```

Initialisiert eine neue Instanz der [ImageMasking](/imaging/python-net/aspose.imaging.masking/imagematching/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| source_image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Das Quellbild. |

### Method: apply_mask(target_image, mask, masking_options)  [static] {#apply_mask_target_image_mask_masking_options_1}


```
 apply_mask(target_image, mask, masking_options) 
```

Wendet die Maske auf das angegebene Quellbild an.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| target_image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Das Zielbild. |
| mask | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Das anzuwendende Maskenbild. |
| masking_options | [MaskingOptions](/imaging/python-net/aspose.imaging.masking.options/maskingoptions/) | Die Maskierungsoptionen. |

### Method: create_session(options) {#create_session_options_2}


```
 create_session(options) 
```

Erstellt die Maskierungssitzung, die Retraining-Dekompositionsoperationen ausführen kann.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| options | [MaskingOptions](/imaging/python-net/aspose.imaging.masking.options/maskingoptions/) | Die Optionen. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [IMaskingSession](/imaging/python-net/aspose.imaging.masking/imaskingsession/) | die Maskierungssitzung, die Retraining-Dekompositionsoperationen ausführen kann. |


### Method: decompose(options) {#decompose_options_3}


```
 decompose(options) 
```

Führt die Dekompositionsoperation unter Verwendung der angegebenen Maskierungsoptionen aus

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| options | [MaskingOptions](/imaging/python-net/aspose.imaging.masking.options/maskingoptions/) | Die Maskierungsoptionen. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [MaskingResult](/imaging/python-net/aspose.imaging.masking.result/maskingresult/) | Ergebnis der Maskierungsoperation als Array von Segment-Bildanbietern. |


### Method: decompose_async(options) {#decompose_async_options_4}


```
 decompose_async(options) 
```

Erstellt die asynchrone Dekompositionsaufgabe unter Verwendung der angegebenen Maskierungsoptionen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| options | [MaskingOptions](/imaging/python-net/aspose.imaging.masking.options/maskingoptions/) | Die Maskierungsoptionen. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [IMaskingAsyncTask](/imaging/python-net/aspose.imaging.masking/imaskingasynctask/) | Die asynchrone Dekompositionsaufgabe |


### Method: load_session(file_path) {#load_session_file_path_5}


```
 load_session(file_path) 
```

Lädt die Sitzung aus der angegebenen Datei.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_path | string | Der Dateipfad. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [IMaskingSession](/imaging/python-net/aspose.imaging.masking/imaskingsession/) | die Maskierungssitzung, die Retraining-Dekompositionsoperationen ausführen kann. |


### Method: load_session(stream) {#load_session_stream_6}


```
 load_session(stream) 
```

Lädt die Sitzung aus dem angegebenen Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Stream | _io.BufferedRandom | Der Stream. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [IMaskingSession](/imaging/python-net/aspose.imaging.masking/imaskingsession/) | die Maskierungssitzung, die Retraining-Dekompositionsoperationen ausführen kann. |


### Method: load_session_from_stream(stream) {#load_session_from_stream_stream_7}


```
 load_session_from_stream(stream) 
```

Lädt die Sitzung aus dem angegebenen Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Stream | _io.BufferedRandom | Der Stream. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [IMaskingSession](/imaging/python-net/aspose.imaging.masking/imaskingsession/) | die Maskierungssitzung, die Retraining-Dekompositionsoperationen ausführen kann. |


