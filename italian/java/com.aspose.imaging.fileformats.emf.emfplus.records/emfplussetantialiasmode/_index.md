---
title: "EmfPlusSetAntiAliasMode"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il record EmfPlusSetAntiAliasMode specifica la modalità di anti-aliasing per l'output del testo."
type: docs
weight: 54
url: /it/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplussetantialiasmode/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusPropertyRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfpluspropertyrecordtype)
```
public final class EmfPlusSetAntiAliasMode extends EmfPlusPropertyRecordType
```

Il record EmfPlusSetAntiAliasMode specifica la modalità di anti-aliasing per l'output del testo.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfPlusSetAntiAliasMode(EmfPlusRecord source)](#EmfPlusSetAntiAliasMode-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Inizializza una nuova istanza della classe `EmfPlusSetAntiAliasMode`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getSmoothingMode()](#getSmoothingMode--) | Ottiene o imposta la modalità di smussatura. |
| [setSmoothingMode(byte value)](#setSmoothingMode-byte-) | Ottiene o imposta la modalità di smussatura. |
| [getAntiAliasing()](#getAntiAliasing--) | Ottiene o imposta un valore che indica se [anti aliasing]. |
| [setAntiAliasing(boolean value)](#setAntiAliasing-boolean-) | Ottiene o imposta un valore che indica se [anti aliasing]. |
### EmfPlusSetAntiAliasMode(EmfPlusRecord source) {#EmfPlusSetAntiAliasMode-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusSetAntiAliasMode(EmfPlusRecord source)
```


Inizializza una nuova istanza della classe `EmfPlusSetAntiAliasMode`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | La sorgente. |

### getSmoothingMode() {#getSmoothingMode--}
```
public byte getSmoothingMode()
```


Ottiene o imposta la modalità di smussatura. (7 bit): il valore della modalità di smussatura, dall'enumerazione SmoothingMode (sezione 2.1.1.28)

Valore: La modalità di smussatura.

**Returns:**
byte
### setSmoothingMode(byte value) {#setSmoothingMode-byte-}
```
public void setSmoothingMode(byte value)
```


Ottiene o imposta la modalità di smussatura. (7 bit): il valore della modalità di smussatura, dall'enumerazione SmoothingMode (sezione 2.1.1.28)

Valore: La modalità di smussatura.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte |  |

### getAntiAliasing() {#getAntiAliasing--}
```
public boolean getAntiAliasing()
```


Ottiene o imposta un valore che indica se [anti aliasing]. Se impostato, l'anti-aliasing DEVE essere eseguito. Se non impostato, l'anti-aliasing NON DEVE essere eseguito.

Valore: `true` se [anti aliasing]; altrimenti, `false`.

**Returns:**
boolean
### setAntiAliasing(boolean value) {#setAntiAliasing-boolean-}
```
public void setAntiAliasing(boolean value)
```


Ottiene o imposta un valore che indica se [anti aliasing]. Se impostato, l'anti-aliasing DEVE essere eseguito. Se non impostato, l'anti-aliasing NON DEVE essere eseguito.

Valore: `true` se [anti aliasing]; altrimenti, `false`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

