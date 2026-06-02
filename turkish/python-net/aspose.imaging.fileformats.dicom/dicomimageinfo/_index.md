---
title: "DicomImageInfo Sınıfı"
type: docs
weight: 30
url: /tr/python-net/aspose.imaging.fileformats.dicom/dicomimageinfo/
---

**Summary:** Contains all meta-information from Dicom file header

**Module:** [aspose.imaging.fileformats.dicom](/imaging/python-net/aspose.imaging.fileformats.dicom/)

**Full Name:** aspose.imaging.fileformats.dicom.DicomImageInfo

## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| bits_allocated | int | r | "bitsAllocated" değerini alır. |
| bits_stored | int | r | Depolanan bit sayısını alır. |
| blues | System.Byte | r | Mavi renk dizisini alır. |
| dicom_header_info_by_bytes | System.Byte | r | DICOM başlık bilgilerini bayt olarak alır. |
| dicom_info | System.Collections.Generic.IList`1[[System.String]] | r | DICOM dosyasının başlık bilgilerini alır. |
| greens | System.Byte | r | Yeşil renk dizisini alır. |
| height | int | r | yüksekliği alır. |
| is_little_endian | bool | r | Bu örneğin küçük endian olup olmadığını gösteren bir değer alır. |
| number_of_frames | int | r | Kare sayısını alır. |
| offset | int | r | Ofseti alır. |
| photo_interpretation | string | r | "PhotoInterpretation" değerini alır. |
| pixel_representation | int | r | Piksel "pixelRepresentation" değerini alır. |
| planar_configuration | int | r | Planar yapılandırmasını alır. |
| readonly_tags_list [static] | System.Collections.Generic.IList`1[[System.String]] | r | Salt okunur etiket listesi. Bu etiket değerleri, görüntü kaydedildiğinde gerçek görüntü verilerine göre sıfırlanacaktır. |
| kırmızılar | System.Byte | r | Kırmızı renk dizisini alır. |
| rescale_intercept | float | r | "rescaleIntercept" değerini alır. |
| rescale_slope | float | r | "rescaleSlope" değerini alır. |
| samples_per_pixel | int | r | "samplesPerPixel" değerini alır. |
| signed_image | bool | r | "signedImage" olup olmadığını belirten bir değer alır. |
| width | int | r | genişliği alır. |
| window_centre | float | r | Pencere merkezini alır. |
| window_width | float | r | Pencerenin genişliğini alır. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [add_tag(tag_description, value)](#add_tag_tag_description_value_1) | Yeni Dicom etiketi ekle. |
| [remove_tag_at(index)](#remove_tag_at_index_2) | Mevcut bir etiketi kaldır. |
| [try_add_tag(tag_description, value)](#try_add_tag_tag_description_value_3) | Yeni Dicom etiketi ekle. |
| [try_remove_tag_at(index)](#try_remove_tag_at_index_4) | Mevcut bir etiketi kaldır. |
| [try_update_tag_at(index, new_value)](#try_update_tag_at_index_new_value_5) | Mevcut bir etiketi güncelle. |
| [update_tag_at(index, new_value)](#update_tag_at_index_new_value_6) | Mevcut bir etiketi güncelle. |


### Method: add_tag(tag_description, value) {#add_tag_tag_description_value_1}


```
 add_tag(tag_description, value) 
```

Yeni Dicom etiketi ekle.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| tag_description | string | Etiket açıklaması. Boş veya yalnızca boşluk olamaz. |
| değer | System.Object | Etiket değeri. Boş olamaz. |

### Method: remove_tag_at(index) {#remove_tag_at_index_2}


```
 remove_tag_at(index) 
```

Mevcut bir etiketi kaldır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| index | int | Güncellenecek etiketin indeksi. |

### Method: try_add_tag(tag_description, value) {#try_add_tag_tag_description_value_3}


```
 try_add_tag(tag_description, value) 
```

Yeni Dicom etiketi ekle.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| tag_description | string | Etiket açıklaması. Boş veya yalnızca boşluk olamaz. |
| değer | System.Object | Etiket değeri. Boş olamaz. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | İşlem sonucu. |


### Method: try_remove_tag_at(index) {#try_remove_tag_at_index_4}


```
 try_remove_tag_at(index) 
```

Mevcut bir etiketi kaldır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| index | int | Güncellenecek etiketin indeksi. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | İşlem sonucu. |


### Method: try_update_tag_at(index, new_value) {#try_update_tag_at_index_new_value_5}


```
 try_update_tag_at(index, new_value) 
```

Mevcut bir etiketi güncelle.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| index | int | Güncellenecek etiketin indeksi. |
| new_value | System.Object | Etiket değeri. Boş olamaz. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | İşlem sonucu. |


### Method: update_tag_at(index, new_value) {#update_tag_at_index_new_value_6}


```
 update_tag_at(index, new_value) 
```

Mevcut bir etiketi güncelle.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| index | int | Güncellenecek etiketin indeksi. |
| new_value | System.Object | Etiket değeri. Boş olamaz. |

