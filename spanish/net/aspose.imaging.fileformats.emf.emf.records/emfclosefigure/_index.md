---
title: EmfCloseFigure
second_title: Aspose.Imaging para la referencia de la API de .NET
description: Este registro cierra una figura abierta en una ruta. El procesamiento del registro EMR_CLOSEFIGURE DEBE cerrar la figura dibujando una línea desde la posición actual hasta el primer punto de la figura y luego DEBE conectar las líneas usando el estilo de unión de líneas. Si una figura se cierra al procesar el registro EMR_LINETO en lugar del registro EMR_CLOSEFIGURE las tapas finales se usan para crear la esquina en lugar de una unión. EMR_LINETO se especifica en la sección 2.3.5.13. El registro EMR_CLOSEFIGURE solo DEBE usarse si hay un ruta abierta corchete en el contexto del dispositivo de reproducción. Una figura en una ruta está abierta a menos que se cierre explícitamente al procesar este registro.
type: docs
weight: 3310
url: /es/net/aspose.imaging.fileformats.emf.emf.records/emfclosefigure/
---
## EmfCloseFigure class

Este registro cierra una figura abierta en una ruta. El procesamiento del registro EMR_CLOSEFIGURE DEBE cerrar la figura dibujando una línea desde la posición actual hasta el primer punto de la figura, y luego DEBE conectar las líneas usando el estilo de unión de líneas. Si una figura se cierra al procesar el registro EMR_LINETO en lugar del registro EMR_CLOSEFIGURE, las tapas finales se usan para crear la esquina en lugar de una unión. EMR_LINETO se especifica en la sección 2.3.5.13. El registro EMR_CLOSEFIGURE solo DEBE usarse si hay un ruta abierta corchete en el contexto del dispositivo de reproducción. Una figura en una ruta está abierta a menos que se cierre explícitamente al procesar este registro.

```csharp
public sealed class EmfCloseFigure : EmfPathBracketRecordType
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [EmfCloseFigure](emfclosefigure)() | Constructor predeterminado |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size) { get; set; } | Obtiene o establece el tamaño del registro |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type) { get; set; } | Obtiene o establece el tipo. |

### Observaciones

Nota: Una figura puede estar abierta incluso si el punto actual y el punto inicial de la figura son los mismos. Después de procesar el registro EMR_CLOSEFIGURE, agregar una línea o curva a la ruta DEBE comenzar una nueva figura.

### Ver también

* class [EmfPathBracketRecordType](../emfpathbracketrecordtype)
* espacio de nombres [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* asamblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->