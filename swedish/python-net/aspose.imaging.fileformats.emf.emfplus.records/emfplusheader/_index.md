---
title: "EmfPlusHeader klass"
type: docs
weight: 310
url: /sv/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusheader/
---

**Summary:** The EmfPlusHeader record specifies the start of EMF+ data in the metafile.<br/>            The EmfPlusHeader record MUST be embedded in an EMF EMR_COMMENT_EMFPLUS record,<br/>             which MUST be the record immediately following the EMF header in the metafile. <br/>            The EMR_COMMENT_EMFPLUS record is specified in [MS-EMF] section 2.3.3.2.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusHeader

**Inheritance:** EmfPlusControlRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusHeader(source)](#EmfPlusHeader_source_1) | Initierar en ny instans av klassen [EmfPlusHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusheader/) klass. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| data_size | int | r/w | Hämtar eller anger ett 32-bitars osignerat heltal som MÅSTE definiera det 32-bitars‑justerade antalet<br/>            databytes i RecordData‑fältet som följer. Detta tal inkluderar inte 12‑bytes posthuvudet. |
| dual_mode | bool | r/w | Hämtar eller anger ett värde som indikerar om [dual mode].<br/>            Om satt indikerar denna flagga att metafilen är \"dual-mode\", vilket betyder<br/>            att den innehåller två uppsättningar poster, där varje uppsättning fullständigt specificerar <br/>            grafikens innehåll. Om rensad specificeras grafikens innehåll av EMF+ <br/>            poster, och eventuellt EMF‑poster som föregås av en EmfPlusGetDC‑post. <br/>            Om denna flagga är satt bör EMF‑poster ensamma vara tillräckliga för att definiera <br/>            grafikens innehåll. Observera att oavsett om \"dual-mode\"‑flaggan är satt eller inte, så finns vissa <br/>            EMF‑poster alltid närvarande, nämligen EMF‑kontrollposter och EMF‑poster <br/>            som innehåller EMF+‑poster. EMF‑kontrollposter specificeras i [MS-EMF] <br/>            avsnitt 2.3.4. |
| emf_plus_flags | int | r/w | Hämtar eller anger EMF‑plus‑flaggorna.<br/>            Ett 32-bitars osignerat heltal som innehåller information om hur denna metafil spelades in.<br/>            om det 31:a biten i fältet är satt, indikerar denna flagga att metafilen spelades in med <br/>            en referensenhet för en videodisplay. Om rensad spelades metafilen in med<br/>            en referensenhet för en skrivare. |
| flaggor | int | r/w | Hämtar eller anger ett 16-bitars osignerat heltal som innehåller information för vissa poster om hur<br/>            operationen ska utföras och om postens struktur. |
| is_valid | bool | r | Hämtar ett värde som indikerar om denna instans är giltig. |
| logical_dpi_x | int | r/w | Hämtar eller anger den logiska dpi‑x.<br/>            Ett 32-bitars osignerat heltal som specificerar den horisontella upplösningen som metafilen <br/>            spelades in för, i enheter av pixlar per tum. |
| logical_dpi_y | int | r/w | Hämtar eller anger den logiska dpi‑y.<br/>            Ett 32-bitars osignerat heltal som specificerar den vertikala upplösningen som metafilen <br/>            spelades in för, i enheter av linjer per tum. |
| storlek | int | r/w | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar det 32-bitars‑justerade antalet bytes<br/>            i hela posten, inklusive 12‑bytes posthuvudet och post‑specifik data. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Hämtar ett 16-bitars osignerat heltal som identifierar posttypen. |
| version | [EmfPlusGraphicsVersion](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsversion/) | r/w | Hämtar eller anger versionen.<br/>            Ett EmfPlusGraphicsVersion‑objekt (avsnitt 2.2.2.19) som specificerar versionen av operativsystemets<br/>            grafik som användes för att skapa denna metafil. |
| video_display | bool | r/w | Hämtar eller anger ett värde som indikerar om videodisplay.<br/>            om satt indikerar denna flagga att metafilen spelades in med en referensenhet<br/>            för en videodisplay. Om rensad spelades metafilen in med en referensenhet<br/>            för en skrivare. |


### Constructor: EmfPlusHeader(source) {#EmfPlusHeader_source_1}


```
 EmfPlusHeader(source) 
```

Initierar en ny instans av klassen [EmfPlusHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusheader/) klass.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | Källan. |

