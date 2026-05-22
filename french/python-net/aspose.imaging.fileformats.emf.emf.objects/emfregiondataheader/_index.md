---
title: "Classe EmfRegionDataHeader"
type: docs
weight: 250
url: /fr/python-net/aspose.imaging.fileformats.emf.emf.objects/emfregiondataheader/
---

**Summary:** The RegionDataHeader object describes the properties of a RegionData object.

**Module:** [aspose.imaging.fileformats.emf.emf.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emf.objects.EmfRegionDataHeader

**Inheritance:** EmfObject

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfRegionDataHeader()](#EmfRegionDataHeader__1) | Initialise une nouvelle instance de la classe EmfRegionDataHeader |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Obtient ou définit un objet WMF RectL de 128 bits ([MS-WMF] section 2.2.2.19), qui spécifie <br/>            les limites de la région. |
| count_rects | int | r/w | Obtient ou définit un entier non signé de 32 bits qui spécifie le nombre de rectangles dans cette région. |
| rgn_size | int | r/w | Obtient ou définit un entier non signé de 32 bits qui spécifie la taille du tampon de rectangles en octets. |
| size | int | r/w | Obtient ou définit un entier non signé de 32 bits qui spécifie la taille de cet objet en octets. Cette valeur DOIT être 0x00000020. |
| type | int | r/w | Obtient ou définit un entier non signé de 32 bits qui spécifie le type de région. Cette valeur DEVRAIT être <br/>            RDH_RECTANGLES (0x00000001). |


### Constructor: EmfRegionDataHeader() {#EmfRegionDataHeader__1}


```
 EmfRegionDataHeader() 
```

Initialise une nouvelle instance de la classe EmfRegionDataHeader

