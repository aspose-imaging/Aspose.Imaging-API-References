---
title: "XmpPackage"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Rappresenta l'astrazione di base per il pacchetto XMP."
type: docs
weight: 19
url: /it/java/com.aspose.imaging.xmp/xmppackage/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.xmp.IXmlValue](../../com.aspose.imaging.xmp/ixmlvalue), com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public class XmpPackage implements IXmlValue, System.Collections.Generic.IGenericEnumerable<System.Collections.Generic.KeyValuePair<String,Object>>
```

Rappresenta l'astrazione di base per il pacchetto XMP.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [XmpPackage(String prefix, String namespaceUri)](#XmpPackage-java.lang.String-java.lang.String-) | Inizializza una nuova istanza della classe `XmpPackage`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getXmlNamespace()](#getXmlNamespace--) | Restituisce lo spazio dei nomi XML. |
| [getPrefix()](#getPrefix--) | Restituisce il prefisso. |
| [getNamespaceUri()](#getNamespaceUri--) | Restituisce l'URI dello spazio dei nomi. |
| [getKeys()](#getKeys--) | Restituisce le chiavi nel pacchetto XMP. |
| [getCount()](#getCount--) | Restituisce il conteggio delle chiavi XMP. |
| [containsKey(String key)](#containsKey-java.lang.String-) | Determina se questa collezione contiene la chiave specificata. |
| [get_Item(String key)](#get-Item-java.lang.String-) | Ottiene o imposta l'`Object` con la chiave specificata. |
| [set_Item(String key, Object value)](#set-Item-java.lang.String-java.lang.Object-) | Imposta l'`Object` con la chiave specificata. |
| [addValue(String key, String value)](#addValue-java.lang.String-java.lang.String-) | Aggiunge il valore alla chiave specificata. |
| [addValue(String key, Object value)](#addValue-java.lang.String-java.lang.Object-) | Aggiunge il valore alla chiave specificata. |
| [tryGetValue(String key, Object[] value)](#tryGetValue-java.lang.String-java.lang.Object---) | Restituisce il valore tramite la `key`. |
| [remove(String key)](#remove-java.lang.String-) | Rimuove il valore con la chiave specificata. |
| [clear()](#clear--) | Cancella questa istanza. |
| [setValue(String key, IXmlValue value)](#setValue-java.lang.String-com.aspose.imaging.xmp.IXmlValue-) | Imposta il valore. |
| [setValue(String key, IXmpType value)](#setValue-java.lang.String-com.aspose.imaging.xmp.types.IXmpType-) | Imposta il valore. |
| [setXmpTypeValue(String key, XmpTypeBase value)](#setXmpTypeValue-java.lang.String-com.aspose.imaging.xmp.types.XmpTypeBase-) | Imposta il valore del tipo XMP. |
| [getXmlValue()](#getXmlValue--) | Converte il valore XMP nella rappresentazione XML. |
| [iterator()](#iterator--) | Restituisce un enumeratore che itera attraverso la collezione. |
### XmpPackage(String prefix, String namespaceUri) {#XmpPackage-java.lang.String-java.lang.String-}
```
public XmpPackage(String prefix, String namespaceUri)
```


Inizializza una nuova istanza della classe `XmpPackage`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| prefisso | java.lang.String | Il prefisso. |
| namespaceUri | java.lang.String | L'URI dello spazio dei nomi. |

### getXmlNamespace() {#getXmlNamespace--}
```
public String getXmlNamespace()
```


Restituisce lo spazio dei nomi XML.

Valore: Lo spazio dei nomi XML.

**Returns:**
java.lang.String
### getPrefix() {#getPrefix--}
```
public String getPrefix()
```


Restituisce il prefisso.

Valore: Il prefisso.

**Returns:**
java.lang.String
### getNamespaceUri() {#getNamespaceUri--}
```
public String getNamespaceUri()
```


Restituisce l'URI dello spazio dei nomi.

Valore: L'URI dello spazio dei nomi.

**Returns:**
java.lang.String
### getKeys() {#getKeys--}
```
public System.Collections.Generic.Dictionary.KeyCollection<String,Object> getKeys()
```


Restituisce le chiavi nel pacchetto XMP.

**Returns:**
com.aspose.ms.System.Collections.Generic.Dictionary.KeyCollection<java.lang.String,java.lang.Object>
### getCount() {#getCount--}
```
public final int getCount()
```


Restituisce il conteggio delle chiavi XMP.

**Returns:**
int - il conteggio delle chiavi XMP.
### containsKey(String key) {#containsKey-java.lang.String-}
```
public boolean containsKey(String key)
```


Determina se questa collezione contiene la chiave specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| chiave | java.lang.String | La chiave da verificare. |

**Returns:**
boolean - `true` se la collezione contiene la chiave specificata; altrimenti, `false`.
### get_Item(String key) {#get-Item-java.lang.String-}
```
public Object get_Item(String key)
```


Ottiene o imposta l'`Object` con la chiave specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| chiave | java.lang.String | La chiave che identifica il valore. |

**Returns:**
java.lang.Object - Restituisce l'`Object` con la chiave specificata.
### set_Item(String key, Object value) {#set-Item-java.lang.String-java.lang.Object-}
```
public void set_Item(String key, Object value)
```


Imposta l'`Object` con la chiave specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| chiave | java.lang.String | La chiave che identifica il valore. |
| valore | java.lang.Object | Il valore dell'`Object`. |

### addValue(String key, String value) {#addValue-java.lang.String-java.lang.String-}
```
public void addValue(String key, String value)
```


Aggiunge il valore alla chiave specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| chiave | java.lang.String | La rappresentazione stringa della chiave identificata con il valore aggiunto. |
| valore | java.lang.String | Il valore a cui aggiungere. |

### addValue(String key, Object value) {#addValue-java.lang.String-java.lang.Object-}
```
public void addValue(String key, Object value)
```


Aggiunge il valore alla chiave specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| chiave | java.lang.String | La rappresentazione stringa della chiave identificata con il valore aggiunto. |
| valore | java.lang.Object | Il valore a cui aggiungere. |

### tryGetValue(String key, Object[] value) {#tryGetValue-java.lang.String-java.lang.Object---}
```
public final boolean tryGetValue(String key, Object[] value)
```


Restituisce il valore tramite la `key`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| chiave | java.lang.String | La chiave dell'elemento XMP. |
| valore | java.lang.Object[] | Il valore XMP. |

**Returns:**
boolean - `true`, se la collezione contiene la `key`; altrimenti, `false`.
### remove(String key) {#remove-java.lang.String-}
```
public boolean remove(String key)
```


Rimuove il valore con la chiave specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| chiave | java.lang.String | La rappresentazione stringa della chiave identificata con il valore rimosso. |

**Returns:**
boolean - Restituisce true se il valore con la chiave specificata è stato rimosso.
### clear() {#clear--}
```
public void clear()
```


Cancella questa istanza.

### setValue(String key, IXmlValue value) {#setValue-java.lang.String-com.aspose.imaging.xmp.IXmlValue-}
```
public void setValue(String key, IXmlValue value)
```


Imposta il valore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| chiave | java.lang.String | La rappresentazione stringa della chiave identificata con il valore aggiunto. |
| value | [IXmlValue](../../com.aspose.imaging.xmp/ixmlvalue) | Il valore a cui aggiungere. |

### setValue(String key, IXmpType value) {#setValue-java.lang.String-com.aspose.imaging.xmp.types.IXmpType-}
```
public void setValue(String key, IXmpType value)
```


Imposta il valore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| chiave | java.lang.String | La rappresentazione stringa della chiave identificata con il valore aggiunto. |
| value | [IXmpType](../../com.aspose.imaging.xmp.types/ixmptype) | Il valore a cui aggiungere. |

### setXmpTypeValue(String key, XmpTypeBase value) {#setXmpTypeValue-java.lang.String-com.aspose.imaging.xmp.types.XmpTypeBase-}
```
public void setXmpTypeValue(String key, XmpTypeBase value)
```


Imposta il valore del tipo XMP.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| chiave | java.lang.String | La rappresentazione stringa della chiave identificata con il valore impostato. |
| value | [XmpTypeBase](../../com.aspose.imaging.xmp.types/xmptypebase) | Il valore da impostare. |

### getXmlValue() {#getXmlValue--}
```
public String getXmlValue()
```


Converte il valore XMP nella rappresentazione XML.

**Returns:**
java.lang.String - Restituisce il valore XMP convertito nella rappresentazione XML.
### iterator() {#iterator--}
```
public System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,Object>> iterator()
```


Restituisce un enumeratore che itera attraverso la collezione.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.Object>> - Un `T:System.Collections.Generic.IEnumerator\`1` che può essere usato per iterare attraverso la collezione.
