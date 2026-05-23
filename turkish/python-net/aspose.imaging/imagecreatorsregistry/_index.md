---
title: "ImageCreatorsRegistry Sınıfı"
type: docs
weight: 5690
url: /tr/python-net/aspose.imaging/imagecreatorsregistry/
---

**Summary:** Represents the image creators registry.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.ImageCreatorsRegistry

## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| registered_descriptors [static] | [IImageCreatorDescriptor[]](/imaging/python-net/aspose.imaging/iimagecreatordescriptor/) | r | Kayıtlı tanımlayıcıları alır. |
| registered_formats [static] | [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | r | Kayıtlı görüntü oluşturma biçimlerini alır. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [create_first_supported_creator(image_options)](#create_first_supported_creator_image_options_1) | Belirtilen için uygun bulunan ilk oluşturucuyu oluşturur. |
| [get_first_supported_descriptor(image_options)](#get_first_supported_descriptor_image_options_2) | Belirtilen için uygun bulunan ilk desteklenen tanımlayıcıyı alır. |
| [register(image_creator_descriptor)](#register_image_creator_descriptor_3) | Belirtilen görüntü oluşturucu tanımlayıcısını kaydeder. |
| [register_creator(creator_descriptor)](#register_creator_creator_descriptor_4) | Oluşturucuyu kaydeder. |
| [unregister_creator(creator_descriptor)](#unregister_creator_creator_descriptor_5) | Oluşturucunun kaydını siler. |


### Method: create_first_supported_creator(image_options)  [static] {#create_first_supported_creator_image_options_1}


```
 create_first_supported_creator(image_options) 
```

Belirtilen için uygun bulunan ilk oluşturucuyu oluşturur.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Görüntü seçenekleri. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [IImageCreator](/imaging/python-net/aspose.imaging/iimagecreator/) | Belirtileni destekleyen oluşturucu; böyle bir oluşturucu bulunamazsa null. |


### Method: get_first_supported_descriptor(image_options)  [static] {#get_first_supported_descriptor_image_options_2}


```
 get_first_supported_descriptor(image_options) 
```

Belirtilen için uygun bulunan ilk desteklenen tanımlayıcıyı alır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Görüntü seçenekleri. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [IImageCreatorDescriptor](/imaging/python-net/aspose.imaging/iimagecreatordescriptor/) | Belirtileni destekleyen oluşturucu tanımlayıcısı; böyle bir tanımlayıcı bulunamazsa null. |


### Method: register(image_creator_descriptor)  [static] {#register_image_creator_descriptor_3}


```
 register(image_creator_descriptor) 
```

Belirtilen görüntü oluşturucu tanımlayıcısını kaydeder.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| image_creator_descriptor | [IImageCreatorDescriptor](/imaging/python-net/aspose.imaging/iimagecreatordescriptor/) | Görüntü oluşturucu tanımlayıcısı. |

### Method: register_creator(creator_descriptor)  [static] {#register_creator_creator_descriptor_4}


```
 register_creator(creator_descriptor) 
```

Oluşturucuyu kaydeder.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| creator_descriptor | [IImageCreatorDescriptor](/imaging/python-net/aspose.imaging/iimagecreatordescriptor/) | Kaydedilecek oluşturucu tanımlayıcısı. |

### Method: unregister_creator(creator_descriptor)  [static] {#unregister_creator_creator_descriptor_5}


```
 unregister_creator(creator_descriptor) 
```

Oluşturucunun kaydını siler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| creator_descriptor | [IImageCreatorDescriptor](/imaging/python-net/aspose.imaging/iimagecreatordescriptor/) | Oluşturucu tanımlayıcısı. |

