---
title: "DicomImageInfo Klasse"
type: docs
weight: 30
url: /de/python-net/aspose.imaging.fileformats.dicom/dicomimageinfo/
---

**Summary:** Contains all meta-information from Dicom file header

**Module:** [aspose.imaging.fileformats.dicom](/imaging/python-net/aspose.imaging.fileformats.dicom/)

**Full Name:** aspose.imaging.fileformats.dicom.DicomImageInfo

## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| bits_allocated | int | r | Gibt einen Wert von "bitsAllocated". |
| bits_stored | int | r | Gibt die Anzahl der gespeicherten Bits zurück. |
| blues | System.Byte | r | Gibt die Array-Farben des Blau zurück. |
| dicom_header_info_by_bytes | System.Byte | r | Gibt die DICOM-Header-Informationen nach Bytes zurück. |
| dicom_info | System.Collections.Generic.IList`1[[System.String]] | r | Gibt die Header-Informationen der DICOM-Datei zurück. |
| greens | System.Byte | r | Gibt die Array-Farben des Grün zurück. |
| height | int | r | Liest die Höhe. |
| is_little_endian | bool | r | Gibt einen Wert zurück, der angibt, ob diese Instanz Little Endian ist. |
| number_of_frames | int | r | Gibt die Anzahl der Frames zurück. |
| offset | int | r | Gibt den Offset zurück. |
| photo_interpretation | string | r | Gibt einen Wert von "PhotoInterpretation" zurück. |
| pixel_representation | int | r | Gibt einen Wert des Pixels "pixelRepresentation" zurück. |
| planar_configuration | int | r | Gibt die planare Konfiguration zurück. |
| readonly_tags_list [static] | System.Collections.Generic.IList`1[[System.String]] | r | Die schreibgeschützte Tag-Liste. Diese Tag-Werte werden beim Speichern des Bildes gemäß den tatsächlichen Bilddaten zurückgesetzt. |
| Rottöne | System.Byte | r | Gibt die Array-Farben des Roten zurück. |
| rescale_intercept | float | r | Gibt einen Wert von "rescaleIntercept" zurück. |
| rescale_slope | float | r | Gibt einen Wert von "rescaleSlope" zurück. |
| samples_per_pixel | int | r | Gibt einen Wert von "samplesPerPixel" zurück. |
| signed_image | bool | r | Gibt einen Wert zurück, der angibt, ob "signedImage". |
| width | int | r | Liest die Breite. |
| window_centre | float | r | Gibt das Fensterzentrum zurück. |
| window_width | float | r | Gibt die Breite des Fensters zurück. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [add_tag(tag_description, value)](#add_tag_tag_description_value_1) | Neuen DICOM-Tag hinzufügen. |
| [remove_tag_at(index)](#remove_tag_at_index_2) | Einen vorhandenen Tag entfernen. |
| [try_add_tag(tag_description, value)](#try_add_tag_tag_description_value_3) | Neuen DICOM-Tag hinzufügen. |
| [try_remove_tag_at(index)](#try_remove_tag_at_index_4) | Einen vorhandenen Tag entfernen. |
| [try_update_tag_at(index, new_value)](#try_update_tag_at_index_new_value_5) | Einen vorhandenen Tag aktualisieren. |
| [update_tag_at(index, new_value)](#update_tag_at_index_new_value_6) | Einen vorhandenen Tag aktualisieren. |


### Method: add_tag(tag_description, value) {#add_tag_tag_description_value_1}


```
 add_tag(tag_description, value) 
```

Neuen DICOM-Tag hinzufügen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| tag_description | string | Die Tag-Beschreibung. Darf nicht null oder leer sein. |
| Wert | System.Object | Der Tag-Wert. Darf nicht null sein. |

### Method: remove_tag_at(index) {#remove_tag_at_index_2}


```
 remove_tag_at(index) 
```

Einen vorhandenen Tag entfernen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| index | int | Der Index des zu aktualisierenden Tags. |

### Method: try_add_tag(tag_description, value) {#try_add_tag_tag_description_value_3}


```
 try_add_tag(tag_description, value) 
```

Neuen DICOM-Tag hinzufügen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| tag_description | string | Die Tag-Beschreibung. Darf nicht null oder leer sein. |
| Wert | System.Object | Der Tag-Wert. Darf nicht null sein. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | Das Ergebnis der Operation. |


### Method: try_remove_tag_at(index) {#try_remove_tag_at_index_4}


```
 try_remove_tag_at(index) 
```

Einen vorhandenen Tag entfernen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| index | int | Der Index des zu aktualisierenden Tags. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | Das Ergebnis der Operation. |


### Method: try_update_tag_at(index, new_value) {#try_update_tag_at_index_new_value_5}


```
 try_update_tag_at(index, new_value) 
```

Einen vorhandenen Tag aktualisieren.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| index | int | Der Index des zu aktualisierenden Tags. |
| new_value | System.Object | Der Tag-Wert. Darf nicht null sein. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | Das Ergebnis der Operation. |


### Method: update_tag_at(index, new_value) {#update_tag_at_index_new_value_6}


```
 update_tag_at(index, new_value) 
```

Einen vorhandenen Tag aktualisieren.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| index | int | Der Index des zu aktualisierenden Tags. |
| new_value | System.Object | Der Tag-Wert. Darf nicht null sein. |

