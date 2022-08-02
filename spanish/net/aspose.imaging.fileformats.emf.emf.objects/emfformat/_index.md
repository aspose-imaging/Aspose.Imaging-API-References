---
title: EmfFormat
second_title: Aspose.Imaging para la referencia de la API de .NET
description: El objeto EmrFormat contiene información que identifica el formato de los datos de imagen en un registro EMR_COMMENT_MULTIFORMATS sección 2.3.3.4.3.
type: docs
weight: 2960
url: /es/net/aspose.imaging.fileformats.emf.emf.objects/emfformat/
---
## EmfFormat class

El objeto EmrFormat contiene información que identifica el formato de los datos de imagen en un registro EMR_COMMENT_MULTIFORMATS (sección 2.3.3.4.3).

```csharp
public sealed class EmfFormat : EmfObject
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [EmfFormat](emfformat)() | Constructor predeterminado |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [OffData](../../aspose.imaging.fileformats.emf.emf.objects/emfformat/offdata) { get; set; } | Obtiene o establece un entero sin signo de 32 bits que especifica el desplazamiento de los datos desde el inicio del campo identificador en un registro EMR_COMMENT_PUBLIC (sección 2.3.3.4). El desplazamiento DEBE estar alineado en 32 bits. |
| [Signature](../../aspose.imaging.fileformats.emf.emf.objects/emfformat/signature) { get; set; } | Obtiene o establece un entero sin signo de 32 bits que especifica el formato de los datos de la imagen. Este valor DEBE estar en la enumeración FormatSignature (sección 2.1.14). |
| [SizeData](../../aspose.imaging.fileformats.emf.emf.objects/emfformat/sizedata) { get; set; } | Obtiene o establece un entero sin signo de 32 bits que especifica el tamaño de los datos en bytes |
| [Version](../../aspose.imaging.fileformats.emf.emf.objects/emfformat/version) { get; set; } | Obtiene o establece un entero sin signo de 32 bits que especifica el número de versión del formato. Si el campo Firma especifica PostScript encapsulado (EPS), este valor DEBE ser 0x00000001; de lo contrario, este valor DEBE ser ignorado |

### Ver también

* class [EmfObject](../emfobject)
* espacio de nombres [Aspose.Imaging.FileFormats.Emf.Emf.Objects](../../aspose.imaging.fileformats.emf.emf.objects)
* asamblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->