---
title: "IMaskingSession Sınıf"
type: docs
weight: 80
url: /tr/python-net/aspose.imaging.masking/imaskingsession/
---

**Summary:** The masking session

**Module:** [aspose.imaging.masking](/imaging/python-net/aspose.imaging.masking/)

**Full Name:** aspose.imaging.masking.IMaskingSession

## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [decompose()](#decompose__1) | İlk kaba ayrıştırma işlemini gerçekleştirir |
| [decompose_async()](#decompose_async__2) | İlk kaba ayrıştırma işlemini gerçekleştirebilen asenkron görevi oluşturur |
| [improve_decomposition(masking_arguments)](#improve_decomposition_masking_arguments_3) | Yeniden eğitim ayrıştırma işlemini gerçekleştirir |
| [improve_decomposition_async(masking_arguments)](#improve_decomposition_async_masking_arguments_4) | Yeniden eğitim ayrıştırma işlemini gerçekleştirebilen asenkron görevi oluşturur |
| [save(file_path)](#save_file_path_5) | Oturum durumunu belirtilen dosyaya kaydeder. |
| [save(stream)](#save_stream_6) | Oturum durumunu belirtilen akışa kaydedin. |


### Method: decompose() {#decompose__1}


```
 decompose() 
```

İlk kaba ayrıştırma işlemini gerçekleştirir

**Returns**

| Tür | Açıklama |
| :- | :- |
| [MaskingResult](/imaging/python-net/aspose.imaging.masking.result/maskingresult/) | Maskeleme işleminin sonucu, segment görüntü sağlayıcıları dizisi olarak. |


### Method: decompose_async() {#decompose_async__2}


```
 decompose_async() 
```

İlk kaba ayrıştırma işlemini gerçekleştirebilen asenkron görevi oluşturur

**Returns**

| Tür | Açıklama |
| :- | :- |
| [IMaskingAsyncTask](/imaging/python-net/aspose.imaging.masking/imaskingasynctask/) | Asenkron ayrıştırma görevi |


### Method: improve_decomposition(masking_arguments) {#improve_decomposition_masking_arguments_3}


```
 improve_decomposition(masking_arguments) 
```

Yeniden eğitim ayrıştırma işlemini gerçekleştirir

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| masking_arguments | [IMaskingArgs](/imaging/python-net/aspose.imaging.masking.options/imaskingargs/) | Maskeleme argümanları. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [MaskingResult](/imaging/python-net/aspose.imaging.masking.result/maskingresult/) | Maskeleme işleminin sonucu, segment görüntü sağlayıcıları dizisi olarak. |


### Method: improve_decomposition_async(masking_arguments) {#improve_decomposition_async_masking_arguments_4}


```
 improve_decomposition_async(masking_arguments) 
```

Yeniden eğitim ayrıştırma işlemini gerçekleştirebilen asenkron görevi oluşturur

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| masking_arguments | [IMaskingArgs](/imaging/python-net/aspose.imaging.masking.options/imaskingargs/) | Maskeleme argümanları. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [IMaskingAsyncTask](/imaging/python-net/aspose.imaging.masking/imaskingasynctask/) | Asenkron ayrıştırma görevi |


### Method: save(file_path) {#save_file_path_5}


```
 save(file_path) 
```

Oturum durumunu belirtilen dosyaya kaydeder.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| file_path | string | Dosya yolu. |

### Method: save(stream) {#save_stream_6}


```
 save(stream) 
```

Oturum durumunu belirtilen akışa kaydedin.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| akış | _io.BufferedRandom | Akış. |

