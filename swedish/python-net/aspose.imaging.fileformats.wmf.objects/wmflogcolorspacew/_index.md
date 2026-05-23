---
title: "WmfLogColorSpaceW-klass"
type: docs
weight: 390
url: /sv/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew/
---

**Summary:** The LogColorSpaceW object specifies a logical color space, which can be<br/>                defined by a color profile file with a name consisting of Unicode 16-bit<br/>                characters.

**Module:** [aspose.imaging.fileformats.wmf.objects](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/)

**Full Name:** aspose.imaging.fileformats.wmf.objects.WmfLogColorSpaceW

**Inheritance:** MetaObject

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [WmfLogColorSpaceW()](#WmfLogColorSpaceW__1) | Initierar en ny instans av klassen WmfLogColorSpaceW |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| color_space_type | [WmfLogicalColorSpaceEnum](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmflogicalcolorspaceenum/) | r/w | Hämtar eller anger ett 32‑bitars signerat heltal som specificerar färgrymdens<br/>                typ. Det MÅSTE definieras i LogicalColorSpace‑enumerationen<br/>                (avsnitt 2.1.1.14). Om detta värde är LCS_sRGB eller<br/>                LCS_WINDOWS_COLOR_SPACE, måste sRGB‑färgrymden användas. |
| endpoints | [WmfCieXyzTriple](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfciexyztriple/) | r/w | Hämtar eller anger ett CIEXYZTriple‑objekt (avsnitt 2.2.2.7) som definierar<br/>                CIE‑kromaticitets‑x, y och z‑koordinaterna för de tre färgerna<br/>                som motsvarar RGB [None](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew/) för den logiska<br/>                färgrymden som är associerad med bitmapen. Om<br/>                [WmfLogColorSpaceW.color_space_type](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew/)‑fältet inte specificerar<br/>                LCS_CALIBRATED_RGB, ska detta fält ignoreras. |
| filename | string | r/w | Hämtar eller anger en valfri, null‑terminerad Unicode UTF16‑LE‑teckensträng<br/>                som specificerar namnet på en fil som innehåller en färgprofil. Om ett filnamn anges, och<br/>                [WmfLogColorSpaceW.color_space_type](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew/)‑fältet är satt till LCS_CALIBRATED_RGB, bör de<br/>                övriga fälten i denna struktur ignoreras. |
| gamma_blue | int | r/w | Hämtar eller anger ett 32‑bitars fast‑punkt‑värde som definierar den tonade<br/>                responskurvan för blå. Om [WmfLogColorSpaceW.color_space_type](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew/)‑fältet<br/>                inte specificerar LCS_CALIBRATED_RGB, ska detta fält ignoreras. |
| gamma_green | int | r/w | Hämtar eller anger ett 32‑bitars fast‑punkt‑värde som definierar den tonade<br/>                responskurvan för grön. Om [WmfLogColorSpaceW.color_space_type](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew/)‑fältet<br/>                inte specificerar LCS_CALIBRATED_RGB, ska detta fält ignoreras. |
| gamma_red | int | r/w | Hämtar eller anger ett 32‑bitars fast‑punkt‑värde som definierar den tonade<br/>                responskurvan för röd. Om [WmfLogColorSpaceW.color_space_type](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew/)‑fältet<br/>                inte specificerar LCS_CALIBRATED_RGB, ska detta fält ignoreras. |
| intent | [WmfGamutMappingIntent](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfgamutmappingintent/) | r/w | Hämtar eller anger ett 32‑bitars signerat heltal som definierar gamut‑mappnings‑intentionen. Det MÅSTE definieras i GamutMappingIntent‑enumerationen<br/>                (avsnitt 2.1.1.11). |
| signature | int | r/w | Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar<br/>                [None](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew/) för färgrymdsobjekt; det MÅSTE sättas till<br/>                värdet 0x50534F43, vilket är ASCII‑kodningen av strängen<br/>                "PSOC". |
| size | int | r/w | Hämtar eller anger ett 32‑bitars osignerat heltal som definierar<br/>                [None](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew/) för detta objekt, i byte. |
| version | int | r/w | Hämtar eller anger ett 32‑bitars osignerat heltal som definierar ett<br/>                [None](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew/)‑nummer; det MÅSTE vara0x00000400. |


### Constructor: WmfLogColorSpaceW() {#WmfLogColorSpaceW__1}


```
 WmfLogColorSpaceW() 
```

Initierar en ny instans av klassen WmfLogColorSpaceW

