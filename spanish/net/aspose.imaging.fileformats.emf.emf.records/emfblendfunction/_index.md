---
title: EmfBlendFunction
second_title: Aspose.Imaging para la referencia de la API de .NET
description: Una estructura que especifica las operaciones de combinación para los mapas de bits de origen y destino.
type: docs
weight: 3270
url: /es/net/aspose.imaging.fileformats.emf.emf.records/emfblendfunction/
---
## EmfBlendFunction structure

Una estructura que especifica las operaciones de combinación para los mapas de bits de origen y destino.

```csharp
public struct EmfBlendFunction
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [EmfBlendFunction](emfblendfunction)(int) | Inicializa una nueva instancia del[`EmfBlendFunction`](../emfblendfunction) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AlphaFormat](../../aspose.imaging.fileformats.emf.emf.records/emfblendfunction/alphaformat) { get; } | Obtiene una estructura que especifica cómo se interpretan los píxeles de origen y destino con respecto a la transparencia alfa. |
| [BlendFlags](../../aspose.imaging.fileformats.emf.emf.records/emfblendfunction/blendflags) { get; } | Obtiene los indicadores de combinación. Este valor DEBE ser 0x00 y DEBE ignorarse. |
| [BlendOperation](../../aspose.imaging.fileformats.emf.emf.records/emfblendfunction/blendoperation) { get; } | Obtiene el código de operación de mezcla. La única operación de combinación de origen y destino que se ha definido es 0x00, que especifica que el mapa de bits de origen DEBE combinarse con el mapa de bits de destino según los valores de transparencia alfa de los píxeles de origen. Vea las siguientes ecuaciones para más detalles. |
| [SrcConstantAlpha](../../aspose.imaging.fileformats.emf.emf.records/emfblendfunction/srcconstantalpha) { get; } | Obtiene un entero sin signo de 8 bits que especifica la transparencia alfa, que determina la combinación de los mapas de bits de origen y destino. Este valor DEBE usarse en todo el mapa de bits de origen. El valor mínimo de transparencia alfa, cero, corresponde a completamente transparente el valor máximo, 0xFF, corresponde a completamente opaco. En efecto, un valor de 0xFF especifica que los valores alfa por píxel determinan la combinación de los mapas de bits de origen y destino. Consulte las ecuaciones más adelante en en esta sección para obtener detalles. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [ToInt](../../aspose.imaging.fileformats.emf.emf.records/emfblendfunction/toint)() | Convierte la representación de cadena de un número en un entero. |

## Otros miembros

| Nombre | Descripción |
| --- | --- |
| enum [AlphaFormatEnum](emfblendfunction.alphaformatenum) | Una estructura que especifica cómo se interpretan los píxeles de origen y destino con respecto a la transparencia alfa. |

### Ver también

* espacio de nombres [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* asamblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
