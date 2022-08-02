---
title: EmfPlusRestore
second_title: Aspose.Imaging para la referencia de la API de .NET
description: El registro EmfPlusRestore restaura el estado de los gráficos identificado por un índice específico a partir de una pila de estados de gráficos guardados.
type: docs
weight: 6230
url: /es/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrestore/
---
## EmfPlusRestore class

El registro EmfPlusRestore restaura el estado de los gráficos, identificado por un índice específico, a partir de una pila de estados de gráficos guardados.

```csharp
public sealed class EmfPlusRestore : EmfPlusStateRecordType
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [EmfPlusRestore](emfplusrestore)(EmfPlusRecord) | Inicializa una nueva instancia del[`EmfPlusRestore`](../emfplusrestore) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize) { get; set; } | Obtiene o establece un entero sin signo de 32 bits que DEBE definir el número alineado de 32 bits de bytes de datos en el campo RecordData que sigue. Este número no incluye el encabezado del registro de 12 bytes. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags) { get; set; } | Obtiene o establece un entero sin signo de 16 bits que contiene información para algunos registros sobre cómo se realizará la operación y sobre la estructura del registro. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size) { get; set; } | Obtiene o establece un entero sin signo de 32 bits que especifica el número alineado de 32 bits de bytes en todo el registro, incluido el encabezado del registro de 12 bytes y los datos específicos del registro. |
| [StackIndex](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrestore/stackindex) { get; set; } | Obtiene o establece un entero sin signo de 32 bits que especifica el nivel asociado con el estado de gráficos a . El valor del nivel fue asignado al estado de los gráficos por un registro anterior de EmfPlusSave (sección 2.3.7.5). |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type) { get; } | Obtiene un entero de 16 bits sin signo que identifica el tipo de registro. |

### Ver también

* class [EmfPlusStateRecordType](../emfplusstaterecordtype)
* espacio de nombres [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records)
* asamblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->