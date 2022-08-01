---
title: EmfHeaderExtension2
second_title: Aspose.Imaging para la referencia de la API de .NET
description: El objeto HeaderExtension2 define la segunda extensión del encabezado del metarchivo EMF. Agrega la capacidad para medir superficies de dispositivos en micrómetros lo que mejora la resolución y la escalabilidad de los metarchivos EMF.
type: docs
weight: 3000
url: /es/net/aspose.imaging.fileformats.emf.emf.objects/emfheaderextension2/
---
## EmfHeaderExtension2 class

El objeto HeaderExtension2 define la segunda extensión del encabezado del metarchivo EMF. Agrega la capacidad para medir superficies de dispositivos en micrómetros, lo que mejora la resolución y la escalabilidad de los metarchivos EMF.

```csharp
public sealed class EmfHeaderExtension2 : EmfHeaderObject
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [EmfHeaderExtension2](emfheaderextension2)() | Constructor predeterminado |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/bounds) { get; set; } | Obtiene o establece un objeto WMF RectL ([MS-WMF] sección 2.2.2.19) que especifica los límites inclusivo-inclusivo rectangular en unidades de dispositivo del rectángulo más pequeño que se puede dibujar alrededor de la imagen almacenada en el metarchivo |
| [Bytes](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/bytes) { get; set; } | Obtiene o establece un entero sin signo de 32 bits que especifica el tamaño del metarchivo, en bytes. |
| [Device](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/device) { get; set; } | Obtiene o establece un objeto WMF SizeL ([MS-WMF] sección 2.2.2.22) que especifica el tamaño del dispositivo de referencia, en píxeles |
| [Frame](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/frame) { get; set; } | Obtiene o establece un objeto WMF RectL que especifica las dimensiones rectangulares inclusivas, en unidades de 0,01 milímetros, de un rectángulo que rodea la imagen almacenada en el metarchivo |
| [Handles](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/handles) { get; set; } | Obtiene o establece un entero sin signo de 16 bits que especifica el número de objetos gráficos que se utilizarán durante el procesamiento del metarchivo |
| [MicrometersX](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderextension2/micrometersx) { get; set; } | Obtiene o establece el tamaño horizontal de 32 bits del dispositivo de visualización para el que se generó la imagen del metarchivo, en micrómetros |
| [MicrometersY](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderextension2/micrometersy) { get; set; } | Obtiene o establece el tamaño vertical de 32 bits del dispositivo de visualización para el que se generó la imagen del metarchivo, en micrómetros. |
| [Millimeters](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/millimeters) { get; set; } | Obtiene o establece un objeto WMF SizeL que especifica el tamaño del dispositivo de referencia, en milímetros |
| [NDesription](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/ndesription) { get; set; } | Obtiene o establece un entero sin signo de 32 bits que especifica el número de caracteres en la matriz que contiene la descripción del contenido del metarchivo. Esto es cero si no hay una cadena de descripción. |
| [NPalEntries](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/npalentries) { get; set; } | Obtiene o establece un entero sin signo de 32 bits que especifica el número de entradas en la paleta del metarchivo . La paleta se encuentra en el registro EMR_EOF |
| [OffDescription](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/offdescription) { get; set; } | Obtiene o establece un entero sin signo de 32 bits que especifica el desplazamiento desde el principio de este registro hasta la matriz que contiene la descripción del contenido del metarchivo |
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
