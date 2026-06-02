---
title: "ImageExportersRegistry Clase"
type: docs
weight: 5700
url: /es/python-net/aspose.imaging/imageexportersregistry/
---

**Summary:** Represents the image exporters registry.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.ImageExportersRegistry

## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| registered_exporter_descriptors [static] | [IImageExporterDescriptor[]](/imaging/python-net/aspose.imaging/iimageexporterdescriptor/) | r | Obtiene los descriptores de exportador registrados. |
| registered_formats [static] | [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | r | Obtiene los formatos de exportación registrados. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [create_first_supported_exporter(image, options)](#create_first_supported_exporter_image_options_1) | Crea el primer exportador encontrado que sea adecuado para las opciones de guardado y la imagen especificadas. |
| [get_first_supported_descriptor(image, options)](#get_first_supported_descriptor_image_options_2) | Obtiene el primer descriptor compatible encontrado que sea adecuado para las opciones de guardado y la imagen especificadas. |
| [register(image_exporter_descriptor)](#register_image_exporter_descriptor_3) | Registra el descriptor de exportador de imagen especificado. |
| [register_exporter(exporter_descriptor)](#register_exporter_exporter_descriptor_4) | Registra el exportador. |
| [unregister_exporter(exporter_descriptor)](#unregister_exporter_exporter_descriptor_5) | Desregistra el exportador. |


### Method: create_first_supported_exporter(image, options)  [static] {#create_first_supported_exporter_image_options_1}


```
 create_first_supported_exporter(image, options) 
```

Crea el primer exportador encontrado que sea adecuado para las opciones de guardado y la imagen especificadas.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | La imagen a exportar. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Las opciones de guardado a usar para la exportación. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [IImageExporter](/imaging/python-net/aspose.imaging/iimageexporter/) | El exportador que soporta la imagen y las opciones de guardado especificadas o null si no se encuentra tal exportador. |


### Method: get_first_supported_descriptor(image, options)  [static] {#get_first_supported_descriptor_image_options_2}


```
 get_first_supported_descriptor(image, options) 
```

Obtiene el primer descriptor compatible encontrado que sea adecuado para las opciones de guardado y la imagen especificadas.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | La imagen a exportar. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Las opciones. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [IImageExporterDescriptor](/imaging/python-net/aspose.imaging/iimageexporterdescriptor/) | El descriptor de exportador que soporta la imagen y las opciones de guardado especificadas o null si no se encuentra tal descriptor. |


### Method: register(image_exporter_descriptor)  [static] {#register_image_exporter_descriptor_3}


```
 register(image_exporter_descriptor) 
```

Registra el descriptor de exportador de imagen especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| image_exporter_descriptor | [IImageExporterDescriptor](/imaging/python-net/aspose.imaging/iimageexporterdescriptor/) | El descriptor de exportador de imagen. |

### Method: register_exporter(exporter_descriptor)  [static] {#register_exporter_exporter_descriptor_4}


```
 register_exporter(exporter_descriptor) 
```

Registra el exportador.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| exporter_descriptor | [IImageExporterDescriptor](/imaging/python-net/aspose.imaging/iimageexporterdescriptor/) | El descriptor de exportador a registrar. |

### Method: unregister_exporter(exporter_descriptor)  [static] {#unregister_exporter_exporter_descriptor_5}


```
 unregister_exporter(exporter_descriptor) 
```

Desregistra el exportador.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| exporter_descriptor | [IImageExporterDescriptor](/imaging/python-net/aspose.imaging/iimageexporterdescriptor/) | El descriptor de exportador a desregistrar. |

