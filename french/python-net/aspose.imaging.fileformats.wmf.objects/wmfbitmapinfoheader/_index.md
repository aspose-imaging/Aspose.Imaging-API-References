---
title: "WmfBitmapInfoHeader Classe"
type: docs
weight: 70
url: /fr/python-net/aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/
---

**Summary:** The BitmapInfoHeader Object contains information about the dimensions and color format of a device-independent<br/>                bitmap (DIB).

**Module:** [aspose.imaging.fileformats.wmf.objects](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/)

**Full Name:** aspose.imaging.fileformats.wmf.objects.WmfBitmapInfoHeader

**Inheritance:** WmfBitmapBaseHeader

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [WmfBitmapInfoHeader()](#WmfBitmapInfoHeader__1) | Initialise une nouvelle instance de la classe WmfBitmapInfoHeader |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| STRUCTURE_SIZE [static] | int | r | La taille de la structure |
| bit_count | [DibBitCount](/imaging/python-net/aspose.imaging.apsbuilder.dib/dibbitcount/) | r/w | Obtient ou définit un entier non signé de 16 bits qui définit le format de<br/>                chaque pixel, et le nombre maximal de couleurs dans le DIB. Cette valeur<br/>                DOIT être dans l'énumération [WmfBitmapBaseHeader.bit_count](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfbitmapbaseheader/) (section 2.1.1.3). |
| color_important | int | r/w | Obtient ou définit un entier non signé de 32 bits qui définit le nombre d'index de couleur requis pour l'affichage<br/>                du DIB.<br/>                Si cette valeur est zéro, tous les index de couleur sont requis |
| color_used | int | r/w | Obtient ou définit un entier non signé de 32 bits qui spécifie le nombre d'index dans la table de couleurs utilisée par le DIB, comme<br/>                suit :<br/>                Si cette valeur est zéro, le DIB utilise le nombre maximal de couleurs correspondant à la valeur BitCount.<br/>                Si cette valeur est non nulle et que la valeur BitCount est inférieure à 16, cette valeur indique le nombre de couleurs utilisées par<br/>                le DIB.<br/>                Si cette valeur est non nulle et que la valeur BitCount est de 16 ou plus, cette valeur indique la taille de la table de couleurs<br/>                utilisée pour optimiser les performances de la palette système.<br/>                Remarque : Si cette valeur est non nulle et supérieure à la taille maximale possible de la table de couleurs basée sur la valeur BitCount<br/>                , la taille maximale de la table de couleurs DOIT être supposée. |
| compression | [WmfCompression](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfcompression/) | r/w | Obtient ou définit un entier non signé de 32 bits qui définit le mode de compression du DIB. Cette valeur DOIT être dans l'<br/>                Énumération Compression (section 2.1.1.7).<br/>                Cette valeur DOIT NE PAS spécifier un format compressé si le DIB est un bitmap top-down, comme indiqué par la valeur Height. |
| header_size | int | r/w | Obtient ou définit un entier non signé de 32 bits qui définit la taille de cet<br/>                objet, en octets. |
| height | int | r/w | Obtient ou définit un entier signé de 32 bits qui définit la hauteur du DIB, en pixels. Cette valeur DOIT NE PAS être zéro.<br/>                Si cette valeur est positive, le DIB est un bitmap bottom-up, et son origine est le coin inférieur gauche.<br/>                Si cette valeur est négative, le DIB est un bitmap top-down, et son origine est le coin supérieur gauche. Les bitmaps top-down<br/>                ne prennent pas en charge la compression.<br/>                Ce champ DOIT spécifier la hauteur du fichier image décompressé, si la valeur Compression spécifie le format JPEG ou PNG<br/>                . |
| image_size | int | r/w | Obtient ou définit un entier non signé de 32 bits qui définit la taille, en octets, de l'image.<br/>                Si la valeur Compression est BI_RGB, cette valeur DOIT être zéro et DOIT être ignorée.<br/>                Si la valeur Compression est BI_JPEG ou BI_PNG, cette valeur DOIT spécifier la taille du tampon d'image JPEG ou PNG,<br/>                respectivement. |
| planes | int | r/w | Obtient ou définit un entier non signé de 16 bits qui définit le nombre de<br/>                [None](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfbitmapbaseheader/) pour le dispositif cible. Cette valeur DOIT être<br/>                0x0001. |
| width | int | r/w | Obtient ou définit un entier signé de 32 bits qui définit la largeur du DIB, en pixels. Cette valeur DOIT être positive.<br/>                Ce champ DOIT spécifier la largeur du fichier image décompressé, si la valeur Compression spécifie le format JPEG ou PNG<br/>                . |
| x_pels_per_meter | int | r/w | Obtient ou définit un entier signé de 32 bits qui définit la résolution horizontale, en pixels par mètre, du dispositif cible<br/>                du DIB |
| y_pels_per_meter | int | r/w | Obtient ou définit un entier signé de 32 bits qui définit la résolution verticale, en pixels par mètre, du dispositif cible<br/>                du DIB |


### Constructor: WmfBitmapInfoHeader() {#WmfBitmapInfoHeader__1}


```
 WmfBitmapInfoHeader() 
```

Initialise une nouvelle instance de la classe WmfBitmapInfoHeader

