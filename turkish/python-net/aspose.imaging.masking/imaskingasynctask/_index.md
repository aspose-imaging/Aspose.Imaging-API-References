---
title: "IMaskingAsyncTask Sınıfı"
type: docs
weight: 60
url: /tr/python-net/aspose.imaging.masking/imaskingasynctask/
---

**Summary:** Represents the masking async task.

**Module:** [aspose.imaging.masking](/imaging/python-net/aspose.imaging.masking/)

**Full Name:** aspose.imaging.masking.IMaskingAsyncTask

**Inheritance:** IAsyncTask

## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| is_busy | bool | r | Bu görevin şu anda çalışıp çalışmadığını gösteren bir değer döndürür. |
| is_canceled | bool | r | Bu görevin iptal edilip edilmediğini gösteren bir değer döndürür. |
| is_faulted | bool | r | Bu görevin hatalı olup olmadığını gösteren bir değer döndürür. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| abort() | Bu görevi iptal eder.<br/>            Görev hemen tamamlanır, dahili yönetilmeyen kaynakların serbest bırakılmama riski vardır. |
| cancel() | Bu görevi iptal eder.<br/>            Görev, algoritmanın kontrollü durdurulmasıyla güvenli bir şekilde tamamlanır. |
| [get_error()](#get_error__1) | Maskeleme işleminin bir hatasını döndürür |
| [get_masking_result()](#get_masking_result__2) | Maskeleme işleminin sonucunu döndürür |
| run_async() | Bu görevi çalıştırır. |
| wait_on_done() | Görev tamamlanana kadar bekler. |


### Method: get_error() {#get_error__1}


```
 get_error() 
```

Maskeleme işleminin bir hatasını döndürür

**Returns**

| Tür | Açıklama |
| :- | :- |
| string | Görev hatası. |


### Method: get_masking_result() {#get_masking_result__2}


```
 get_masking_result() 
```

Maskeleme işleminin sonucunu döndürür

**Returns**

| Tür | Açıklama |
| :- | :- |
| [MaskingResult](/imaging/python-net/aspose.imaging.masking.result/maskingresult/) | Bu görevin sonucu. |


