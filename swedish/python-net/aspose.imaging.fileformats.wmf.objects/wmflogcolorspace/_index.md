---
title: "WmfLogColorSpace-klass"
type: docs
weight: 380
url: /sv/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/
---

**Summary:** The LogColorSpace object specifies a logical color space for the<br/>                playback device context, which can be the name of a color profile in<br/>                ASCII characters.

**Module:** [aspose.imaging.fileformats.wmf.objects](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/)

**Full Name:** aspose.imaging.fileformats.wmf.objects.WmfLogColorSpace

**Inheritance:** MetaObject

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [WmfLogColorSpace()](#WmfLogColorSpace__1) | Initierar en ny instans av klassen WmfLogColorSpace |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| color_space_type | [WmfLogicalColorSpaceEnum](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmflogicalcolorspaceenum/) | r/w | Hämtar eller anger ett 32‑bitars signerat heltal som specificerar färgrymdens<br/>                typ. Det MÅSTE definieras i LogicalColorSpace‑enumerationen<br/>                (avsnitt 2.1.1.14). Om detta värde är LCS_sRGB eller<br/>                LCS_WINDOWS_COLOR_SPACE, måste sRGB‑färgrymden användas. |
| endpoints | [WmfCieXyzTriple](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfciexyztriple/) | r/w | Hämtar eller anger ett CIEXYZTriple‑objekt (avsnitt 2.2.2.7) som definierar<br/>                CIE‑kromaticitets‑x, y och z‑koordinaterna för de tre färgerna<br/>                som motsvarar RGB [None](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/) för den logiska<br/>                färgrymden som är associerad med bitmapen. Om<br/>                [WmfLogColorSpace.color_space_type](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/)‑fältet inte specificerar<br/>                LCS_CALIBRATED_RGB, ska detta fält ignoreras. |
| filename | string | r/w | Hämtar eller anger en valfri ASCII‑teckensträng som specificerar<br/>                namnet på en fil som innehåller en färgprofil. Om ett filnamn är<br/>                angivet, och [WmfLogColorSpace.color_space_type](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/)‑fältet är satt till<br/>                LCS_CALIBRATED_RGB, bör de övriga fälten i denna struktur ignoreras. |
| gamma_blue | int | r/w | Hämtar eller anger ett 32‑bitars fast‑punkt‑värde som definierar den tonade<br/>                responskurvan för blå. Om [WmfLogColorSpace.color_space_type](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/)‑fältet<br/>                inte specificerar LCS_CALIBRATED_RGB, ska detta fält ignoreras. |
| gamma_green | int | r/w | Hämtar eller anger ett 32‑bitars fast‑punkt‑värde som definierar den tonade<br/>                responskurvan för grön. Om [WmfLogColorSpace.color_space_type](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/)‑fältet<br/>                inte specificerar LCS_CALIBRATED_RGB, ska detta fält ignoreras. |
| gamma_red | int | r/w | Hämtar eller anger ett 32‑bitars fast‑punkt‑värde som definierar den tonade<br/>                responskurvan för röd. Om [WmfLogColorSpace.color_space_type](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/)‑fältet<br/>                inte specificerar LCS_CALIBRATED_RGB, ska detta fält ignoreras. |
| intent | [WmfGamutMappingIntent](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfgamutmappingintent/) | r/w | Hämtar eller anger ett 32‑bitars signerat heltal som definierar gamut‑mappnings‑intentionen. Det MÅSTE definieras i GamutMappingIntent‑enumerationen<br/>                (avsnitt 2.1.1.11). |
| signature | int | r/w | Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar<br/>                [None](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/) för färgrymdsobjekt; det MÅSTE sättas till<br/>                värdet 0x50534F43, vilket är ASCII‑kodningen av strängen<br/>                "PSOC". |
| size | int | r/w | Hämtar eller anger ett 32‑bitars osignerat heltal som definierar<br/>                [None](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/) för detta objekt, i byte. |
| version | int | r/w | Hämtar eller anger ett 32‑bitars osignerat heltal som definierar ett<br/>                [None](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/)‑nummer; det MÅSTE vara0x00000400. |


### Constructor: WmfLogColorSpace() {#WmfLogColorSpace__1}


```
 WmfLogColorSpace() 
```

Initierar en ny instans av klassen WmfLogColorSpace

