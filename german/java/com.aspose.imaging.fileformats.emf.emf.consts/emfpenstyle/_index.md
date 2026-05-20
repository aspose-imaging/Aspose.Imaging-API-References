---
title: "EmfPenStyle"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Die PenStyle‑Aufzählung definiert die Attribute von Stiften, die in Grafikoperationen verwendet werden können."
type: docs
weight: 34
url: /de/java/com.aspose.imaging.fileformats.emf.emf.consts/emfpenstyle/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPenStyle extends System.Enum
```

Die PenStyle-Aufzählung definiert die Attribute von Stiften, die in Grafikoperationen verwendet werden können. Ein Stiftstil ist eine Kombination aus Stifttyp, Linienstil, Linienende und Linienverbindung.
## Felder

| Feld | Beschreibung |
| --- | --- |
| [PS_COSMETIC](#PS-COSMETIC) | Ein Stifttyp, der eine Linie mit einer Breite von einer logischen Einheit und einem Stil, der eine Vollfarbe ist, spezifiziert. |
| [PS_ENDCAP_ROUND](#PS-ENDCAP-ROUND) | Ein Linienende, das runde Enden spezifiziert. |
| [PS_JOIN_ROUND](#PS-JOIN-ROUND) | Eine Linienverbindung, die runde Verbindungen spezifiziert. |
| [PS_SOLID](#PS-SOLID) | Ein Linienstil, der eine Vollfarbe ist. |
| [PS_DASH](#PS-DASH) | Ein Linienstil, der gestrichelt ist. |
| [PS_DOT](#PS-DOT) | Ein Linienstil, der punktiert ist. |
| [PS_DASHDOT](#PS-DASHDOT) | Ein Linienstil, der aus abwechselnden Strichen und Punkten besteht. |
| [PS_DASHDOTDOT](#PS-DASHDOTDOT) | Ein Linienstil, der aus Strichen und doppelten Punkten besteht. |
| [PS_NULL](#PS-NULL) | Ein Linienstil, der unsichtbar ist. |
| [PS_INSIDEFRAME](#PS-INSIDEFRAME) | Ein Linienstil, der eine einfarbige Farbe hat. |
| [PS_USERSTYLE](#PS-USERSTYLE) | Ein Linienstil, der durch ein Stil-Array definiert ist, das die Längen von Strichen und Lücken in der Linie angibt. |
| [PS_ALTERNATE](#PS-ALTERNATE) | Ein Linienstil, bei dem jedes zweite Pixel gesetzt ist. |
| [PS_ENDCAP_SQUARE](#PS-ENDCAP-SQUARE) | Ein Linienabschluss, der quadratische Enden spezifiziert. |
| [PS_ENDCAP_FLAT](#PS-ENDCAP-FLAT) | Ein Linienabschluss, der flache Enden spezifiziert. |
| [PS_JOIN_BEVEL](#PS-JOIN-BEVEL) | Eine Linienverbindung, die abgeschrägte Verbindungen spezifiziert. |
| [PS_JOIN_MITER](#PS-JOIN-MITER) | Eine Linienverbindung, die Gehrungsverbindungen angibt, wenn die Längen der Verbindungen innerhalb des aktuellen Gehrungs‑Längenlimits liegen, das im Wiedergabegerätekontext festgelegt ist. |
| [PS_GEOMETRIC](#PS-GEOMETRIC) | Ein Stifttyp, der eine Linie mit einer Breite, gemessen in logischen Einheiten, und einen Stil, der beliebige Attribute eines Pinsels enthalten kann, spezifiziert. |
| [StyleMask](#StyleMask) | Die Stilmaske |
| [EndCapMask](#EndCapMask) | Die Endkap-Maske |
| [JoinMask](#JoinMask) | Die Verbindungsmaske |
| [TypeMask](#TypeMask) | Die Typmaske |
### PS_COSMETIC {#PS-COSMETIC}
```
public static final int PS_COSMETIC
```


Ein Stifttyp, der eine Linie mit einer Breite von einer logischen Einheit und einem Stil, der eine Vollfarbe ist, spezifiziert.

### PS_ENDCAP_ROUND {#PS-ENDCAP-ROUND}
```
public static final int PS_ENDCAP_ROUND
```


Ein Linienende, das runde Enden spezifiziert.

### PS_JOIN_ROUND {#PS-JOIN-ROUND}
```
public static final int PS_JOIN_ROUND
```


Eine Linienverbindung, die runde Verbindungen spezifiziert.

### PS_SOLID {#PS-SOLID}
```
public static final int PS_SOLID
```


Ein Linienstil, der eine Vollfarbe ist.

### PS_DASH {#PS-DASH}
```
public static final int PS_DASH
```


Ein Linienstil, der gestrichelt ist.

### PS_DOT {#PS-DOT}
```
public static final int PS_DOT
```


Ein Linienstil, der punktiert ist.

### PS_DASHDOT {#PS-DASHDOT}
```
public static final int PS_DASHDOT
```


Ein Linienstil, der aus abwechselnden Strichen und Punkten besteht.

### PS_DASHDOTDOT {#PS-DASHDOTDOT}
```
public static final int PS_DASHDOTDOT
```


Ein Linienstil, der aus Strichen und doppelten Punkten besteht.

### PS_NULL {#PS-NULL}
```
public static final int PS_NULL
```


Ein Linienstil, der unsichtbar ist.

### PS_INSIDEFRAME {#PS-INSIDEFRAME}
```
public static final int PS_INSIDEFRAME
```


Ein Linienstil, der eine einfarbige Farbe ist. Wenn dieser Stil in einem Zeichenrecord angegeben wird, das ein Begrenzungsrechteck verwendet, werden die Abmessungen der Figur verkleinert, sodass sie vollständig in das Begrenzungsrechteck passt, wobei die Breite des Stifts berücksichtigt wird.

### PS_USERSTYLE {#PS-USERSTYLE}
```
public static final int PS_USERSTYLE
```


Ein Linienstil, der durch ein Stil-Array definiert ist, das die Längen von Strichen und Lücken in der Linie angibt.

### PS_ALTERNATE {#PS-ALTERNATE}
```
public static final int PS_ALTERNATE
```


Ein Linienstil, bei dem jedes zweite Pixel gesetzt ist. Dieser Stil ist nur für einen Stifttyp von PS\_COSMETIC anwendbar.

### PS_ENDCAP_SQUARE {#PS-ENDCAP-SQUARE}
```
public static final int PS_ENDCAP_SQUARE
```


Ein Linienabschluss, der quadratische Enden spezifiziert.

### PS_ENDCAP_FLAT {#PS-ENDCAP-FLAT}
```
public static final int PS_ENDCAP_FLAT
```


Ein Linienabschluss, der flache Enden spezifiziert.

### PS_JOIN_BEVEL {#PS-JOIN-BEVEL}
```
public static final int PS_JOIN_BEVEL
```


Eine Linienverbindung, die abgeschrägte Verbindungen spezifiziert.

### PS_JOIN_MITER {#PS-JOIN-MITER}
```
public static final int PS_JOIN_MITER
```


Eine Linienverbindung, die Gehrungsverbindungen angibt, wenn die Längen der Verbindungen innerhalb des aktuellen Gehrungs‑Längenlimits liegen, das im Wiedergabegerätekontext festgelegt ist. Überschreiten die Längen der Verbindungen das Gehrungs‑Limit, werden abgeschrägte Verbindungen angegeben.

### PS_GEOMETRIC {#PS-GEOMETRIC}
```
public static final int PS_GEOMETRIC
```


Ein Stifttyp, der eine Linie mit einer Breite, gemessen in logischen Einheiten, und einen Stil, der beliebige Attribute eines Pinsels enthalten kann, spezifiziert.

### StyleMask {#StyleMask}
```
public static final int StyleMask
```


Die Stilmaske

### EndCapMask {#EndCapMask}
```
public static final int EndCapMask
```


Die Endkap-Maske

### JoinMask {#JoinMask}
```
public static final int JoinMask
```


Die Verbindungsmaske

### TypeMask {#TypeMask}
```
public static final int TypeMask
```


Die Typmaske

