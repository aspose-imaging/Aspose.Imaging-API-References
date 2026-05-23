---
title: "EmfExtTextOutOptions uppräkning"
type: docs
weight: 100
url: /sv/python-net/aspose.imaging.fileformats.emf.emf.consts/emfexttextoutoptions/
---

ExtTextOutOptions‑enumerationen specificerar parametrar som styr olika aspekter av<br/>            textutmatning via EMR_SMALLTEXTOUT‑poster (avsnitt 2.3.5.37) och i EmrText‑objekt.

**Module:** [aspose.imaging.fileformats.emf.emf.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emf.consts.EmfExtTextOutOptions

## **Members**
| **Member name** | **Description** |
| :- | :- |
| ETO_CLIPPED | Den här biten indikerar att texten SKALL klippas till rektangeln. |
| ETO_GLYPH_INDEX | Den här biten indikerar att koderna för tecken i en utdata-textsträng faktiskt är <br/>            index för teckenglyfer i ett TrueType-typsnitt. Glyfindex är typsnittsspecifika, <br/>            så för att visa de korrekta tecknen vid uppspelning, måste det typsnitt som används VARA <br/>            identiskt med det typsnitt som användes för att generera indexen. |
| ETO_IGNORELANGUAGE | Den här biten indikerar att ingen speciell operativsystembehandling för glyfplacering ska <br/>            utföras på höger-till-vänster-strängar; det vill säga, all glyfpositionering SKALL tas om hand av <br/>            ritning och tillståndsposter i metafilen. |
| ETO_NO_RECT | Den här biten indikerar att posten inte specificerar en avgränsande rektangel för textutdata. |
| ETO_NUMERICSLATIN | Den här biten indikerar att för att visa siffror bör europeiska siffror SKALL användas |
| ETO_NUMERICSLOCAL | Den här biten indikerar att för att visa siffror bör siffror som är lämpliga för den aktuella lokalen SKALL användas |
| ETO_OPAQUE | Den här biten indikerar att den aktuella bakgrundsfärgen SKALL användas för att fylla rektangeln |
| ETO_PDY | Den här biten indikerar att både horisontella och vertikala teckenförskjutningsvärden SKALL tillhandahållas |
| ETO_REVERSE_INDEX_MAP | Den här biten är reserverad och SKALL INTE användas |
| ETO_RTLREADING | Den här biten indikerar att texten MÅSTE läggas ut i högra-till-vänstra läsordning, <br/>            istället för standard vänstra-till-högra ordning. Detta BÖR endast tillämpas när teckensnittet<br/>            som valts i uppspelningsenhetens kontext är antingen hebreiska eller arabiska |
| ETO_SMALL_CHARS | Den här biten indikerar att koderna för tecken i en utdata‑textsträng är 8 bitar, <br/>            härledda från de låga bytena i 16‑bitars Unicode UTF16‑LE teckenkoder, <br/>            där den högre byten antas vara 0. |
