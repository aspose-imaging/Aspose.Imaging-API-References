---
title: "Classe EmfUniversalFontId"
type: docs
weight: 280
url: /fr/python-net/aspose.imaging.fileformats.emf.emf.objects/emfuniversalfontid/
---

**Summary:** The UniversalFontId object defines a mechanism for identifying fonts in EMF metafiles.

**Module:** [aspose.imaging.fileformats.emf.emf.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emf.objects.EmfUniversalFontId

**Inheritance:** EmfObject

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfUniversalFontId()](#EmfUniversalFontId__1) | Initialise une nouvelle instance de la classe EmfUniversalFontId |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| somme de contrôle | int | r/w | Obtient ou définit un entier non signé de 32 bits qui est la somme de contrôle de la police.<br/>            La valeur de la somme de contrôle a les significations suivantes.<br/>            0x00000000  L’objet est une police de dispositif. <br/>            0x00000001  L’objet est une police Type 1 qui a été installée sur la machine cliente et est <br/>            répertoriée par le pilote d’imprimante PostScript comme une police de dispositif. <br/>            0x00000002  L’objet n’est pas une police mais un rasteriseur Type 1. <br/>            3 ≤ valeur   L’objet est une police bitmap, vectorielle ou TrueType, ou une police rasterisée Type 1 qui <br/>            a été créée par un rasteriseur Type 1. |
| index | int | r/w | Obtient ou définit un entier non signé de 32 bits qui est un index associé à l’objet police. Le <br/>            sens de ce champ est déterminé par le type de police. |


### Constructor: EmfUniversalFontId() {#EmfUniversalFontId__1}


```
 EmfUniversalFontId() 
```

Initialise une nouvelle instance de la classe EmfUniversalFontId

