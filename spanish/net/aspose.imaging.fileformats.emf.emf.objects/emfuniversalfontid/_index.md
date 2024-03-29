---
title: EmfUniversalFontId
second_title: Aspose.Imaging para la referencia de la API de .NET
description: El objeto UniversalFontId define un mecanismo para identificar fuentes en metarchivos EMF.
type: docs
weight: 3180
url: /es/net/aspose.imaging.fileformats.emf.emf.objects/emfuniversalfontid/
---
## EmfUniversalFontId class

El objeto UniversalFontId define un mecanismo para identificar fuentes en metarchivos EMF.

```csharp
public sealed class EmfUniversalFontId : EmfObject
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [EmfUniversalFontId](emfuniversalfontid)() | Constructor predeterminado |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Checksum](../../aspose.imaging.fileformats.emf.emf.objects/emfuniversalfontid/checksum) { get; set; } | Obtiene o establece un entero sin signo de 32 bits que es la suma de comprobación de la fuente. El valor de la suma de comprobación tiene los siguientes significados. 0x00000000 El objeto es una fuente de dispositivo. 0x00000001 El objeto es una fuente Tipo 1 que se ha instalado en la máquina cliente y el controlador de impresora PostScript enumera como una fuente de dispositivo. 0x00000002 El objeto no es una fuente sino un rasterizador Tipo 1. 3 ≤ valor El objeto es una fuente de mapa de bits, vectorial o TrueType, o una fuente rasterizada Tipo 1 que fue creada por un rasterizador Tipo 1. |
| [Index](../../aspose.imaging.fileformats.emf.emf.objects/emfuniversalfontid/index) { get; set; } | Obtiene o establece un entero sin signo de 32 bits que es un índice asociado con el objeto de fuente. El significado de este campo está determinado por el tipo de fuente. |

### Ver también

* class [EmfObject](../emfobject)
* espacio de nombres [Aspose.Imaging.FileFormats.Emf.Emf.Objects](../../aspose.imaging.fileformats.emf.emf.objects)
* asamblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
