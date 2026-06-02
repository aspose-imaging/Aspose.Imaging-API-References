---
title: "Livello"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Rappresenta il livello di testo Photoshop."
type: docs
weight: 11
url: /it/java/com.aspose.imaging.xmp.schemas.photoshop/layer/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.xmp.types.XmpTypeBase](../../com.aspose.imaging.xmp.types/xmptypebase)

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable
```
public class Layer extends XmpTypeBase implements System.IEquatable<Layer>
```

Rappresenta il livello di testo Photoshop.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Layer(String layerName, String layerText)](#Layer-java.lang.String-java.lang.String-) | Inizializza una nuova istanza della classe `Layer`. |
| [Layer()](#Layer--) | Inizializza una nuova istanza della classe `Layer`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getName()](#getName--) | Ottiene o imposta il nome del livello di testo. |
| [setName(String value)](#setName-java.lang.String-) | Ottiene o imposta il nome del livello di testo. |
| [getText()](#getText--) | Ottiene o imposta il contenuto testuale del livello. |
| [setText(String value)](#setText-java.lang.String-) | Ottiene o imposta il contenuto testuale del livello. |
| [getXmpRepresentation()](#getXmpRepresentation--) | Restituisce il valore contenuto della stringa in formato XMP. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determina se lo `System.Object` specificato è uguale a questa istanza. |
| [isEquals(Layer other)](#isEquals-com.aspose.imaging.xmp.schemas.photoshop.Layer-) | Indica se l'oggetto corrente è uguale a un altro oggetto dello stesso tipo. |
| [hashCode()](#hashCode--) | Restituisce un codice hash per questa istanza. |
### Layer(String layerName, String layerText) {#Layer-java.lang.String-java.lang.String-}
```
public Layer(String layerName, String layerText)
```


Inizializza una nuova istanza della classe `Layer`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| layerName | java.lang.String | Nome del livello. |
| layerText | java.lang.String | Il testo del livello. |

### Layer() {#Layer--}
```
public Layer()
```


Inizializza una nuova istanza della classe `Layer`.

### getName() {#getName--}
```
public String getName()
```


Ottiene o imposta il nome del livello di testo.

Valore: Il nome del livello di testo.

**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Ottiene o imposta il nome del livello di testo.

Valore: Il nome del livello di testo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getText() {#getText--}
```
public String getText()
```


Ottiene o imposta il contenuto testuale del livello.

Valore: Il contenuto testuale del livello.

**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


Ottiene o imposta il contenuto testuale del livello.

Valore: Il contenuto testuale del livello.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


Restituisce il valore contenuto della stringa in formato XMP.

**Returns:**
java.lang.String - Restituisce il valore della stringa contenuta in formato XMP.
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
### isEquals(Layer other) {#isEquals-com.aspose.imaging.xmp.schemas.photoshop.Layer-}
```
public boolean isEquals(Layer other)
```


Indica se l'oggetto corrente è uguale a un altro oggetto dello stesso tipo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| other | [Layer](../../com.aspose.imaging.xmp.schemas.photoshop/layer) | Un oggetto da confrontare con questo oggetto. |

**Returns:**
boolean - true se l'oggetto corrente è uguale al parametro `other`; altrimenti, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Restituisce un codice hash per questa istanza.

**Returns:**
int - Un codice hash per questa istanza, adatto per l'uso in algoritmi di hashing e strutture dati come una tabella hash.
