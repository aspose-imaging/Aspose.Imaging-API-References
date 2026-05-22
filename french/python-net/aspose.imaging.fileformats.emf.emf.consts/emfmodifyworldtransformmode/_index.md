---
title: "EmfModifyWorldTransformMode Énumération"
type: docs
weight: 240
url: /fr/python-net/aspose.imaging.fileformats.emf.emf.consts/emfmodifyworldtransformmode/
---

L'énumération ModifyWorldTransformMode définit des modes pour utiliser les données de transformation spécifiées<br/>            afin de modifier la transformation de l'espace monde vers l'espace page qui est actuellement définie dans le contexte de périphérique de lecture.

**Module:** [aspose.imaging.fileformats.emf.emf.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emf.consts.EmfModifyWorldTransformMode

## **Members**
| **Nom du membre** | **Description** |
| :- | :- |
| MWT_IDENTITY | Réinitialisez la transformation actuelle en utilisant la matrice identité. Dans ce mode, les données de transformation spécifiées sont ignorées |
| MWT_LEFTMULTIPLY | Multipliez la transformation actuelle. Dans ce mode, les données de transformation spécifiées sont le multiplicande gauche, et <br/>            la transformation actuellement définie dans le contexte du dispositif de lecture est le multiplicande droit |
| MWT_RIGHTMULTIPLY | Multipliez la transformation actuelle. Dans ce mode, les données de transformation spécifiées sont le multiplicande droit, <br/>            et la transformation actuellement définie dans le contexte du dispositif de lecture est le multiplicande gauche |
| MWT_SET | Exécutez la fonction d'un enregistrement EMR_SETWORLDTRANSFORM (section 2.3.12.2). |
