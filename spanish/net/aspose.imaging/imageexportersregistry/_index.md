---
title: ImageExportersRegistry
second_title: Aspose.Imaging para la referencia de la API de .NET
description: Representa el registro de exportadores de imágenes.
type: docs
weight: 9700
url: /es/net/aspose.imaging/imageexportersregistry/
---
## ImageExportersRegistry class

Representa el registro de exportadores de imágenes.

```csharp
public static class ImageExportersRegistry
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| static [RegisteredExporterDescriptors](../../aspose.imaging/imageexportersregistry/registeredexporterdescriptors) { get; } | Obtiene los descriptores del exportador registrado. |
| static [RegisteredFormats](../../aspose.imaging/imageexportersregistry/registeredformats) { get; } | Obtiene los formatos de exportación registrados. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [CreateFirstSupportedExporter](../../aspose.imaging/imageexportersregistry/createfirstsupportedexporter)(Image, ImageOptionsBase) | Crea el primer exportador encontrado adecuado para las opciones de guardado y la imagen especificados. |
| static [GetFirstSupportedDescriptor](../../aspose.imaging/imageexportersregistry/getfirstsupporteddescriptor)(Image, ImageOptionsBase) | Obtiene el primer descriptor admitido adecuado para las opciones de guardado y la imagen especificados. |
| static [Register](../../aspose.imaging/imageexportersregistry/register)(IImageExporterDescriptor) | Registra el descriptor del exportador de imágenes especificado. |
| static [RegisterExporter](../../aspose.imaging/imageexportersregistry/registerexporter)(IImageExporterDescriptor) | Da de alta al exportador. |
| static [UnregisterExporter](../../aspose.imaging/imageexportersregistry/unregisterexporter)(IImageExporterDescriptor) | Da de baja al exportador. |

### Ver también

* espacio de nombres [Aspose.Imaging](../../aspose.imaging)
* asamblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
