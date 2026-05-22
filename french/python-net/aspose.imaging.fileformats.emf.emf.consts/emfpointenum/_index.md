---
title: "EmfPointEnum Énumération"
type: docs
weight: 260
url: /fr/python-net/aspose.imaging.fileformats.emf.emf.consts/emfpointenum/
---

L'énumération Point est utilisée pour spécifier comment un point doit être utilisé dans un appel de dessin.

**Module:** [aspose.imaging.fileformats.emf.emf.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emf.consts.EmfPointEnum

## **Members**
| **Nom du membre** | **Description** |
| :- | :- |
| BEZIERTO | Spécifie que ce point est un point de contrôle ou un point final pour une courbe de Bézier. |
| CLOSEFIGURE | Un type PT_LINETO ou PT_BEZIERTO peut être combiné avec cette valeur en utilisant l'opérateur binaire <br/>            OR pour indiquer que le point correspondant est le dernier point d'une figure <br/>            et que la figure est fermée |
| LINETO | Spécifie qu'une ligne doit être tracée depuis la position actuelle jusqu'à ce point, <br/>            qui devient alors la nouvelle position actuelle |
| MOVETO | Spécifie que ce point démarre une figure distincte. Ce point devient la nouvelle position actuelle. |
