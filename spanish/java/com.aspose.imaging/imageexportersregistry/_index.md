---
title: "ImageExportersRegistry"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Representa el registro de exportadores de imágenes."
type: docs
weight: 59
url: /es/java/com.aspose.imaging/imageexportersregistry/
---
**Inheritance:**
java.lang.Object
```
public final class ImageExportersRegistry
```

Representa el registro de exportadores de imágenes.
## Métodos

| Método | Descripción |
| --- | --- |
| [getRegisteredFormats()](#getRegisteredFormats--) | Obtiene los formatos de exportación registrados. |
| [getRegisteredExporterDescriptors()](#getRegisteredExporterDescriptors--) | Obtiene los descriptores de exportador registrados. |
| [register(IImageExporterDescriptor exporterDescriptor)](#register-com.aspose.imaging.IImageExporterDescriptor-) | Registra el descriptor de exportador de imagen especificado. |
| [getFirstSupportedDescriptor(Image image, ImageOptionsBase options)](#getFirstSupportedDescriptor-com.aspose.imaging.Image-com.aspose.imaging.ImageOptionsBase-) | Obtiene el primer descriptor compatible encontrado adecuado para las opciones de guardado e imagen especificadas. |
| [createFirstSupportedExporter(Image image, ImageOptionsBase options)](#createFirstSupportedExporter-com.aspose.imaging.Image-com.aspose.imaging.ImageOptionsBase-) | Crea el primer exportador encontrado adecuado para las opciones de guardado e imagen especificadas. |
| [registerExporter(IImageExporterDescriptor exporterDescriptor)](#registerExporter-com.aspose.imaging.IImageExporterDescriptor-) | Registra el exportador. |
| [unregisterExporter(IImageExporterDescriptor exporterDescriptor)](#unregisterExporter-com.aspose.imaging.IImageExporterDescriptor-) | Anula el registro del exportador. |
### getRegisteredFormats() {#getRegisteredFormats--}
```
public static long getRegisteredFormats()
```


Obtiene los formatos de exportación registrados.

Valor: Los formatos de exportación registrados.

**Returns:**
long
### getRegisteredExporterDescriptors() {#getRegisteredExporterDescriptors--}
```
public static IImageExporterDescriptor[] getRegisteredExporterDescriptors()
```


Obtiene los descriptores de exportador registrados.

Valor: Los descriptores de exportador registrados.

**Returns:**
com.aspose.imaging.IImageExporterDescriptor[]
### register(IImageExporterDescriptor exporterDescriptor) {#register-com.aspose.imaging.IImageExporterDescriptor-}
```
public static void register(IImageExporterDescriptor exporterDescriptor)
```


Registra el descriptor de exportador de imagen especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| exporterDescriptor | [IImageExporterDescriptor](../../com.aspose.imaging/iimageexporterdescriptor) | El descriptor del exportador de imagen. |

### getFirstSupportedDescriptor(Image image, ImageOptionsBase options) {#getFirstSupportedDescriptor-com.aspose.imaging.Image-com.aspose.imaging.ImageOptionsBase-}
```
public static IImageExporterDescriptor getFirstSupportedDescriptor(Image image, ImageOptionsBase options)
```


Obtiene el primer descriptor compatible encontrado adecuado para las opciones de guardado e imagen especificadas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | La imagen a exportar. |
|  | options | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | Las opciones. |

El primer descriptor de exportador será en realidad el último registrado. |

**Returns:**
[IImageExporterDescriptor](../../com.aspose.imaging/iimageexporterdescriptor) - The exporter descriptor which supports the specified image and save options or null if no such descriptor is found.
### createFirstSupportedExporter(Image image, ImageOptionsBase options) {#createFirstSupportedExporter-com.aspose.imaging.Image-com.aspose.imaging.ImageOptionsBase-}
```
public static IImageExporter createFirstSupportedExporter(Image image, ImageOptionsBase options)
```


Crea el primer exportador encontrado adecuado para las opciones de guardado e imagen especificadas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | La imagen a exportar. |
|  | options | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | Las opciones de guardado a usar para la exportación. |

El primer exportador será en realidad el último registrado. |

**Returns:**
[IImageExporter](../../com.aspose.imaging/iimageexporter) - The exporter which supports the specified image and save options or null if no such exporter is found.
### registerExporter(IImageExporterDescriptor exporterDescriptor) {#registerExporter-com.aspose.imaging.IImageExporterDescriptor-}
```
public static void registerExporter(IImageExporterDescriptor exporterDescriptor)
```


Registra el exportador.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| exporterDescriptor | [IImageExporterDescriptor](../../com.aspose.imaging/iimageexporterdescriptor) | El descriptor del exportador a registrar. |

### unregisterExporter(IImageExporterDescriptor exporterDescriptor) {#unregisterExporter-com.aspose.imaging.IImageExporterDescriptor-}
```
public static void unregisterExporter(IImageExporterDescriptor exporterDescriptor)
```


Anula el registro del exportador.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| exporterDescriptor | [IImageExporterDescriptor](../../com.aspose.imaging/iimageexporterdescriptor) | El descriptor del exportador a desregistrar. |

