---
title: EmfVertexData
second_title: Aspose.Imaging para la referencia de la API de .NET
description: Objetos que especifican los vértices de rectángulos o triángulos y los colores que les corresponden.
type: docs
weight: 4650
url: /es/net/aspose.imaging.fileformats.emf.emf.records/emfvertexdata/
---
## EmfVertexData class

Objetos que especifican los vértices de rectángulos o triángulos y los colores que les corresponden.

```csharp
public sealed class EmfVertexData
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [EmfVertexData](emfvertexdata)() | Constructor predeterminado |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [VertexIndexes](../../aspose.imaging.fileformats.emf.emf.records/emfvertexdata/vertexindexes) { get; set; } | Obtiene o establece una matriz de objetos nTri GradientRectangle (sección 2.2.7) u objetos GradientTriangle (sección 2.2.8), según el valor del campo ulMode. Cada objeto especifica índices en la matriz de objetos TriVertex en el campo VertexObjects. |
| [VertexObjects](../../aspose.imaging.fileformats.emf.emf.records/emfvertexdata/vertexobjects) { get; set; } | Obtiene o establece una matriz de objetos nVer TriVertex (sección 2.2.26). Cada objeto especifica la posición y el color de un vértice de un rectángulo o un triángulo, dependiendo del valor del campo ulMode. |
| [VertexPadding](../../aspose.imaging.fileformats.emf.emf.records/emfvertexdata/vertexpadding) { get; set; } | Obtiene o establece una matriz opcional de longitud variable de nTri por cuatro bytes que DEBE estar presente si el valor del campo ulMode indica objetos GradientRectangle (sección 2.2.7). Si el valor del campo ulMode indica objetos GradientTriangle (sección 2.2.8), no hay VertexPadding presente. Este campo DEBE ser ignorado. |

### Ver también

* espacio de nombres [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* asamblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
