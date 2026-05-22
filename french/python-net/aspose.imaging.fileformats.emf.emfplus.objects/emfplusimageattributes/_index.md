---
title: "Classe EmfPlusImageAttributes"
type: docs
weight: 390
url: /fr/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageattributes/
---

**Summary:** The EmfPlusImageAttributes object specifies how bitmap image<br/>            colors are manipulated during rendering.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImageAttributes

**Inheritance:** EmfPlusGraphicsObjectType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusImageAttributes()](#EmfPlusImageAttributes__1) | Initialise une nouvelle instance de la classe EmfPlusImageAttributes |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| clamp_argb_32_color | int | r/w | Obtient ou définit l'objet EmfPlusARGB (section 2.2.2.1) qui spécifie la couleur de bord à utiliser <br/>            lorsque la valeur WrapMode est WrapModeClamp. Cette couleur est visible lorsque le <br/>            rectangle source traité par un enregistrement EmfPlusDrawImage (section 2.3.4.8) <br/>            est plus grand que l'image elle-même. |
| object_clamp | [EmfPlusObjectClamp](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusobjectclamp/) | r/w | Obtient ou définit un entier signé de 32 bits qui spécifie le comportement de serrage de l'objet.<br/>            Il n'est pas utilisé tant que cet objet n'est pas appliqué à une image en cours de <br/>            dessin. Cette valeur DOIT être l'une des valeurs définies dans le <br/>            tableau suivant. |
| version | [EmfPlusGraphicsVersion](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsversion/) | r/w | Obtient ou définit la version. |
| wrap_mode | [EmfPlusWrapMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluswrapmode/) | r/w | Obtient ou définit un entier non signé de 32 bits qui spécifie comment gérer les conditions de bord avec <br/>            une valeur de l'énumération WrapMode (section 2.1.1.34). |


### Constructor: EmfPlusImageAttributes() {#EmfPlusImageAttributes__1}


```
 EmfPlusImageAttributes() 
```

Initialise une nouvelle instance de la classe EmfPlusImageAttributes

