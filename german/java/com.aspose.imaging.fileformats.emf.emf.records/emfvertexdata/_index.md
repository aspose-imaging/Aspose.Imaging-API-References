---
title: "EmfVertexData"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Objekte, die die Eckpunkte von Rechtecken oder Dreiecken sowie die zugehörigen Farben angeben."
type: docs
weight: 155
url: /de/java/com.aspose.imaging.fileformats.emf.emf.records/emfvertexdata/
---
**Inheritance:**
java.lang.Object
```
public final class EmfVertexData
```

Objekte, die die Eckpunkte von Rechtecken oder Dreiecken sowie die zugehörigen Farben angeben.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfVertexData()](#EmfVertexData--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getVertexObjects()](#getVertexObjects--) | Liest oder setzt ein Array von nVer TriVertex-Objekten (Abschnitt 2.2.26). |
| [setVertexObjects(EmfTriVertex[] value)](#setVertexObjects-com.aspose.imaging.fileformats.emf.emf.objects.EmfTriVertex---) | Liest oder setzt ein Array von nVer TriVertex-Objekten (Abschnitt 2.2.26). |
| [getVertexIndexes()](#getVertexIndexes--) | Liest oder setzt ein Array von nTri GradientRectangle-Objekten (Abschnitt 2.2.7) oder GradientTriangle-Objekten (Abschnitt 2.2.8), abhängig vom Wert des ulMode-Feldes. |
| [setVertexIndexes(EmfGradientRectangle[] value)](#setVertexIndexes-com.aspose.imaging.fileformats.emf.emf.objects.EmfGradientRectangle---) | Liest oder setzt ein Array von nTri GradientRectangle-Objekten (Abschnitt 2.2.7) oder GradientTriangle-Objekten (Abschnitt 2.2.8), abhängig vom Wert des ulMode-Feldes. |
| [getVertexPadding()](#getVertexPadding--) | Liest oder setzt ein optionales, variabel langes Array von nTri mal vier Bytes, das VORHANDEN SEIN MUSS, wenn der Wert des ulMode-Feldes GradientRectangle-Objekte (Abschnitt 2.2.7) anzeigt. |
| [setVertexPadding(byte[] value)](#setVertexPadding-byte---) | Liest oder setzt ein optionales, variabel langes Array von nTri mal vier Bytes, das VORHANDEN SEIN MUSS, wenn der Wert des ulMode-Feldes GradientRectangle-Objekte (Abschnitt 2.2.7) anzeigt. |
### EmfVertexData() {#EmfVertexData--}
```
public EmfVertexData()
```


### getVertexObjects() {#getVertexObjects--}
```
public EmfTriVertex[] getVertexObjects()
```


Liest oder setzt ein Array von nVer TriVertex-Objekten (Abschnitt 2.2.26). Jedes Objekt gibt die Position und Farbe eines Scheitelpunkts eines Rechtecks oder Dreiecks an, abhängig vom Wert des ulMode-Feldes.

**Returns:**
com.aspose.imaging.fileformats.emf.emf.objects.EmfTriVertex[]
### setVertexObjects(EmfTriVertex[] value) {#setVertexObjects-com.aspose.imaging.fileformats.emf.emf.objects.EmfTriVertex---}
```
public void setVertexObjects(EmfTriVertex[] value)
```


Liest oder setzt ein Array von nVer TriVertex-Objekten (Abschnitt 2.2.26). Jedes Objekt gibt die Position und Farbe eines Scheitelpunkts eines Rechtecks oder Dreiecks an, abhängig vom Wert des ulMode-Feldes.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [EmfTriVertex\[\]](../../com.aspose.imaging.fileformats.emf.emf.objects/emftrivertex) |  |

### getVertexIndexes() {#getVertexIndexes--}
```
public EmfGradientRectangle[] getVertexIndexes()
```


Liest oder setzt ein Array von nTri GradientRectangle-Objekten (Abschnitt 2.2.7) oder GradientTriangle-Objekten (Abschnitt 2.2.8), abhängig vom Wert des ulMode-Feldes. Jedes Objekt gibt Indizes in das Array von TriVertex-Objekten im Feld VertexObjects an.

**Returns:**
com.aspose.imaging.fileformats.emf.emf.objects.EmfGradientRectangle[]
### setVertexIndexes(EmfGradientRectangle[] value) {#setVertexIndexes-com.aspose.imaging.fileformats.emf.emf.objects.EmfGradientRectangle---}
```
public void setVertexIndexes(EmfGradientRectangle[] value)
```


Liest oder setzt ein Array von nTri GradientRectangle-Objekten (Abschnitt 2.2.7) oder GradientTriangle-Objekten (Abschnitt 2.2.8), abhängig vom Wert des ulMode-Feldes. Jedes Objekt gibt Indizes in das Array von TriVertex-Objekten im Feld VertexObjects an.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [EmfGradientRectangle\[\]](../../com.aspose.imaging.fileformats.emf.emf.objects/emfgradientrectangle) |  |

### getVertexPadding() {#getVertexPadding--}
```
public byte[] getVertexPadding()
```


Liest oder setzt ein optionales, variabel langes Array von nTri mal vier Bytes, das VORHANDEN SEIN MUSS, wenn der Wert des ulMode-Feldes GradientRectangle-Objekte (Abschnitt 2.2.7) anzeigt. Wenn der Wert des ulMode-Feldes GradientTriangle-Objekte (Abschnitt 2.2.8) anzeigt, ist kein VertexPadding vorhanden. Dieses Feld MUSS ignoriert werden.

**Returns:**
byte[]
### setVertexPadding(byte[] value) {#setVertexPadding-byte---}
```
public void setVertexPadding(byte[] value)
```


Liest oder setzt ein optionales, variabel langes Array von nTri mal vier Bytes, das VORHANDEN SEIN MUSS, wenn der Wert des ulMode-Feldes GradientRectangle-Objekte (Abschnitt 2.2.7) anzeigt. Wenn der Wert des ulMode-Feldes GradientTriangle-Objekte (Abschnitt 2.2.8) anzeigt, ist kein VertexPadding vorhanden. Dieses Feld MUSS ignoriert werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte[] |  |

