---
title: WmfClipPrecisionFlags
second_title: Aspose.Imaging för .NET API-referens
description: ClipPrecision-flaggor anger klippprecision vilket definierar hur tecken som är delvis är utanför en klippningsregion ska klippas. Dessa flaggor kan kombineras för att ange flera alternativ.
type: docs
weight: 8130
url: /sv/net/aspose.imaging.fileformats.wmf.consts/wmfclipprecisionflags/
---
## WmfClipPrecisionFlags enumeration

ClipPrecision-flaggor anger klippprecision, vilket definierar hur tecken som är delvis är utanför en klippningsregion ska klippas. Dessa flaggor kan kombineras för att ange flera alternativ.

```csharp
[Flags]
public enum WmfClipPrecisionFlags : byte
```

### Värderingar

| namn | Värde | Beskrivning |
| --- | --- | --- |
| Default | `0` | Anger att standardklippning MÅSTE användas. |
| Character | `1` | Detta värde SKA INTE användas. |
| Stroke | `2` | Det här värdet KAN returneras vid uppräkning av rastrerade TrueType och vektorteckensnitt. [33] (Windows NT 3.1, Windows NT 3.5, Windows NT 3.51, Windows NT 4.0, Detta värde returneras alltid, Windows 2 och Windows XP uppräkning av teckensnitt.) |
| LhAngles | `10` | Detta värde används för att styra teckensnittsrotation, enligt följande: - Om inställt, SKA rotationen för alla teckensnitt bestämmas av orienteringen för koordinatsystemet; det vill säga om orienteringen är vänsterhänt eller högerhänt. - Om den är ren, SKA enhetsteckensnitt rotera moturs, men rotationen av andra teckensnitt BÖR bestämmas av orienteringen av systemet koordinat ._x000. |
| TtAlways | `20` | Det här värdet BÖR INTE [34] användas. [34] Detta värde ignoreras i följande Windows-versioner: - Windows Vista - Windows Server 2008 - Windows 7 - Windows Server _x0d_1 Windows Server 2008 - Windows Server 2008 - Windows Server 2008 R2 8.1 - Windows Server 2012 R2 |
| DfaDisable | `40` | Detta värde anger att teckensnittsassociation SKA [35] stängas av. [35] Detta värde stöds inte.i Windows 95, Windows 98 och Windows Millennium Edition. Teckensnittsassociation är avstängd i Windows 2000, Windows XP, och Windows Server 2003. Detta värde ignoreras i dessa Windows-versioner: - Windows Vista - Windows Server 2008 - Windows 7 - Windows Server 2008 R2 - Windows Server 2012 - Windows 8 - Windows 8.1 - Windows Server 2012 R2 |
| Embedded | `80` | Detta värde anger att teckensnittsinbäddning MÅSTE användas för att rendera document innehåll; inbäddade teckensnitt är skrivskyddade. |

### Se även

* namnutrymme [Aspose.Imaging.FileFormats.Wmf.Consts](../../aspose.imaging.fileformats.wmf.consts)
* hopsättning [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->