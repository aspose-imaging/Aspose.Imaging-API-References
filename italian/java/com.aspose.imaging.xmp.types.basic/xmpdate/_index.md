---
title: "XmpDate"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Rappresenta la data nel pacchetto XMP."
type: docs
weight: 11
url: /it/java/com.aspose.imaging.xmp.types.basic/xmpdate/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.xmp.types.XmpTypeBase](../../com.aspose.imaging.xmp.types/xmptypebase)
```
public final class XmpDate extends XmpTypeBase
```

Rappresenta la data nel pacchetto XMP.

Un valore data-ora è rappresentato usando un sottoinsieme dei formati come definito in Formati di Data e Ora: YYYY YYYY-MM YYYY-MM-DD YYYY-MM-DDThh:mmTZD YYYY-MM-DDThh:mm:ssTZD YYYY-MM-DDThh:mm:ss.sTZD
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [XmpDate(Date dateTime)](#XmpDate-java.util.Date-) | Inizializza una nuova istanza della classe `XmpDate`. |
| [XmpDate(String dateString)](#XmpDate-java.lang.String-) | Inizializza una nuova istanza della classe `XmpDate`. |
## Campi

| Campo | Descrizione |
| --- | --- |
| [ISO_8601_FORMAT](#ISO-8601-FORMAT) | La stringa di formato ISO 8601 (roundtrip). |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getValue()](#getValue--) | Ottiene o imposta il valore della data. |
| [setValue(Date value)](#setValue-java.util.Date-) | Ottiene o imposta il valore della data. |
| [getFormat()](#getFormat--) | Ottiene la stringa di formato per il valore corrente. |
| [getXmpRepresentation()](#getXmpRepresentation--) | Restituisce il valore contenuto della stringa in formato XMP. |
### XmpDate(Date dateTime) {#XmpDate-java.util.Date-}
```
public XmpDate(Date dateTime)
```


Inizializza una nuova istanza della classe `XmpDate`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dateTime | java.util.Date | Un valore data-ora rappresentato usando un sottoinsieme della formattazione ISO RFC 8601. |

### XmpDate(String dateString) {#XmpDate-java.lang.String-}
```
public XmpDate(String dateString)
```


Inizializza una nuova istanza della classe `XmpDate`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dateString | java.lang.String | La rappresentazione stringa della data. |

### ISO_8601_FORMAT {#ISO-8601-FORMAT}
```
public static final String ISO_8601_FORMAT
```


La stringa di formato ISO 8601 (roundtrip).

Vedi di più: [ here ][here].


[here]: https://en.wikipedia.org/wiki/ISO_8601

### getValue() {#getValue--}
```
public Date getValue()
```


Ottiene o imposta il valore della data.

Valore: Il valore della data.

**Returns:**
java.util.Date
### setValue(Date value) {#setValue-java.util.Date-}
```
public void setValue(Date value)
```


Ottiene o imposta il valore della data.

Valore: Il valore della data.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.util.Date |  |

### getFormat() {#getFormat--}
```
public String getFormat()
```


Ottiene la stringa di formato per il valore corrente.

Valore: La stringa di formato per il valore corrente.

**Returns:**
java.lang.String
### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


Restituisce il valore contenuto della stringa in formato XMP.

**Returns:**
java.lang.String - Restituisce la stringa contenente la rappresentazione xmp
