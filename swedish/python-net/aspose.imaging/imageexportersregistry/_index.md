---
title: "ImageExportersRegistry klass"
type: docs
weight: 5700
url: /sv/python-net/aspose.imaging/imageexportersregistry/
---

**Summary:** Represents the image exporters registry.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.ImageExportersRegistry

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| registered_exporter_descriptors [static] | [IImageExporterDescriptor[]](/imaging/python-net/aspose.imaging/iimageexporterdescriptor/) | r | Hämtar de registrerade exportörbeskrivningarna. |
| registered_formats [static] | [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | r | Hämtar de registrerade exportformaten. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_first_supported_exporter(image, options)](#create_first_supported_exporter_image_options_1) | Skapar den första hittade exportören som är lämplig för de angivna sparalternativen och bilden. |
| [get_first_supported_descriptor(image, options)](#get_first_supported_descriptor_image_options_2) | Hämtar den första hittade stödjande beskrivningen som är lämplig för de angivna sparalternativen och bilden. |
| [register(image_exporter_descriptor)](#register_image_exporter_descriptor_3) | Registrerar den angivna bildexportörbeskrivningen. |
| [register_exporter(exporter_descriptor)](#register_exporter_exporter_descriptor_4) | Registrerar exportören. |
| [unregister_exporter(exporter_descriptor)](#unregister_exporter_exporter_descriptor_5) | Avregistrerar exportören. |


### Method: create_first_supported_exporter(image, options)  [static] {#create_first_supported_exporter_image_options_1}


```
 create_first_supported_exporter(image, options) 
```

Skapar den första hittade exportören som är lämplig för de angivna sparalternativen och bilden.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Bilden att exportera. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Sparalternativen att använda för export. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [IImageExporter](/imaging/python-net/aspose.imaging/iimageexporter/) | Exportören som stödjer den angivna bilden och sparalternativen eller null om ingen sådan exportör hittas. |


### Method: get_first_supported_descriptor(image, options)  [static] {#get_first_supported_descriptor_image_options_2}


```
 get_first_supported_descriptor(image, options) 
```

Hämtar den första hittade stödjande beskrivningen som är lämplig för de angivna sparalternativen och bilden.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Bilden att exportera. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Alternativen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [IImageExporterDescriptor](/imaging/python-net/aspose.imaging/iimageexporterdescriptor/) | Exportörbeskrivningen som stödjer den angivna bilden och sparalternativen eller null om ingen sådan beskrivning hittas. |


### Method: register(image_exporter_descriptor)  [static] {#register_image_exporter_descriptor_3}


```
 register(image_exporter_descriptor) 
```

Registrerar den angivna bildexportörbeskrivningen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| image_exporter_descriptor | [IImageExporterDescriptor](/imaging/python-net/aspose.imaging/iimageexporterdescriptor/) | Bildexportörbeskrivningen. |

### Method: register_exporter(exporter_descriptor)  [static] {#register_exporter_exporter_descriptor_4}


```
 register_exporter(exporter_descriptor) 
```

Registrerar exportören.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| exporter_descriptor | [IImageExporterDescriptor](/imaging/python-net/aspose.imaging/iimageexporterdescriptor/) | Exportörbeskrivningen att registrera. |

### Method: unregister_exporter(exporter_descriptor)  [static] {#unregister_exporter_exporter_descriptor_5}


```
 unregister_exporter(exporter_descriptor) 
```

Avregistrerar exportören.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| exporter_descriptor | [IImageExporterDescriptor](/imaging/python-net/aspose.imaging/iimageexporterdescriptor/) | Exportörbeskrivningen att avregistrera. |

