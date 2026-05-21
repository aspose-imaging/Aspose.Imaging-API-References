---
title: "EmfPenStyle"
second_title: "Aspose.Imaging för Java API-referens"
description: "PenStyle‑uppräkningen definierar attributen för pennor som kan användas i grafikoperationer."
type: docs
weight: 34
url: /sv/java/com.aspose.imaging.fileformats.emf.emf.consts/emfpenstyle/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPenStyle extends System.Enum
```

PenStyle‑enumerationen definierar attributen för pennor som kan användas i grafikoperationer. En pennstil är en kombination av penntyp, linjestil, linjeändpunkt och linjesammanfogning.
## Fält

| Fält | Beskrivning |
| --- | --- |
| [PS_COSMETIC](#PS-COSMETIC) | En penntyp som specificerar en linje med en bredd på en logisk enhet och en stil som är en solid färg |
| [PS_ENDCAP_ROUND](#PS-ENDCAP-ROUND) | En linjeändpunkt som specificerar runda ändar. |
| [PS_JOIN_ROUND](#PS-JOIN-ROUND) | En linjesammanfogning som specificerar runda fogar |
| [PS_SOLID](#PS-SOLID) | En linjestil som är en solid färg |
| [PS_DASH](#PS-DASH) | En linjestil som är streckad |
| [PS_DOT](#PS-DOT) | En linjestil som är prickad. |
| [PS_DASHDOT](#PS-DASHDOT) | En linjestil som består av växlande streck och prickar |
| [PS_DASHDOTDOT](#PS-DASHDOTDOT) | En linjestil som består av streck och dubbla punkter. |
| [PS_NULL](#PS-NULL) | En linjestil som är osynlig. |
| [PS_INSIDEFRAME](#PS-INSIDEFRAME) | En linjestil som är en solid färg. |
| [PS_USERSTYLE](#PS-USERSTYLE) | En linjestil som definieras av en stiliseringsarray, som specificerar längderna på strecken och mellanrummen i linjen |
| [PS_ALTERNATE](#PS-ALTERNATE) | En linjestil där varannan pixel är satt. |
| [PS_ENDCAP_SQUARE](#PS-ENDCAP-SQUARE) | En linjeänd som specificerar fyrkantiga ändar. |
| [PS_ENDCAP_FLAT](#PS-ENDCAP-FLAT) | En linjeänd som specificerar platta ändar. |
| [PS_JOIN_BEVEL](#PS-JOIN-BEVEL) | En linjesammanfogning som specificerar avfasade fogar. |
| [PS_JOIN_MITER](#PS-JOIN-MITER) | En linjesammanfogning som specificerar snedställda fogar när fogarnas längder är inom den aktuella snedställda längdgränsen som är inställd i uppspelningsenhetens kontext. |
| [PS_GEOMETRIC](#PS-GEOMETRIC) | En pennatyp som specificerar en linje med en bredd som mäts i logiska enheter och en stil som kan innehålla någon av egenskaperna hos en pensel. |
| [StyleMask](#StyleMask) | Stilmasken |
| [EndCapMask](#EndCapMask) | Masken för ändkappen |
| [JoinMask](#JoinMask) | Masken för fogen |
| [TypeMask](#TypeMask) | Typmasken |
### PS_COSMETIC {#PS-COSMETIC}
```
public static final int PS_COSMETIC
```


En penntyp som specificerar en linje med en bredd på en logisk enhet och en stil som är en solid färg

### PS_ENDCAP_ROUND {#PS-ENDCAP-ROUND}
```
public static final int PS_ENDCAP_ROUND
```


En linjeändpunkt som specificerar runda ändar.

### PS_JOIN_ROUND {#PS-JOIN-ROUND}
```
public static final int PS_JOIN_ROUND
```


En linjesammanfogning som specificerar runda fogar

### PS_SOLID {#PS-SOLID}
```
public static final int PS_SOLID
```


En linjestil som är en solid färg

### PS_DASH {#PS-DASH}
```
public static final int PS_DASH
```


En linjestil som är streckad

### PS_DOT {#PS-DOT}
```
public static final int PS_DOT
```


En linjestil som är prickad.

### PS_DASHDOT {#PS-DASHDOT}
```
public static final int PS_DASHDOT
```


En linjestil som består av växlande streck och prickar

### PS_DASHDOTDOT {#PS-DASHDOTDOT}
```
public static final int PS_DASHDOTDOT
```


En linjestil som består av streck och dubbla punkter.

### PS_NULL {#PS-NULL}
```
public static final int PS_NULL
```


En linjestil som är osynlig.

### PS_INSIDEFRAME {#PS-INSIDEFRAME}
```
public static final int PS_INSIDEFRAME
```


En linjestil som är en solid färg. När denna stil specificeras i en ritpost som tar en avgränsande rektangel, krymps figurens dimensioner så att den passar helt inom den avgränsande rektangeln, med hänsyn till pennans bredd.

### PS_USERSTYLE {#PS-USERSTYLE}
```
public static final int PS_USERSTYLE
```


En linjestil som definieras av en stiliseringsarray, som specificerar längderna på strecken och mellanrummen i linjen

### PS_ALTERNATE {#PS-ALTERNATE}
```
public static final int PS_ALTERNATE
```


En linjestil där varannan pixel är satt. Denna stil är endast tillämplig för en pennatyp av PS\_COSMETIC

### PS_ENDCAP_SQUARE {#PS-ENDCAP-SQUARE}
```
public static final int PS_ENDCAP_SQUARE
```


En linjeänd som specificerar fyrkantiga ändar.

### PS_ENDCAP_FLAT {#PS-ENDCAP-FLAT}
```
public static final int PS_ENDCAP_FLAT
```


En linjeänd som specificerar platta ändar.

### PS_JOIN_BEVEL {#PS-JOIN-BEVEL}
```
public static final int PS_JOIN_BEVEL
```


En linjesammanfogning som specificerar avfasade fogar.

### PS_JOIN_MITER {#PS-JOIN-MITER}
```
public static final int PS_JOIN_MITER
```


En linjesammanfogning som specificerar snedställda fogar när fogarnas längder är inom den aktuella snedställda längdgränsen som är inställd i uppspelningsenhetens kontext. Om fogarnas längder överskrider snedställda gränsen, specificeras avfasade fogar.

### PS_GEOMETRIC {#PS-GEOMETRIC}
```
public static final int PS_GEOMETRIC
```


En pennatyp som specificerar en linje med en bredd som mäts i logiska enheter och en stil som kan innehålla någon av egenskaperna hos en pensel.

### StyleMask {#StyleMask}
```
public static final int StyleMask
```


Stilmasken

### EndCapMask {#EndCapMask}
```
public static final int EndCapMask
```


Masken för ändkappen

### JoinMask {#JoinMask}
```
public static final int JoinMask
```


Masken för fogen

### TypeMask {#TypeMask}
```
public static final int TypeMask
```


Typmasken

