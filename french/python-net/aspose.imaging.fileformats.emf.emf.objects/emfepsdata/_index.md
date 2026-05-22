---
title: "Classe EmfEpsData"
type: docs
weight: 50
url: /fr/python-net/aspose.imaging.fileformats.emf.emf.objects/emfepsdata/
---

**Summary:** The EpsData object is a container for EPS data

**Module:** [aspose.imaging.fileformats.emf.emf.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emf.objects.EmfEpsData

**Inheritance:** EmfObject

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfEpsData()](#EmfEpsData__1) | Initialise une nouvelle instance de la classe EmfEpsData |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| points | [EmfPoint28To4[]](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emfpoint28to4/) | r/w | Obtient ou définit un tableau de trois objets Point28_4 (section 2.2.23) qui définit les <br/>            coordonnées du parallélogramme de sortie en utilisant la notation FIX de 28,4 bits |
| post_script_data | System.Byte | r/w | Obtient ou définit un tableau d'octets de données PostScript. La longueur de ce tableau peut <br/>            être calculée à partir du champ SizeData. Ces données PEUVENT être utilisées pour rendre une image. |
| size_data | int | r/w | Obtient ou définit un entier non signé de 32 bits qui indique la taille totale de cet objet, en octets |
| version | int | r/w | Obtient ou définit un entier non signé de 32 bits qui indique le niveau du langage PostScript. Cette <br/>            valeur DOIT être 0x00000001 |


### Constructor: EmfEpsData() {#EmfEpsData__1}


```
 EmfEpsData() 
```

Initialise une nouvelle instance de la classe EmfEpsData

