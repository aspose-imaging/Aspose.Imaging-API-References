---
title: "EmfEpsData"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "L'oggetto EpsData è un contenitore per i dati EPS"
type: docs
weight: 14
url: /it/java/com.aspose.imaging.fileformats.emf.emf.objects/emfepsdata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public final class EmfEpsData extends EmfObject
```

L'oggetto EpsData è un contenitore per i dati EPS
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfEpsData()](#EmfEpsData--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getSizeData()](#getSizeData--) | Ottiene o imposta un intero senza segno a 32 bit che specifica la dimensione totale di questo oggetto, in byte |
| [setSizeData(int value)](#setSizeData-int-) | Ottiene o imposta un intero senza segno a 32 bit che specifica la dimensione totale di questo oggetto, in byte |
| [getVersion()](#getVersion--) | Ottiene o imposta un intero senza segno a 32 bit che specifica il livello del linguaggio PostScript. |
| [setVersion(int value)](#setVersion-int-) | Ottiene o imposta un intero senza segno a 32 bit che specifica il livello del linguaggio PostScript. |
| [getPoints()](#getPoints--) | Ottiene o imposta un array di tre oggetti Point28\_4 (sezione 2.2.23) che definisce le coordinate del parallelogramma di output usando la notazione FIX a 28,4 bit |
| [setPoints(EmfPoint28To4[] value)](#setPoints-com.aspose.imaging.fileformats.emf.emf.objects.EmfPoint28To4---) | Ottiene o imposta un array di tre oggetti Point28\_4 (sezione 2.2.23) che definisce le coordinate del parallelogramma di output usando la notazione FIX a 28,4 bit |
| [getPostScriptData()](#getPostScriptData--) | Ottiene o imposta un array di byte dei dati PostScript. |
| [setPostScriptData(byte[] value)](#setPostScriptData-byte---) | Ottiene o imposta un array di byte dei dati PostScript. |
### EmfEpsData() {#EmfEpsData--}
```
public EmfEpsData()
```


### getSizeData() {#getSizeData--}
```
public int getSizeData()
```


Ottiene o imposta un intero senza segno a 32 bit che specifica la dimensione totale di questo oggetto, in byte

**Returns:**
int
### setSizeData(int value) {#setSizeData-int-}
```
public void setSizeData(int value)
```


Ottiene o imposta un intero senza segno a 32 bit che specifica la dimensione totale di questo oggetto, in byte

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getVersion() {#getVersion--}
```
public int getVersion()
```


Ottiene o imposta un intero senza segno a 32 bit che specifica il livello del linguaggio PostScript. Questo valore DEVE essere 0x00000001

**Returns:**
int
### setVersion(int value) {#setVersion-int-}
```
public void setVersion(int value)
```


Ottiene o imposta un intero senza segno a 32 bit che specifica il livello del linguaggio PostScript. Questo valore DEVE essere 0x00000001

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getPoints() {#getPoints--}
```
public EmfPoint28To4[] getPoints()
```


Ottiene o imposta un array di tre oggetti Point28\_4 (sezione 2.2.23) che definisce le coordinate del parallelogramma di output usando la notazione FIX a 28,4 bit

L'angolo in alto a sinistra del parallelogramma è il primo punto di questo array, l'angolo in alto a destra è il secondo punto, e l'angolo in basso a sinistra è il terzo punto. L'angolo in basso a destra del parallelogramma è calcolato dai primi tre punti (A, B e C) trattandoli come vettori.

**Returns:**
com.aspose.imaging.fileformats.emf.emf.objects.EmfPoint28To4[]
### setPoints(EmfPoint28To4[] value) {#setPoints-com.aspose.imaging.fileformats.emf.emf.objects.EmfPoint28To4---}
```
public void setPoints(EmfPoint28To4[] value)
```


Ottiene o imposta un array di tre oggetti Point28\_4 (sezione 2.2.23) che definisce le coordinate del parallelogramma di output usando la notazione FIX a 28,4 bit

L'angolo in alto a sinistra del parallelogramma è il primo punto di questo array, l'angolo in alto a destra è il secondo punto, e l'angolo in basso a sinistra è il terzo punto. L'angolo in basso a destra del parallelogramma è calcolato dai primi tre punti (A, B e C) trattandoli come vettori.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [EmfPoint28To4\[\]](../../com.aspose.imaging.fileformats.emf.emf.objects/emfpoint28to4) |  |

### getPostScriptData() {#getPostScriptData--}
```
public byte[] getPostScriptData()
```


Ottiene o imposta un array di byte dei dati PostScript. La lunghezza di questo array può essere calcolata dal campo SizeData. Questi dati POSSONO essere usati per renderizzare un'immagine.

**Returns:**
byte[]
### setPostScriptData(byte[] value) {#setPostScriptData-byte---}
```
public void setPostScriptData(byte[] value)
```


Ottiene o imposta un array di byte dei dati PostScript. La lunghezza di questo array può essere calcolata dal campo SizeData. Questi dati POSSONO essere usati per renderizzare un'immagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte[] |  |

