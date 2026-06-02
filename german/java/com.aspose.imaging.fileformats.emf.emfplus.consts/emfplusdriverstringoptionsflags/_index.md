---
title: "EmfPlusDriverStringOptionsFlags"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Die DriverStringOptions-Flags geben Eigenschaften der Positionierung und Darstellung von Grafiktext an."
type: docs
weight: 21
url: /de/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfplusdriverstringoptionsflags/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusDriverStringOptionsFlags extends System.Enum
```

Die DriverStringOptions-Flags geben Eigenschaften der Positionierung und Darstellung von Grafiktext an. Diese Flags können kombiniert werden, um mehrere Optionen anzugeben.

--------------------

Die Grafik-Textausgabe wird in den [EmfPlusDrawDriverString](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring)-Datensätzen angegeben.
## Felder

| Feld | Beschreibung |
| --- | --- |
| [DriverStringOptionsCmapLookup](#DriverStringOptionsCmapLookup) | Wenn gesetzt, sollten die Positionen der Zeichen-Glyphen in einer Zeichenkartensuch-Tabelle angegeben werden. |
| [DriverStringOptionsVertical](#DriverStringOptionsVertical) | Wenn gesetzt, sollte die Zeichenkette vertikal dargestellt werden. |
| [DriverStringOptionsRealizedAdvance](#DriverStringOptionsRealizedAdvance) | Wenn gesetzt, sollten die Positionen der Zeichen-Glyphen relativ zur Position der ersten Glyphen berechnet werden. |
| [DriverStringOptionsLimitSubpixel](#DriverStringOptionsLimitSubpixel) | Wenn gesetzt, sollte weniger Speicher verwendet werden, um anti-aliased Glyphen zwischenzuspeichern, was eine geringere Textdarstellungsqualität zur Folge hat. |
### DriverStringOptionsCmapLookup {#DriverStringOptionsCmapLookup}
```
public static final int DriverStringOptionsCmapLookup
```


Wenn gesetzt, sollten die Positionen der Zeichen-Glyphen in einer Zeichenkartensuch-Tabelle angegeben werden. Wenn nicht gesetzt, sollten die Glyphenpositionen aus einem Koordinatenarray bezogen werden.

### DriverStringOptionsVertical {#DriverStringOptionsVertical}
```
public static final int DriverStringOptionsVertical
```


Wenn gesetzt, sollte die Zeichenkette vertikal dargestellt werden. Wenn nicht gesetzt, sollte die Zeichenkette horizontal dargestellt werden.

### DriverStringOptionsRealizedAdvance {#DriverStringOptionsRealizedAdvance}
```
public static final int DriverStringOptionsRealizedAdvance
```


Wenn gesetzt, sollten die Positionen der Zeichen-Glyphen relativ zur Position der ersten Glyphen berechnet werden. Wenn nicht gesetzt, sollten die Glyphenpositionen aus einem Koordinatenarray bezogen werden.

### DriverStringOptionsLimitSubpixel {#DriverStringOptionsLimitSubpixel}
```
public static final int DriverStringOptionsLimitSubpixel
```


Wenn gesetzt, sollte weniger Speicher verwendet werden, um anti-aliased Glyphen zwischenzuspeichern, was eine geringere Textdarstellungsqualität zur Folge hat. Wenn nicht gesetzt, sollte mehr Speicher verwendet werden, was eine höhere Textdarstellungsqualität zur Folge hat.

