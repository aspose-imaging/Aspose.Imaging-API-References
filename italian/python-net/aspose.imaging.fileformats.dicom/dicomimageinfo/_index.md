---
title: "Classe DicomImageInfo"
type: docs
weight: 30
url: /it/python-net/aspose.imaging.fileformats.dicom/dicomimageinfo/
---

**Summary:** Contains all meta-information from Dicom file header

**Module:** [aspose.imaging.fileformats.dicom](/imaging/python-net/aspose.imaging.fileformats.dicom/)

**Full Name:** aspose.imaging.fileformats.dicom.DicomImageInfo

## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| bits_allocated | int | r | Ottiene un valore di "bitsAllocated". |
| bits_stored | int | r | Ottiene il numero di bit memorizzati. |
| blues | System.Byte | r | Ottiene i colori dell'array del blu |
| dicom_header_info_by_bytes | System.Byte | r | Ottiene le informazioni dell'intestazione DICOM per byte. |
| dicom_info | System.Collections.Generic.IList`1[[System.String]] | r | Ottiene le informazioni dell'intestazione del file DICOM. |
| greens | System.Byte | r | Ottiene i colori dell'array del verde. |
| height | int | r | Ottiene l'altezza. |
| is_little_endian | bool | r | Ottiene un valore che indica se questa istanza è little endian. |
| number_of_frames | int | r | Ottiene il numero di fotogrammi. |
| offset | int | r | Ottiene l'offset. |
| photo_interpretation | string | r | Ottiene un valore di "PhotoInterpretation". |
| pixel_representation | int | r | Ottiene un valore del pixel "pixelRepresentation". |
| configurazione_planare | int | r | Ottiene la configurazione planare. |
| readonly_tags_list [static] | System.Collections.Generic.IList`1[[System.String]] | r | L'elenco dei tag di sola lettura. Questi valori dei tag verranno reimpostati in base ai dati immagine effettivi al salvataggio dell'immagine. |
| rossi | System.Byte | r | Ottiene i colori dell'array del rosso |
| rescale_intercept | float | r | Ottiene un valore di "rescaleIntercept". |
| rescale_slope | float | r | Ottiene un valore di "rescaleSlope". |
| campioni_per_pixel | int | r | Ottiene un valore di "samplesPerPixel". |
| signed_image | bool | r | Ottiene un valore che indica se "signedImage". |
| width | int | r | Ottiene la larghezza. |
| window_centre | float | r | Ottiene il centro della finestra. |
| window_width | float | r | Ottiene la larghezza della finestra. |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [add_tag(tag_description, value)](#add_tag_tag_description_value_1) | Aggiungi un nuovo tag Dicom. |
| [remove_tag_at(index)](#remove_tag_at_index_2) | Rimuovi un tag esistente. |
| [try_add_tag(tag_description, value)](#try_add_tag_tag_description_value_3) | Aggiungi un nuovo tag Dicom. |
| [try_remove_tag_at(index)](#try_remove_tag_at_index_4) | Rimuovi un tag esistente. |
| [try_update_tag_at(index, new_value)](#try_update_tag_at_index_new_value_5) | Aggiorna un tag esistente. |
| [update_tag_at(index, new_value)](#update_tag_at_index_new_value_6) | Aggiorna un tag esistente. |


### Method: add_tag(tag_description, value) {#add_tag_tag_description_value_1}


```
 add_tag(tag_description, value) 
```

Aggiungi un nuovo tag Dicom.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| tag_description | string | La descrizione del tag. Non può essere nulla o vuota. |
| valore | System.Object | Il valore del tag. Non può essere nullo. |

### Method: remove_tag_at(index) {#remove_tag_at_index_2}


```
 remove_tag_at(index) 
```

Rimuovi un tag esistente.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| index | int | L'indice del tag da aggiornare. |

### Method: try_add_tag(tag_description, value) {#try_add_tag_tag_description_value_3}


```
 try_add_tag(tag_description, value) 
```

Aggiungi un nuovo tag Dicom.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| tag_description | string | La descrizione del tag. Non può essere nulla o vuota. |
| valore | System.Object | Il valore del tag. Non può essere nullo. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | Il risultato dell'operazione. |


### Method: try_remove_tag_at(index) {#try_remove_tag_at_index_4}


```
 try_remove_tag_at(index) 
```

Rimuovi un tag esistente.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| index | int | L'indice del tag da aggiornare. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | Il risultato dell'operazione. |


### Method: try_update_tag_at(index, new_value) {#try_update_tag_at_index_new_value_5}


```
 try_update_tag_at(index, new_value) 
```

Aggiorna un tag esistente.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| index | int | L'indice del tag da aggiornare. |
| new_value | System.Object | Il valore del tag. Non può essere nullo. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | Il risultato dell'operazione. |


### Method: update_tag_at(index, new_value) {#update_tag_at_index_new_value_6}


```
 update_tag_at(index, new_value) 
```

Aggiorna un tag esistente.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| index | int | L'indice del tag da aggiornare. |
| new_value | System.Object | Il valore del tag. Non può essere nullo. |

