---
title: "WmfTextAlignmentModeFlags"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "TextAlignmentMode‑Flags geben die Beziehung zwischen einem Referenzpunkt und einem Begrenzungsrechteck für die Textausrichtung an."
type: docs
weight: 36
url: /de/java/com.aspose.imaging.fileformats.wmf.consts/wmftextalignmentmodeflags/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class WmfTextAlignmentModeFlags extends System.Enum
```

TextAlignmentMode‑Flags geben die Beziehung zwischen einem Referenzpunkt und einem Begrenzungsrechteck für die Textausrichtung an. Diese Flags können kombiniert werden, um mehrere Optionen anzugeben, wobei die Einschränkung gilt, dass nur ein Flag gewählt werden darf, das die Zeichenposition im Wiedergabegeräte‑Kontext ändert. Die horizontale Textausrichtung wird durchgeführt, wenn die Schrift eine horizontale Standard‑Grundlinie hat.

--------------------

TextAlignmentMode‑Flags geben drei verschiedene Komponenten der Textausrichtung an: - Die horizontale Position des Referenzpunkts wird durch TA\_RIGHT und TA\_CENTER bestimmt; sind diese Bits nicht gesetzt, muss die Ausrichtung TA\_LEFT sein. - Die vertikale Position des Referenzpunkts wird durch TA\_BOTTOM und TA\_BASELINE bestimmt; sind diese Bits nicht gesetzt, muss die Ausrichtung TA\_TOP sein. - Ob die Ausgabeposition im Wiedergabegeräte‑Kontext nach der Textausgabe aktualisiert wird, wird durch TA\_UPDATECP bestimmt; ist dieses Bit nicht gesetzt, darf die Position NICHT aktualisiert werden. Dies ist der Grund für die Definition von drei verschiedenen Nullwerten in der Aufzählung; sie repräsentieren die Standardzustände der drei Komponenten der Textausrichtung.
## Felder

| Feld | Beschreibung |
| --- | --- |
| [Noupdatecp](#Noupdatecp) | Die Zeichenposition im Wiedergabegeräte‑Kontext DARF NICHT nach jedem Textausgabebefehl aktualisiert werden. |
| [Left](#Left) | Der Referenzpunkt MUSS sich an der linken Kante des Begrenzungsrechtecks befinden. |
| [Top](#Top) | Der Referenzpunkt MUSS sich an der oberen Kante des Begrenzungsrechtecks befinden. |
| [Updatecp](#Updatecp) | Die Zeichenposition im Wiedergabegeräte‑Kontext MUSS nach jedem Textausgabebefehl aktualisiert werden. |
| [Right](#Right) | Der Referenzpunkt MUSS sich an der rechten Kante des Begrenzungsrechtecks befinden. |
| [Center](#Center) | Der Referenzpunkt MUSS horizontal mit der Mitte des Begrenzungsrechtecks ausgerichtet werden. |
| [Bottom](#Bottom) | Der Referenzpunkt MUSS sich an der unteren Kante des Begrenzungsrechtecks befinden. |
| [Baseline](#Baseline) | Der Referenzpunkt MUSS sich auf der Grundlinie des Textes befinden. |
| [Rtlreading](#Rtlreading) | Der Text MUSS in Leserichtung von rechts nach links angeordnet werden, anstatt in der standardmäßigen Leserichtung von links nach rechts. |
| [Horizontal](#Horizontal) | Represents Horizontal text align sets (Left | Right | Mitte) |
| [Vertical](#Vertical) | Represents Vertical text align sets (Top | Bottom | Grundlinie) |
### Noupdatecp {#Noupdatecp}
```
public static final int Noupdatecp
```


Die Zeichenposition im Wiedergabegeräte‑Kontext DARF NICHT nach jedem Textausgabebefehl aktualisiert werden. Der Referenzpunkt MUSS an die Textausgabefunktion übergeben werden.

### Left {#Left}
```
public static final int Left
```


Der Referenzpunkt MUSS sich an der linken Kante des Begrenzungsrechtecks befinden.

### Top {#Top}
```
public static final int Top
```


Der Referenzpunkt MUSS sich an der oberen Kante des Begrenzungsrechtecks befinden.

### Updatecp {#Updatecp}
```
public static final int Updatecp
```


Die Zeichenposition im Wiedergabegeräte‑Kontext MUSS nach jedem Textausgabebefehl aktualisiert werden. Sie MUSS als Referenzpunkt verwendet werden.

### Right {#Right}
```
public static final int Right
```


Der Referenzpunkt MUSS sich an der rechten Kante des Begrenzungsrechtecks befinden.

### Center {#Center}
```
public static final int Center
```


Der Referenzpunkt MUSS horizontal mit der Mitte des Begrenzungsrechtecks ausgerichtet werden.

### Bottom {#Bottom}
```
public static final int Bottom
```


Der Referenzpunkt MUSS sich an der unteren Kante des Begrenzungsrechtecks befinden.

### Baseline {#Baseline}
```
public static final int Baseline
```


Der Referenzpunkt MUSS sich auf der Grundlinie des Textes befinden.

### Rtlreading {#Rtlreading}
```
public static final int Rtlreading
```


Der Text MUSS in Leserichtung von rechts nach links angeordnet werden, anstatt in der standardmäßigen Leserichtung von links nach rechts. Dies SOLLTE nur angewendet werden, wenn die im Wiedergabegeräte‑Kontext definierte Schrift entweder Hebräisch oder Arabisch ist.

### Horizontal {#Horizontal}
```
public static final int Horizontal
```


Stellt horizontale Textausrichtungs‑Sätze dar (Left | Right | Center)

### Vertical {#Vertical}
```
public static final int Vertical
```


Stellt vertikale Textausrichtungs‑Sätze dar (Top | Bottom | Baseline)

