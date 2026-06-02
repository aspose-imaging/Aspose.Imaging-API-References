---
title: "Classe EmfPlusBitmap"
type: docs
weight: 50
url: /fr/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusbitmap/
---

**Summary:** The EmfPlusBitmap object specifies a bitmap that contains a graphics image.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBitmap

**Inheritance:** EmfPlusBaseImageData

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusBitmap()](#EmfPlusBitmap__1) | Initialise une nouvelle instance de la classe EmfPlusBitmap |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bitmap_data | [EmfPlusBaseBitmapData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasebitmapdata/) | r/w | Obtient ou définit les données du bitmap<br/>            BitmapData (variable) : Données de longueur variable qui définissent l'objet de données du bitmap spécifié dans le champ Type. Le<br/>            contenu et le format des données peuvent différer selon chaque type de bitmap. |
| height | int | r/w | Obtient ou définit la hauteur du bitmap<br/>            Height (4 octets) : Un entier signé de 32 bits qui spécifie la hauteur en pixels de la zone occupée par le bitmap.<br/>            Si l'image est compressée, selon le champ Type, cette valeur est indéfinie et DOIT être ignorée. |
| pixel_format | [EmfPlusPixelFormat](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluspixelformat/) | r/w | Obtient ou définit le format des pixels<br/>            PixelFormat (4 octets) : Un entier non signé de 32 bits qui spécifie le format des pixels qui composent l'image du bitmap.<br/>            Les formats de pixels pris en charge sont indiqués dans l'énumération [EmfPlusPixelFormat](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluspixelformat/) (section<br/>            2.1.1.25).<br/>            Si l'image est compressée, selon le champ Type, cette valeur est indéfinie et DOIT être ignorée. |
| stride | int | r/w | Obtient ou définit le stride de l'image<br/>            Stride (4 octets) : Un entier signé de 32 bits qui spécifie le décalage en octets entre le début d'une ligne de balayage et<br/>            la suivante. Cette valeur correspond au nombre d'octets par pixel, indiqué dans le champ PixelFormat, multiplié par<br/>            la largeur en pixels, indiquée dans le champ Width. La valeur de ce champ DOIT être un multiple de quatre.<br/>            Si l'image est compressée, selon le champ Type, cette valeur est indéfinie et DOIT être ignorée. |
| type | [EmfPlusBitmapDataType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusbitmapdatatype/) | r/w | Obtient ou définit le type de l'image<br/>            Type (4 octets) : Un entier non signé de 32 bits qui spécifie le type de données dans le champ BitmapData. Cette valeur DOIT<br/>            être définie dans l'énumération [EmfPlusBitmapDataType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusbitmapdatatype/) (section 2.1.1.2). |
| width | int | r/w | Obtient ou définit la largeur de l'image<br/>            Width (4 octets) : Un entier signé de 32 bits qui spécifie la largeur en pixels de la zone occupée par le bitmap.<br/>            Si l'image est compressée, selon le champ Type, cette valeur est indéfinie et DOIT être ignorée. |


### Constructor: EmfPlusBitmap() {#EmfPlusBitmap__1}


```
 EmfPlusBitmap() 
```

Initialise une nouvelle instance de la classe EmfPlusBitmap

