---
title: "EmfPenStyle"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "L'enumerazione PenStyle definisce gli attributi delle penne che possono essere utilizzate nelle operazioni grafiche."
type: docs
weight: 34
url: /it/java/com.aspose.imaging.fileformats.emf.emf.consts/emfpenstyle/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPenStyle extends System.Enum
```

L'enumerazione PenStyle definisce gli attributi delle penne che possono essere utilizzate nelle operazioni grafiche. Uno stile di penna è una combinazione di tipo di penna, stile di linea, estremità di linea e giunzione di linea.
## Campi

| Campo | Descrizione |
| --- | --- |
| [PS_COSMETIC](#PS-COSMETIC) | Un tipo di penna che specifica una linea con larghezza di un'unità logica e uno stile di colore solido |
| [PS_ENDCAP_ROUND](#PS-ENDCAP-ROUND) | Un'estremità di linea che specifica estremità arrotondate. |
| [PS_JOIN_ROUND](#PS-JOIN-ROUND) | Una giunzione di linea che specifica giunzioni arrotondate |
| [PS_SOLID](#PS-SOLID) | Uno stile di linea di colore solido |
| [PS_DASH](#PS-DASH) | Uno stile di linea tratteggiato |
| [PS_DOT](#PS-DOT) | Uno stile di linea puntinato. |
| [PS_DASHDOT](#PS-DASHDOT) | Uno stile di linea costituito da trattini e punti alternati |
| [PS_DASHDOTDOT](#PS-DASHDOTDOT) | Uno stile di linea che consiste in trattini e doppi punti. |
| [PS_NULL](#PS-NULL) | Uno stile di linea che è invisibile. |
| [PS_INSIDEFRAME](#PS-INSIDEFRAME) | Uno stile di linea di colore solido. |
| [PS_USERSTYLE](#PS-USERSTYLE) | Uno stile di linea definito da un array di stile, che specifica le lunghezze dei trattini e degli spazi nella linea |
| [PS_ALTERNATE](#PS-ALTERNATE) | Uno stile di linea in cui ogni altro pixel è impostato. |
| [PS_ENDCAP_SQUARE](#PS-ENDCAP-SQUARE) | Un'estremità di linea che specifica estremità quadrate. |
| [PS_ENDCAP_FLAT](#PS-ENDCAP-FLAT) | Un'estremità di linea che specifica estremità piatte. |
| [PS_JOIN_BEVEL](#PS-JOIN-BEVEL) | Una giunzione di linea che specifica giunzioni smussate. |
| [PS_JOIN_MITER](#PS-JOIN-MITER) | Una giunzione di linea che specifica giunzioni a spigolo quando le lunghezze delle giunzioni rientrano nel limite di lunghezza dello spigolo corrente impostato nel contesto del dispositivo di riproduzione. |
| [PS_GEOMETRIC](#PS-GEOMETRIC) | Un tipo di penna che specifica una linea con una larghezza misurata in unità logiche e uno stile che può contenere qualsiasi attributo di un pennello. |
| [StyleMask](#StyleMask) | La maschera di stile |
| [EndCapMask](#EndCapMask) | La maschera di estremità |
| [JoinMask](#JoinMask) | La maschera di giunzione |
| [TypeMask](#TypeMask) | La maschera di tipo |
### PS_COSMETIC {#PS-COSMETIC}
```
public static final int PS_COSMETIC
```


Un tipo di penna che specifica una linea con larghezza di un'unità logica e uno stile di colore solido

### PS_ENDCAP_ROUND {#PS-ENDCAP-ROUND}
```
public static final int PS_ENDCAP_ROUND
```


Un'estremità di linea che specifica estremità arrotondate.

### PS_JOIN_ROUND {#PS-JOIN-ROUND}
```
public static final int PS_JOIN_ROUND
```


Una giunzione di linea che specifica giunzioni arrotondate

### PS_SOLID {#PS-SOLID}
```
public static final int PS_SOLID
```


Uno stile di linea di colore solido

### PS_DASH {#PS-DASH}
```
public static final int PS_DASH
```


Uno stile di linea tratteggiato

### PS_DOT {#PS-DOT}
```
public static final int PS_DOT
```


Uno stile di linea puntinato.

### PS_DASHDOT {#PS-DASHDOT}
```
public static final int PS_DASHDOT
```


Uno stile di linea costituito da trattini e punti alternati

### PS_DASHDOTDOT {#PS-DASHDOTDOT}
```
public static final int PS_DASHDOTDOT
```


Uno stile di linea che consiste in trattini e doppi punti.

### PS_NULL {#PS-NULL}
```
public static final int PS_NULL
```


Uno stile di linea che è invisibile.

### PS_INSIDEFRAME {#PS-INSIDEFRAME}
```
public static final int PS_INSIDEFRAME
```


Uno stile di linea di colore solido. Quando questo stile è specificato in un record di disegno che utilizza un rettangolo di delimitazione, le dimensioni della figura vengono ridotte in modo che si adattino interamente al rettangolo di delimitazione, tenendo conto della larghezza della penna.

### PS_USERSTYLE {#PS-USERSTYLE}
```
public static final int PS_USERSTYLE
```


Uno stile di linea definito da un array di stile, che specifica le lunghezze dei trattini e degli spazi nella linea

### PS_ALTERNATE {#PS-ALTERNATE}
```
public static final int PS_ALTERNATE
```


Uno stile di linea in cui ogni altro pixel è impostato. Questo stile è applicabile solo a un tipo di penna PS\_COSMETIC

### PS_ENDCAP_SQUARE {#PS-ENDCAP-SQUARE}
```
public static final int PS_ENDCAP_SQUARE
```


Un'estremità di linea che specifica estremità quadrate.

### PS_ENDCAP_FLAT {#PS-ENDCAP-FLAT}
```
public static final int PS_ENDCAP_FLAT
```


Un'estremità di linea che specifica estremità piatte.

### PS_JOIN_BEVEL {#PS-JOIN-BEVEL}
```
public static final int PS_JOIN_BEVEL
```


Una giunzione di linea che specifica giunzioni smussate.

### PS_JOIN_MITER {#PS-JOIN-MITER}
```
public static final int PS_JOIN_MITER
```


Una giunzione di linea che specifica giunzioni a spigolo quando le lunghezze delle giunzioni rientrano nel limite di lunghezza dello spigolo corrente impostato nel contesto del dispositivo di riproduzione. Se le lunghezze delle giunzioni superano il limite dello spigolo, vengono specificate giunzioni smussate

### PS_GEOMETRIC {#PS-GEOMETRIC}
```
public static final int PS_GEOMETRIC
```


Un tipo di penna che specifica una linea con una larghezza misurata in unità logiche e uno stile che può contenere qualsiasi attributo di un pennello.

### StyleMask {#StyleMask}
```
public static final int StyleMask
```


La maschera di stile

### EndCapMask {#EndCapMask}
```
public static final int EndCapMask
```


La maschera di estremità

### JoinMask {#JoinMask}
```
public static final int JoinMask
```


La maschera di giunzione

### TypeMask {#TypeMask}
```
public static final int TypeMask
```


La maschera di tipo

