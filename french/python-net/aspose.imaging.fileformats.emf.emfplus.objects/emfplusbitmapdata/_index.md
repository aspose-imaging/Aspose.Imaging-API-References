---
title: "Classe EmfPlusBitmapData"
type: docs
weight: 60
url: /fr/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusbitmapdata/
---

**Summary:** The EmfPlusBitmapData object specifies a bitmap image with pixel data.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBitmapData

**Inheritance:** EmfPlusBaseBitmapData

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusBitmapData()](#EmfPlusBitmapData__1) | Initialise une nouvelle instance de la classe EmfPlusBitmapData |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| colors | [EmfPlusPalette](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspalette/) | r/w | Obtient ou définit les couleurs de la palette <br/>            Colors (variable) : Un objet optionnel [EmfPlusPalette](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspalette/) (section 2.2.2.28), qui spécifie la palette<br/>            des couleurs utilisées dans les données de pixel. Ce champ DOIT être présent si le drapeau I est défini dans le champ PixelFormat du<br/>            objet [EmfPlusBitmap](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusbitmap/). |
| pixel_data | System.Byte | r/w | Obtient ou définit les données de pixel <br/>            PixelData (variable) : Un tableau d'octets qui spécifie les données de pixel. La taille et le format de ces données peuvent être<br/>            calculés à partir des champs de l'objet EmfPlusBitmap, y compris le format de pixel provenant du<br/>            [EmfPlusPixelFormat](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluspixelformat/) énumération (section 2.1.1.25). |


### Constructor: EmfPlusBitmapData() {#EmfPlusBitmapData__1}


```
 EmfPlusBitmapData() 
```

Initialise une nouvelle instance de la classe EmfPlusBitmapData

