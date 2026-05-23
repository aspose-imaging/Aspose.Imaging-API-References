---
title: "ImageExportersRegistry Sınıfı"
type: docs
weight: 5700
url: /tr/python-net/aspose.imaging/imageexportersregistry/
---

**Summary:** Represents the image exporters registry.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.ImageExportersRegistry

## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| registered_exporter_descriptors [static] | [IImageExporterDescriptor[]](/imaging/python-net/aspose.imaging/iimageexporterdescriptor/) | r | Kayıtlı dışa aktarıcı tanımlayıcılarını alır. |
| registered_formats [static] | [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | r | Kayıtlı dışa aktarma formatlarını alır. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [create_first_supported_exporter(image, options)](#create_first_supported_exporter_image_options_1) | Belirtilen kaydetme seçenekleri ve görüntü için uygun olan ilk bulunan dışa aktarıcıyı oluşturur. |
| [get_first_supported_descriptor(image, options)](#get_first_supported_descriptor_image_options_2) | Belirtilen kaydetme seçenekleri ve görüntü için uygun olan ilk bulunan desteklenen tanımlayıcıyı alır. |
| [register(image_exporter_descriptor)](#register_image_exporter_descriptor_3) | Belirtilen görüntü dışa aktarıcı tanımlayıcısını kaydeder. |
| [register_exporter(exporter_descriptor)](#register_exporter_exporter_descriptor_4) | Dışa aktarıcıyı kaydeder. |
| [unregister_exporter(exporter_descriptor)](#unregister_exporter_exporter_descriptor_5) | Dışa aktarıcıyı kayıttan çıkarır. |


### Method: create_first_supported_exporter(image, options)  [static] {#create_first_supported_exporter_image_options_1}


```
 create_first_supported_exporter(image, options) 
```

Belirtilen kaydetme seçenekleri ve görüntü için uygun olan ilk bulunan dışa aktarıcıyı oluşturur.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Dışa aktarılacak görüntü. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Dışa aktarma için kullanılacak kaydetme seçenekleri. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [IImageExporter](/imaging/python-net/aspose.imaging/iimageexporter/) | Belirtilen görüntü ve kaydetme seçeneklerini destekleyen dışa aktarıcı veya böyle bir dışa aktarıcı bulunamazsa null. |


### Method: get_first_supported_descriptor(image, options)  [static] {#get_first_supported_descriptor_image_options_2}


```
 get_first_supported_descriptor(image, options) 
```

Belirtilen kaydetme seçenekleri ve görüntü için uygun olan ilk bulunan desteklenen tanımlayıcıyı alır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Dışa aktarılacak görüntü. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Seçenekler. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [IImageExporterDescriptor](/imaging/python-net/aspose.imaging/iimageexporterdescriptor/) | Belirtilen görüntü ve kaydetme seçeneklerini destekleyen dışa aktarıcı tanımlayıcısı veya böyle bir tanımlayıcı bulunamazsa null. |


### Method: register(image_exporter_descriptor)  [static] {#register_image_exporter_descriptor_3}


```
 register(image_exporter_descriptor) 
```

Belirtilen görüntü dışa aktarıcı tanımlayıcısını kaydeder.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| image_exporter_descriptor | [IImageExporterDescriptor](/imaging/python-net/aspose.imaging/iimageexporterdescriptor/) | Görüntü dışa aktarıcı tanımlayıcısı. |

### Method: register_exporter(exporter_descriptor)  [static] {#register_exporter_exporter_descriptor_4}


```
 register_exporter(exporter_descriptor) 
```

Dışa aktarıcıyı kaydeder.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| exporter_descriptor | [IImageExporterDescriptor](/imaging/python-net/aspose.imaging/iimageexporterdescriptor/) | Kaydedilecek dışa aktarıcı tanımlayıcısı. |

### Method: unregister_exporter(exporter_descriptor)  [static] {#unregister_exporter_exporter_descriptor_5}


```
 unregister_exporter(exporter_descriptor) 
```

Dışa aktarıcıyı kayıttan çıkarır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| exporter_descriptor | [IImageExporterDescriptor](/imaging/python-net/aspose.imaging/iimageexporterdescriptor/) | Kayıttan çıkarılacak dışa aktarıcı tanımlayıcısı. |

