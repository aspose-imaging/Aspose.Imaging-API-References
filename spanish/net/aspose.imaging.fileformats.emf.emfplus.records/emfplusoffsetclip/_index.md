---
title: EmfPlusOffsetClip
second_title: Aspose.Imaging para la referencia de la API de .NET
description: El registro EmfPlusOffsetClip aplica una transformación de traducción en la región de recorte actual para el espacio mundial. La nueva región de recorte actual se establece en el resultado de la transformación de traducción.
type: docs
weight: 6180
url: /es/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusoffsetclip/
---
## EmfPlusOffsetClip class

El registro EmfPlusOffsetClip aplica una transformación de traducción en la región de recorte actual para el espacio mundial. La nueva región de recorte actual se establece en el resultado de la transformación de traducción.

```csharp
public sealed class EmfPlusOffsetClip : EmfPlusClippingRecordType
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [EmfPlusOffsetClip](emfplusoffsetclip)(EmfPlusRecord) | Inicializa una nueva instancia del[`EmfPlusOffsetClip`](../emfplusoffsetclip) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize) { get; set; } | Obtiene o establece un entero sin signo de 32 bits que DEBE definir el número alineado de 32 bits de bytes de datos en el campo RecordData que sigue. Este número no incluye el encabezado del registro de 12 bytes. |
| [Dx](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusoffsetclip/dx) { get; set; } | Obtiene o establece un valor de coma flotante de 32 bits que especifica el desplazamiento horizontal de la traducción. |
| [Dy](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusoffsetclip/dy) { get; set; } | Obtiene o establece un valor de coma flotante de 32 bits que especifica el desplazamiento vertical de la traducción. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags) { get; set; } | Obtiene o establece un entero sin signo de 16 bits que contiene información para algunos registros sobre cómo se realizará la operación y sobre la estructura del registro. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size) { get; set; } | Obtiene o establece un entero sin signo de 32 bits que especifica el número alineado de 32 bits de bytes en todo el registro, incluido el encabezado del registro de 12 bytes y los datos específicos del registro. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type) { get; } | Obtiene un entero de 16 bits sin signo que identifica el tipo de registro. |

### Ver también

* class [EmfPlusClippingRecordType](../emfplusclippingrecordtype)
* espacio de nombres [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records)
* asamblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->