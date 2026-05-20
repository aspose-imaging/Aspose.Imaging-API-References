---
title: "XmpElementBase"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Rappresenta l'elemento base XMP che contiene attributi."
type: docs
weight: 16
url: /it/java/com.aspose.imaging.xmp/xmpelementbase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable
```
public abstract class XmpElementBase implements System.IEquatable<XmpElementBase>
```

Rappresenta l'elemento base XMP che contiene attributi.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [addAttribute(String attribute, String value)](#addAttribute-java.lang.String-java.lang.String-) | Aggiunge l'attributo. |
| [getAttribute(String attribute)](#getAttribute-java.lang.String-) | Ottiene l'attributo. |
| [clearAttributes()](#clearAttributes--) | Rimuove tutti gli attributi. |
| [isEquals(XmpElementBase other)](#isEquals-com.aspose.imaging.xmp.XmpElementBase-) | Indica se l'oggetto corrente è uguale a un altro oggetto dello stesso tipo. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determina se l'`Object` specificato è uguale a questa istanza. |
| [hashCode()](#hashCode--) | Restituisce un codice hash per questa istanza. |
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

### getAttribute(String attribute) {#getAttribute-java.lang.String-}
```
public String getAttribute(String attribute)
```


Ottiene l'attributo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| attributo | java.lang.String | L'attributo. |

**Returns:**
java.lang.String - Restituisce l'attributo per il nome dell'attributo specificato.
### clearAttributes() {#clearAttributes--}
```
public void clearAttributes()
```


Rimuove tutti gli attributi.

### isEquals(XmpElementBase other) {#isEquals-com.aspose.imaging.xmp.XmpElementBase-}
```
public boolean isEquals(XmpElementBase other)
```


Indica se l'oggetto corrente è uguale a un altro oggetto dello stesso tipo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| other | [XmpElementBase](../../com.aspose.imaging.xmp/xmpelementbase) | Un oggetto da confrontare con questo oggetto. |

**Returns:**
boolean - true se l'oggetto corrente è uguale al parametro `other`; altrimenti, false.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determina se l'`Object` specificato è uguale a questa istanza.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | java.lang.Object | L'`Object` da confrontare con questa istanza. |

**Returns:**
boolean - `true` se l'`Object` specificato è uguale a questa istanza; altrimenti, `false`.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Restituisce un codice hash per questa istanza.

**Returns:**
int - Un codice hash per questa istanza, adatto per l'uso in algoritmi di hashing e strutture dati come una tabella hash.
