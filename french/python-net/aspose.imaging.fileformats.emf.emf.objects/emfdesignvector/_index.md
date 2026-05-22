---
title: "Classe EmfDesignVector"
type: docs
weight: 40
url: /fr/python-net/aspose.imaging.fileformats.emf.emf.objects/emfdesignvector/
---

**Summary:** The DesignVector (section 2.2.3) object defines the design vector, which specifies values for the font axes of a multiple master font.

**Module:** [aspose.imaging.fileformats.emf.emf.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emf.objects.EmfDesignVector

**Inheritance:** EmfObject

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfDesignVector()](#EmfDesignVector__1) | Initialise une nouvelle instance de la classe EmfDesignVector |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| num_axes | int | r/w | Obtient ou définit un entier non signé de 32 bits qui spécifie le nombre d'éléments dans <br/>            le tableau Values. Il DOIT être compris entre 0 et 16, inclus. |
| signature | int | r/w | Obtient ou définit un entier non signé de 32 bits qui DOIT être défini à la valeur 0x08007664. |
| values | int[] | r/w | Obtient ou définit un tableau optionnel d'entiers signés de 32 bits qui spécifient les valeurs <br/>            des axes de police d'une police OpenType à maîtres multiples. Le nombre maximal de valeurs dans le tableau est 16. |


### Constructor: EmfDesignVector() {#EmfDesignVector__1}


```
 EmfDesignVector() 
```

Initialise une nouvelle instance de la classe EmfDesignVector

