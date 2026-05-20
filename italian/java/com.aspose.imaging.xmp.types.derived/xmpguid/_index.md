---
title: "XmpGuid"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Rappresenta l'identificatore unico globale XMP."
type: docs
weight: 14
url: /it/java/com.aspose.imaging.xmp.types.derived/xmpguid/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.xmp.types.XmpTypeBase](../../com.aspose.imaging.xmp.types/xmptypebase)
```
public final class XmpGuid extends XmpTypeBase
```

Rappresenta l'identificatore unico globale XMP.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [XmpGuid(String value)](#XmpGuid-java.lang.String-) | Inizializza una nuova istanza della classe `XmpGuid`. |
| [XmpGuid(UUID guid)](#XmpGuid-java.util.UUID-) | Inizializza una nuova istanza della classe `XmpGuid`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getPrefix()](#getPrefix--) | Ottiene o imposta il prefisso, ad esempio uuid. |
| [setPrefix(String value)](#setPrefix-java.lang.String-) | Ottiene o imposta il prefisso, ad esempio uuid. |
| [getValue()](#getValue--) | Ottiene o imposta il valore. |
| [setValue(UUID value)](#setValue-java.util.UUID-) | Ottiene o imposta il valore. |
| [getXmpRepresentation()](#getXmpRepresentation--) | Ottiene il valore della stringa contenuta in formato XMP. |
### XmpGuid(String value) {#XmpGuid-java.lang.String-}
```
public XmpGuid(String value)
```


Inizializza una nuova istanza della classe `XmpGuid`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String | Il valore. |

### XmpGuid(UUID guid) {#XmpGuid-java.util.UUID-}
```
public XmpGuid(UUID guid)
```


Inizializza una nuova istanza della classe `XmpGuid`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| guid | java.util.UUID | L'identificatore univoco. |

### getPrefix() {#getPrefix--}
```
public String getPrefix()
```


Ottiene o imposta il prefisso, ad esempio uuid.

Valore: Il prefisso, ad esempio uuid.

**Returns:**
java.lang.String
### setPrefix(String value) {#setPrefix-java.lang.String-}
```
public void setPrefix(String value)
```


Ottiene o imposta il prefisso, ad esempio uuid.

Valore: Il prefisso, ad esempio uuid.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getValue() {#getValue--}
```
public UUID getValue()
```


Ottiene o imposta il valore.

Valore: Il valore.

**Returns:**
java.util.UUID
### setValue(UUID value) {#setValue-java.util.UUID-}
```
public void setValue(UUID value)
```


Ottiene o imposta il valore.

Valore: Il valore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.util.UUID |  |

### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


Ottiene il valore della stringa contenuta in formato XMP.

**Returns:**
java.lang.String - Restituisce il valore della stringa contenuta in formato XMP.
