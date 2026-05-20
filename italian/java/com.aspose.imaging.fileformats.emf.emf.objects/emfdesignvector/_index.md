---
title: "EmfDesignVector"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "L'oggetto DesignVector della sezione 2.2.3 definisce il vettore di design che specifica i valori per gli assi del font di un font multiple master."
type: docs
weight: 13
url: /it/java/com.aspose.imaging.fileformats.emf.emf.objects/emfdesignvector/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public final class EmfDesignVector extends EmfObject
```

L'oggetto DesignVector (sezione 2.2.3) definisce il vettore di design, che specifica i valori per gli assi del carattere di un font master multiplo.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfDesignVector()](#EmfDesignVector--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getSignature()](#getSignature--) | Ottiene o imposta un intero senza segno a 32 bit che DEVE essere impostato al valore 0x08007664. |
| [setSignature(int value)](#setSignature-int-) | Ottiene o imposta un intero senza segno a 32 bit che DEVE essere impostato al valore 0x08007664. |
| [getNumAxes()](#getNumAxes--) | Ottiene o imposta un intero senza segno a 32 bit che specifica il numero di elementi nell'array Values. |
| [setNumAxes(int value)](#setNumAxes-int-) | Ottiene o imposta un intero senza segno a 32 bit che specifica il numero di elementi nell'array Values. |
| [getValues()](#getValues--) | Ottiene o imposta un array opzionale di interi con segno a 32 bit che specificano i valori degli assi del font di un font multiple master OpenType. |
| [setValues(int[] value)](#setValues-int---) | Ottiene o imposta un array opzionale di interi con segno a 32 bit che specificano i valori degli assi del font di un font multiple master OpenType. |
### EmfDesignVector() {#EmfDesignVector--}
```
public EmfDesignVector()
```


### getSignature() {#getSignature--}
```
public int getSignature()
```


Ottiene o imposta un intero senza segno a 32 bit che DEVE essere impostato al valore 0x08007664.

**Returns:**
int
### setSignature(int value) {#setSignature-int-}
```
public void setSignature(int value)
```


Ottiene o imposta un intero senza segno a 32 bit che DEVE essere impostato al valore 0x08007664.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getNumAxes() {#getNumAxes--}
```
public int getNumAxes()
```


Ottiene o imposta un intero senza segno a 32 bit che specifica il numero di elementi nell'array Values. Deve trovarsi nell'intervallo da 0 a 16, inclusi.

**Returns:**
int
### setNumAxes(int value) {#setNumAxes-int-}
```
public void setNumAxes(int value)
```


Ottiene o imposta un intero senza segno a 32 bit che specifica il numero di elementi nell'array Values. Deve trovarsi nell'intervallo da 0 a 16, inclusi.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getValues() {#getValues--}
```
public int[] getValues()
```


Ottiene o imposta un array opzionale di interi con segno a 32 bit che specificano i valori degli assi del font di un font multiple master OpenType. Il numero massimo di valori nell'array è 16.

**Returns:**
int[]
### setValues(int[] value) {#setValues-int---}
```
public void setValues(int[] value)
```


Ottiene o imposta un array opzionale di interi con segno a 32 bit che specificano i valori degli assi del font di un font multiple master OpenType. Il numero massimo di valori nell'array è 16.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int[] |  |

