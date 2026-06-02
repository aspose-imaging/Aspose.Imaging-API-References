---
title: "Énumération EmfPlusFilterType"
type: docs
weight: 140
url: /fr/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusfiltertype/
---

L'énumération FilterType définit les types d'algorithmes de filtrage qui peuvent être utilisés pour l'amélioration de la qualité du texte et des graphiques ainsi que le rendu d'images.

**Module:** [aspose.imaging.fileformats.emf.emfplus.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.consts.EmfPlusFilterType

## **Members**
| **Nom du membre** | **Description** |
| :- | :- |
| FILTER_TYPE_BOX | Spécifie un algorithme de filtre boîte, dans lequel chaque pixel de destination est calculé en moyennant un rectangle de pixels source. Cet algorithme n'est utile que lors de la réduction de la taille d'une image. |
| FILTER_TYPE_GAUSSIAN_QUAD | Spécifie qu'un filtre gaussien à 4 échantillons est utilisé, ce qui crée un effet de flou sur une image. |
| FILTER_TYPE_LINEAR | Spécifie que l'interpolation linéaire est effectuée en utilisant la moyenne pondérée d'une zone de 2 × 2 pixels entourant le pixel source. |
| FILTER_TYPE_NONE | Spécifie qu'aucun filtrage n'est effectué. |
| FILTER_TYPE_POINT | Spécifie que chaque pixel de destination est calculé en échantillonnant le pixel le plus proche de l'image source. |
| FILTER_TYPE_PYRAMIDAL_QUAD | Spécifie qu'un filtre en tente à 4 échantillons est utilisé. |
| FILTER_TYPE_TRIANGLE | Spécifie que chaque pixel de l'image source contribue de manière égale à l'image de destination. C'est le plus lent des algorithmes de filtrage. |
