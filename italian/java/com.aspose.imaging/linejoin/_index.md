---
title: "LineJoin"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Specifica come unire segmenti consecutivi di linee o curve in un sotto-percorso di figura contenuto in un oggetto GraphicsPath."
type: docs
weight: 69
url: /it/java/com.aspose.imaging/linejoin/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class LineJoin extends System.Enum
```

Specifica come unire segmenti consecutivi di linee o curve in una figura (sottotraccia) contenuta in un oggetto `GraphicsPath`.
## Campi

| Campo | Descrizione |
| --- | --- |
| [Miter](#Miter) | Specifica una giunzione a spigolo. |
| [Bevel](#Bevel) | Specifica una giunzione smussata. |
| [Round](#Round) | Specifica una giunzione circolare. |
| [MiterClipped](#MiterClipped) | Specifica una giunzione a spigolo. |
### Miter {#Miter}
```
public static final int Miter
```


Specifica una giunzione a spigolo. Questo produce un angolo acuto o un angolo tagliato, a seconda che la lunghezza dello spigolo superi il limite dello spigolo.

### Bevel {#Bevel}
```
public static final int Bevel
```


Specifica una giunzione smussata. Questo produce un angolo diagonale.

### Round {#Round}
```
public static final int Round
```


Specifica una giunzione circolare. Questo produce un arco circolare e fluido tra le linee.

### MiterClipped {#MiterClipped}
```
public static final int MiterClipped
```


Specifica una giunzione a spigolo. Questo produce un angolo acuto o un angolo smussato, a seconda che la lunghezza dello spigolo superi il limite dello spigolo.

