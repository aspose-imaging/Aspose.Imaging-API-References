---
title: "Clase DicomImageInfo"
type: docs
weight: 30
url: /es/python-net/aspose.imaging.fileformats.dicom/dicomimageinfo/
---

**Summary:** Contains all meta-information from Dicom file header

**Module:** [aspose.imaging.fileformats.dicom](/imaging/python-net/aspose.imaging.fileformats.dicom/)

**Full Name:** aspose.imaging.fileformats.dicom.DicomImageInfo

## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| bits_allocated | int | r | Obtiene un valor de "bitsAllocated". |
| bits_stored | int | r | Obtiene el número de bits almacenados. |
| blues | System.Byte | r | Obtiene los colores del arreglo azul |
| dicom_header_info_by_bytes | System.Byte | r | Obtiene la información del encabezado DICOM por bytes. |
| dicom_info | System.Collections.Generic.IList`1[[System.String]] | r | Obtiene la información del encabezado del archivo DICOM. |
| greens | System.Byte | r | Obtiene los colores del arreglo verde. |
| height | int | r | Obtiene la altura. |
| is_little_endian | bool | r | Obtiene un valor que indica si esta instancia es little endian. |
| number_of_frames | int | r | Obtiene el número de fotogramas. |
| offset | int | r | Obtiene el desplazamiento. |
| photo_interpretation | string | r | Obtiene un valor de "PhotoInterpretation". |
| pixel_representation | int | r | Obtiene un valor del píxel "pixelRepresentation". |
| configuración_planar | int | r | Obtiene la configuración planar. |
| readonly_tags_list [static] | System.Collections.Generic.IList`1[[System.String]] | r | La lista de etiquetas de solo lectura. Estos valores de etiqueta se restablecerán según los datos reales de la imagen al guardar la imagen. |
| rojos | System.Byte | r | Obtiene los colores del arreglo rojo |
| rescale_intercept | float | r | Obtiene un valor de "rescaleIntercept". |
| rescale_slope | float | r | Obtiene un valor de "rescaleSlope". |
| muestras_por_píxel | int | r | Obtiene un valor de "samplesPerPixel". |
| signed_image | bool | r | Obtiene un valor que indica si "signedImage". |
| width | int | r | Obtiene el ancho. |
| window_centre | float | r | Obtiene el centro de la ventana. |
| window_width | float | r | Obtiene el ancho de la ventana. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [add_tag(tag_description, value)](#add_tag_tag_description_value_1) | Agregar una nueva etiqueta Dicom. |
| [remove_tag_at(index)](#remove_tag_at_index_2) | Eliminar una etiqueta existente. |
| [try_add_tag(tag_description, value)](#try_add_tag_tag_description_value_3) | Agregar una nueva etiqueta Dicom. |
| [try_remove_tag_at(index)](#try_remove_tag_at_index_4) | Eliminar una etiqueta existente. |
| [try_update_tag_at(index, new_value)](#try_update_tag_at_index_new_value_5) | Actualizar una etiqueta existente. |
| [update_tag_at(index, new_value)](#update_tag_at_index_new_value_6) | Actualizar una etiqueta existente. |


### Method: add_tag(tag_description, value) {#add_tag_tag_description_value_1}


```
 add_tag(tag_description, value) 
```

Agregar una nueva etiqueta Dicom.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| tag_description | string | La descripción de la etiqueta. No puede ser nula o estar vacía. |
| valor | System.Object | El valor de la etiqueta. No puede ser nulo. |

### Method: remove_tag_at(index) {#remove_tag_at_index_2}


```
 remove_tag_at(index) 
```

Eliminar una etiqueta existente.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| index | int | El índice de la etiqueta a actualizar. |

### Method: try_add_tag(tag_description, value) {#try_add_tag_tag_description_value_3}


```
 try_add_tag(tag_description, value) 
```

Agregar una nueva etiqueta Dicom.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| tag_description | string | La descripción de la etiqueta. No puede ser nula o estar vacía. |
| valor | System.Object | El valor de la etiqueta. No puede ser nulo. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | El resultado de la operación. |


### Method: try_remove_tag_at(index) {#try_remove_tag_at_index_4}


```
 try_remove_tag_at(index) 
```

Eliminar una etiqueta existente.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| index | int | El índice de la etiqueta a actualizar. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | El resultado de la operación. |


### Method: try_update_tag_at(index, new_value) {#try_update_tag_at_index_new_value_5}


```
 try_update_tag_at(index, new_value) 
```

Actualizar una etiqueta existente.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| index | int | El índice de la etiqueta a actualizar. |
| new_value | System.Object | El valor de la etiqueta. No puede ser nulo. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | El resultado de la operación. |


### Method: update_tag_at(index, new_value) {#update_tag_at_index_new_value_6}


```
 update_tag_at(index, new_value) 
```

Actualizar una etiqueta existente.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| index | int | El índice de la etiqueta a actualizar. |
| new_value | System.Object | El valor de la etiqueta. No puede ser nulo. |

