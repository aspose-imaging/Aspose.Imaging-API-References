---
title: "IImageExporterDescriptor Sınıfı"
type: docs
weight: 5330
url: /tr/python-net/aspose.imaging/iimageexporterdescriptor/
---

**Summary:** Represents the image exporter descriptor. The exporter descriptor is used to overcome the necessity to contain each exporter instance<br/>            in memory and multithreading issues.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.IImageExporterDescriptor

## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [can_export(image, options_base)](#can_export_image_options_base_1) | Görüntü dışa aktarıcının, kaydetme seçenekleriyle belirtilen görüntüyü belirtilen görüntü formatına dışa aktarabilip aktaramayacağını belirler. |
| [create_instance()](#create_instance__2) | Yeni bir dışa aktarıcı örneği oluşturur. |


### Method: can_export(image, options_base) {#can_export_image_options_base_1}


```
 can_export(image, options_base) 
```

Görüntü dışa aktarıcının, kaydetme seçenekleriyle belirtilen görüntüyü belirtilen görüntü formatına dışa aktarabilip aktaramayacağını belirler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Dışa aktarılacak görüntü. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Seçeneklerin temeli. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | <c>True</c> eğer bu tanımlayıcı tarafından oluşturulan dışa aktarıcı belirtilen görüntüyü belirtilen dosya formatına dışa aktarabiliyorsa; aksi takdirde <c>false</c>. |


### Method: create_instance() {#create_instance__2}


```
 create_instance() 
```

Yeni bir dışa aktarıcı örneği oluşturur.

**Returns**

| Tür | Açıklama |
| :- | :- |
| [IImageExporter](/imaging/python-net/aspose.imaging/iimageexporter/) | Yeni bir dışa aktarıcı örneği. |


