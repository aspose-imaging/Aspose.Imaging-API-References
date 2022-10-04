---
title: CmykColorHelper
second_title: Aspose.Imaging für .NET-API-Referenz
description: Hilfsmethoden zum Arbeiten mit CMYK-Farben die als vorzeichenbehafteter 32-Bit-Ganzzahlwert dargestellt werden. Bietet eine ähnliche API wie dieCmykColor./cmykcolor struct. Es ist leichter da CMYK-Farben nur als Int32 dargestellt werden und nicht als Struktur mit internen Feldern. Bitte verwenden Sie nach Möglichkeit statische Methoden dieser Klasse anstelle der veralteten CmykColor./cmykcolor struct.
type: docs
weight: 290
url: /de/net/aspose.imaging/cmykcolorhelper/
---
## CmykColorHelper class

Hilfsmethoden zum Arbeiten mit CMYK-Farben, die als vorzeichenbehafteter 32-Bit-Ganzzahlwert dargestellt werden. Bietet eine ähnliche API wie die[`CmykColor`](../cmykcolor) struct. Es ist leichter, da CMYK-Farben nur als Int32 dargestellt werden und nicht als Struktur mit internen Feldern. Bitte verwenden Sie nach Möglichkeit statische Methoden dieser Klasse anstelle der veralteten [`CmykColor`](../cmykcolor) struct.

```csharp
public static class CmykColorHelper
```

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [FromComponents](../../aspose.imaging/cmykcolorhelper/fromcomponents)(int, int, int, int) | Erstellt CMYK aus 32-Bit-Cyan-, Magenta-, Gelb- und Schwarzwerten. |
| static [GetC](../../aspose.imaging/cmykcolorhelper/getc)(int) | Ruft den Cyan-Komponentenwert ab. |
| static [GetK](../../aspose.imaging/cmykcolorhelper/getk)(int) | Ruft den Schwarzkomponentenwert ab. |
| static [GetM](../../aspose.imaging/cmykcolorhelper/getm)(int) | Ruft den Magenta-Komponentenwert ab. |
| static [GetY](../../aspose.imaging/cmykcolorhelper/gety)(int) | Ruft den gelben Komponentenwert ab. |
| static [ToArgb](../../aspose.imaging/cmykcolorhelper/toargb#toargb)(int) | Die Konvertierung von CMYK-Farbe in ARGB-Farbe. |
| static [ToArgb](../../aspose.imaging/cmykcolorhelper/toargb#toargb_1)(int[]) | Die Konvertierung von CMYK-Farben in ARGB-Farben. |
| static [ToArgb32](../../aspose.imaging/cmykcolorhelper/toargb32)(int[]) | Die Konvertierung von CMYK-Farben in ARGB-Farben. |
| static [ToArgbIcc](../../aspose.imaging/cmykcolorhelper/toargbicc#toargbicc)(int) | Die Konvertierung von CMYK-Farbe in ARGB-Farbe mithilfe der Icc-Konvertierung mit Standardprofilen. |
| static [ToArgbIcc](../../aspose.imaging/cmykcolorhelper/toargbicc#toargbicc_2)(int[]) | Die Konvertierung von CMYK-Farben in ARGB-Farben mithilfe der Icc-Konvertierung mit Standardprofilen. |
| static [ToArgbIcc](../../aspose.imaging/cmykcolorhelper/toargbicc#toargbicc_1)(int, Stream, Stream) | Die Konvertierung von CMYK-Farbe in ARGB-Farbe mithilfe der Icc-Konvertierung mit benutzerdefiniertem Profil. |
| static [ToArgbIcc](../../aspose.imaging/cmykcolorhelper/toargbicc#toargbicc_3)(int[], Stream, Stream) | Die Konvertierung von CMYK-Farben in ARGB-Farben mithilfe der Icc-Konvertierung mit benutzerdefinierten Profilen. |
| static [ToCmyk](../../aspose.imaging/cmykcolorhelper/tocmyk#tocmyk)(Color) | Die Umwandlung von ARGB-Farbe in CMYK-Farbe. |
| static [ToCmyk](../../aspose.imaging/cmykcolorhelper/tocmyk#tocmyk_2)(Color[]) | Die Konvertierung von ARGB-Farben in CMYK-Farben. |
| static [ToCmyk](../../aspose.imaging/cmykcolorhelper/tocmyk#tocmyk_1)(int) | Die Umwandlung von ARGB-Farbe in CMYK-Farbe. |
| static [ToCmyk](../../aspose.imaging/cmykcolorhelper/tocmyk#tocmyk_3)(int[]) | Die Konvertierung von ARGB-Farben in CMYK-Farben. |
| static [ToCmykBytes](../../aspose.imaging/cmykcolorhelper/tocmykbytes)(int[], int, int) | Wandelt RGB in CMYK um. |
| static [ToCmykIcc](../../aspose.imaging/cmykcolorhelper/tocmykicc#tocmykicc)(Color) | Die Konvertierung von ARGB-Farbe in CMYK-Farbe mithilfe der Icc-Konvertierung mit Standardprofilen. |
| static [ToCmykIcc](../../aspose.imaging/cmykcolorhelper/tocmykicc#tocmykicc_2)(Color[]) | Die Konvertierung von ARGB-Farben in CMYK-Farben mithilfe der Icc-Konvertierung mit Standardprofilen. |
| static [ToCmykIcc](../../aspose.imaging/cmykcolorhelper/tocmykicc#tocmykicc_1)(Color, Stream, Stream) | Die Konvertierung von ARGB-Farbe in CMYK-Farbe mithilfe der Icc-Konvertierung mit benutzerdefinierten Profilen. |
| static [ToCmykIcc](../../aspose.imaging/cmykcolorhelper/tocmykicc#tocmykicc_3)(Color[], Stream, Stream) | Die Konvertierung von ARGB-Farben in CMYK-Farben mithilfe der Icc-Konvertierung mit benutzerdefinierten Profilen. |
| static [ToCmykIccBytes](../../aspose.imaging/cmykcolorhelper/tocmykiccbytes)(int[], int, int, Stream, Stream) | Konvertiert RGB in CMYK mit benutzerdefinierten ICC-Profilen. |

### Siehe auch

* namensraum [Aspose.Imaging](../../aspose.imaging)
* Montage [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->