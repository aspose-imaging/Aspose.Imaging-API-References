---
title: "ImageMasking Sınıfı"
type: docs
weight: 90
url: /tr/python-net/aspose.imaging.masking/imagemasking/
---

**Summary:** Provides image masking operations

**Module:** [aspose.imaging.masking](/imaging/python-net/aspose.imaging.masking/)

**Full Name:** aspose.imaging.masking.ImageMasking

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [ImageMasking(source_image)](#ImageMasking_source_image_1) | Yeni bir [ImageMasking](/imaging/python-net/aspose.imaging.masking/imagemasking/) sınıfı örneği başlatır. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [apply_mask(target_image, mask, masking_options)](#apply_mask_target_image_mask_masking_options_1) | Maske, belirtilen kaynak görüntüye uygulanır. |
| [create_session(options)](#create_session_options_2) | Yeniden eğitim ayrıştırma işlemlerini gerçekleştirebilen maskeleme oturumunu oluşturur. |
| [decompose(options)](#decompose_options_3) | Belirtilen maskeleme seçeneklerini kullanarak ayrıştırma işlemini gerçekleştirir |
| [decompose_async(options)](#decompose_async_options_4) | Belirtilen maskeleme seçeneklerini kullanarak asenkron ayrıştırma görevini oluşturur. |
| [load_session(file_path)](#load_session_file_path_5) | Oturumu belirtilen dosyadan yükle. |
| [load_session(stream)](#load_session_stream_6) | Oturumu belirtilen akıştan yükle. |
| [load_session_from_stream(stream)](#load_session_from_stream_stream_7) | Oturumu belirtilen akıştan yükle. |


### Constructor: ImageMasking(source_image) {#ImageMasking_source_image_1}


```
 ImageMasking(source_image) 
```

Yeni bir [ImageMasking](/imaging/python-net/aspose.imaging.masking/imagemasking/) sınıfı örneği başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| source_image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Kaynak görüntü. |

### Method: apply_mask(target_image, mask, masking_options)  [static] {#apply_mask_target_image_mask_masking_options_1}


```
 apply_mask(target_image, mask, masking_options) 
```

Maske, belirtilen kaynak görüntüye uygulanır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| target_image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Hedef görüntü. |
| mask | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Uygulanacak maske görüntüsü. |
| masking_options | [MaskingOptions](/imaging/python-net/aspose.imaging.masking.options/maskingoptions/) | Maskeleme seçenekleri. |

### Method: create_session(options) {#create_session_options_2}


```
 create_session(options) 
```

Yeniden eğitim ayrıştırma işlemlerini gerçekleştirebilen maskeleme oturumunu oluşturur.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| options | [MaskingOptions](/imaging/python-net/aspose.imaging.masking.options/maskingoptions/) | Seçenekler. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [IMaskingSession](/imaging/python-net/aspose.imaging.masking/imaskingsession/) | yeniden eğitim ayrıştırma işlemlerini gerçekleştirebilen maskeleme oturumu. |


### Method: decompose(options) {#decompose_options_3}


```
 decompose(options) 
```

Belirtilen maskeleme seçeneklerini kullanarak ayrıştırma işlemini gerçekleştirir

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| options | [MaskingOptions](/imaging/python-net/aspose.imaging.masking.options/maskingoptions/) | Maskeleme seçenekleri. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [MaskingResult](/imaging/python-net/aspose.imaging.masking.result/maskingresult/) | Maskeleme işleminin sonucu, segment görüntü sağlayıcıları dizisi olarak. |


### Method: decompose_async(options) {#decompose_async_options_4}


```
 decompose_async(options) 
```

Belirtilen maskeleme seçeneklerini kullanarak asenkron ayrıştırma görevini oluşturur.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| options | [MaskingOptions](/imaging/python-net/aspose.imaging.masking.options/maskingoptions/) | Maskeleme seçenekleri. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [IMaskingAsyncTask](/imaging/python-net/aspose.imaging.masking/imaskingasynctask/) | Asenkron ayrıştırma görevi |


### Method: load_session(file_path) {#load_session_file_path_5}


```
 load_session(file_path) 
```

Oturumu belirtilen dosyadan yükle.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| file_path | string | Dosya yolu. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [IMaskingSession](/imaging/python-net/aspose.imaging.masking/imaskingsession/) | yeniden eğitim ayrıştırma işlemlerini gerçekleştirebilen maskeleme oturumu. |


### Method: load_session(stream) {#load_session_stream_6}


```
 load_session(stream) 
```

Oturumu belirtilen akıştan yükle.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| akış | _io.BufferedRandom | Akış. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [IMaskingSession](/imaging/python-net/aspose.imaging.masking/imaskingsession/) | yeniden eğitim ayrıştırma işlemlerini gerçekleştirebilen maskeleme oturumu. |


### Method: load_session_from_stream(stream) {#load_session_from_stream_stream_7}


```
 load_session_from_stream(stream) 
```

Oturumu belirtilen akıştan yükle.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| akış | _io.BufferedRandom | Akış. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [IMaskingSession](/imaging/python-net/aspose.imaging.masking/imaskingsession/) | yeniden eğitim ayrıştırma işlemlerini gerçekleştirebilen maskeleme oturumu. |


