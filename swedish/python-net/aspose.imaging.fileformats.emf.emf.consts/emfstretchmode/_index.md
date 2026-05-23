---
title: "EmfStretchMode Enumeration"
type: docs
weight: 340
url: /sv/python-net/aspose.imaging.fileformats.emf.emf.consts/emfstretchmode/
---

Den StretchMode enumeration används för att specificera hur färgdata läggs till eller tas bort från bitmaps som sträcks eller komprimeras.

**Module:** [aspose.imaging.fileformats.emf.emf.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emf.consts.EmfStretchMode

## **Members**
| **Member name** | **Description** |
| :- | :- |
| STRETCH_ANDSCANS | Utför en boolesk AND‑operation med färgvärdena för de eliminerade och befintliga pixlarna.<br/>            Om bitmapen är en monokrom bitmap, bevarar detta läge svarta pixlar på bekostnad av vita pixlar. |
| STRETCH_DELETESCANS | Raderar pixlarna. Detta läge raderar alla eliminerade pixelrader utan att försöka bevara deras information. |
| STRETCH_HALFTONE | Mappar pixlar från källrektangeln till block av pixlar i destinationsrektangeln. <br/>            Den genomsnittliga färgen över destinationsblocket av pixlar approximera färgen på källpixlarna. |
| STRETCH_ORSCANS | Utför en boolesk OR‑operation med färgvärdena för de eliminerade och befintliga pixlarna. <br/>            Om bitmapen är en monokrom bitmap, bevarar detta läge vita pixlar på bekostnad av svarta pixlar. |
