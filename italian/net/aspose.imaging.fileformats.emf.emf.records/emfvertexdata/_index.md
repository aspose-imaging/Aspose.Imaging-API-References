---
title: EmfVertexData
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Oggetti che specificano i vertici di rettangoli o triangoli e i colori che corrispondono ad essi.
type: docs
weight: 4650
url: /it/net/aspose.imaging.fileformats.emf.emf.records/emfvertexdata/
---
## EmfVertexData class

Oggetti che specificano i vertici di rettangoli o triangoli e i colori che corrispondono ad essi.

```csharp
public sealed class EmfVertexData
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [EmfVertexData](emfvertexdata)() | Default_Costruttore |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [VertexIndexes](../../aspose.imaging.fileformats.emf.emf.records/emfvertexdata/vertexindexes) { get; set; } | Ottiene o imposta una matrice di oggetti nTri GradientRectangle (sezione 2.2.7) o GradientTriangle (sezione 2.2.8), a seconda del valore del campo ulMode. Ogni oggetto specifica gli indici nell'array di oggetti TriVertex nel campo VertexObjects. |
| [VertexObjects](../../aspose.imaging.fileformats.emf.emf.records/emfvertexdata/vertexobjects) { get; set; } | Ottiene o imposta un array di oggetti nVer TriVertex (sezione 2.2.26). Ogni oggetto specifica la posizione e il colore di un vertice di un rettangolo o di un triangolo, a seconda del valore del campo ulMode. |
| [VertexPadding](../../aspose.imaging.fileformats.emf.emf.records/emfvertexdata/vertexpadding) { get; set; } | Ottiene o imposta un array di lunghezza variabile opzionale di nTri per quattro byte che DEVE essere presente se il valore del campo ulMode indica oggetti GradientRectangle (sezione 2.2.7). Se il valore del campo ulMode indica oggetti GradientTriangle (sezione 2.2.8), non è presente alcun VertexPadding. Questo campo DEVE essere ignorato. |

### Guarda anche

* spazio dei nomi [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* assemblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
