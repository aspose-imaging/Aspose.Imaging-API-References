---
title: "EmfPlusDriverStringOptionsFlags"
second_title: "Aspose.Imaging för Java API-referens"
description: "DriverStringOptions‑flaggorna specificerar egenskaper för placering och rendering av grafiktext."
type: docs
weight: 21
url: /sv/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfplusdriverstringoptionsflags/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusDriverStringOptionsFlags extends System.Enum
```

DriverStringOptions-flaggorna specificerar egenskaper för grafiktextens positionering och rendering. Dessa flaggor kan kombineras för att ange flera alternativ.

--------------------

Grafisk textutmatning specificeras i [EmfPlusDrawDriverString](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring) poster.
## Fält

| Fält | Beskrivning |
| --- | --- |
| [DriverStringOptionsCmapLookup](#DriverStringOptionsCmapLookup) | Om den är satt ska positionerna för teckenglyfer specificeras i en teckenkartuppslagningstabell. |
| [DriverStringOptionsVertical](#DriverStringOptionsVertical) | Om den är satt ska strängen renderas vertikalt. |
| [DriverStringOptionsRealizedAdvance](#DriverStringOptionsRealizedAdvance) | Om den är satt ska teckenglyfpositioner beräknas relativt positionen för den första glyfen. |
| [DriverStringOptionsLimitSubpixel](#DriverStringOptionsLimitSubpixel) | Om den är satt bör mindre minne användas för att cachea anti-aliasade glyfer, vilket ger lägre kvalitet på textrenderingen. |
### DriverStringOptionsCmapLookup {#DriverStringOptionsCmapLookup}
```
public static final int DriverStringOptionsCmapLookup
```


Om den är satt ska positionerna för teckenglyfer specificeras i en teckenkartuppslagningstabell. Om den är avstängd ska glyfpositionerna hämtas från en koordinatarray.

### DriverStringOptionsVertical {#DriverStringOptionsVertical}
```
public static final int DriverStringOptionsVertical
```


Om den är satt ska strängen renderas vertikalt. Om den är avstängd ska strängen renderas horisontellt.

### DriverStringOptionsRealizedAdvance {#DriverStringOptionsRealizedAdvance}
```
public static final int DriverStringOptionsRealizedAdvance
```


Om den är satt ska teckenglyfpositioner beräknas relativt positionen för den första glyfen. Om den är avstängd ska glyfpositionerna hämtas från en koordinatarray.

### DriverStringOptionsLimitSubpixel {#DriverStringOptionsLimitSubpixel}
```
public static final int DriverStringOptionsLimitSubpixel
```


Om den är satt bör mindre minne användas för att cachea anti-aliasade glyfer, vilket ger lägre kvalitet på textrenderingen. Om den är avstängd bör mer minne användas, vilket ger högre kvalitet på textrenderingen.

