---
title: "EmfPlusLineCapType"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Die LineCapType-Aufzählung definiert Typen von Linienenden, die an den Enden von Linien verwendet werden, die mit Grafikstiften gezeichnet werden."
type: docs
weight: 31
url: /de/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfpluslinecaptype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusLineCapType extends System.Enum
```

Die LineCapType-Aufzählung definiert Typen von Linienenden, die an den Enden von Linien verwendet werden, die mit Grafikstiften gezeichnet werden.

--------------------

Grafik-Linienenden werden durch [EmfPlusPen](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspen) Objekte (Abschnitt 2.2.1.7) spezifiziert.
## Felder

| Feld | Beschreibung |
| --- | --- |
| [LineCapTypeFlat](#LineCapTypeFlat) | Gibt einen abgeflachten Linienabschluss an. |
| [LineCapTypeSquare](#LineCapTypeSquare) | Gibt einen quadratischen Linienabschluss an. |
| [LineCapTypeRound](#LineCapTypeRound) | Gibt einen kreisförmigen Linienabschluss an. |
| [LineCapTypeTriangle](#LineCapTypeTriangle) | Gibt einen dreieckigen Linienabschluss an. |
| [LineCapTypeNoAnchor](#LineCapTypeNoAnchor) | Gibt an, dass das Linienende nicht verankert ist. |
| [LineCapTypeSquareAnchor](#LineCapTypeSquareAnchor) | Gibt an, dass das Linienende mit einem quadratischen Linienabschluss verankert ist. |
| [LineCapTypeRoundAnchor](#LineCapTypeRoundAnchor) | Gibt an, dass das Linienende mit einem kreisförmigen Linienabschluss verankert ist. |
| [LineCapTypeDiamondAnchor](#LineCapTypeDiamondAnchor) | Gibt an, dass das Linienende mit einem diamantförmigen Linienabschluss verankert ist, der ein um 45 Grad gedrehtes Quadrat ist. |
| [LineCapTypeArrowAnchor](#LineCapTypeArrowAnchor) | Gibt an, dass das Linienende mit einer Pfeilspitzenform verankert ist. |
| [LineCapTypeAnchorMask](#LineCapTypeAnchorMask) | Maske, die verwendet wird, um zu prüfen, ob ein Linienabschluss ein Ankerabschluss ist. |
| [LineCapTypeCustom](#LineCapTypeCustom) | Gibt einen benutzerdefinierten Linienabschluss an. |
### LineCapTypeFlat {#LineCapTypeFlat}
```
public static final int LineCapTypeFlat
```


Gibt einen abgeflachten Linienabschluss an. Das Ende der Linie MUSS der letzte Punkt der Linie sein.

### LineCapTypeSquare {#LineCapTypeSquare}
```
public static final int LineCapTypeSquare
```


Gibt einen quadratischen Linienabschluss an. Der Mittelpunkt des Quadrats MUSS am letzten Punkt der Linie liegen. Die Breite des Quadrats entspricht der Linienbreite.

### LineCapTypeRound {#LineCapTypeRound}
```
public static final int LineCapTypeRound
```


Gibt einen kreisförmigen Linienabschluss an. Der Mittelpunkt des Kreises MUSS am letzten Punkt der Linie liegen. Der Durchmesser des Kreises entspricht der Linienbreite.

### LineCapTypeTriangle {#LineCapTypeTriangle}
```
public static final int LineCapTypeTriangle
```


Gibt einen dreieckigen Linienabschluss an. Die Basis des Dreiecks MUSS am letzten Punkt der Linie liegen. Die Basis des Dreiecks entspricht der Linienbreite.

### LineCapTypeNoAnchor {#LineCapTypeNoAnchor}
```
public static final int LineCapTypeNoAnchor
```


Gibt an, dass das Linienende nicht verankert ist.

### LineCapTypeSquareAnchor {#LineCapTypeSquareAnchor}
```
public static final int LineCapTypeSquareAnchor
```


Gibt an, dass das Linienende mit einem quadratischen Linienabschluss verankert ist. Der Mittelpunkt des Quadrats MUSS am letzten Punkt der Linie liegen. Höhe und Breite des Quadrats entsprechen der Linienbreite.

### LineCapTypeRoundAnchor {#LineCapTypeRoundAnchor}
```
public static final int LineCapTypeRoundAnchor
```


Gibt an, dass das Linienende mit einem kreisförmigen Linienabschluss verankert ist. Der Mittelpunkt des Kreises MUSS am letzten Punkt der Linie liegen. Der Kreis SOLLTE breiter als die Linie sein.

### LineCapTypeDiamondAnchor {#LineCapTypeDiamondAnchor}
```
public static final int LineCapTypeDiamondAnchor
```


Gibt an, dass das Linienende mit einem diamantförmigen Linienabschluss verankert ist, der ein um 45 Grad gedrehtes Quadrat ist. Der Mittelpunkt des Diamanten MUSS am letzten Punkt der Linie liegen. Der Diamant SOLLTE breiter als die Linie sein.

### LineCapTypeArrowAnchor {#LineCapTypeArrowAnchor}
```
public static final int LineCapTypeArrowAnchor
```


Gibt an, dass das Linienende mit einer Pfeilspitzenform verankert ist. Der Pfeilspitzenpunkt MUSS am letzten Punkt der Linie liegen. Die Pfeilspitze SOLLTE breiter als die Linie sein.

### LineCapTypeAnchorMask {#LineCapTypeAnchorMask}
```
public static final int LineCapTypeAnchorMask
```


Maske, die verwendet wird, um zu prüfen, ob ein Linienabschluss ein Ankerabschluss ist.

### LineCapTypeCustom {#LineCapTypeCustom}
```
public static final int LineCapTypeCustom
```


Gibt einen benutzerdefinierten Linienabschluss an.

