---
title: "EmfBlendFunction"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Eine Struktur, die die Mischoperationen für Quell- und Ziel-Bitmaps angibt."
type: docs
weight: 18
url: /de/java/com.aspose.imaging.fileformats.emf.emf.records/emfblendfunction/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class EmfBlendFunction extends Struct<EmfBlendFunction>
```

Eine Struktur, die die Mischoperationen für Quell- und Ziel-Bitmaps angibt.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfBlendFunction()](#EmfBlendFunction--) |  |
| [EmfBlendFunction(int dwordData)](#EmfBlendFunction-int-) | Initialisiert eine neue Instanz der `EmfBlendFunction`-Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getBlendOperation()](#getBlendOperation--) | Liest den Blend-Operationscode. |
| [getBlendFlags()](#getBlendFlags--) | Liest die Blend-Flags. |
| [getSrcConstantAlpha()](#getSrcConstantAlpha--) | Liest eine 8‑Bit‑vorzeichenlose Ganzzahl, die die Alpha‑Transparenz angibt, welche die Mischung der Quell‑ und Ziel‑Bitmaps bestimmt. |
| [getAlphaFormat()](#getAlphaFormat--) | Liest eine Struktur, die angibt, wie Quell‑ und Zielpixel in Bezug auf die Alpha‑Transparenz interpretiert werden. |
| [toInt()](#toInt--) | Konvertiert die Zeichenkettenrepräsentation einer Zahl in eine Ganzzahl. |
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


Initialisiert eine neue Instanz der `EmfBlendFunction`-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| dwordData | int | Die dword‑Daten. |

### getBlendOperation() {#getBlendOperation--}
```
public byte getBlendOperation()
```


Liest den Blend-Operationscode. Die einzige definierte Quell‑ und Ziel‑Blend‑Operation ist 0x00, die angibt, dass die Quell‑Bitmap MIT DER ZIEL‑Bitmap kombiniert werden MUSS, basierend auf den Alpha‑Transparenzwerten der Quellpixel. Siehe die folgenden Gleichungen für Details.

**Returns:**
byte
### getBlendFlags() {#getBlendFlags--}
```
public byte getBlendFlags()
```


Liest die Blend-Flags. Dieser Wert MUSS 0x00 sein und MUSS ignoriert werden.

**Returns:**
byte
### getSrcConstantAlpha() {#getSrcConstantAlpha--}
```
public byte getSrcConstantAlpha()
```


Liest eine 8‑Bit‑vorzeichenlose Ganzzahl, die die Alpha‑Transparenz angibt, welche die Mischung der Quell‑ und Ziel‑Bitmaps bestimmt. Dieser Wert MUSS für die gesamte Quell‑Bitmap verwendet werden. Der minimale Alpha‑Transparenzwert, null, entspricht vollständig transparent, der maximale Wert, 0xFF, entspricht vollständig undurchsichtig. Effektiv gibt ein Wert von 0xFF an, dass die Alpha‑Werte pro Pixel die Mischung der Quell‑ und Ziel‑Bitmaps bestimmen. Siehe die Gleichungen später in diesem Abschnitt für Details.

**Returns:**
byte
### getAlphaFormat() {#getAlphaFormat--}
```
public byte getAlphaFormat()
```


Liest eine Struktur, die angibt, wie Quell‑ und Zielpixel in Bezug auf die Alpha‑Transparenz interpretiert werden.

**Returns:**
byte
### toInt() {#toInt--}
```
public int toInt()
```


Konvertiert die Zeichenkettenrepräsentation einer Zahl in eine Ganzzahl.

**Returns:**
int – Der DWORD‑Wert der Struktur.
### CloneTo(EmfBlendFunction that) {#CloneTo-com.aspose.imaging.fileformats.emf.emf.records.EmfBlendFunction-}
```
public void CloneTo(EmfBlendFunction that)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
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
| Parameter | Typ | Beschreibung |
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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj1 | [EmfBlendFunction](../../com.aspose.imaging.fileformats.emf.emf.records/emfblendfunction) |  |
| obj2 | [EmfBlendFunction](../../com.aspose.imaging.fileformats.emf.emf.records/emfblendfunction) |  |

**Returns:**
boolean
