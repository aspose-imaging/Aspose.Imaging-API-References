---
title: "XmpHeaderPi"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Rappresenta l'istruzione di elaborazione dell'intestazione XMP."
type: docs
weight: 17
url: /it/java/com.aspose.imaging.xmp/xmpheaderpi/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.xmp.IXmlValue](../../com.aspose.imaging.xmp/ixmlvalue), com.aspose.ms.System.IEquatable
```
public final class XmpHeaderPi implements IXmlValue, System.IEquatable<XmpHeaderPi>
```

Rappresenta l'istruzione di elaborazione dell'intestazione XMP.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [XmpHeaderPi()](#XmpHeaderPi--) | Inizializza una nuova istanza della classe `XmpHeaderPi`. |
| [XmpHeaderPi(String guid)](#XmpHeaderPi-java.lang.String-) | Inizializza una nuova istanza della classe `XmpHeaderPi`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getGuid()](#getGuid--) | Rappresenta l'GUID dell'intestazione. |
| [setGuid(String value)](#setGuid-java.lang.String-) | Rappresenta l'GUID dell'intestazione. |
| [getXmlValue()](#getXmlValue--) | Converte il valore XMP nella rappresentazione XML. |
| [isEquals(XmpHeaderPi other)](#isEquals-com.aspose.imaging.xmp.XmpHeaderPi-) | Indica se l'oggetto corrente è uguale a un altro oggetto dello stesso tipo. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determina se lo `System.Object` specificato è uguale a questa istanza. |
| [hashCode()](#hashCode--) | Restituisce un codice hash per questa istanza. |
### XmpHeaderPi() {#XmpHeaderPi--}
```
public XmpHeaderPi()
```


Inizializza una nuova istanza della classe `XmpHeaderPi`.

### XmpHeaderPi(String guid) {#XmpHeaderPi-java.lang.String-}
```
public XmpHeaderPi(String guid)
```


Inizializza una nuova istanza della classe `XmpHeaderPi`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| guid | java.lang.String | L'identificatore univoco. |

### getGuid() {#getGuid--}
```
public String getGuid()
```


Rappresenta l'GUID dell'intestazione.

Il testo dell'intestazione PI contiene un GUID, rendendo improbabile che appaia accidentalmente nel flusso di dati.

**Returns:**
java.lang.String
### setGuid(String value) {#setGuid-java.lang.String-}
```
public void setGuid(String value)
```


Rappresenta l'GUID dell'intestazione.

Il testo dell'intestazione PI contiene un GUID, rendendo improbabile che appaia accidentalmente nel flusso di dati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getXmlValue() {#getXmlValue--}
```
public String getXmlValue()
```


Converte il valore XMP nella rappresentazione XML.

**Returns:**
java.lang.String - Restituisce il valore XMP convertito nella rappresentazione XML.
### isEquals(XmpHeaderPi other) {#isEquals-com.aspose.imaging.xmp.XmpHeaderPi-}
```
public boolean isEquals(XmpHeaderPi other)
```


Indica se l'oggetto corrente è uguale a un altro oggetto dello stesso tipo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| other | [XmpHeaderPi](../../com.aspose.imaging.xmp/xmpheaderpi) | Un oggetto da confrontare con questo oggetto. |

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
