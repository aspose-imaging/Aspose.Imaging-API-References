---
title: EmfPlusSetTextContrast
second_title: Aspose.Imaging para la referencia de la API de .NET
description: El registro EmfPlusSetTextContrast especifica el contraste del texto según el valor de corrección gamma.
type: docs
weight: 6380
url: /es/net/aspose.imaging.fileformats.emf.emfplus.records/emfplussettextcontrast/
---
## EmfPlusSetTextContrast class

El registro EmfPlusSetTextContrast especifica el contraste del texto según el valor de corrección gamma.

```csharp
public sealed class EmfPlusSetTextContrast : EmfPlusPropertyRecordType
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [EmfPlusSetTextContrast](emfplussettextcontrast)(EmfPlusRecord) | Inicializa una nueva instancia del[`EmfPlusSetTextContrast`](../emfplussettextcontrast) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize) { get; set; } | Obtiene o establece un entero sin signo de 32 bits que DEBE definir el número alineado de 32 bits de bytes de datos en el campo RecordData que sigue. Este número no incluye el encabezado del registro de 12 bytes. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags) { get; set; } | Obtiene o establece un entero sin signo de 16 bits que contiene información para algunos registros sobre cómo se realizará la operación y sobre la estructura del registro. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size) { get; set; } | Obtiene o establece un entero sin signo de 32 bits que especifica el número alineado de 32 bits de bytes en todo el registro, incluido el encabezado del registro de 12 bytes y los datos específicos del registro. |
| [TextContrast](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettextcontrast/textcontrast) { get; set; } | Obtiene o establece el valor de corrección gamma X 1000, que se aplicará a operaciones de representación de texto posteriores. El rango permitido es de 1000 a 2200, que representa valores gamma de texto de 1,0 a 2,2. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type) { get; } | Obtiene un entero de 16 bits sin signo que identifica el tipo de registro. |

### Ver también

* class [EmfPlusPropertyRecordType](../emfpluspropertyrecordtype)
* espacio de nombres [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records)
* asamblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->