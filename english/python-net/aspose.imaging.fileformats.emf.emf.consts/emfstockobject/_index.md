---
title: EmfStockObject Enumeration
type: docs
weight: 330
url: /python-net/aspose.imaging.fileformats.emf.emf.consts/emfstockobject/
---

The StockObject enumeration specifies the indexes of predefined logical graphics objects <br/>            that can be used in graphics operations.The specific structures of stock objects are <br/>            implementation-dependent; however, the properties of stock objects SHOULD be equivalent to <br/>            the properties of explicitly created objects of the same type. <br/>            These properties are specified where possible for the stock objects defined in this enumeration.

**Module:** [aspose.imaging.fileformats.emf.emf.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emf.consts.EmfStockObject

## **Members**
| **Member name** | **Description** |
| :- | :- |
| ANSI_FIXED_FONT | A fixed-width font that is equivalent to a logical font with the following properties:<br/>            Charset: ANSI_CHARSET<br/>            PitchAndFamily: FF_DONTCARE + FIXED_PITCH |
| ANSI_VAR_FONT | A variable-width font that is equivalent to a logical font with the following properties:<br/>            Charset: ANSI_CHARSET<br/>            PitchAndFamily: FF_DONTCARE + VARIABLE_PITCH |
| BLACK_BRUSH | A black, solid color brush that is equivalent to a logical brush with the following properties:<br/>            BrushStyle: BS_SOLID<br/>            Color: 0x00000000 |
| BLACK_PEN | A black, solid-color pen that is equivalent to a logical pen with the following properties:<br/>            PenStyle: PS_COSMETIC + PS_SOLID<br/>            ColorRef: 0x00000000 |
| DC_BRUSH | The solid-color brush that is currently selected in the playback device context |
| DC_PEN | The solid-color pen that is currently selected in the playback device context |
| DEFAULT_GUI_FONT | A fixed-width font that is guaranteed to be available in the operating system. <br/>            The actual font that is specified by this value is implementation-dependent |
| DEFAULT_PALETTE | The default palette that is defined for the current output device. <br/>            The actual palette that is specified by this value is implementation-dependent |
| DEVICE_DEFAULT_FONT | The default font that is provided by the graphics device driver for the current output device. <br/>            The actual font that is specified by this value is implementation-dependent |
| DKGRAY_BRUSH | A dark gray, solid color brush that is equivalent to a logical brush with the following properties:<br/>            BrushStyle: BS_SOLID<br/>            Color: 0x00404040 |
| GRAY_BRUSH | A gray, solid-color brush that is equivalent to a logical brush with the following properties:<br/>            BrushStyle: BS_SOLID<br/>            Color: 0x00808080 |
| LTGRAY_BRUSH | A light gray, solid-color brush that is equivalent to a logical brush with the following properties:<br/>            BrushStyle: BS_SOLID<br/>            Color: 0x00C0C0C0 |
| NULL_BRUSH | A null brush that is equivalent to a logical brush with the following properties:<br/>            BrushStyle: BS_NULL |
| NULL_PEN | A null pen that is equivalent to a logical pen with the following properties:<br/>            PenStyle: PS_NULL |
| OEM_FIXED_FONT | A fixed-width, OEM character set font that is equivalent to a logical font <br/>            (LogFont object, section 2.2.13) with the following properties:<br/>            Charset: OEM_CHARSET (WMF CharacterSet enumeration, [MS-WMF] section 2.1.1.5)<br/>            PitchAndFamily: FF_DONTCARE (WMF FamilyFont enumeration, [MS-WMF] section 2.1.1.8) <br/>            + FIXED_PITCH (WMF PitchFont enumeration, [MS-WMF] section 2.1.1.24) |
| SYSTEM_FIXED_FONT | A fixed-width font that is guaranteed to be available in the operating system. <br/>            The actual font that is specified by this value is implementation-dependent |
| SYSTEM_FONT | A font that is guaranteed to be available in the operating system. <br/>            The actual font that is specified by this value is implementation-dependent |
| WHITE_BRUSH | A white, solid-color brush that is equivalent to a logical brush <br/>            (LogBrushEx object, section 2.2.12) with the following properties:<br/>            BrushStyle: BS_SOLID (WMF BrushStyle enumeration, [MS-WMF] section 2.1.1.4)<br/>            Color: 0x00FFFFFF (WMF ColorRef object, [MS-WMF] section 2.2.2.8) |
| WHITE_PEN | A white, solid-color pen that is equivalent to a logical pen (LogPen object, section 2.2.19)<br/>            with the following properties:<br/>            PenStyle: PS_COSMETIC + PS_SOLID (PenStyle enumeration, section 2.1.25)<br/>            ColorRef: 0x00FFFFFF (WMF ColorRef object). |
