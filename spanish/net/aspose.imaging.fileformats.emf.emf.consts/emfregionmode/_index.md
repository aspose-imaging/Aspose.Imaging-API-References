---
title: EmfRegionMode
second_title: Aspose.Imaging para la referencia de la API de .NET
description: La enumeración RegionMode define valores que se utilizan con EMR_SELECTCLIPPATH y EMR_EXTSELECTCLIPRGN especificando la ruta actual o una nueva región que se combina con la región de clip actual.
type: docs
weight: 2830
url: /es/net/aspose.imaging.fileformats.emf.emf.consts/emfregionmode/
---
## EmfRegionMode enumeration

La enumeración RegionMode define valores que se utilizan con EMR_SELECTCLIPPATH y EMR_EXTSELECTCLIPRGN, especificando la ruta actual o una nueva región que se combina con la región de clip actual.

```csharp
public enum EmfRegionMode
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| RGN_AND | `1` | La nueva región de recorte incluye la intersección (áreas superpuestas) de la región de recorte actual y la ruta actual (o nueva región). |
| RGN_OR | `2` | La nueva región de recorte incluye la unión (áreas combinadas) de la región de recorte actual y la ruta actual (o nueva región). |
| RGN_XOR | `3` | La nueva región de recorte incluye la unión de la región de recorte actual y la ruta actual (o nueva región) pero sin las áreas superpuestas |
| RGN_DIFF | `4` | La nueva región de recorte incluye las áreas de la región de recorte actual con las de la ruta actual (o nueva región) excluidas. |
| RGN_COPY | `5` | La nueva región de recorte es la ruta actual (o la nueva región). |

### Ver también

* espacio de nombres [Aspose.Imaging.FileFormats.Emf.Emf.Consts](../../aspose.imaging.fileformats.emf.emf.consts)
* asamblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->