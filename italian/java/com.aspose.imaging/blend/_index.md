---
title: "Blend"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Definisce un modello di fusione."
type: docs
weight: 12
url: /it/java/com.aspose.imaging/blend/
---
**Inheritance:**
java.lang.Object
```
public final class Blend
```

Definisce un modello di blend. Questa classe non può essere ereditata.

L'uso tipico della classe blend consiste nel definire un modello di blend per il pennello. Pertanto le proprietà del blend devono essere inizializzate con attenzione. Gli array null non sono consentiti. Il pennello genererà l'eccezione appropriata se gli array di fattori o di posizioni del blend sono vuoti o se la loro lunghezza non è la stessa. Se ci sono due o più elementi nell'array delle posizioni, il primo elemento deve essere 0 e l'ultimo deve essere 1.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Blend()](#Blend--) | Inizializza una nuova istanza della classe `Blend`. |
| [Blend(int count)](#Blend-int-) | Inizializza una nuova istanza della classe `Blend` con il numero specificato di fattori e posizioni. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getFactors()](#getFactors--) | Restituisce l'array dei fattori blend per il gradiente. |
| [setFactors(float[] value)](#setFactors-float---) | Imposta l'array dei fattori blend per il gradiente. |
| [getPositions()](#getPositions--) | Restituisce l'array delle posizioni blend per il gradiente. |
| [setPositions(float[] value)](#setPositions-float---) | Imposta l'array delle posizioni blend per il gradiente. |
| [equals(Object obj)](#equals-java.lang.Object-) | Verifica se l'oggetto specificato è una classe `com.aspose.imaging.Blend` ed è equivalente a questa classe `com.aspose.imaging.Blend`. |
| [hashCode()](#hashCode--) | Restituisce un codice hash per questa istanza. |
### Blend() {#Blend--}
```
public Blend()
```


Inizializza una nuova istanza della classe `Blend`. Il numero di elementi negli array dei fattori e dei blend sarà pari a 1.

### Blend(int count) {#Blend-int-}
```
public Blend(int count)
```


Inizializza una nuova istanza della classe `Blend` con il numero specificato di fattori e posizioni.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| count | int | Il numero di elementi negli array dei fattori e delle posizioni. |

### getFactors() {#getFactors--}
```
public float[] getFactors()
```


Restituisce l'array dei fattori blend per il gradiente.

**Returns:**
float[] - L'array dei fattori di blend che specifica le percentuali del colore iniziale e del colore finale da utilizzare nella posizione corrispondente.
### setFactors(float[] value) {#setFactors-float---}
```
public void setFactors(float[] value)
```


Imposta l'array dei fattori blend per il gradiente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float[] | L'array dei fattori di blend che specifica le percentuali del colore iniziale e del colore finale da utilizzare nella posizione corrispondente. |

### getPositions() {#getPositions--}
```
public float[] getPositions()
```


Restituisce l'array delle posizioni blend per il gradiente.

**Returns:**
float[] - L'array delle posizioni di blend che specifica le percentuali di distanza lungo la linea del gradiente.
### setPositions(float[] value) {#setPositions-float---}
```
public void setPositions(float[] value)
```


Imposta l'array delle posizioni blend per il gradiente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float[] | L'array delle posizioni di blend che specifica le percentuali di distanza lungo la linea del gradiente. |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Verifica se l'oggetto specificato è una classe `com.aspose.imaging.Blend` ed è equivalente a questa classe `com.aspose.imaging.Blend`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | java.lang.Object | L'oggetto da testare. |

**Returns:**
boolean - True se `obj` è una classe `com.aspose.imaging.Blend` equivalente a questa classe `com.aspose.imaging.Blend`; altrimenti, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Restituisce un codice hash per questa istanza.

**Returns:**
int - Un codice hash per questa istanza, adatto per l'uso in algoritmi di hashing e strutture dati come una tabella hash.
