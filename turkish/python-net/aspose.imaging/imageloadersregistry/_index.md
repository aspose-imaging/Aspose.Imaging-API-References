---
title: "ImageLoadersRegistry Sınıfı"
type: docs
weight: 5720
url: /tr/python-net/aspose.imaging/imageloadersregistry/
---

**Summary:** Represents the image loaders registry.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.ImageLoadersRegistry

## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| registered_descriptors [static] | [IImageLoaderDescriptor[]](/imaging/python-net/aspose.imaging/iimageloaderdescriptor/) | r | Kayıtlı tanımlayıcıları alır. |
| registered_formats [static] | [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | r | Kayıtlı görüntü yükleme biçimlerini alır. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [create_first_supported_loader(stream, load_options)](#create_first_supported_loader_stream_load_options_1) | Belirtilen _stream_ için uygun olan ilk bulunan yükleyiciyi oluşturur ve isteğe bağlı olarak _loadOptions_. |
| [get_first_supported_descriptor(stream, load_options)](#get_first_supported_descriptor_stream_load_options_2) | Belirtilen _stream_ için uygun olan ilk bulunan desteklenen tanımlayıcıyı alır ve isteğe bağlı olarak _loadOptions_. |
| [get_first_supported_descriptor_by_file_format(file_format)](#get_first_supported_descriptor_by_file_format_file_format_3) | Tür adıyla ilk desteklenen dosya biçimini alır. |
| [get_first_supported_descriptor_by_type_name(descriptor_type_name)](#get_first_supported_descriptor_by_type_name_descriptor_type_name_4) | Tür adıyla ilk desteklenen tanımlayıcıyı alır. |
| [register(image_loader_descriptor)](#register_image_loader_descriptor_5) | Belirtilen görüntü yükleyici tanımlayıcısını kaydeder. |
| [register_loader(loader_descriptor)](#register_loader_loader_descriptor_6) | Yükleyiciyi kaydeder. |
| [unregister_loader(loader_descriptor)](#unregister_loader_loader_descriptor_7) | Yükleyicinin kaydını kaldırır. |


### Method: create_first_supported_loader(stream, load_options)  [static] {#create_first_supported_loader_stream_load_options_1}


```
 create_first_supported_loader(stream, load_options) 
```

Belirtilen _stream_ için uygun olan ilk bulunan yükleyiciyi oluşturur ve isteğe bağlı olarak _loadOptions_.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| akış | _io.BufferedRandom | Akış. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | Yükleme seçenekleri. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [IImageLoader](/imaging/python-net/aspose.imaging/iimageloader/) | Belirtilen _stream_ ve _loadOptions_ destekleyen yükleyici veya böyle bir yükleyici bulunamazsa null. |


### Method: get_first_supported_descriptor(stream, load_options)  [static] {#get_first_supported_descriptor_stream_load_options_2}


```
 get_first_supported_descriptor(stream, load_options) 
```

Belirtilen _stream_ için uygun olan ilk bulunan desteklenen tanımlayıcıyı alır ve isteğe bağlı olarak _loadOptions_.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| akış | _io.BufferedRandom | Akış. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | Yükleme seçenekleri. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [IImageLoaderDescriptor](/imaging/python-net/aspose.imaging/iimageloaderdescriptor/) | Belirtilen _stream_ ve _loadOptions_ destekleyen yükleyici tanımlayıcısı veya böyle bir tanımlayıcı bulunamazsa null. |


### Method: get_first_supported_descriptor_by_file_format(file_format)  [static] {#get_first_supported_descriptor_by_file_format_file_format_3}


```
 get_first_supported_descriptor_by_file_format(file_format) 
```

Tür adıyla ilk desteklenen dosya biçimini alır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| file_format | [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | Desteklenen tanımlayıcı dosya biçimi. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [IImageLoaderDescriptor](/imaging/python-net/aspose.imaging/iimageloaderdescriptor/) | İlk bulunan yükleyici tanımlayıcısı veya böyle bir tanımlayıcı bulunamazsa null. |


### Method: get_first_supported_descriptor_by_type_name(descriptor_type_name)  [static] {#get_first_supported_descriptor_by_type_name_descriptor_type_name_4}


```
 get_first_supported_descriptor_by_type_name(descriptor_type_name) 
```

Tür adıyla ilk desteklenen tanımlayıcıyı alır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| descriptor_type_name | string | Tanımlayıcı tür adı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [IImageLoaderDescriptor](/imaging/python-net/aspose.imaging/iimageloaderdescriptor/) | İlk bulunan yükleyici tanımlayıcısı veya böyle bir tanımlayıcı bulunamazsa null. |


### Method: register(image_loader_descriptor)  [static] {#register_image_loader_descriptor_5}


```
 register(image_loader_descriptor) 
```

Belirtilen görüntü yükleyici tanımlayıcısını kaydeder.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| image_loader_descriptor | [IImageLoaderDescriptor](/imaging/python-net/aspose.imaging/iimageloaderdescriptor/) | Görüntü yükleyici tanımlayıcısı. |

### Method: register_loader(loader_descriptor)  [static] {#register_loader_loader_descriptor_6}


```
 register_loader(loader_descriptor) 
```

Yükleyiciyi kaydeder.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| loader_descriptor | [IImageLoaderDescriptor](/imaging/python-net/aspose.imaging/iimageloaderdescriptor/) | Kaydedilecek yükleyici tanımlayıcısı. |

### Method: unregister_loader(loader_descriptor)  [static] {#unregister_loader_loader_descriptor_7}


```
 unregister_loader(loader_descriptor) 
```

Yükleyicinin kaydını kaldırır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| loader_descriptor | [IImageLoaderDescriptor](/imaging/python-net/aspose.imaging/iimageloaderdescriptor/) | Kaydı kaldırılacak yükleyici tanımlayıcısı. |

