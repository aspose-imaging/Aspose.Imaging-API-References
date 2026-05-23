---
title: "IImageCreatorDescriptor Sınıf"
type: docs
weight: 5300
url: /tr/python-net/aspose.imaging/iimagecreatordescriptor/
---

**Summary:** The image creator descriptor specifying the creator properties. The creator descriptor is used to overcome<br/>            the necessity to contain each image creator instance in memory and multithreading issues.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.IImageCreatorDescriptor

## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [can_create(image_options)](#can_create_image_options_1) | Görüntü oluşturucunun _imageOptions_ kullanarak yeni bir görüntü oluşturup oluşturamayacağını belirler. |
| [create_instance()](#create_instance__2) | Yeni bir oluşturucu örneği oluşturur. |


### Method: can_create(image_options) {#can_create_image_options_1}


```
 can_create(image_options) 
```

Görüntü oluşturucunun _imageOptions_ kullanarak yeni bir görüntü oluşturup oluşturamayacağını belirler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Görüntü seçenekleri. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | <c>True</c> eğer bu tanımlayıcı tarafından oluşturulan görüntü oluşturucu belirtilen _imageOptions_ kullanarak görüntü verisi oluşturabiliyorsa; aksi takdirde <c>false</c>. |


### Method: create_instance() {#create_instance__2}


```
 create_instance() 
```

Yeni bir oluşturucu örneği oluşturur.

**Returns**

| Tür | Açıklama |
| :- | :- |
| [IImageCreator](/imaging/python-net/aspose.imaging/iimagecreator/) | Yeni bir oluşturucu örneği. |


