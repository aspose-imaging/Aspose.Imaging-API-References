---
title: "EmfVertexData"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Oggetti che specificano i vertici di rettangoli o triangoli e i colori corrispondenti."
type: docs
weight: 155
url: /it/java/com.aspose.imaging.fileformats.emf.emf.records/emfvertexdata/
---
**Inheritance:**
java.lang.Object
```
public final class EmfVertexData
```

Oggetti che specificano i vertici di rettangoli o triangoli e i colori corrispondenti.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfVertexData()](#EmfVertexData--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getVertexObjects()](#getVertexObjects--) | Ottiene o imposta un array di oggetti nVer TriVertex (sezione 2.2.26). |
| [setVertexObjects(EmfTriVertex[] value)](#setVertexObjects-com.aspose.imaging.fileformats.emf.emf.objects.EmfTriVertex---) | Ottiene o imposta un array di oggetti nVer TriVertex (sezione 2.2.26). |
| [getVertexIndexes()](#getVertexIndexes--) | Ottiene o imposta un array di oggetti nTri GradientRectangle (sezione 2.2.7) o oggetti GradientTriangle (sezione 2.2.8), a seconda del valore del campo ulMode. |
| [setVertexIndexes(EmfGradientRectangle[] value)](#setVertexIndexes-com.aspose.imaging.fileformats.emf.emf.objects.EmfGradientRectangle---) | Ottiene o imposta un array di oggetti nTri GradientRectangle (sezione 2.2.7) o oggetti GradientTriangle (sezione 2.2.8), a seconda del valore del campo ulMode. |
| [getVertexPadding()](#getVertexPadding--) | Ottiene o imposta un array opzionale a lunghezza variabile di nTri per quattro byte che DEVE essere presente se il valore del campo ulMode indica oggetti GradientRectangle (sezione 2.2.7). |
| [setVertexPadding(byte[] value)](#setVertexPadding-byte---) | Ottiene o imposta un array opzionale a lunghezza variabile di nTri per quattro byte che DEVE essere presente se il valore del campo ulMode indica oggetti GradientRectangle (sezione 2.2.7). |
### EmfVertexData() {#EmfVertexData--}
```
public EmfVertexData()
```


### getVertexObjects() {#getVertexObjects--}
```
public EmfTriVertex[] getVertexObjects()
```


Ottiene o imposta un array di oggetti nVer TriVertex (sezione 2.2.26). Ogni oggetto specifica la posizione e il colore di un vertice di un rettangolo o di un triangolo, a seconda del valore del campo ulMode.

**Returns:**
com.aspose.imaging.fileformats.emf.emf.objects.EmfTriVertex[]
### setVertexObjects(EmfTriVertex[] value) {#setVertexObjects-com.aspose.imaging.fileformats.emf.emf.objects.EmfTriVertex---}
```
public void setVertexObjects(EmfTriVertex[] value)
```


Ottiene o imposta un array di oggetti nVer TriVertex (sezione 2.2.26). Ogni oggetto specifica la posizione e il colore di un vertice di un rettangolo o di un triangolo, a seconda del valore del campo ulMode.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [EmfTriVertex\[\]](../../com.aspose.imaging.fileformats.emf.emf.objects/emftrivertex) |  |

### getVertexIndexes() {#getVertexIndexes--}
```
public EmfGradientRectangle[] getVertexIndexes()
```


Ottiene o imposta un array di oggetti nTri GradientRectangle (sezione 2.2.7) o oggetti GradientTriangle (sezione 2.2.8), a seconda del valore del campo ulMode. Ogni oggetto specifica gli indici nell'array di oggetti TriVertex nel campo VertexObjects.

**Returns:**
com.aspose.imaging.fileformats.emf.emf.objects.EmfGradientRectangle[]
### setVertexIndexes(EmfGradientRectangle[] value) {#setVertexIndexes-com.aspose.imaging.fileformats.emf.emf.objects.EmfGradientRectangle---}
```
public void setVertexIndexes(EmfGradientRectangle[] value)
```


Ottiene o imposta un array di oggetti nTri GradientRectangle (sezione 2.2.7) o oggetti GradientTriangle (sezione 2.2.8), a seconda del valore del campo ulMode. Ogni oggetto specifica gli indici nell'array di oggetti TriVertex nel campo VertexObjects.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [EmfGradientRectangle\[\]](../../com.aspose.imaging.fileformats.emf.emf.objects/emfgradientrectangle) |  |

### getVertexPadding() {#getVertexPadding--}
```
public byte[] getVertexPadding()
```


Ottiene o imposta un array opzionale a lunghezza variabile di nTri per quattro byte che DEVE essere presente se il valore del campo ulMode indica oggetti GradientRectangle (sezione 2.2.7). Se il valore del campo ulMode indica oggetti GradientTriangle (sezione 2.2.8), non è presente VertexPadding. Questo campo DEVE essere ignorato.

**Returns:**
byte[]
### setVertexPadding(byte[] value) {#setVertexPadding-byte---}
```
public void setVertexPadding(byte[] value)
```


Ottiene o imposta un array opzionale a lunghezza variabile di nTri per quattro byte che DEVE essere presente se il valore del campo ulMode indica oggetti GradientRectangle (sezione 2.2.7). Se il valore del campo ulMode indica oggetti GradientTriangle (sezione 2.2.8), non è presente VertexPadding. Questo campo DEVE essere ignorato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte[] |  |

