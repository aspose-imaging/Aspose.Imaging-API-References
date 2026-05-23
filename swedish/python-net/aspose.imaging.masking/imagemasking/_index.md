---
title: "ImageMasking klass"
type: docs
weight: 90
url: /sv/python-net/aspose.imaging.masking/imagemasking/
---

**Summary:** Provides image masking operations

**Module:** [aspose.imaging.masking](/imaging/python-net/aspose.imaging.masking/)

**Full Name:** aspose.imaging.masking.ImageMasking

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [ImageMasking(source_image)](#ImageMasking_source_image_1) | Initialiserar en ny instans av klassen [ImageMasking](/imaging/python-net/aspose.imaging.masking/imagematching/). |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [apply_mask(target_image, mask, masking_options)](#apply_mask_target_image_mask_masking_options_1) | Applicerar masken på den angivna källbilden. |
| [create_session(options)](#create_session_options_2) | Skapar maskeringssessionen som kan utföra återträning av dekomponeringsoperationer. |
| [decompose(options)](#decompose_options_3) | Utför dekomponeringsoperationen med angivna maskeringsalternativ |
| [decompose_async(options)](#decompose_async_options_4) | Skapar den asynkrona dekomponeringsuppgiften med angivna maskeringsalternativ. |
| [load_session(file_path)](#load_session_file_path_5) | Läs in sessionen från den angivna filen. |
| [load_session(stream)](#load_session_stream_6) | Läs in sessionen från den angivna strömmen. |
| [load_session_from_stream(stream)](#load_session_from_stream_stream_7) | Läs in sessionen från den angivna strömmen. |


### Constructor: ImageMasking(source_image) {#ImageMasking_source_image_1}


```
 ImageMasking(source_image) 
```

Initialiserar en ny instans av klassen [ImageMasking](/imaging/python-net/aspose.imaging.masking/imagematching/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source_image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Källbilden. |

### Method: apply_mask(target_image, mask, masking_options)  [static] {#apply_mask_target_image_mask_masking_options_1}


```
 apply_mask(target_image, mask, masking_options) 
```

Applicerar masken på den angivna källbilden.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| target_image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Målbilden. |
| mask | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Maskbilden att applicera. |
| masking_options | [MaskingOptions](/imaging/python-net/aspose.imaging.masking.options/maskingoptions/) | Maskeringsalternativen. |

### Method: create_session(options) {#create_session_options_2}


```
 create_session(options) 
```

Skapar maskeringssessionen som kan utföra återträning av dekomponeringsoperationer.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| options | [MaskingOptions](/imaging/python-net/aspose.imaging.masking.options/maskingoptions/) | Alternativen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [IMaskingSession](/imaging/python-net/aspose.imaging.masking/imaskingsession/) | maskeringssessionen som kan utföra återträning av dekomponeringsoperationer. |


### Method: decompose(options) {#decompose_options_3}


```
 decompose(options) 
```

Utför dekomponeringsoperationen med angivna maskeringsalternativ

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| options | [MaskingOptions](/imaging/python-net/aspose.imaging.masking.options/maskingoptions/) | Maskeringsalternativen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [MaskingResult](/imaging/python-net/aspose.imaging.masking.result/maskingresult/) | Resultat av maskeringsoperation som en array av segmentbildsleverantörer. |


### Method: decompose_async(options) {#decompose_async_options_4}


```
 decompose_async(options) 
```

Skapar den asynkrona dekomponeringsuppgiften med angivna maskeringsalternativ.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| options | [MaskingOptions](/imaging/python-net/aspose.imaging.masking.options/maskingoptions/) | Maskeringsalternativen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [IMaskingAsyncTask](/imaging/python-net/aspose.imaging.masking/imaskingasynctask/) | Den asynkrona dekomponeringsuppgiften |


### Method: load_session(file_path) {#load_session_file_path_5}


```
 load_session(file_path) 
```

Läs in sessionen från den angivna filen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_path | string | Filsökvägen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [IMaskingSession](/imaging/python-net/aspose.imaging.masking/imaskingsession/) | maskeringssessionen som kan utföra återträning av dekomponeringsoperationer. |


### Method: load_session(stream) {#load_session_stream_6}


```
 load_session(stream) 
```

Läs in sessionen från den angivna strömmen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| ström | _io.BufferedRandom | Strömmen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [IMaskingSession](/imaging/python-net/aspose.imaging.masking/imaskingsession/) | maskeringssessionen som kan utföra återträning av dekomponeringsoperationer. |


### Method: load_session_from_stream(stream) {#load_session_from_stream_stream_7}


```
 load_session_from_stream(stream) 
```

Läs in sessionen från den angivna strömmen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| ström | _io.BufferedRandom | Strömmen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [IMaskingSession](/imaging/python-net/aspose.imaging.masking/imaskingsession/) | maskeringssessionen som kan utföra återträning av dekomponeringsoperationer. |


