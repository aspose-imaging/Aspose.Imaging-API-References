---
title: EmfPlusHeader
second_title: Aspose.Imaging para la referencia de la API de .NET
description: El registro EmfPlusHeader especifica el inicio de los datos EMF en el metarchivo. El registro EmfPlusHeader DEBE estar incrustado en un registro EMF EMR_COMMENT_EMFPLUS que DEBE ser el registro que sigue inmediatamente al encabezado EMF en el metarchivo. El registro EMR_COMMENT_EMFPLUS se especifica en MS-EMF sección 2.3.3.2.
type: docs
weight: 6140
url: /es/aspose.imaging.fileformats.emf.emfplus.records/emfplusheader/
---
## EmfPlusHeader class

El registro EmfPlusHeader especifica el inicio de los datos EMF+ en el metarchivo. El registro EmfPlusHeader DEBE estar incrustado en un registro EMF EMR_COMMENT_EMFPLUS, que DEBE ser el registro que sigue inmediatamente al encabezado EMF en el metarchivo. El registro EMR_COMMENT_EMFPLUS se especifica en [MS-EMF] sección 2.3.3.2.

```csharp
public sealed class EmfPlusHeader : EmfPlusControlRecordType
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [EmfPlusHeader](emfplusheader)(EmfPlusRecord) | Inicializa una nueva instancia del[`EmfPlusHeader`](../emfplusheader) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize) { get; set; } | Obtiene o establece un entero sin signo de 32 bits que DEBE definir el número alineado de 32 bits de bytes de datos en el campo RecordData que sigue. Este número no incluye el encabezado del registro de 12 bytes. |
| [DualMode](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusheader/dualmode) { get; set; } | Obtiene o establece un valor que indica si [modo dual]. Si se establece, esta bandera indica que este metarchivo es de "modo dual", lo que significa que contiene dos conjuntos de registros, cada uno de los cuales especifica completamente el contenido de gráficos. Si está claro, el contenido de gráficos se especifica mediante registros EMF+ y posiblemente registros EMF precedidos por un registro EmfPlusGetDC. Si se establece este indicador, los registros EMF por sí solos DEBERÍAN ser suficientes para definir el contenido de gráficos . Tenga en cuenta que ya sea que el indicador de "modo dual" esté configurado o no, algunos registros EMF siempre están presentes, es decir, los registros de control EMF y los registros EMF que contienen registros EMF+. Los registros de control de EMF se especifican en [MS-EMF] sección 2.3.4. |
| [EmfPlusFlags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusheader/emfplusflags) { get; set; } | Obtiene o establece los indicadores EMF plus. Un entero de 32 bits sin signo que contiene información sobre cómo se registró este metarchivo. si se establece el bit 31 del campo, este indicador indica que el metarchivo se registró con como referencia contexto de dispositivo para una visualización de vídeo. Si está claro, el metarchivo se registró con un contexto de dispositivo de referencia para una impresora. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags) { get; set; } | Obtiene o establece un entero sin signo de 16 bits que contiene información para algunos registros sobre cómo se realizará la operación y sobre la estructura del registro. |
| [IsValid](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusheader/isvalid) { get; } | Obtiene un valor que indica si esta instancia es válida. |
| [LogicalDpiX](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusheader/logicaldpix) { get; set; } | Obtiene o establece los ppp lógicos x. Un entero de 32 bits sin signo que especifica la resolución horizontal para la que se grabó el metarchivo , en unidades de píxeles por pulgada. |
| [LogicalDpiY](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusheader/logicaldpiy) { get; set; } | Obtiene o establece el dpi lógico y. Un entero de 32 bits sin signo que especifica la resolución vertical para la que se grabó el metarchivo , en unidades de líneas por pulgada |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size) { get; set; } | Obtiene o establece un entero sin signo de 32 bits que especifica el número alineado de 32 bits de bytes en todo el registro, incluido el encabezado del registro de 12 bytes y los datos específicos del registro. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type) { get; } | Obtiene un entero de 16 bits sin signo que identifica el tipo de registro. |
| [Version](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusheader/version) { get; set; } | Obtiene o establece la versión. Un objeto EmfPlusGraphicsVersion (sección 2.2.2.19) que especifica la versión de los gráficos del sistema operativo que se utilizó para crear este metarchivo. |
| [VideoDisplay](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusheader/videodisplay) { get; set; } | Obtiene o establece un valor que indica si se muestra video. si se establece, esta marca indica que el metarchivo se grabó con un contexto de dispositivo de referencia para una pantalla de video. Si está claro, el metarchivo se registró con un contexto de dispositivo de referencia para una impresora. |

### Ver también

* class [EmfPlusControlRecordType](../emfpluscontrolrecordtype)
* espacio de nombres [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records)
* asamblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
