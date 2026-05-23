---
title: "WmfLogColorSpaceW Klasse"
type: docs
weight: 390
url: /de/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew/
---

**Summary:** The LogColorSpaceW object specifies a logical color space, which can be<br/>                defined by a color profile file with a name consisting of Unicode 16-bit<br/>                characters.

**Module:** [aspose.imaging.fileformats.wmf.objects](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/)

**Full Name:** aspose.imaging.fileformats.wmf.objects.WmfLogColorSpaceW

**Inheritance:** MetaObject

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [WmfLogColorSpaceW()](#WmfLogColorSpaceW__1) | Initialisiert eine neue Instanz der Klasse WmfLogColorSpaceW |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| color_space_type | [WmfLogicalColorSpaceEnum](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmflogicalcolorspaceenum/) | r/w | Liest oder schreibt einen 32‑Bit vorzeichenbehafteten Integer, der den Farbraum<br/>                Typ angibt. Er MUSS in der LogicalColorSpace‑Aufzählung definiert sein<br/>                (Abschnitt 2.1.1.14). Wenn dieser Wert LCS_sRGB oder<br/>                LCS_WINDOWS_COLOR_SPACE ist, MUSS der sRGB‑Farbraum verwendet werden. |
| endpoints | [WmfCieXyzTriple](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfciexyztriple/) | r/w | Liest oder schreibt ein CIEXYZTriple‑Objekt (Abschnitt 2.2.2.7), das die CIE‑Chromatizitäts‑x‑, y‑ und z‑Koordinaten der drei Farben definiert,<br/>                die dem RGB [None](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew/) für den logischen<br/>                Farbraum des zugehörigen Bitmaps entsprechen. Wenn das Feld<br/>                [WmfLogColorSpaceW.color_space_type](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew/) nicht<br/>                LCS_CALIBRATED_RGB angibt, MUSS dieses Feld ignoriert werden. |
| filename | string | r/w | Liest oder schreibt einen optionalen, nullterminierten Unicode‑UTF16‑LE‑Zeichenstring, der den Namen einer Datei angibt, die ein Farbprofil enthält.<br/>                Wenn ein Dateiname angegeben ist und das Feld<br/>                [WmfLogColorSpaceW.color_space_type](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew/) auf LCS_CALIBRATED_RGB gesetzt ist, SOLLTEN die anderen Felder dieser Struktur ignoriert werden. |
| gamma_blue | int | r/w | Liest oder schreibt einen 32‑Bit‑Festkommawert, der die abgestufte<br/>                Antwortkurve für Blau definiert. Wenn das Feld [WmfLogColorSpaceW.color_space_type](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew/) nicht LCS_CALIBRATED_RGB angibt, MUSS dieses Feld ignoriert werden. |
| gamma_green | int | r/w | Liest oder schreibt einen 32‑Bit‑Festkommawert, der die abgestufte<br/>                Antwortkurve für Grün definiert. Wenn das Feld [WmfLogColorSpaceW.color_space_type](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew/) nicht LCS_CALIBRATED_RGB angibt, MUSS dieses Feld ignoriert werden. |
| gamma_red | int | r/w | Liest oder schreibt einen 32‑Bit‑Festkommawert, der die abgestufte<br/>                Antwortkurve für Rot definiert. Wenn das Feld [WmfLogColorSpaceW.color_space_type](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew/) nicht LCS_CALIBRATED_RGB angibt, MUSS dieses Feld ignoriert werden. |
| intent | [WmfGamutMappingIntent](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfgamutmappingintent/) | r/w | Liest oder schreibt einen 32‑Bit vorzeichenbehafteten Integer, der die Gamut‑Mapping‑Intention definiert.<br/>                Er MUSS in der GamutMappingIntent‑Aufzählung definiert sein<br/>                (Abschnitt 2.1.1.11). |
| signature | int | r/w | Liest oder schreibt einen 32‑Bit vorzeichenlosen Integer, der das<br/>                [None](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew/) von Farbraumobjekten angibt; er MUSS auf den Wert 0x50534F43 gesetzt werden, der die ASCII‑Kodierung der Zeichenkette<br/>                \"PSOC\" ist. |
| size | int | r/w | Liest oder schreibt einen 32‑Bit vorzeichenlosen Integer, der das<br/>                [None](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew/) dieses Objekts in Bytes definiert. |
| version | int | r/w | Liest oder schreibt einen 32‑Bit vorzeichenlosen Integer, der eine<br/>                [None](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew/)‑Nummer definiert; er MUSS 0x00000400 sein. |


### Constructor: WmfLogColorSpaceW() {#WmfLogColorSpaceW__1}


```
 WmfLogColorSpaceW() 
```

Initialisiert eine neue Instanz der Klasse WmfLogColorSpaceW

