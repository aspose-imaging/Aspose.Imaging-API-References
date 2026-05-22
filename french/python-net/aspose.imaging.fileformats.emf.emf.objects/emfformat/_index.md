---
title: "Classe EmfFormat"
type: docs
weight: 60
url: /fr/python-net/aspose.imaging.fileformats.emf.emf.objects/emfformat/
---

**Summary:** The EmrFormat object contains information that identifies the format of image data in an<br/>            EMR_COMMENT_MULTIFORMATS record(section 2.3.3.4.3).

**Module:** [aspose.imaging.fileformats.emf.emf.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emf.objects.EmfFormat

**Inheritance:** EmfObject

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfFormat()](#EmfFormat__1) | Initialise une nouvelle instance de la classe EmfFormat |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| off_data | int | r/w | Obtient ou définit un entier non signé de 32 bits qui spécifie le décalage des données par rapport au <br/>            début du champ d'identifiant dans un enregistrement EMR_COMMENT_PUBLIC (section 2.3.3.4). <br/>            Le décalage DOIT être aligné sur 32 bits. |
| signature | [EmfFormatSignature](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfformatsignature/) | r/w | Obtient ou définit un entier non signé de 32 bits qui spécifie le format des données d'image. <br/>            Cette valeur DOIT appartenir à l'énumération FormatSignature (section 2.1.14). |
| size_data | int | r/w | Obtient ou définit un entier non signé de 32 bits qui spécifie la taille des données en octets |
| version | int | r/w | Obtient ou définit un entier non signé de 32 bits qui spécifie le numéro de version du format. <br/>            Si le champ Signature indique un PostScript encapsulé (EPS), <br/>            cette valeur DOIT être 0x00000001 ; sinon, cette valeur DOIT être ignorée. |


### Constructor: EmfFormat() {#EmfFormat__1}


```
 EmfFormat() 
```

Initialise une nouvelle instance de la classe EmfFormat

