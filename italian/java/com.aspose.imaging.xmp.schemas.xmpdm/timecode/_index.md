---
title: "Timecode"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Rappresenta il valore del timecode nel video."
type: docs
weight: 16
url: /it/java/com.aspose.imaging.xmp.schemas.xmpdm/timecode/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.xmp.types.XmpTypeBase](../../com.aspose.imaging.xmp.types/xmptypebase)

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable
```
public final class Timecode extends XmpTypeBase implements System.IEquatable<Timecode>
```

Rappresenta il valore del timecode nel video.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Timecode(TimeFormat format, String timeValue)](#Timecode-com.aspose.imaging.xmp.schemas.xmpdm.TimeFormat-java.lang.String-) | Inizializza una nuova istanza della classe `Timecode`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getFormat()](#getFormat--) | Ottiene o imposta il formato utilizzato in `TimeValue`. |
| [setFormat(TimeFormat value)](#setFormat-com.aspose.imaging.xmp.schemas.xmpdm.TimeFormat-) | Ottiene o imposta il formato utilizzato in `TimeValue`. |
| [getTimeValue()](#getTimeValue--) | Ottiene o imposta il valore temporale nel formato specificato. |
| [setTimeValue(String value)](#setTimeValue-java.lang.String-) | Ottiene o imposta il valore temporale nel formato specificato. |
| [getXmpRepresentation()](#getXmpRepresentation--) | Restituisce il valore stringa contenuto in formato XMP. |
| [isEquals(Timecode other)](#isEquals-com.aspose.imaging.xmp.schemas.xmpdm.Timecode-) | Indica se l'oggetto corrente è uguale a un altro oggetto dello stesso tipo. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determina se lo `System.Object` specificato è uguale a questa istanza. |
| [hashCode()](#hashCode--) | Restituisce un codice hash per questa istanza. |
### Timecode(TimeFormat format, String timeValue) {#Timecode-com.aspose.imaging.xmp.schemas.xmpdm.TimeFormat-java.lang.String-}
```
public Timecode(TimeFormat format, String timeValue)
```


Inizializza una nuova istanza della classe `Timecode`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| format | [TimeFormat](../../com.aspose.imaging.xmp.schemas.xmpdm/timeformat) | Il formato temporale. |
| timeValue | java.lang.String | Il valore temporale. |

### getFormat() {#getFormat--}
```
public TimeFormat getFormat()
```


Ottiene o imposta il formato utilizzato in `TimeValue`.

Valore: Il formato utilizzato in `TimeValue`.

**Returns:**
[TimeFormat](../../com.aspose.imaging.xmp.schemas.xmpdm/timeformat)
### setFormat(TimeFormat value) {#setFormat-com.aspose.imaging.xmp.schemas.xmpdm.TimeFormat-}
```
public void setFormat(TimeFormat value)
```


Ottiene o imposta il formato utilizzato in `TimeValue`.

Valore: Il formato utilizzato in `TimeValue`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [TimeFormat](../../com.aspose.imaging.xmp.schemas.xmpdm/timeformat) |  |

### getTimeValue() {#getTimeValue--}
```
public String getTimeValue()
```


Ottiene o imposta il valore temporale nel formato specificato.

Valore: Il valore temporale nel formato specificato.

**Returns:**
java.lang.String
### setTimeValue(String value) {#setTimeValue-java.lang.String-}
```
public void setTimeValue(String value)
```


Ottiene o imposta il valore temporale nel formato specificato.

Valore: Il valore temporale nel formato specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


Restituisce il valore stringa contenuto in formato XMP.

**Returns:**
java.lang.String - Restituisce la stringa contenente la rappresentazione xmp.
### isEquals(Timecode other) {#isEquals-com.aspose.imaging.xmp.schemas.xmpdm.Timecode-}
```
public boolean isEquals(Timecode other)
```


Indica se l'oggetto corrente è uguale a un altro oggetto dello stesso tipo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| other | [Timecode](../../com.aspose.imaging.xmp.schemas.xmpdm/timecode) | Un oggetto da confrontare con questo oggetto. |

**Returns:**
boolean - true se l'oggetto corrente è uguale al parametro `other`; altrimenti, false.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determina se lo `System.Object` specificato è uguale a questa istanza.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | java.lang.Object | Il `System.Object` da confrontare con questa istanza. |

**Returns:**
boolean - `true` se lo `System.Object` specificato è uguale a questa istanza; altrimenti, `false`.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Restituisce un codice hash per questa istanza.

**Returns:**
int - Un codice hash per questa istanza, adatto per l'uso in algoritmi di hashing e strutture dati come una tabella hash.
