---
title: "Класс DicomImageInfo"
type: docs
weight: 30
url: /ru/python-net/aspose.imaging.fileformats.dicom/dicomimageinfo/
---

**Summary:** Contains all meta-information from Dicom file header

**Module:** [aspose.imaging.fileformats.dicom](/imaging/python-net/aspose.imaging.fileformats.dicom/)

**Full Name:** aspose.imaging.fileformats.dicom.DicomImageInfo

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bits_allocated | int | r | Получает значение "bitsAllocated". |
| bits_stored | int | r | Получает количество сохранённых бит. |
| blues | System.Byte | r | Получает массив цветов синего |
| dicom_header_info_by_bytes | System.Byte | r | Получает информацию заголовка DICOM по байтам. |
| dicom_info | System.Collections.Generic.IList`1[[System.String]] | r | Получает информацию заголовка DICOM-файла. |
| greens | System.Byte | r | Получает массив цветов зелёного |
| height | int | r | Получает высоту. |
| is_little_endian | bool | r | Получает значение, указывающее, является ли этот экземпляр little endian. |
| number_of_frames | int | r | Получает количество кадров. |
| offset | int | r | Получает смещение. |
| photo_interpretation | string | r | Получает значение "PhotoInterpretation". |
| pixel_representation | int | r | Получает значение пикселя "pixelRepresentation". |
| планарная_конфигурация | int | r | Получает планарную конфигурацию. |
| readonly_tags_list [static] | System.Collections.Generic.IList`1[[System.String]] | r | Список только для чтения тегов. Эти значения тегов будут сброшены в соответствии с фактическими данными изображения при сохранении изображения. |
| красные | System.Byte | r | Получает массив цветов красного |
| rescale_intercept | float | r | Получает значение "rescaleIntercept". |
| rescale_slope | float | r | Получает значение "rescaleSlope". |
| образцов_на_пиксель | int | r | Получает значение "samplesPerPixel". |
| signed_image | bool | r | Получает значение, указывающее, является ли "signedImage". |
| width | int | r | Получает ширину. |
| window_centre | float | r | Получает центр окна. |
| window_width | float | r | Получает ширину окна. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_tag(tag_description, value)](#add_tag_tag_description_value_1) | Добавить новый тег Dicom. |
| [remove_tag_at(index)](#remove_tag_at_index_2) | Удалить существующий тег. |
| [try_add_tag(tag_description, value)](#try_add_tag_tag_description_value_3) | Добавить новый тег Dicom. |
| [try_remove_tag_at(index)](#try_remove_tag_at_index_4) | Удалить существующий тег. |
| [try_update_tag_at(index, new_value)](#try_update_tag_at_index_new_value_5) | Обновить существующий тег. |
| [update_tag_at(index, new_value)](#update_tag_at_index_new_value_6) | Обновить существующий тег. |


### Method: add_tag(tag_description, value) {#add_tag_tag_description_value_1}


```
 add_tag(tag_description, value) 
```

Добавить новый тег Dicom.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| tag_description | string | Описание тега. Не может быть пустым или состоять только из пробелов. |
| значение | System.Object | Значение тега. Не может быть пустым. |

### Method: remove_tag_at(index) {#remove_tag_at_index_2}


```
 remove_tag_at(index) 
```

Удалить существующий тег.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| index | int | Индекс тега, который будет обновлен. |

### Method: try_add_tag(tag_description, value) {#try_add_tag_tag_description_value_3}


```
 try_add_tag(tag_description, value) 
```

Добавить новый тег Dicom.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| tag_description | string | Описание тега. Не может быть пустым или состоять только из пробелов. |
| значение | System.Object | Значение тега. Не может быть пустым. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | Результат операции. |


### Method: try_remove_tag_at(index) {#try_remove_tag_at_index_4}


```
 try_remove_tag_at(index) 
```

Удалить существующий тег.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| index | int | Индекс тега, который будет обновлен. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | Результат операции. |


### Method: try_update_tag_at(index, new_value) {#try_update_tag_at_index_new_value_5}


```
 try_update_tag_at(index, new_value) 
```

Обновить существующий тег.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| index | int | Индекс тега, который будет обновлен. |
| new_value | System.Object | Значение тега. Не может быть пустым. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | Результат операции. |


### Method: update_tag_at(index, new_value) {#update_tag_at_index_new_value_6}


```
 update_tag_at(index, new_value) 
```

Обновить существующий тег.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| index | int | Индекс тега, который будет обновлен. |
| new_value | System.Object | Значение тега. Не может быть пустым. |

