---
title: "Time"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Rappresentazione di un valore temporale in secondi."
type: docs
weight: 14
url: /it/java/com.aspose.imaging.xmp.schemas.xmpdm/time/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.xmp.types.XmpTypeBase](../../com.aspose.imaging.xmp.types/xmptypebase)
```
public final class Time extends XmpTypeBase
```

Rappresentazione di un valore temporale in secondi.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Time(Rational scale, int value)](#Time-com.aspose.imaging.xmp.types.derived.Rational-int-) | Inizializza una nuova istanza della classe `Time`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getScale()](#getScale--) | Ottiene o imposta la scala per il valore del tempo. |
| [setScale(Rational value)](#setScale-com.aspose.imaging.xmp.types.derived.Rational-) | Ottiene o imposta la scala per il valore del tempo. |
| [getValue()](#getValue--) | Ottiene o imposta il valore temporale nella scala specificata. |
| [setValue(int value)](#setValue-int-) | Ottiene o imposta il valore temporale nella scala specificata. |
| [getXmpRepresentation()](#getXmpRepresentation--) | Ottiene il valore della stringa contenuta in formato XMP. |
### Time(Rational scale, int value) {#Time-com.aspose.imaging.xmp.types.derived.Rational-int-}
```
public Time(Rational scale, int value)
```


Inizializza una nuova istanza della classe `Time`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| scale | [Rational](../../com.aspose.imaging.xmp.types.derived/rational) | La scala. |
| valore | int | Il valore. |

### getScale() {#getScale--}
```
public Rational getScale()
```


Ottiene o imposta la scala per il valore del tempo.

Per NTSC, usa 1001/30000, o il meno preciso 100/2997. Per PAL, usa 1/25. Valore: La scala per il valore temporale.

**Returns:**
[Rational](../../com.aspose.imaging.xmp.types.derived/rational)
### setScale(Rational value) {#setScale-com.aspose.imaging.xmp.types.derived.Rational-}
```
public void setScale(Rational value)
```


Ottiene o imposta la scala per il valore del tempo.

Per NTSC, usa 1001/30000, o il meno preciso 100/2997. Per PAL, usa 1/25. Valore: La scala per il valore temporale.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Rational](../../com.aspose.imaging.xmp.types.derived/rational) |  |

### getValue() {#getValue--}
```
public int getValue()
```


Ottiene o imposta il valore temporale nella scala specificata.

Valore: Il valore temporale nella scala specificata.

**Returns:**
int
### setValue(int value) {#setValue-int-}
```
public void setValue(int value)
```


Ottiene o imposta il valore temporale nella scala specificata.

Valore: Il valore temporale nella scala specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


Ottiene il valore della stringa contenuta in formato XMP.

**Returns:**
java.lang.String - Restituisce il valore della stringa contenuta in formato XMP.
