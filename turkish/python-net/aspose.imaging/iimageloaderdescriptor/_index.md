---
title: "IImageLoaderDescriptor Sınıfı"
type: docs
weight: 5350
url: /tr/python-net/aspose.imaging/iimageloaderdescriptor/
---

**Summary:** The image loader descriptor specifying the loader properties. The loader descriptor is used to overcome<br/>            the necessity to contain each image loader instance in memory and multithreading issues.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.IImageLoaderDescriptor

## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [can_load(stream_container, load_options)](#can_load_stream_container_load_options_1) | Belirtilen akıştan yeni bir görüntüyü okuyup okuyamayacağını ve isteğe bağlı olarak _loadOptions_ kullanıp kullanmayacağını belirler. |
| [create_instance()](#create_instance__2) | Yeni bir yükleyici örneği oluşturur. |


### Method: can_load(stream_container, load_options) {#can_load_stream_container_load_options_1}


```
 can_load(stream_container, load_options) 
```

Belirtilen akıştan yeni bir görüntüyü okuyup okuyamayacağını ve isteğe bağlı olarak _loadOptions_ kullanıp kullanmayacağını belirler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| stream_container | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | Akış kapsayıcısı. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | _loadOptions_ tarafından belirtilen dosya formatı ayrıntıları. _loadOptions_ null olabilir. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | Bu tanımlayıcı tarafından oluşturulan görüntü yükleyicisi akıştan görüntü okuyabiliyorsa <c>true</c>; aksi takdirde <c>false</c>. |


### Method: create_instance() {#create_instance__2}


```
 create_instance() 
```

Yeni bir yükleyici örneği oluşturur.

**Returns**

| Tür | Açıklama |
| :- | :- |
| [IImageLoader](/imaging/python-net/aspose.imaging/iimageloader/) | Yeni bir yükleyici örneği. |


