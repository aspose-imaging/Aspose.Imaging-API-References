---
title: EmfVertexData
second_title: Aspose.Imaging für .NET-API-Referenz
description: Objekte die die Scheitelpunkte von Rechtecken oder Dreiecken und die ihnen entsprechenden Farben angeben.
type: docs
weight: 4650
url: /de/net/aspose.imaging.fileformats.emf.emf.records/emfvertexdata/
---
## EmfVertexData class

Objekte, die die Scheitelpunkte von Rechtecken oder Dreiecken und die ihnen entsprechenden Farben angeben.

```csharp
public sealed class EmfVertexData
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [EmfVertexData](emfvertexdata)() | Default_Constructor |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [VertexIndexes](../../aspose.imaging.fileformats.emf.emf.records/emfvertexdata/vertexindexes) { get; set; } | Ruft ein Array von nTri GradientRectangle-Objekten (Abschnitt 2.2.7) oder GradientTriangle-Objekten (Abschnitt 2.2.8) ab oder legt es fest, abhängig vom Wert des ulMode-Felds. Jedes Objekt gibt Indizes für das Array von TriVertex-Objekten im Feld VertexObjects an. |
| [VertexObjects](../../aspose.imaging.fileformats.emf.emf.records/emfvertexdata/vertexobjects) { get; set; } | Holt oder setzt ein Array von nVer TriVertex-Objekten (Abschnitt 2.2.26). Jedes -Objekt gibt die Position und Farbe eines Scheitelpunkts entweder eines Rechtecks oder eines Dreiecks an, abhängig vom Wert des ulMode-Felds. |
| [VertexPadding](../../aspose.imaging.fileformats.emf.emf.records/emfvertexdata/vertexpadding) { get; set; } | Ruft ein optionales Array variabler Länge von nTri mal vier Bytes ab oder legt es fest, das vorhanden sein MUSS, wenn der Wert des ulMode-Felds GradientRectangle -Objekte angibt (Abschnitt 2.2.7). Wenn der Wert des ulMode-Felds GradientTriangle -Objekte anzeigt (Abschnitt 2.2.8), ist kein VertexPadding vorhanden. Dieses Feld MUSS ignoriert werden. |

### Siehe auch

* namensraum [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* Montage [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->