---
title: Enum EmfStockObject
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.Emf.Consts.EmfStockObject enum. The StockObject enumeration specifies the indexes of predefined logical graphics objects that can be used in graphics operations.The specific structures of stock objects are implementationdependent however the properties of stock objects SHOULD be equivalent to the properties of explicitly created objects of the same type. These properties are specified where possible for the stock objects defined in this enumeration
type: docs
weight: 2950
url: /net/aspose.imaging.fileformats.emf.emf.consts/emfstockobject/
---
## EmfStockObject enumeration

The StockObject enumeration specifies the indexes of predefined logical graphics objects that can be used in graphics operations.The specific structures of stock objects are implementation-dependent; however, the properties of stock objects SHOULD be equivalent to the properties of explicitly created objects of the same type. These properties are specified where possible for the stock objects defined in this enumeration.

```csharp
public enum EmfStockObject
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| WHITE_BRUSH | `-2147483648` | A white, solid-color brush that is equivalent to a logical brush (LogBrushEx object, section 2.2.12) with the following properties: BrushStyle: BS_SOLID (WMF BrushStyle enumeration, [MS-WMF] section 2.1.1.4) Color: 0x00FFFFFF (WMF ColorRef object, [MS-WMF] section 2.2.2.8) |
| LTGRAY_BRUSH | `-2147483647` | A light gray, solid-color brush that is equivalent to a logical brush with the following properties: BrushStyle: BS_SOLID Color: 0x00C0C0C0 |
| GRAY_BRUSH | `-2147483646` | A gray, solid-color brush that is equivalent to a logical brush with the following properties: BrushStyle: BS_SOLID Color: 0x00808080 |
| DKGRAY_BRUSH | `-2147483645` | A dark gray, solid color brush that is equivalent to a logical brush with the following properties: BrushStyle: BS_SOLID Color: 0x00404040 |
| BLACK_BRUSH | `-2147483644` | A black, solid color brush that is equivalent to a logical brush with the following properties: BrushStyle: BS_SOLID Color: 0x00000000 |
| NULL_BRUSH | `-2147483643` | A null brush that is equivalent to a logical brush with the following properties: BrushStyle: BS_NULL |
| WHITE_PEN | `-2147483642` | A white, solid-color pen that is equivalent to a logical pen (LogPen object, section 2.2.19) with the following properties: PenStyle: PS_COSMETIC + PS_SOLID (PenStyle enumeration, section 2.1.25) ColorRef: 0x00FFFFFF (WMF ColorRef object). |
| BLACK_PEN | `-2147483641` | A black, solid-color pen that is equivalent to a logical pen with the following properties: PenStyle: PS_COSMETIC + PS_SOLID ColorRef: 0x00000000 |
| NULL_PEN | `-2147483640` | A null pen that is equivalent to a logical pen with the following properties: PenStyle: PS_NULL |
| OEM_FIXED_FONT | `-2147483638` | A fixed-width, OEM character set font that is equivalent to a logical font (LogFont object, section 2.2.13) with the following properties: Charset: OEM_CHARSET (WMF CharacterSet enumeration, [MS-WMF] section 2.1.1.5) PitchAndFamily: FF_DONTCARE (WMF FamilyFont enumeration, [MS-WMF] section 2.1.1.8) + FIXED_PITCH (WMF PitchFont enumeration, [MS-WMF] section 2.1.1.24) |
| ANSI_FIXED_FONT | `-2147483637` | A fixed-width font that is equivalent to a logical font with the following properties: Charset: ANSI_CHARSET PitchAndFamily: FF_DONTCARE + FIXED_PITCH |
| ANSI_VAR_FONT | `-2147483636` | A variable-width font that is equivalent to a logical font with the following properties: Charset: ANSI_CHARSET PitchAndFamily: FF_DONTCARE + VARIABLE_PITCH |
| SYSTEM_FONT | `-2147483635` | A font that is guaranteed to be available in the operating system. The actual font that is specified by this value is implementation-dependent |
| DEVICE_DEFAULT_FONT | `-2147483634` | The default font that is provided by the graphics device driver for the current output device. The actual font that is specified by this value is implementation-dependent |
| DEFAULT_PALETTE | `-2147483633` | The default palette that is defined for the current output device. The actual palette that is specified by this value is implementation-dependent |
| SYSTEM_FIXED_FONT | `-2147483632` | A fixed-width font that is guaranteed to be available in the operating system. The actual font that is specified by this value is implementation-dependent |
| DEFAULT_GUI_FONT | `-2147483631` | A fixed-width font that is guaranteed to be available in the operating system. The actual font that is specified by this value is implementation-dependent |
| DC_BRUSH | `-2147483630` | The solid-color brush that is currently selected in the playback device context |
| DC_PEN | `-2147483629` | The solid-color pen that is currently selected in the playback device context |

### See Also

* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Consts](../../aspose.imaging.fileformats.emf.emf.consts/)
* assembly [Aspose.Imaging](../../)


