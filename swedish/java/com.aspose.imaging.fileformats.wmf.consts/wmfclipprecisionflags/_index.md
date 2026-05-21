---
title: "WmfClipPrecisionFlags"
second_title: "Aspose.Imaging för Java API-referens"
description: "ClipPrecision Flags specificerar klippningsprecision som definierar hur man klipper tecken som delvis ligger utanför ett klippningsområde."
type: docs
weight: 14
url: /sv/java/com.aspose.imaging.fileformats.wmf.consts/wmfclipprecisionflags/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class WmfClipPrecisionFlags extends System.Enum
```

ClipPrecision Flags specificerar klippningsprecision, vilket definierar hur man klipper tecken som delvis ligger utanför ett klippningsområde. Dessa flaggor kan kombineras för att specificera flera alternativ.
## Fält

| Fält | Beskrivning |
| --- | --- |
| [Default](#Default) | Anger att standardklippning MÅSTE användas. |
| [Character](#Character) | Detta värde BÖR INTE användas. |
| [Stroke](#Stroke) | Detta värde KAN returneras vid uppräkning av rasteriserade, TrueType- och vektorfonter. |
| [LhAngles](#LhAngles) | Detta värde används för att styra teckensnittsrörelse, enligt följande: - Om det är satt ska rotationen för alla teckensnitt BÖR bestämmas av koordinatsystemets orientering; det vill säga om orienteringen är vänsterhänt eller högrehänt. |
| [TtAlways](#TtAlways) | Detta värde BÖR INTE [34] användas. |
| [DfaDisable](#DfaDisable) | Detta värde specificerar att teckensnittstillhörighet BÖR [35] stängas av. |
| [Embedded](#Embedded) | Detta värde specificerar att inbäddning av teckensnitt MÅSTE användas för att rendera dokumentinnehåll; inbäddade teckensnitt är skrivskyddade. |
### Default {#Default}
```
public static final byte Default
```


Anger att standardklippning MÅSTE användas.

### Character {#Character}
```
public static final byte Character
```


Detta värde BÖR INTE användas.

### Stroke {#Stroke}
```
public static final byte Stroke
```


Detta värde KAN returneras vid uppräkning av rasteriserade, TrueType- och vektorfonter. [33] (Windows NT 3.1, Windows NT 3.5, Windows NT 3.51, Windows NT 4.0, Windows 2000 och Windows XP: Detta värde returneras alltid vid uppräkning av teckensnitt.)

### LhAngles {#LhAngles}
```
public static final byte LhAngles
```


Detta värde används för att styra teckensnittsrörelse, enligt följande: - Om det är satt ska rotationen för alla teckensnitt BÖR bestämmas av koordinatsystemets orientering; det vill säga om orienteringen är vänsterhänt eller högrehänt. - Om det är rensat ska enhetsteckensnitt BÖR rotera moturs, men rotationen för andra teckensnitt BÖR bestämmas av koordinatsystemets orientering.

### TtAlways {#TtAlways}
```
public static final byte TtAlways
```


Detta värde BÖR INTE [34] användas. [34] Detta värde ignoreras i följande Windows-versioner: - Windows Vista - Windows Server 2008 - Windows 7 - Windows Server 2008 R2 - Windows 8 - Windows Server 2012 - Windows 8.1 - Windows Server 2012 R2

### DfaDisable {#DfaDisable}
```
public static final byte DfaDisable
```


Detta värde specificerar att teckensnittstillhörighet BÖR [35] stängas av. [35] Detta värde stöds inte i Windows 95, Windows 98 och Windows Millennium Edition. Teckensnittstillhörighet är avstängd i Windows 2000, Windows XP och Windows Server 2003. Detta värde ignoreras i dessa Windows-versioner: - Windows Vista - Windows Server 2008 - Windows 7 - Windows Server 2008 R2 - Windows 8 - Windows Server 2012 - Windows 8.1 - Windows Server 2012 R2

### Embedded {#Embedded}
```
public static final byte Embedded
```


Detta värde specificerar att inbäddning av teckensnitt MÅSTE användas för att rendera dokumentinnehåll; inbäddade teckensnitt är skrivskyddade.

