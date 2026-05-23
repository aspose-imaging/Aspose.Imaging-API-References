---
title: "EmfBlendFunction Klasse"
type: docs
weight: 90
url: /de/python-net/aspose.imaging.fileformats.emf.emf.records/emfblendfunction/
---

**Summary:** A structure that specifies the blending operations for source and destination bitmaps.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfBlendFunction

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [EmfBlendFunction()](#EmfBlendFunction__1) | Initialisiert eine neue Instanz der EmfBlendFunction Klasse |
| [EmfBlendFunction(dword_data)](#EmfBlendFunction_dword_data_2) | Initialisiert eine neue Instanz der [EmfBlendFunction](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfblendfunction/) Klasse |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| alpha_format | [EmfBlendFunction+AlphaFormatEnum](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfblendfunction+alphaformatenum/) | r | Ruft eine Struktur ab, die angibt, wie Quell‑ und Zielpixel <br/>            in Bezug auf Alpha‑Transparenz interpretiert werden. |
| blend_flags | System.Byte | r | Liest die Blend-Flags.<br/>            Dieser Wert MUSS 0x00 sein und MUSS ignoriert werden. |
| blend_operation | System.Byte | r | Liest den Blend-Operationscode. <br/>            Die einzige definierte Quell- und Ziel-<br/>            Blend-Operation ist 0x00, die festlegt, dass das Quell-Bitmap <br/>            MIT dem Ziel-Bitmap basierend auf den Alpha-Transparenzwerten <br/>            der Quellpixel KOMBINIERT werden MUSS. Siehe die folgenden Gleichungen für Details. |
| src_constant_alpha | System.Byte | r | Liest einen 8‑Bit vorzeichenlosen Integer, der die Alpha‑Transparenz angibt, <br/>            der die Mischung des Quell‑ und Ziel‑Bitmaps bestimmt. Dieser Wert MUSS <br/>            auf das gesamte Quell‑Bitmap angewendet werden. Der minimale Alpha‑Transparenzwert, Null, <br/>            entspricht vollständig transparent, der maximale Wert, 0xFF, entspricht <br/>            vollständig undurchsichtig. Effektiv gibt ein Wert von 0xFF an, dass die pro‑Pixel‑Alpha‑Werte <br/>            die Mischung des Quell‑ und Ziel‑Bitmaps bestimmen. Siehe die Gleichungen später in <br/>            diesem Abschnitt für Details. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [to_int()](#to_int__1) | Konvertiert die Zeichenkettenrepräsentation einer Zahl in einen Integer. |


### Constructor: EmfBlendFunction() {#EmfBlendFunction__1}


```
 EmfBlendFunction() 
```

Initialisiert eine neue Instanz der EmfBlendFunction Klasse

### Constructor: EmfBlendFunction(dword_data) {#EmfBlendFunction_dword_data_2}


```
 EmfBlendFunction(dword_data) 
```

Initialisiert eine neue Instanz der [EmfBlendFunction](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfblendfunction/) Klasse

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| dword_data | int | Die DWORD-Daten. |

### Method: to_int() {#to_int__1}


```
 to_int() 
```

Konvertiert die Zeichenkettenrepräsentation einer Zahl in einen Integer.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int | Der DWORD-Wert der Struktur. |


