---
title: "WmfClipPrecisionFlags uppräkning"
type: docs
weight: 50
url: /sv/python-net/aspose.imaging.fileformats.wmf.consts/wmfclipprecisionflags/
---

ClipPrecision‑flaggor specificerar klippningsprecision, vilket definierar hur tecken som är<br/>                delvis utanför ett klippningsområde ska klippas. Dessa flaggor kan kombineras för att ange flera alternativ.

**Module:** [aspose.imaging.fileformats.wmf.consts](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/)

**Full Name:** aspose.imaging.fileformats.wmf.consts.WmfClipPrecisionFlags

## **Members**
| **Member name** | **Description** |
| :- | :- |
| CHARACTER | Detta värde BÖR INTE användas. |
| DEFAULT | Anger att standardklippning MÅSTE användas. |
| DFA_DISABLE | Detta värde anger att teckensnittstillhörighet BÖR [35] vara avstängd.<br/>                [35] Detta värde stöds inte i Windows 95, Windows 98 och Windows Millennium Edition.<br/>                Teckensnittstillhörighet är avstängd i Windows 2000, Windows XP och Windows Server 2003.<br/>                Detta värde ignoreras i följande Windows-versioner:<br/>                - Windows Vista<br/>                - Windows Server 2008<br/>                - Windows 7<br/>                - Windows Server 2008 R2<br/>                - Windows 8<br/>                - Windows Server 2012<br/>                - Windows 8.1<br/>                - Windows Server 2012 R2 |
| EMBEDDED | Detta värde anger att teckensnittsinbäddning MÅSTE användas för att rendera dokumentets<br/>                innehåll; inbäddade teckensnitt är skrivskyddade. |
| LH_ANGLES | Detta värde används för att kontrollera teckensnittsrörelse, enligt följande:<br/>                - Om satt, bör rotationen för alla teckensnitt bestämmas av orienteringen<br/>                av koordinatsystemet; det vill säga om orienteringen är vänsterhänt<br/>                eller högrehänt.<br/>                - Om rensat, bör enhetsteckensnitt rotera moturs, men rotationen för<br/>                andra teckensnitt bör bestämmas av orienteringen av koordinatsystemet. |
| STROKE | Detta värde KAN returneras vid uppräkning av rasteriserade, TrueType- och<br/>                vektor­teckensnitt.<br/>                [33] (Windows NT 3.1, Windows NT 3.5, Windows NT 3.51, Windows NT 4.0,<br/>                Windows 2000 och Windows XP: Detta värde returneras alltid vid uppräkning av teckensnitt.) |
| TT_ALWAYS | Detta värde BÖR INTE [34] användas.<br/>                [34] Detta värde ignoreras i följande Windows-versioner:<br/>                - Windows Vista<br/>                - Windows Server 2008<br/>                - Windows 7<br/>                - Windows Server 2008 R2<br/>                - Windows 8<br/>                - Windows Server 2012<br/>                - Windows 8.1<br/>                - Windows Server 2012 R2 |
