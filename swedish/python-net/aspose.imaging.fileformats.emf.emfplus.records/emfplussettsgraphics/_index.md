---
title: "EmfPlusSetTsGraphics klass"
type: docs
weight: 580
url: /sv/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/
---

**Summary:** The EmfPlusSetTSGraphics record specifies the state of a graphics device context for a terminal server.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusSetTsGraphics

**Inheritance:** EmfPlusTerminalServerRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusSetTsGraphics(source)](#EmfPlusSetTsGraphics_source_1) | Initierar en ny instans av klassen [EmfPlusSetTsGraphics](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| anti_alias_mode | [EmfPlusSmoothingMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplussmoothingmode/) | r/w | Hämtar eller anger ett 8-bitars osignerat heltal som specificerar kvaliteten på linjerendering,<br/>            inklusive typen av linjeantialiasing. Det MÅSTE definieras i SmoothingMode‑enumerationen<br/>            (avsnitt 2.1.1.28). |
| basic_vga_colors | bool | r | Hämtar ett värde som indikerar om [basic vga colors].<br/>            Om satt innehåller paletten endast de grundläggande VGA-färgerna. |
| compositing_mode | [EmfPlusCompositingMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluscompositingmode/) | r/w | Hämtar eller anger ett 8-bitars osignerat heltal som specificerar hur källfärger<br/>            kombineras med bakgrundsfärger. Det MÅSTE vara ett värde i CompositingMode‑enumerationen<br/>            (avsnitt 2.1.1.5). |
| compositing_quality | [EmfPlusCompositingQuality](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluscompositingquality/) | r/w | Hämtar eller anger ett 8-bitars osignerat heltal som specificerar graden av<br/>            utjämning som ska tillämpas på linjer, kurvor och kanterna på fyllda områden för att få dem att framstå mer<br/>            kontinuerliga eller skarpt definierade. Det MÅSTE vara ett värde i CompositingQuality‑enumerationen (avsnitt 2.1.1.6). |
| data_size | int | r/w | Hämtar eller anger ett 32-bitars osignerat heltal som MÅSTE definiera det 32-bitars‑justerade antalet<br/>            databytes i RecordData‑fältet som följer. Detta tal inkluderar inte 12‑bytes posthuvudet. |
| filter_type | [EmfPlusFilterType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusfiltertype/) | r/w | Hämtar eller anger ett 8-bitars osignerat heltal som specificerar hur skalning, inklusive sträckning<br/>            och krympning, utförs. Det MÅSTE vara ett värde i FilterType‑enumerationen (avsnitt 2.1.1.11). |
| flaggor | int | r/w | Hämtar eller anger ett 16-bitars osignerat heltal som innehåller information för vissa poster om hur<br/>            operationen ska utföras och om postens struktur. |
| have_palette | bool | r | Hämtar ett värde som indikerar om [have palette].<br/>            Om satt innehåller denna post ett EmfPlusPalette‑objekt (avsnitt 2.2.2.28) i<br/>            Palette‑fältet efter grafikstatusdata. |
| palette | [EmfPlusPalette](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspalette/) | r/w | Hämtar eller anger ett valfritt EmfPlusPalette‑objekt. |
| pixel_offset | [EmfPlusPixelOffsetMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluspixeloffsetmode/) | r/w | Hämtar eller anger ett 8-bitars osignerat heltal som specificerar den övergripande kvaliteten på bild<br/>            och textrenderingsprocessen. Det MÅSTE vara ett värde i PixelOffsetMode‑enumerationen (avsnitt 2.1.1.26). |
| render_origin_x | int | r/w | Hämtar eller anger ett 16-bitars signerat heltal, vilket är den horisontella koordinaten för<br/>            ursprunget för rendering av halftoning‑ och dithermatriser. |
| render_origin_y | int | r/w | Hämtar eller anger ett 16-bitars signerat heltal, vilket är den vertikala koordinaten för ursprunget<br/>            för rendering av halftoning‑ och dithermatriser. |
| storlek | int | r/w | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar det 32-bitars‑justerade antalet bytes<br/>            i hela posten, inklusive 12‑bytes posthuvudet och post‑specifik data. |
| text_contrast | int | r/w | Hämtar eller anger ett 16-bitars osignerat heltal som specificerar gamma‑korrektionsvärdet<br/>            som används för rendering av antialiasad och ClearType‑text. Detta värde MÅSTE ligga i intervallet 0 till 12, inklusive. |
| text_render_hint | [EmfPlusTextRenderingHint](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplustextrenderinghint/) | r/w | Hämtar eller anger ett 8-bitars osignerat heltal som specificerar kvaliteten på text<br/>            rendering, inklusive typen av textantialiasing. Det MÅSTE definieras i<br/>            TextRenderingHint‑enumerationen (avsnitt 2.1.1.32). |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Hämtar ett 16-bitars osignerat heltal som identifierar posttypen. |
| world_to_device | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | Hämtar eller anger ett 192-bitars EmfPlusTransformMatrix-objekt (avsnitt 2.2.2.47) som<br/> specificerar transformeringar från världsrummet till enhetsrummet. |


### Constructor: EmfPlusSetTsGraphics(source) {#EmfPlusSetTsGraphics_source_1}


```
 EmfPlusSetTsGraphics(source) 
```

Initierar en ny instans av klassen [EmfPlusSetTsGraphics](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | Källan. |

