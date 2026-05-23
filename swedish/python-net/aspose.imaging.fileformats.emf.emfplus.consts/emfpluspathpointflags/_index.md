---
title: "EmfPlusPathPointFlags Enumeration"
type: docs
weight: 290
url: /sv/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluspathpointflags/
---

En 32-bitars osignerad heltal som specificerar hur punkterna och tillhörande puntstyper som definieras av detta objekt ska tolkas.<br/>            C  (1 bit): Om satt, anger PathPoints‑arrayen absoluta positioner i koordinatrymden med 16-bitars heltalskoordinater.<br/>             Om rensad, anger PathPoints‑arrayen absoluta positioner i koordinatrymden med 32-bitars flyttalskoordinater.<br/>             Obs! Om P‑flaggan (nedan) är satt, kan denna flagga VARA rensad och MÅSTE ignoreras.<br/>            R (1 bit): Om satt, specificeras puntstyperna i PathPointTypes‑arrayen av EmfPlusPathPointTypeRle‑objekt (avsnitt 2.2.2.32), <br/>             som använder run‑length‑kodning (RLE)‑komprimering, och/eller EmfPlusPathPointType‑objekt (avsnitt 2.2.2.31). Se [MS-WMF] avsnitt 3.1.6 för mer information om RLE‑komprimering.<br/>             Om rensad, specificeras puntstyperna i PathPointTypes‑arrayen av EmfPlusPathPointType‑objekt.<br/>            P (1 bit): Om satt, anger varje element i PathPoints‑arrayen en position i koordinatrymden som är relativ till den<br/>             position som anges av föregående element i arrayen. För det första elementet i PathPoints antas en föregående position vid koordinaterna (0,0).<br/>             Om rensad, anger varje element i PathPoints‑arrayen en absolut position.

**Module:** [aspose.imaging.fileformats.emf.emfplus.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.consts.EmfPlusPathPointFlags

## **Members**
| **Member name** | **Description** |
| :- | :- |
| C | c-flaggan |
| P | p-flaggan |
| R | r-flaggan |
