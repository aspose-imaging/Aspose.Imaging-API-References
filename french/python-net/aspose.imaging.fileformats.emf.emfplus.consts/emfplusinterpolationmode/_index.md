---
title: "EmfPlusInterpolationMode Énumération"
type: docs
weight: 200
url: /fr/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusinterpolationmode/
---

L'énumération InterpolationMode définit les méthodes d'échelle, y compris l'étirement et la réduction.

**Module:** [aspose.imaging.fileformats.emf.emfplus.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.consts.EmfPlusInterpolationMode

## **Members**
| **Nom du membre** | **Description** |
| :- | :- |
| INTERPOLATION_MODE_BICUBIC | Spécifie l’interpolation bicubique, qui utilise le voisinage 4x4 le plus proche des pixels connus entourant le pixel interpolé. La moyenne pondérée de ces 16 valeurs de pixels connus détermine la valeur à attribuer au pixel interpolé. Comme les pixels connus sont susceptibles d’être à des distances variables du pixel interpolé, les pixels plus proches reçoivent un poids plus élevé dans le calcul. Le résultat apparaît plus lisse que InterpolationModeBilinear. |
| INTERPOLATION_MODE_BILINEAR | Spécifie l’interpolation bilinéaire, qui utilise le voisinage 2x2 le plus proche des pixels connus entourant le pixel interpolé. La moyenne pondérée de ces 4 valeurs de pixels connus détermine la valeur à attribuer au pixel interpolé. Le résultat apparaît plus lisse que InterpolationModeNearestNeighbor. |
| INTERPOLATION_MODE_DEFAULT | Spécifie le mode d’interpolation par défaut, qui est défini comme InterpolationModeBilinear. |
| INTERPOLATION_MODE_HIGH_QUALITY | Spécifie un mode d'interpolation de haute qualité, qui est défini comme InterpolationModeHighQualityBicubic. |
| INTERPOLATION_MODE_HIGH_QUALITY_BICUBIC | Spécifie une interpolation bicubique avec préfiltrage, qui produit le résultat de la plus haute qualité parmi ces options. |
| INTERPOLATION_MODE_HIGH_QUALITY_BILINEAR | Spécifie une interpolation bilinéaire avec préfiltrage. |
| INTERPOLATION_MODE_LOW_QUALITY | Spécifie un mode d'interpolation de basse qualité, qui est défini comme InterpolationModeNearestNeighbor. |
| INTERPOLATION_MODE_NEAREST_NEIGHBOR | Spécifie une interpolation du plus proche voisin, qui n'utilise que la valeur du pixel le plus proche du pixel interpolé. Ce mode duplique ou supprime simplement les pixels, produisant le résultat de la plus basse qualité parmi ces options. |
