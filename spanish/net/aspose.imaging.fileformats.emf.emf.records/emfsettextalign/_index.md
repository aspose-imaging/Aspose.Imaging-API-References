---
title: EmfSetTextAlign
second_title: Aspose.Imaging para la referencia de la API de .NET
description: El registro EMR_SETTEXTALIGN especifica la alineación del texto.
type: docs
weight: 4490
url: /es/net/aspose.imaging.fileformats.emf.emf.records/emfsettextalign/
---
## EmfSetTextAlign class

El registro EMR_SETTEXTALIGN especifica la alineación del texto.

```csharp
public sealed class EmfSetTextAlign : EmfStateRecordType
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [EmfSetTextAlign](emfsettextalign#constructor)() | Inicializa una nueva instancia del[`EmfSetTextAlign`](../emfsettextalign) clase. |
| [EmfSetTextAlign](emfsettextalign#constructor_1)(EmfRecord) | Inicializa una nueva instancia del[`EmfSetTextAlign`](../emfsettextalign) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size) { get; set; } | Obtiene o establece el tamaño del registro |
| [TextAlignmentMode](../../aspose.imaging.fileformats.emf.emf.records/emfsettextalign/textalignmentmode) { get; set; } | Obtiene o establece un entero sin signo de 32 bits que especifica la alineación del texto por mediante una máscara de marcas de alineación del texto. Estos son[`WmfTextAlignmentModeFlags`](../../aspose.imaging.fileformats.wmf.consts/wmftextalignmentmodeflags) ([MS-WMF] sección 2.1.2.3) para texto con una línea base horizontal, o[`WmfVerticalTextAlignmentModeFlags`](../../aspose.imaging.fileformats.wmf.consts/wmfverticaltextalignmentmodeflags) ([MS-WMF] sección 2.1.2.4) para texto con una línea de base vertical . Solo se puede elegir un valor de los que afectan a la alineación horizontal y vertical . |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type) { get; set; } | Obtiene o establece el tipo. |

### Observaciones

Los registros EMR_SMALLTEXTOUT, EMR_EXTTEXTOUTA y EMR_EXTTEXTOUTW utilizan valores de alineación text para colocar una cadena de texto en el medio de salida. Los valores especifican la relación entre un punto de referencia y un rectángulo que delimita el texto. El punto de referencia es la posición actual o un punto pasado a un registro de salida de texto. El rectángulo que limita el texto está formado por las celdas de caracteres en la cadena de texto.

### Ver también

* class [EmfStateRecordType](../emfstaterecordtype)
* espacio de nombres [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* asamblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
