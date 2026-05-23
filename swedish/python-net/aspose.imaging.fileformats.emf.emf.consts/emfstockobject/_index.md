---
title: "EmfStockObject Enumeration"
type: docs
weight: 330
url: /sv/python-net/aspose.imaging.fileformats.emf.emf.consts/emfstockobject/
---

Den StockObject enumeration specificerar indexen för fördefinierade logiska grafikobjekt <br/>            som kan användas i grafikoperationer. De specifika strukturerna för stock‑objekt är <br/>            implementationsberoende; dock bör egenskaperna för stock‑objekt vara ekvivalenta med <br/>            egenskaperna för explicit skapade objekt av samma typ. <br/>            Dessa egenskaper specificeras där det är möjligt för de stock‑objekt som definieras i denna enumeration.

**Module:** [aspose.imaging.fileformats.emf.emf.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emf.consts.EmfStockObject

## **Members**
| **Member name** | **Description** |
| :- | :- |
| ANSI_FIXED_FONT | Ett fast breddteckensnitt som är ekvivalent med ett logiskt teckensnitt med följande egenskaper:<br/>            Charset: ANSI_CHARSET<br/>            PitchAndFamily: FF_DONTCARE + FIXED_PITCH |
| ANSI_VAR_FONT | Ett variabelbreddsteckensnitt som är ekvivalent med ett logiskt teckensnitt med följande egenskaper:<br/>            Charset: ANSI_CHARSET<br/>            PitchAndFamily: FF_DONTCARE + VARIABLE_PITCH |
| BLACK_BRUSH | En svart, solid färgpensel som är ekvivalent med en logisk pensel med följande egenskaper:<br/>            BrushStyle: BS_SOLID<br/>            Color: 0x00000000 |
| BLACK_PEN | En svart, solidfärgad penna som är ekvivalent med en logisk penna med följande egenskaper:<br/>            PenStyle: PS_COSMETIC + PS_SOLID<br/>            ColorRef: 0x00000000 |
| DC_BRUSH | Den solidfärgade penseln som för närvarande är vald i uppspelningsenhetens kontext |
| DC_PEN | Den solidfärgade pennan som för närvarande är vald i uppspelningsenhetens kontext |
| DEFAULT_GUI_FONT | Ett fast breddteckensnitt som garanteras vara tillgängligt i operativsystemet. <br/>            Det faktiska teckensnittet som specificeras av detta värde är implementationsberoende |
| DEFAULT_PALETTE | Den standardpalett som definieras för den aktuella utdataenheten. <br/>            Den faktiska paletten som specificeras av detta värde är implementationsberoende |
| DEVICE_DEFAULT_FONT | Det standardteckensnitt som tillhandahålls av grafikdrivrutinen för den aktuella utdataenheten. <br/>            Det faktiska teckensnittet som specificeras av detta värde är implementationsberoende |
| DKGRAY_BRUSH | En mörkgrå, solid färgborste som är ekvivalent med en logisk borste med följande egenskaper:<br/>            BrushStyle: BS_SOLID<br/>            Color: 0x00404040 |
| GRAY_BRUSH | En grå, solid-färgsborste som är ekvivalent med en logisk borste med följande egenskaper:<br/>            BrushStyle: BS_SOLID<br/>            Color: 0x00808080 |
| LTGRAY_BRUSH | En ljusgrå, solid-färgsborste som är ekvivalent med en logisk borste med följande egenskaper:<br/>            BrushStyle: BS_SOLID<br/>            Color: 0x00C0C0C0 |
| NULL_BRUSH | En nullborste som är ekvivalent med en logisk borste med följande egenskaper:<br/>            BrushStyle: BS_NULL |
| NULL_PEN | En nullpenna som är ekvivalent med en logisk penna med följande egenskaper:<br/>            PenStyle: PS_NULL |
| OEM_FIXED_FONT | Ett fast bredd, OEM-teckenuppsättningsfont som är ekvivalent med ett logiskt teckensnitt <br/>            (LogFont-objekt, avsnitt 2.2.13) med följande egenskaper:<br/>            Charset: OEM_CHARSET (WMF CharacterSet-enumeration, [MS-WMF] avsnitt 2.1.1.5)<br/>            PitchAndFamily: FF_DONTCARE (WMF FamilyFont-enumeration, [MS-WMF] avsnitt 2.1.1.8) <br/>            + FIXED_PITCH (WMF PitchFont-enumeration, [MS-WMF] avsnitt 2.1.24) |
| SYSTEM_FIXED_FONT | Ett fast breddteckensnitt som garanteras vara tillgängligt i operativsystemet. <br/>            Det faktiska teckensnittet som specificeras av detta värde är implementationsberoende |
| SYSTEM_FONT | Ett teckensnitt som garanteras vara tillgängligt i operativsystemet. <br/>            Det faktiska teckensnittet som specificeras av detta värde är implementationsberoende |
| WHITE_BRUSH | En vit, solid-färgsborste som är ekvivalent med en logisk borste <br/>            (LogBrushEx-objekt, avsnitt 2.2.12) med följande egenskaper:<br/>            BrushStyle: BS_SOLID (WMF BrushStyle-enumeration, [MS-WMF] avsnitt 2.1.1.4)<br/>            Color: 0x00FFFFFF (WMF ColorRef-objekt, [MS-WMF] avsnitt 2.2.2.8) |
| WHITE_PEN | En vit, solid-färgspenna som är ekvivalent med en logisk penna (LogPen-objekt, avsnitt 2.2.19)<br/>            med följande egenskaper:<br/>            PenStyle: PS_COSMETIC + PS_SOLID (PenStyle-enumeration, avsnitt 2.1.25)<br/>            ColorRef: 0x00FFFFFF (WMF ColorRef-objekt). |
