---
title: "XmpTrailerPi"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Rappresenta l'istruzione di elaborazione del trailer XMP."
type: docs
weight: 23
url: /it/java/com.aspose.imaging.xmp/xmptrailerpi/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.xmp.IXmlValue](../../com.aspose.imaging.xmp/ixmlvalue), com.aspose.ms.System.IEquatable
```
public final class XmpTrailerPi implements IXmlValue, System.IEquatable<XmpTrailerPi>
```

Rappresenta l'istruzione di elaborazione del trailer XMP.

La parte end=\"w\" o end=\"r\" deve essere usata dai processori di scansione dei pacchetti per determinare se l'XMP può essere modificato in loco.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [XmpTrailerPi(boolean isWritable)](#XmpTrailerPi-boolean-) | Inizializza una nuova istanza della classe `XmpTrailerPi`. |
| [XmpTrailerPi()](#XmpTrailerPi--) | Inizializza una nuova istanza della classe `XmpTrailerPi`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [isWritable()](#isWritable--) | Ottiene o imposta un valore che indica se questa istanza è scrivibile. |
| [setWritable(boolean value)](#setWritable-boolean-) | Ottiene o imposta un valore che indica se questa istanza è scrivibile. |
| [getXmlValue()](#getXmlValue--) | Converte il valore xmp nella rappresentazione xml. |
| [isEquals(XmpTrailerPi other)](#isEquals-com.aspose.imaging.xmp.XmpTrailerPi-) | Indica se l'oggetto corrente è uguale a un altro oggetto dello stesso tipo. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determina se lo `System.Object` specificato è uguale a questa istanza. |
| [hashCode()](#hashCode--) | Restituisce un codice hash per questa istanza. |
### XmpTrailerPi(boolean isWritable) {#XmpTrailerPi-boolean-}
```
public XmpTrailerPi(boolean isWritable)
```


Inizializza una nuova istanza della classe `XmpTrailerPi`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| isWritable | boolean | Indica se il trailer è scrivibile. |

### XmpTrailerPi() {#XmpTrailerPi--}
```
public XmpTrailerPi()
```


Inizializza una nuova istanza della classe `XmpTrailerPi`.

### isWritable() {#isWritable--}
```
public boolean isWritable()
```


Ottiene o imposta un valore che indica se questa istanza è scrivibile.

Valore: `true` se questa istanza è scrivibile; altrimenti, `false`.

**Returns:**
boolean
### setWritable(boolean value) {#setWritable-boolean-}
```
public void setWritable(boolean value)
```


Ottiene o imposta un valore che indica se questa istanza è scrivibile.

Valore: `true` se questa istanza è scrivibile; altrimenti, `false`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### getXmlValue() {#getXmlValue--}
```
public String getXmlValue()
```


Converte il valore xmp nella rappresentazione xml.

**Returns:**
java.lang.String - Restituisce la rappresentazione XML di XMP.
### isEquals(XmpTrailerPi other) {#isEquals-com.aspose.imaging.xmp.XmpTrailerPi-}
```
public boolean isEquals(XmpTrailerPi other)
```


Indica se l'oggetto corrente è uguale a un altro oggetto dello stesso tipo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| other | [XmpTrailerPi](../../com.aspose.imaging.xmp/xmptrailerpi) | Un oggetto da confrontare con questo oggetto. |

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
