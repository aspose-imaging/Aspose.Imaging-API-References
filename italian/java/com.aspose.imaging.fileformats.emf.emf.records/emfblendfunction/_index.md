---
title: "EmfBlendFunction"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Una struttura che specifica le operazioni di fusione per i bitmap sorgente e di destinazione."
type: docs
weight: 18
url: /it/java/com.aspose.imaging.fileformats.emf.emf.records/emfblendfunction/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class EmfBlendFunction extends Struct<EmfBlendFunction>
```

Una struttura che specifica le operazioni di fusione per i bitmap sorgente e di destinazione.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfBlendFunction()](#EmfBlendFunction--) |  |
| [EmfBlendFunction(int dwordData)](#EmfBlendFunction-int-) | Inizializza una nuova istanza della classe `EmfBlendFunction`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getBlendOperation()](#getBlendOperation--) | Ottiene il codice dell'operazione di fusione. |
| [getBlendFlags()](#getBlendFlags--) | Ottiene i flag di fusione. |
| [getSrcConstantAlpha()](#getSrcConstantAlpha--) | Ottiene un intero senza segno a 8 bit che specifica la trasparenza alfa, la quale determina la fusione delle bitmap di origine e destinazione. |
| [getAlphaFormat()](#getAlphaFormat--) | Ottiene una struttura che specifica come i pixel di origine e destinazione sono interpretati rispetto alla trasparenza alfa. |
| [toInt()](#toInt--) | Converte la rappresentazione stringa di un numero in un intero. |
| [CloneTo(EmfBlendFunction that)](#CloneTo-com.aspose.imaging.fileformats.emf.emf.records.EmfBlendFunction-) |  |
| [Clone()](#Clone--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [hashCode()](#hashCode--) |  |
| [isEquals(EmfBlendFunction obj1, EmfBlendFunction obj2)](#isEquals-com.aspose.imaging.fileformats.emf.emf.records.EmfBlendFunction-com.aspose.imaging.fileformats.emf.emf.records.EmfBlendFunction-) |  |
### EmfBlendFunction() {#EmfBlendFunction--}
```
public EmfBlendFunction()
```


### EmfBlendFunction(int dwordData) {#EmfBlendFunction-int-}
```
public EmfBlendFunction(int dwordData)
```


Inizializza una nuova istanza della classe `EmfBlendFunction`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dwordData | int | I dati dword. |

### getBlendOperation() {#getBlendOperation--}
```
public byte getBlendOperation()
```


Ottiene il codice dell'operazione di fusione. L'unica operazione di fusione di origine e destinazione definita è 0x00, che specifica che la bitmap di origine DEVE essere combinata con la bitmap di destinazione in base ai valori di trasparenza alfa dei pixel di origine. Vedere le seguenti equazioni per i dettagli.

**Returns:**
byte
### getBlendFlags() {#getBlendFlags--}
```
public byte getBlendFlags()
```


Ottiene i flag di fusione. Questo valore DEVE essere 0x00 e DEVE essere ignorato.

**Returns:**
byte
### getSrcConstantAlpha() {#getSrcConstantAlpha--}
```
public byte getSrcConstantAlpha()
```


Ottiene un intero senza segno a 8 bit che specifica la trasparenza alfa, la quale determina la fusione delle bitmap di origine e destinazione. Questo valore DEVE essere utilizzato sull'intera bitmap di origine. Il valore minimo di trasparenza alfa, zero, corrisponde a completamente trasparente; il valore massimo, 0xFF, corrisponde a completamente opaco. In pratica, un valore di 0xFF specifica che i valori alfa per pixel determinano la fusione delle bitmap di origine e destinazione. Vedere le equazioni più avanti in questa sezione per i dettagli.

**Returns:**
byte
### getAlphaFormat() {#getAlphaFormat--}
```
public byte getAlphaFormat()
```


Ottiene una struttura che specifica come i pixel di origine e destinazione sono interpretati rispetto alla trasparenza alfa.

**Returns:**
byte
### toInt() {#toInt--}
```
public int toInt()
```


Converte la rappresentazione stringa di un numero in un intero.

**Returns:**
int - Il valore DWORD della struttura.
### CloneTo(EmfBlendFunction that) {#CloneTo-com.aspose.imaging.fileformats.emf.emf.records.EmfBlendFunction-}
```
public void CloneTo(EmfBlendFunction that)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| that | [EmfBlendFunction](../../com.aspose.imaging.fileformats.emf.emf.records/emfblendfunction) |  |

### Clone() {#Clone--}
```
public EmfBlendFunction Clone()
```




**Returns:**
[EmfBlendFunction](../../com.aspose.imaging.fileformats.emf.emf.records/emfblendfunction)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int
### isEquals(EmfBlendFunction obj1, EmfBlendFunction obj2) {#isEquals-com.aspose.imaging.fileformats.emf.emf.records.EmfBlendFunction-com.aspose.imaging.fileformats.emf.emf.records.EmfBlendFunction-}
```
public static boolean isEquals(EmfBlendFunction obj1, EmfBlendFunction obj2)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj1 | [EmfBlendFunction](../../com.aspose.imaging.fileformats.emf.emf.records/emfblendfunction) |  |
| obj2 | [EmfBlendFunction](../../com.aspose.imaging.fileformats.emf.emf.records/emfblendfunction) |  |

**Returns:**
boolean
