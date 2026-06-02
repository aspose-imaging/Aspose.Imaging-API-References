---
title: "EmfPlusSetTsClip"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der EmfPlusSetTSClip-Datensatz gibt Clipping‑Bereiche im Grafikgerätekontext für einen Terminalserver an."
type: docs
weight: 66
url: /de/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplussettsclip/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusTerminalServerRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusterminalserverrecordtype)
```
public final class EmfPlusSetTsClip extends EmfPlusTerminalServerRecordType
```

Der EmfPlusSetTSClip-Datensatz gibt Clipping‑Bereiche im Grafikgerätekontext für einen Terminalserver an.

Das Komprimierungsschema für Daten in diesem Datensatz verwendet den folgenden Algorithmus. Jeder Punkt jedes Rechtecks wird entweder in einem einzelnen Byte oder in 2 Bytes kodiert. Wird der Punkt in einem einzelnen Byte kodiert, muss das höchstwertige Bit (0x80) des Bytes gesetzt sein, und der Wert ist eine vorzeichenbehaftete Zahl, die durch die unteren 7 Bits dargestellt wird. Ist das höchstwertige Bit nicht gesetzt, wird der Wert in 2 Bytes kodiert, wobei das höherwertige Byte in den 7 unteren Bits des ersten Bytes kodiert wird und das niederwertige Byte im zweiten Byte. Jeder Punkt wird als Differenz zwischen dem Punkt im aktuellen Rechteck und dem Punkt im vorherigen Rechteck kodiert. Der untere Punkt des Rechtecks wird als Differenz zwischen der unteren Koordinate und der oberen Koordinate im aktuellen Rechteck kodiert.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfPlusSetTsClip(EmfPlusRecord source)](#EmfPlusSetTsClip-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initialisiert eine neue Instanz der Klasse `EmfPlusSetTsClip`. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getCompressed()](#getCompressed--) | Ruft einen Wert ab, der angibt, ob dieses `EmfPlusSetTsClip` komprimiert ist. |
| [getNumRects()](#getNumRects--) | Liefert die Anzahl der Rechtecke. |
| [getRects()](#getRects--) | Liest oder setzt ein Array von NumRects‑Rechtecken, die Clipping‑Bereiche definieren. |
| [setRects(Rectangle[] value)](#setRects-com.aspose.imaging.Rectangle---) | Liest oder setzt ein Array von NumRects‑Rechtecken, die Clipping‑Bereiche definieren. |
### EmfPlusSetTsClip(EmfPlusRecord source) {#EmfPlusSetTsClip-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusSetTsClip(EmfPlusRecord source)
```


Initialisiert eine neue Instanz der Klasse `EmfPlusSetTsClip`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Die Quelle. |

### getCompressed() {#getCompressed--}
```
public boolean getCompressed()
```


Liefert einen Wert, der angibt, ob dieses `EmfPlusSetTsClip` komprimiert ist. Dieses Bit gibt das Format der Rechteckdaten im Feld rects an. Ist das Bit gesetzt, wird jedes Rechteck in 4 Byte definiert. Ist das Bit gelöscht, wird jedes Rechteck in 8 Byte definiert.

Wert: `true`, wenn komprimiert; andernfalls `false`.

**Returns:**
boolean
### getNumRects() {#getNumRects--}
```
public short getNumRects()
```


Liefert die Anzahl der Rechtecke. Dieses Feld gibt die Anzahl der im Feld rect definierten Rechtecke an.

Wert: Die Anzahl der Rechtecke.

**Returns:**
short
### getRects() {#getRects--}
```
public Rectangle[] getRects()
```


Liest oder setzt ein Array von NumRects‑Rechtecken, die Clipping‑Bereiche definieren. Das Format dieser Daten wird durch das C‑Bit im Flags‑Feld bestimmt.

Wert: Die Rechtecke.

**Returns:**
com.aspose.imaging.Rectangle[]
### setRects(Rectangle[] value) {#setRects-com.aspose.imaging.Rectangle---}
```
public void setRects(Rectangle[] value)
```


Liest oder setzt ein Array von NumRects‑Rechtecken, die Clipping‑Bereiche definieren. Das Format dieser Daten wird durch das C‑Bit im Flags‑Feld bestimmt.

Wert: Die Rechtecke.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Rectangle\[\]](../../com.aspose.imaging/rectangle) |  |

