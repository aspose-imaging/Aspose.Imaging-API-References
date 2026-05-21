---
title: "XmpMeta"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Rappresenta i metadati XMP."
type: docs
weight: 18
url: /it/java/com.aspose.imaging.xmp/xmpmeta/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.xmp.XmpElementBase](../../com.aspose.imaging.xmp/xmpelementbase)

**All Implemented Interfaces:**
[com.aspose.imaging.xmp.IXmlValue](../../com.aspose.imaging.xmp/ixmlvalue), com.aspose.ms.System.IEquatable
```
public final class XmpMeta extends XmpElementBase implements IXmlValue, System.IEquatable<XmpElementBase>
```

Rappresenta i meta xmp. Opzionale. Lo scopo di questo elemento è identificare i metadati XMP all'interno di testo XML generale che potrebbe contenere altri usi non XMP di RDF.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [XmpMeta(String toolkitVersion)](#XmpMeta-java.lang.String-) | Inizializza una nuova istanza della classe `XmpMeta`. |
| [XmpMeta()](#XmpMeta--) | Inizializza una nuova istanza della classe `XmpMeta`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getAdobeXmpToolkit()](#getAdobeXmpToolkit--) | Ottiene o imposta la versione del toolkit Adobe Xmp. |
| [setAdobeXmpToolkit(String value)](#setAdobeXmpToolkit-java.lang.String-) | Ottiene o imposta la versione del toolkit Adobe Xmp. |
| [addAttribute(String attribute, String value)](#addAttribute-java.lang.String-java.lang.String-) | Aggiunge l'attributo. |
| [getXmlValue()](#getXmlValue--) | Converte il valore XMP nella rappresentazione XML. |
| [isEquals(XmpMeta other)](#isEquals-com.aspose.imaging.xmp.XmpMeta-) | Indica se l'oggetto corrente è uguale a un altro oggetto dello stesso tipo. |
| [equals(Object other)](#equals-java.lang.Object-) | Determina se lo `System.Object` specificato è uguale a questa istanza. |
| [hashCode()](#hashCode--) | Restituisce un codice hash per questa istanza. |
### XmpMeta(String toolkitVersion) {#XmpMeta-java.lang.String-}
```
public XmpMeta(String toolkitVersion)
```


Inizializza una nuova istanza della classe `XmpMeta`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| toolkitVersion | java.lang.String | Versione del toolkit Adobe XMP. |

### XmpMeta() {#XmpMeta--}
```
public XmpMeta()
```


Inizializza una nuova istanza della classe `XmpMeta`.

### getAdobeXmpToolkit() {#getAdobeXmpToolkit--}
```
public String getAdobeXmpToolkit()
```


Ottiene o imposta la versione del toolkit Adobe Xmp.

**Returns:**
java.lang.String
### setAdobeXmpToolkit(String value) {#setAdobeXmpToolkit-java.lang.String-}
```
public void setAdobeXmpToolkit(String value)
```


Ottiene o imposta la versione del toolkit Adobe Xmp.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### addAttribute(String attribute, String value) {#addAttribute-java.lang.String-java.lang.String-}
```
public void addAttribute(String attribute, String value)
```


Aggiunge l'attributo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| attributo | java.lang.String | L'attributo. |
| valore | java.lang.String | Il valore. |

### getXmlValue() {#getXmlValue--}
```
public String getXmlValue()
```


Converte il valore XMP nella rappresentazione XML.

**Returns:**
java.lang.String - Restituisce il valore XMP convertito nella rappresentazione XML.
### isEquals(XmpMeta other) {#isEquals-com.aspose.imaging.xmp.XmpMeta-}
```
public boolean isEquals(XmpMeta other)
```


Indica se l'oggetto corrente è uguale a un altro oggetto dello stesso tipo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| other | [XmpMeta](../../com.aspose.imaging.xmp/xmpmeta) | Un oggetto da confrontare con questo oggetto. |

**Returns:**
boolean - true se l'oggetto corrente è uguale al parametro `other`; altrimenti, false.
### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


Determina se lo `System.Object` specificato è uguale a questa istanza.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| altro | java.lang.Object | Il `System.Object` da confrontare con questa istanza. |

**Returns:**
boolean - `true` se lo `System.Object` specificato è uguale a questa istanza; altrimenti, `false`.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Restituisce un codice hash per questa istanza.

**Returns:**
int - Un codice hash per questa istanza, adatto per l'uso in algoritmi di hashing e strutture dati come una tabella hash.
