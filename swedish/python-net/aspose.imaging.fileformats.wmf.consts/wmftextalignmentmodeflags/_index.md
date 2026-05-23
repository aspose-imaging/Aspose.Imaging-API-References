---
title: "WmfTextAlignmentModeFlags uppräkning"
type: docs
weight: 270
url: /sv/python-net/aspose.imaging.fileformats.wmf.consts/wmftextalignmentmodeflags/
---

TextAlignmentMode‑flaggor specificerar förhållandet mellan en referenspunkt och en avgränsande<br/>                rektangel för textjustering. Dessa flaggor kan kombineras för att specificera flera alternativ, med den<br/>                begränsning att endast en flagga kan väljas som ändrar ritpositionen i uppspelningsenhetens<br/>                kontext.<br/>                Horisontell textjustering utförs när teckensnittet har en horisontell standardbaslinje.

**Module:** [aspose.imaging.fileformats.wmf.consts](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/)

**Full Name:** aspose.imaging.fileformats.wmf.consts.WmfTextAlignmentModeFlags

## **Members**
| **Member name** | **Description** |
| :- | :- |
| BASELINE | Referenspunkten MUST vara på baslinjen för texten. |
| BOTTOM | Referenspunkten MUST vara på den nedre kanten av den avgränsande rektangeln. |
| CENTER | Referenspunkten MUST vara horisontellt justerad med mitten av den omgivande rektangeln. |
| HORIZONTAL | Representerar horisontella textjusteringsuppsättningar (Left | Höger | Center) |
| LEFT | Referenspunkten MUST vara på den vänstra kanten av den avgränsande rektangeln. |
| NOUPDATECP | Ritpositionen i uppspelningsenhetens kontext MUST NOT uppdateras efter varje<br/>                textutmatningsanrop. Referenspunkten MUST skickas till textutmatningsfunktionen. |
| RIGHT | Referenspunkten MUST vara på den högra kanten av den avgränsande rektangeln. |
| RTLREADING | Texten MUST läggas ut i läsordning från höger till vänster, istället för standardordning från vänster till höger. Detta SHOULD<br/>                tillämpas endast när teckensnittet som definieras i uppspelnings<br/>                enhetens kontext är antingen hebreiska eller arabiska. |
| TOP | Referenspunkten MUST vara på den övre kanten av den avgränsande rektangeln. |
| UPDATECP | Ritpositionen i uppspelningsenhetens kontext MUST uppdateras efter varje text<br/>                utmatningsanrop. Den MUST användas som referenspunkten. |
| VERTICAL | Representerar vertikala textjusteringsuppsättningar (Top | Botten | Baseline) |
