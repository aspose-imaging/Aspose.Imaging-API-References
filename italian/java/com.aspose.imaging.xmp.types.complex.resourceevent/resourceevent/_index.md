---
title: "ResourceEvent"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Contiene le dimensioni per un oggetto disegnato."
type: docs
weight: 10
url: /it/java/com.aspose.imaging.xmp.types.complex.resourceevent/resourceevent/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.xmp.types.XmpTypeBase](../../com.aspose.imaging.xmp.types/xmptypebase), [com.aspose.imaging.xmp.types.complex.ComplexTypeBase](../../com.aspose.imaging.xmp.types.complex/complextypebase)
```
public final class ResourceEvent extends ComplexTypeBase
```

Contiene le dimensioni per un oggetto disegnato.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [ResourceEvent()](#ResourceEvent--) | Inizializza una nuova istanza della classe `ResourceEvent`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getAction()](#getAction--) | Restituisce l'azione. |
| [setAction(String value)](#setAction-java.lang.String-) | Imposta l'azione. |
| [getChanged()](#getChanged--) | Restituisce l'elenco delimitato da punti e virgola delle parti della risorsa che sono state modificate dalla cronologia degli eventi precedente. |
| [setChanged(String value)](#setChanged-java.lang.String-) | Imposta l'elenco delimitato da punti e virgola delle parti della risorsa che sono state modificate dalla cronologia degli eventi precedente. |
| [getInstanceId()](#getInstanceId--) | Restituisce il valore di xmpMM:InstanceId. |
| [setInstanceId(UUID value)](#setInstanceId-java.util.UUID-) | Restituisce o imposta il valore di xmpMM:InstanceId. |
| [getParameters()](#getParameters--) | Restituisce o imposta la descrizione aggiuntiva dell'azione. |
| [setParameters(String value)](#setParameters-java.lang.String-) | Restituisce o imposta la descrizione aggiuntiva dell'azione. |
| [getSofwareAgentName()](#getSofwareAgentName--) | Restituisce o imposta il nome dell'agente software. |
| [setSofwareAgentName(String value)](#setSofwareAgentName-java.lang.String-) | Restituisce o imposta il nome dell'agente software. |
| [getActionDate()](#getActionDate--) | Restituisce o imposta la data dell'azione. |
| [setActionDate(Date value)](#setActionDate-java.util.Date-) | Restituisce o imposta la data dell'azione. |
| [getXmpRepresentation()](#getXmpRepresentation--) | Ottiene il valore della stringa contenuta in formato XMP. |
### ResourceEvent() {#ResourceEvent--}
```
public ResourceEvent()
```


Inizializza una nuova istanza della classe `ResourceEvent`.

### getAction() {#getAction--}
```
public String getAction()
```


Restituisce l'azione.

I valori definiti sono: converted, copied, created, cropped, edited, filtered, formatted, version\_updated, printed, published, managed, produced, resized, saved. I nuovi valori dovrebbero essere verbi al tempo passato.

**Returns:**
java.lang.String - L'azione.
### setAction(String value) {#setAction-java.lang.String-}
```
public void setAction(String value)
```


Imposta l'azione.

I valori definiti sono: converted, copied, created, cropped, edited, filtered, formatted, version\_updated, printed, published, managed, produced, resized, saved. I nuovi valori dovrebbero essere verbi al tempo passato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String | L'azione. |

### getChanged() {#getChanged--}
```
public String getChanged()
```


Restituisce l'elenco delimitato da punti e virgola delle parti della risorsa che sono state modificate dalla cronologia degli eventi precedente.

**Returns:**
java.lang.String - L'elenco delimitato da punti e virgola delle parti della risorsa che sono state modificate dalla cronologia degli eventi precedente.
### setChanged(String value) {#setChanged-java.lang.String-}
```
public void setChanged(String value)
```


Imposta l'elenco delimitato da punti e virgola delle parti della risorsa che sono state modificate dalla cronologia degli eventi precedente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String | L'elenco delimitato da punti e virgola delle parti della risorsa che sono state modificate dalla cronologia degli eventi precedente. |

### getInstanceId() {#getInstanceId--}
```
public UUID getInstanceId()
```


Restituisce il valore di xmpMM:InstanceId.

**Returns:**
java.util.UUID - Il valore di xmpMM:InstanceId.
### setInstanceId(UUID value) {#setInstanceId-java.util.UUID-}
```
public void setInstanceId(UUID value)
```


Restituisce o imposta il valore di xmpMM:InstanceId.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.util.UUID | Il valore di xmpMM:InstanceId. |

### getParameters() {#getParameters--}
```
public String getParameters()
```


Restituisce o imposta la descrizione aggiuntiva dell'azione.

Valore: La descrizione aggiuntiva dell'azione.

**Returns:**
java.lang.String
### setParameters(String value) {#setParameters-java.lang.String-}
```
public void setParameters(String value)
```


Restituisce o imposta la descrizione aggiuntiva dell'azione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String | La descrizione aggiuntiva dell'azione. |

### getSofwareAgentName() {#getSofwareAgentName--}
```
public String getSofwareAgentName()
```


Restituisce o imposta il nome dell'agente software.

**Returns:**
java.lang.String - Il nome dell'agente software.
### setSofwareAgentName(String value) {#setSofwareAgentName-java.lang.String-}
```
public void setSofwareAgentName(String value)
```


Restituisce o imposta il nome dell'agente software.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String | Il nome dell'agente software. |

### getActionDate() {#getActionDate--}
```
public Date getActionDate()
```


Restituisce o imposta la data dell'azione.

**Returns:**
java.util.Date - La data dell'azione.
### setActionDate(Date value) {#setActionDate-java.util.Date-}
```
public void setActionDate(Date value)
```


Restituisce o imposta la data dell'azione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.util.Date | La data dell'azione. |

### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


Ottiene il valore della stringa contenuta in formato XMP.

**Returns:**
java.lang.String - Restituisce il valore della stringa contenuta in formato XMP.
