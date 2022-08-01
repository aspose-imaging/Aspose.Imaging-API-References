---
title: EmfHeaderExtension1
second_title: Aspose.Imaging para la referencia de la API de .NET
description: El objeto HeaderExtension1 define la primera extensión del encabezado del metarchivo EMF. Agrega soporte para un objeto PixelFormatDescriptor sección 2.2.22 y registros OpenGL OPENGL sección 2.3.9.
type: docs
weight: 2990
url: /es/net/aspose.imaging.fileformats.emf.emf.objects/emfheaderextension1/
---
## EmfHeaderExtension1 class

El objeto HeaderExtension1 define la primera extensión del encabezado del metarchivo EMF. Agrega soporte para un objeto PixelFormatDescriptor (sección 2.2.22) y registros OpenGL [OPENGL] (sección 2.3.9).

```csharp
public sealed class EmfHeaderExtension1 : EmfHeaderObject
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [EmfHeaderExtension1](emfheaderextension1)() | Constructor predeterminado |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [BOpenGl](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderextension1/bopengl) { get; set; } | Obtiene o establece un entero sin signo de 32 bits que indica si los comandos de OpenGL están presentes en el metarchivo. 0x00000000 Los registros de OpenGL no están presentes en el metarchivo. 0x00000001 Los registros de OpenGL están presentes en el metarchivo. |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/bounds) { get; set; } | Obtiene o establece un objeto WMF RectL ([MS-WMF] sección 2.2.2.19) que especifica los límites inclusivo-inclusivo rectangular en unidades de dispositivo del rectángulo más pequeño que se puede dibujar alrededor de la imagen almacenada en el metarchivo |
| [Bytes](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/bytes) { get; set; } | Obtiene o establece un entero sin signo de 32 bits que especifica el tamaño del metarchivo, en bytes. |
| [CbPixelFormat](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderextension1/cbpixelformat) { get; set; } | Obtiene o establece un entero sin signo de 32 bits que especifica el tamaño del objeto PixelFormatDescriptor. DEBE ser 0x00000000 si no se establece ningún formato de píxel |
| [Device](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/device) { get; set; } | Obtiene o establece un objeto WMF SizeL ([MS-WMF] sección 2.2.2.22) que especifica el tamaño del dispositivo de referencia, en píxeles |
| [Frame](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/frame) { get; set; } | Obtiene o establece un objeto WMF RectL que especifica las dimensiones rectangulares inclusivas, en unidades de 0,01 milímetros, de un rectángulo que rodea la imagen almacenada en el metarchivo |
| [Handles](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/handles) { get; set; } | Obtiene o establece un entero sin signo de 16 bits que especifica el número de objetos gráficos que se utilizarán durante el procesamiento del metarchivo |
| [Millimeters](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/millimeters) { get; set; } | Obtiene o establece un objeto WMF SizeL que especifica el tamaño del dispositivo de referencia, en milímetros |
| [NDesription](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/ndesription) { get; set; } | Obtiene o establece un entero sin signo de 32 bits que especifica el número de caracteres en la matriz que contiene la descripción del contenido del metarchivo. Esto es cero si no hay una cadena de descripción. |
| [NPalEntries](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/npalentries) { get; set; } | Obtiene o establece un entero sin signo de 32 bits que especifica el número de entradas en la paleta del metarchivo . La paleta se encuentra en el registro EMR_EOF |
| [OffDescription](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/offdescription) { get; set; } | Obtiene o establece un entero sin signo de 32 bits que especifica el desplazamiento desde el principio de este registro hasta la matriz que contiene la descripción del contenido del metarchivo |
| [OffPixelFormat](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderextension1/offpixelformat) { get; set; } | Obtiene o establece un entero sin signo de 32 bits que especifica el desplazamiento del objeto PixelFormatDescriptor. DEBE ser 0x00000000 si no se establece ningún formato de píxel. |
| [Records](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/records) { get; set; } | Obtiene o establece un entero sin signo de 32 bits que especifica el número de registros en el metarchivo |
| [RecordSignature](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/recordsignature) { get; set; } | Obtiene o establece un entero sin signo de 32 bits que especifica la firma del registro. DEBE ser ENHMETA_SIGNATURE, de la enumeración FormatSignature (sección 2.1.14). |
| [Reserved](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/reserved) { get; set; } | Obtiene o establece un entero sin signo de 16 bits que DEBE ser 0x0000 y DEBE ignorarse |
| [Valid](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/valid) { get; } | Obtiene un valor que indica si este[`EmfHeaderObject`](../emfheaderobject)es válido. |
| [Version](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/version) { get; set; } | Obtiene o establece la versión (4 bytes): un entero sin signo de 32 bits que especifica la interoperabilidad del metarchivo EMF. Esto DEBE ser 0x00010000 |

### Ver también

* class [EmfHeaderObject](../emfheaderobject)
* espacio de nombres [Aspose.Imaging.FileFormats.Emf.Emf.Objects](../../aspose.imaging.fileformats.emf.emf.objects)
* asamblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
