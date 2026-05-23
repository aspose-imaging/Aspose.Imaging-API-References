---
title: "EmfMapMode uppräkning"
type: docs
weight: 210
url: /sv/python-net/aspose.imaging.fileformats.emf.emf.consts/emfmapmode/
---

MapMode‑enumerationen används för att definiera måttenheten för att omvandla sidans <br/>            rymdenheter till enheterna i enhetsrymden och för att definiera orienteringen av ritningsaxlarna.

**Module:** [aspose.imaging.fileformats.emf.emf.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emf.consts.EmfMapMode

## **Members**
| **Member name** | **Description** |
| :- | :- |
| MM_ANISOTROPIC | Logiska enheter mappas till godtyckliga enheter med godtyckligt skalade axlar. <br/>            EMR_SETWINDOWEXTEX och EMR_SETVIEWPORTEXTEX-poster SHOULD användas för att ange enheterna, <br/>            orienteringen och skalningen. |
| MM_HIENGLISH | Varje logisk enhet mappas till 0,001 tum. Positiv x är åt höger; positiv y är uppåt. |
| MM_HIMETRIC | Varje logisk enhet mappas till 0,01 millimeter. Positiv x är åt höger; positiv y är uppåt. |
| MM_ISOTROPIC | Logiska enheter mappas till godtyckliga enheter med lika skalade axlar; det vill säga, en enhet <br/>            längs x-axeln är lika med en enhet längs y-axeln. EMR_SETWINDOWEXTEX- och <br/>            EMR_SETVIEWPORTEXTEX-poster SHOULD användas för att ange enheterna och orienteringen <br/>            av axlarna.<br/>            Justeringar MUST göras vid behov för att säkerställa att x- och y-enheterna förblir samma storlek. <br/>            Till exempel, när fönsterutbredningen sätts, MUST viewporten justeras för att hålla enheterna isotropa. |
| MM_LOENGLISH | Varje logisk enhet mappas till 0,01 tum. Positiv x är åt höger; positiv y är uppåt |
| MM_LOMETRIC | Varje logisk enhet mappas till 0,1 millimeter. Positiv x är åt höger; positiv y är uppåt. |
| MM_TEXT | Varje logisk enhet mappas till en enhetlig bildpunkt. Positiv x är åt höger; positiv y är nedåt. |
| MM_TWIPS | Varje logisk enhet mappas till en tjugondel av ett skrivarens punkt <br/>            (1/1440 tum, även kallad en "twip"). Positiv x är åt höger; positiv y är uppåt. |
