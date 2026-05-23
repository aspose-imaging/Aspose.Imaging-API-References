---
title: "EmfPlusFilterType Enumeración"
type: docs
weight: 140
url: /es/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusfiltertype/
---

La enumeración FilterType define tipos de algoritmos de filtrado que pueden usarse para la mejora de la calidad del texto y los gráficos y la renderización de imágenes.

**Module:** [aspose.imaging.fileformats.emf.emfplus.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.consts.EmfPlusFilterType

## **Members**
| **Nombre del miembro** | **Descripción** |
| :- | :- |
| FILTER_TYPE_BOX | Especifica un algoritmo de filtro de caja, en el que cada píxel de destino se calcula promediando un rectángulo de píxeles de origen. Este algoritmo es útil solo al reducir el tamaño de una imagen. |
| FILTER_TYPE_GAUSSIAN_QUAD | Especifica que se utiliza un filtro gaussiano de 4 muestras, que crea un efecto de desenfoque en una imagen. |
| FILTER_TYPE_LINEAR | Especifica que se realiza interpolación lineal usando el promedio ponderado de un área de 2x2 píxeles que rodean al píxel de origen. |
| FILTER_TYPE_NONE | Especifica que no se realiza filtrado. |
| FILTER_TYPE_POINT | Especifica que cada píxel de destino se calcula muestreando el píxel más cercano de la imagen de origen. |
| FILTER_TYPE_PYRAMIDAL_QUAD | Especifica que se utiliza un filtro de tienda de 4 muestras. |
| FILTER_TYPE_TRIANGLE | Especifica que cada píxel de la imagen de origen contribuye por igual a la imagen de destino. Este es el algoritmo de filtrado más lento. |
