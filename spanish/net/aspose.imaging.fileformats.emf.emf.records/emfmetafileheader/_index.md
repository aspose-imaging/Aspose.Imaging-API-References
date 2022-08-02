---
title: EmfMetafileHeader
second_title: Aspose.Imaging para la referencia de la API de .NET
description: Los tipos de registro EMR_HEADER definen los puntos de partida de los metarchivos EMF y especifican las propiedades del dispositivo en el que se creó la imagen en el metarchivo . La información en el registro de encabezado hace posible que los metarchivos EMF sean independientes de cualquier dispositivo de salida específico. El valor del campo Tamaño se puede usar para distinguir entre los diferentes tipos de registro EMR_HEADER enumerados anteriormente en esta sección. Hay tres posibles headers El encabezado base que es el registro EmfMetafileHeader. La parte de tamaño fijo de este encabezado es de 88 bytes y contiene un objeto Header. El primer encabezado de extensión que es el registro EmfMetafileHeaderExtension1. El tamaño fijo parte de este encabezado tiene 100 bytes y contiene un objeto Header y un objeto HeaderExtension1 sección 2.2.10. El segundo encabezado de extensión que es el registro EmfMetafileHeaderExtension2. La parte de tamaño fijo de este encabezado es de 108 bytes y contiene un objeto Header un objeto HeaderExtension1 y un objeto HeaderExtension2 sección 2.2.11.
type: docs
weight: 3810
url: /es/net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/
---
## EmfMetafileHeader class

Los tipos de registro EMR_HEADER definen los puntos de partida de los metarchivos EMF y especifican las propiedades del dispositivo en el que se creó la imagen en el metarchivo . La información en el registro de encabezado hace posible que los metarchivos EMF sean independientes de cualquier dispositivo de salida específico. El valor del campo Tamaño se puede usar para distinguir entre los diferentes tipos de registro EMR_HEADER enumerados anteriormente en esta sección. Hay tres posibles headers: El encabezado base, que es el registro EmfMetafileHeader. La parte de tamaño fijo de este encabezado es de 88 bytes y contiene un objeto Header. El primer encabezado de extensión, que es el registro EmfMetafileHeaderExtension1. El tamaño fijo parte de este encabezado tiene 100 bytes y contiene un objeto Header y un objeto HeaderExtension1 (sección 2.2.10). El segundo encabezado de extensión, que es el registro EmfMetafileHeaderExtension2. La parte de tamaño fijo de este encabezado es de 108 bytes, y contiene un objeto Header, un objeto HeaderExtension1 y un objeto HeaderExtension2 (sección 2.2.11).

```csharp
public class EmfMetafileHeader : EmfRecord
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [EmfMetafileHeader](emfmetafileheader#constructor)() | Inicializa una nueva instancia del[`EmfMetafileHeader`](../emfmetafileheader) clase. |
| [EmfMetafileHeader](emfmetafileheader#constructor_1)(EmfMetafileHeader) | Inicializa una nueva instancia del[`EmfMetafileHeader`](../emfmetafileheader) clase. |
| [EmfMetafileHeader](emfmetafileheader#constructor_2)(EmfRecord) | Inicializa una nueva instancia del[`EmfMetafileHeader`](../emfmetafileheader) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [EmfDescription](../../aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/emfdescription) { get; set; } | Obtiene o establece la descripción EMF Una cadena opcional Unicode UTF16-LE terminada en nulo de longitud y contenido arbitrarios. Su ubicación en el registro y el número de caracteres se especifican mediante los campos offDescription y nDescription, respectivamente, en EmfHeader. Si el valor de cualquiera de los campos es cero, no hay una cadena de descripción presente. |
| [EmfDescriptionBuffer](../../aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/emfdescriptionbuffer) { get; set; } | Obtiene o establece la descripción de EMF buffer Una matriz opcional de bytes que contiene la cadena de descripción de EMF, que no es necesaria para ser contigua a la parte fija del registro EmfMetafileHeader . En consecuencia, el campo en este búfer que está etiquetado como "UndefinedSpace" es opcional y DEBE ignorarse. |
| [EmfHeader](../../aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/emfheader) { get; set; } | Obtiene o establece un objeto Header (sección 2.2.9), que contiene información sobre el contenido y la estructura del metarchivo |
| [EmfHeaderRecordBuffer](../../aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/emfheaderrecordbuffer) { get; set; } | Obtiene o establece una matriz opcional de bytes que contiene el resto del registro de encabezado EMF. El tamaño de este campo DEBE ser un múltiplo de 4 bytes |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size) { get; set; } | Obtiene o establece el tamaño del registro |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type) { get; set; } | Obtiene o establece el tipo. |

### Ver también

* class [EmfRecord](../emfrecord)
* espacio de nombres [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* asamblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
