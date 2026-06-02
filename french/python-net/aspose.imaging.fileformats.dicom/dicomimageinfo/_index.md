---
title: "Classe DicomImageInfo"
type: docs
weight: 30
url: /fr/python-net/aspose.imaging.fileformats.dicom/dicomimageinfo/
---

**Summary:** Contains all meta-information from Dicom file header

**Module:** [aspose.imaging.fileformats.dicom](/imaging/python-net/aspose.imaging.fileformats.dicom/)

**Full Name:** aspose.imaging.fileformats.dicom.DicomImageInfo

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bits_allocated | int | r | Obtient une valeur de "bitsAllocated". |
| bits_stored | int | r | Obtient le nombre de bits stockés. |
| blues | System.Byte | r | Obtient le tableau des couleurs du bleu |
| dicom_header_info_by_bytes | System.Byte | r | Obtient les informations d'en-tête dicom par octets. |
| dicom_info | System.Collections.Generic.IList`1[[System.String]] | r | Obtient les informations d'en-tête du fichier DICOM. |
| greens | System.Byte | r | Obtient le tableau des couleurs du vert |
| height | int | r | Obtient la hauteur. |
| is_little_endian | bool | r | Obtient une valeur indiquant si cette instance est en little endian. |
| number_of_frames | int | r | Obtient le nombre de trames. |
| offset | int | r | Obtient le décalage. |
| photo_interpretation | string | r | Obtient une valeur de "PhotoInterpretation". |
| pixel_representation | int | r | Obtient une valeur du pixel "pixelRepresentation". |
| planar_configuration | int | r | Obtient la configuration planaire. |
| readonly_tags_list [static] | System.Collections.Generic.IList`1[[System.String]] | r | La liste des balises en lecture seule. Ces valeurs de balise seront réinitialisées en fonction des données réelles de l'image lors de l'enregistrement de l'image. |
| rouges | System.Byte | r | Obtient les couleurs du tableau rouge |
| rescale_intercept | float | r | Obtient une valeur de "rescaleIntercept". |
| rescale_slope | float | r | Obtient une valeur de "rescaleSlope". |
| samples_per_pixel | int | r | Obtient une valeur de "samplesPerPixel". |
| signed_image | bool | r | Obtient une valeur indiquant si "signedImage". |
| width | int | r | Obtient la largeur. |
| window_centre | float | r | Obtient le centre de la fenêtre. |
| window_width | float | r | Obtient la largeur de la fenêtre. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_tag(tag_description, value)](#add_tag_tag_description_value_1) | Ajouter une nouvelle balise Dicom. |
| [remove_tag_at(index)](#remove_tag_at_index_2) | Supprimer une balise existante. |
| [try_add_tag(tag_description, value)](#try_add_tag_tag_description_value_3) | Ajouter une nouvelle balise Dicom. |
| [try_remove_tag_at(index)](#try_remove_tag_at_index_4) | Supprimer une balise existante. |
| [try_update_tag_at(index, new_value)](#try_update_tag_at_index_new_value_5) | Mettre à jour une balise existante. |
| [update_tag_at(index, new_value)](#update_tag_at_index_new_value_6) | Mettre à jour une balise existante. |


### Method: add_tag(tag_description, value) {#add_tag_tag_description_value_1}


```
 add_tag(tag_description, value) 
```

Ajouter une nouvelle balise Dicom.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| tag_description | string | La description de la balise. Ne peut pas être nulle ou vide. |
| value | System.Object | La valeur de la balise. Ne peut pas être nulle. |

### Method: remove_tag_at(index) {#remove_tag_at_index_2}


```
 remove_tag_at(index) 
```

Supprimer une balise existante.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| index | int | L'index de la balise à mettre à jour. |

### Method: try_add_tag(tag_description, value) {#try_add_tag_tag_description_value_3}


```
 try_add_tag(tag_description, value) 
```

Ajouter une nouvelle balise Dicom.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| tag_description | string | La description de la balise. Ne peut pas être nulle ou vide. |
| value | System.Object | La valeur de la balise. Ne peut pas être nulle. |

**Returns**

| Type | Description |
| :- | :- |
| bool | Le résultat de l'opération. |


### Method: try_remove_tag_at(index) {#try_remove_tag_at_index_4}


```
 try_remove_tag_at(index) 
```

Supprimer une balise existante.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| index | int | L'index de la balise à mettre à jour. |

**Returns**

| Type | Description |
| :- | :- |
| bool | Le résultat de l'opération. |


### Method: try_update_tag_at(index, new_value) {#try_update_tag_at_index_new_value_5}


```
 try_update_tag_at(index, new_value) 
```

Mettre à jour une balise existante.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| index | int | L'index de la balise à mettre à jour. |
| new_value | System.Object | La valeur de la balise. Ne peut pas être nulle. |

**Returns**

| Type | Description |
| :- | :- |
| bool | Le résultat de l'opération. |


### Method: update_tag_at(index, new_value) {#update_tag_at_index_new_value_6}


```
 update_tag_at(index, new_value) 
```

Mettre à jour une balise existante.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| index | int | L'index de la balise à mettre à jour. |
| new_value | System.Object | La valeur de la balise. Ne peut pas être nulle. |

