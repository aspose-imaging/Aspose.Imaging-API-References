---
title: "EmfPlusPathPointFlags Énumération"
type: docs
weight: 290
url: /fr/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluspathpointflags/
---

Un entier non signé de 32 bits qui spécifie comment interpréter les points et les types de points associés définis par cet objet.<br/>            C  (1 bit) : Si défini, le tableau PathPoints indique des emplacements absolus dans l'espace de coordonnées avec des coordonnées entières de 16 bits.<br/>             Si non défini, le tableau PathPoints indique des emplacements absolus dans l'espace de coordonnées avec des coordonnées à virgule flottante de 32 bits.<br/>             Remarque : Si le drapeau P (ci‑dessous) est défini, ce drapeau PEUT être non défini et DOIT être ignoré.<br/>            R (1 bit) : Si défini, les types de points dans le tableau PathPointTypes sont spécifiés par des objets EmfPlusPathPointTypeRle (section 2.2.2.32), <br/>             qui utilisent la compression par codage run‑length (RLE), et/ou des objets EmfPlusPathPointType (section 2.2.2.31). Voir la section 3.1.6 de [MS‑WMF] pour plus d'informations sur la compression RLE.<br/>             Si non défini, les types de points dans le tableau PathPointTypes sont spécifiés par des objets EmfPlusPathPointType.<br/>            P (1 bit) : Si défini, chaque élément du tableau PathPoints indique un emplacement dans l'espace de coordonnées relatif à l'<br/>             emplacement spécifié par l'élément précédent du tableau. Dans le cas du premier élément de PathPoints, on suppose un emplacement précédent aux coordonnées (0,0).<br/>             Si non défini, chaque élément du tableau PathPoints indique un emplacement absolu.

**Module:** [aspose.imaging.fileformats.emf.emfplus.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.consts.EmfPlusPathPointFlags

## **Members**
| **Nom du membre** | **Description** |
| :- | :- |
| C | Le drapeau c |
| P | Le drapeau p |
| R | Le drapeau r |
