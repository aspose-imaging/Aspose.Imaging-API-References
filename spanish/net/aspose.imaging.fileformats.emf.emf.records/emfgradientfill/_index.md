---
title: EmfGradientFill
second_title: Aspose.Imaging para la referencia de la API de .NET
description: El registro EMR_GRADIENTFILL especifica el relleno de rectángulos o triángulos con degradados de color.
type: docs
weight: 3760
url: /es/net/aspose.imaging.fileformats.emf.emf.records/emfgradientfill/
---
## EmfGradientFill class

El registro EMR_GRADIENTFILL especifica el relleno de rectángulos o triángulos con degradados de color.

```csharp
public sealed class EmfGradientFill : EmfDrawingRecordType
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [EmfGradientFill](emfgradientfill)(EmfRecord) | Inicializa una nueva instancia del[`EmfGradientFill`](../emfgradientfill) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.records/emfgradientfill/bounds) { get; set; } | Obtiene o establece un objeto WMF RectL ([MS-WMF] sección 2.2.2.19) que especifica un rectángulo delimitador , en unidades de dispositivo inclusivo-inclusivo. |
| [NTri](../../aspose.imaging.fileformats.emf.emf.records/emfgradientfill/ntri) { get; set; } | Obtiene o establece un entero sin signo de 32 bits que especifica el número de rectángulos o triángulos a rellenar. |
| [NVer](../../aspose.imaging.fileformats.emf.emf.records/emfgradientfill/nver) { get; set; } | Obtiene o establece un entero sin signo de 32 bits que especifica el número de vértices. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size) { get; set; } | Obtiene o establece el tamaño del registro |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type) { get; set; } | Obtiene o establece el tipo. |
| [UlMode](../../aspose.imaging.fileformats.emf.emf.records/emfgradientfill/ulmode) { get; set; } | Obtiene o establece un entero sin signo de 32 bits que especifica el modo de relleno degradado. El valor DEBE estar en la enumeración GradientFill (sección 2.1.15). |
| [VertexData](../../aspose.imaging.fileformats.emf.emf.records/emfgradientfill/vertexdata) { get; set; } | Obtiene o establece objetos que especifican los vértices de rectángulos o triángulos y los colores que les corresponden. |

### Observaciones

Un registro EMR_GRADIENTFILL que especifica que los tres vértices de un triángulo DEBERÍAN llenar la figura con gradientes suaves de colores.[85] Un registro EMR_GRADIENTFILL que especifica que los vértices superior izquierdo e inferior derecho de un rectángulo DEBERÍAN llenar el figura con suaves degradados de color. Hay dos modos de relleno degradado en la enumeración GradientFill que se puede usar al dibujar un rectángulo. En el modo GRADIENT_FILL_RECT_H, el rectángulo se rellena de izquierda a derecha. En el modo GRADIENT_FILL_RECT_V, el rectángulo se rellena de arriba abajo. Nota Un registro EMR_GRADIENTFILL DEBE ignorar los campos Alfa en los objetos TriVertex. Se puede usar un registro EMR_ALPHABLEND (sección 2.3.1.1) que sigue inmediatamente al registro EMR_GRADIENTFILL para aplicar un degradado de transparencia alfa al área rellenada.

### Ver también

* class [EmfDrawingRecordType](../emfdrawingrecordtype)
* espacio de nombres [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* asamblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->