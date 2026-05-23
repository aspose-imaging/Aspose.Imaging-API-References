---
title: "Enumeración EmfPlusInterpolationMode"
type: docs
weight: 200
url: /es/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusinterpolationmode/
---

La enumeración InterpolationMode define formas de realizar el escalado, incluyendo estiramiento y reducción.

**Module:** [aspose.imaging.fileformats.emf.emfplus.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.consts.EmfPlusInterpolationMode

## **Members**
| **Nombre del miembro** | **Descripción** |
| :- | :- |
| INTERPOLATION_MODE_BICUBIC | Especifica interpolación bicúbica, que utiliza el vecindario 4x4 más cercano de píxeles conocidos que rodean el píxel interpolado. El promedio ponderado de estos 16 valores de píxeles conocidos determina el valor a asignar al píxel interpolado. Debido a que los píxeles conocidos pueden estar a diferentes distancias del píxel interpolado, los píxeles más cercanos reciben un peso mayor en el cálculo. El resultado tiene una apariencia más suave que InterpolationModeBilinear. |
| INTERPOLATION_MODE_BILINEAR | Especifica interpolación bilineal, que utiliza el vecindario 2x2 más cercano de píxeles conocidos que rodean el píxel interpolado. El promedio ponderado de estos 4 valores de píxeles conocidos determina el valor a asignar al píxel interpolado. El resultado tiene una apariencia más suave que InterpolationModeNearestNeighbor. |
| INTERPOLATION_MODE_DEFAULT | Especifica el modo de interpolación predeterminado, que se define como InterpolationModeBilinear. |
| INTERPOLATION_MODE_HIGH_QUALITY | Especifica un modo de interpolación de alta calidad, que se define como InterpolationModeHighQualityBicubic. |
| INTERPOLATION_MODE_HIGH_QUALITY_BICUBIC | Especifica interpolación bicúbica con prefiltrado, que produce el resultado de mayor calidad entre estas opciones. |
| INTERPOLATION_MODE_HIGH_QUALITY_BILINEAR | Especifica interpolación bilineal con prefiltrado. |
| INTERPOLATION_MODE_LOW_QUALITY | Especifica un modo de interpolación de baja calidad, que se define como InterpolationModeNearestNeighbor. |
| INTERPOLATION_MODE_NEAREST_NEIGHBOR | Especifica interpolación del vecino más cercano, que utiliza solo el valor del píxel más cercano al píxel interpolado. Este modo simplemente duplica o elimina píxeles, produciendo el resultado de menor calidad entre estas opciones. |
