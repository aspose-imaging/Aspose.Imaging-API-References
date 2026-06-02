---
title: "DicomImageInfo-klass"
type: docs
weight: 30
url: /sv/python-net/aspose.imaging.fileformats.dicom/dicomimageinfo/
---

**Summary:** Contains all meta-information from Dicom file header

**Module:** [aspose.imaging.fileformats.dicom](/imaging/python-net/aspose.imaging.fileformats.dicom/)

**Full Name:** aspose.imaging.fileformats.dicom.DicomImageInfo

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bits_allocated | int | r | Hämtar ett värde för "bitsAllocated". |
| bits_stored | int | r | Hämtar antalet lagrade bitar. |
| blues | System.Byte | r | Hämtar färgarrayen för blått. |
| dicom_header_info_by_bytes | System.Byte | r | Hämtar DICOM-huvudinformationsdata per byte. |
| dicom_info | System.Collections.Generic.IList`1[[System.String]] | r | Hämtar huvudinformationen för DICOM-filen. |
| greens | System.Byte | r | Hämtar färgarrayen för grönt. |
| height | int | r | Hämtar höjden. |
| is_little_endian | bool | r | Hämtar ett värde som indikerar om denna instans är little endian. |
| number_of_frames | int | r | Hämtar antalet bildrutor. |
| offset | int | r | Hämtar förskjutningen. |
| photo_interpretation | string | r | Hämtar ett värde för "PhotoInterpretation". |
| pixel_representation | int | r | Hämtar ett värde för pixelen "pixelRepresentation". |
| planar_configuration | int | r | Hämtar den plana konfigurationen. |
| readonly_tags_list [static] | System.Collections.Generic.IList`1[[System.String]] | r | Den skrivskyddade tagglistan. Dessa taggvärden kommer att återställas enligt den faktiska bilddata vid bildsparning. |
| röda | System.Byte | r | Hämtar arrayens färger för röd |
| rescale_intercept | float | r | Hämtar ett värde för "rescaleIntercept". |
| rescale_slope | float | r | Hämtar ett värde för "rescaleSlope". |
| samples_per_pixel | int | r | Hämtar ett värde för "samplesPerPixel". |
| signed_image | bool | r | Hämtar ett värde som indikerar om "signedImage". |
| width | int | r | Hämtar bredden. |
| window_centre | float | r | Hämtar fönstrets centrum. |
| window_width | float | r | Hämtar fönstrets bredd. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_tag(tag_description, value)](#add_tag_tag_description_value_1) | Lägg till ny Dicom-tag. |
| [remove_tag_at(index)](#remove_tag_at_index_2) | Ta bort en befintlig tagg. |
| [try_add_tag(tag_description, value)](#try_add_tag_tag_description_value_3) | Lägg till ny Dicom-tag. |
| [try_remove_tag_at(index)](#try_remove_tag_at_index_4) | Ta bort en befintlig tagg. |
| [try_update_tag_at(index, new_value)](#try_update_tag_at_index_new_value_5) | Uppdatera en befintlig tagg. |
| [update_tag_at(index, new_value)](#update_tag_at_index_new_value_6) | Uppdatera en befintlig tagg. |


### Method: add_tag(tag_description, value) {#add_tag_tag_description_value_1}


```
 add_tag(tag_description, value) 
```

Lägg till ny Dicom-tag.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| tag_description | string | Taggbeskrivningen. Får inte vara null eller tom. |
| värde | System.Object | Taggvärdet. Får inte vara null. |

### Method: remove_tag_at(index) {#remove_tag_at_index_2}


```
 remove_tag_at(index) 
```

Ta bort en befintlig tagg.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| index | int | Indexet för taggen som ska uppdateras. |

### Method: try_add_tag(tag_description, value) {#try_add_tag_tag_description_value_3}


```
 try_add_tag(tag_description, value) 
```

Lägg till ny Dicom-tag.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| tag_description | string | Taggbeskrivningen. Får inte vara null eller tom. |
| värde | System.Object | Taggvärdet. Får inte vara null. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | Resultatet av operationen. |


### Method: try_remove_tag_at(index) {#try_remove_tag_at_index_4}


```
 try_remove_tag_at(index) 
```

Ta bort en befintlig tagg.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| index | int | Indexet för taggen som ska uppdateras. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | Resultatet av operationen. |


### Method: try_update_tag_at(index, new_value) {#try_update_tag_at_index_new_value_5}


```
 try_update_tag_at(index, new_value) 
```

Uppdatera en befintlig tagg.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| index | int | Indexet för taggen som ska uppdateras. |
| new_value | System.Object | Taggvärdet. Får inte vara null. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | Resultatet av operationen. |


### Method: update_tag_at(index, new_value) {#update_tag_at_index_new_value_6}


```
 update_tag_at(index, new_value) 
```

Uppdatera en befintlig tagg.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| index | int | Indexet för taggen som ska uppdateras. |
| new_value | System.Object | Taggvärdet. Får inte vara null. |

