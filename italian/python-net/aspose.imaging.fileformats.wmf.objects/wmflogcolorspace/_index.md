---
title: "WmfLogColorSpace Classe"
type: docs
weight: 380
url: /it/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/
---

**Summary:** The LogColorSpace object specifies a logical color space for the<br/>                playback device context, which can be the name of a color profile in<br/>                ASCII characters.

**Module:** [aspose.imaging.fileformats.wmf.objects](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/)

**Full Name:** aspose.imaging.fileformats.wmf.objects.WmfLogColorSpace

**Inheritance:** MetaObject

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [WmfLogColorSpace()](#WmfLogColorSpace__1) | Inizializza una nuova istanza della classe WmfLogColorSpace |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| color_space_type | [WmfLogicalColorSpaceEnum](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmflogicalcolorspaceenum/) | r/w | Ottiene o imposta un intero con segno a 32 bit che specifica lo spazio colore<br/>                tipo. DEVE essere definito nell'enumerazione LogicalColorSpace<br/>                (sezione 2.1.1.14). Se questo valore è LCS_sRGB o<br/>                LCS_WINDOWS_COLOR_SPACE, lo spazio colore sRGB DEVE essere usato. |
| endpoints | [WmfCieXyzTriple](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfciexyztriple/) | r/w | Ottiene o imposta un oggetto CIEXYZTriple (sezione 2.2.2.7) che definisce<br/>                le coordinate di cromaticità CIE x, y e z dei tre colori<br/>                che corrispondono al RGB [None](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/) per lo spazio colore logico<br/>                associato al bitmap. Se il campo<br/>                [WmfLogColorSpace.color_space_type](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/) non specifica<br/>                LCS_CALIBRATED_RGB, questo campo DEVE essere ignorato. |
| filename | string | r/w | Ottiene o imposta una stringa di caratteri ASCII opzionale che specifica il<br/>                nome di un file che contiene un profilo colore. Se è specificato un nome file, e il campo [WmfLogColorSpace.color_space_type](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/) è impostato a LCS_CALIBRATED_RGB, gli altri campi di questa struttura DEVE essere ignorati. |
| gamma_blue | int | r/w | Ottiene o imposta un valore a punto fisso a 32 bit che definisce la curva di risposta tonificata<br/>                per il blu. Se il campo [WmfLogColorSpace.color_space_type](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/) non specifica LCS_CALIBRATED_RGB, questo campo DEVE essere ignorato. |
| gamma_green | int | r/w | Ottiene o imposta un valore a punto fisso a 32 bit che definisce la curva di risposta tonificata<br/>                per il verde. Se il campo [WmfLogColorSpace.color_space_type](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/) non specifica LCS_CALIBRATED_RGB, questo campo DEVE essere ignorato. |
| gamma_red | int | r/w | Ottiene o imposta un valore a punto fisso a 32 bit che definisce la curva di risposta tonificata<br/>                per il rosso. Se il campo [WmfLogColorSpace.color_space_type](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/) non specifica LCS_CALIBRATED_RGB, questo campo DEVE essere ignorato. |
| intent | [WmfGamutMappingIntent](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfgamutmappingintent/) | r/w | Ottiene o imposta un intero con segno a 32 bit che definisce l'intento di mappatura del gamut. DEVE essere definito nell'enumerazione GamutMappingIntent<br/>                (sezione 2.1.1.11). |
| signature | int | r/w | Ottiene o imposta un intero senza segno a 32 bit che specifica il<br/>                [None](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/) degli oggetti spazio colore; DEVE essere impostato al<br/>                valore 0x50534F43, che è la codifica ASCII della stringa<br/>                "PSOC". |
| size | int | r/w | Ottiene o imposta un intero senza segno a 32 bit che definisce il<br/>                [None](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/) di questo oggetto, in byte. |
| version | int | r/w | Ottiene o imposta un intero senza segno a 32 bit che definisce un<br/>                [None](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/) numero; DEVE essere 0x00000400. |


### Constructor: WmfLogColorSpace() {#WmfLogColorSpace__1}


```
 WmfLogColorSpace() 
```

Inizializza una nuova istanza della classe WmfLogColorSpace

