---
title: "EmfRop4"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Eine quartäre Rasteroperation, die ternäre Rasteroperationen für die Vorder‑ und Hintergrundfarben einer Bitmap festlegt."
type: docs
weight: 110
url: /de/java/com.aspose.imaging.fileformats.emf.emf.records/emfrop4/
---
**Inheritance:**
java.lang.Object
```
public final class EmfRop4
```

Eine quartäre Rasteroperation, die ternäre Rasteroperationen für die Vorder‑ und Hintergrundfarben einer Bitmap festlegt. Diese Werte definieren, wie die Farbdaten des Quellrechtecks mit den Farbdaten des Zielrechtecks kombiniert werden.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfRop4(int dwordData)](#EmfRop4-int-) | Initialisiert eine neue Instanz der `EmfRop4`‑Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getBackgroundRop3()](#getBackgroundRop3--) | Liest den Hintergrund‑ROP3. |
| [getForegroundRop3()](#getForegroundRop3--) | Liest den Vordergrund‑ROP3. |
### EmfRop4(int dwordData) {#EmfRop4-int-}
```
public EmfRop4(int dwordData)
```


Initialisiert eine neue Instanz der `EmfRop4`‑Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| dwordData | int | Die dword‑Daten. |

### getBackgroundRop3() {#getBackgroundRop3--}
```
public byte getBackgroundRop3()
```


Liest den Hintergrund‑ROP3. Die vorzeichenlosen, höchstwertigen 8 Bits eines 24‑Bit‑ternären Rasteroperationswertes aus der WMF‑Ternary‑Raster‑Operation‑Aufzählung ([MS-WMF] Abschnitt 2.1.1.31). Dieser Code definiert, wie die Hintergrundfarbdaten der Quell‑ und Ziel‑Bitmaps sowie des Pinselmusterns kombiniert werden.

Wert: Der Hintergrund‑ROP3.

**Returns:**
byte
### getForegroundRop3() {#getForegroundRop3--}
```
public byte getForegroundRop3()
```


Liest den Vordergrund‑ROP3. Die vorzeichenlosen, höchstwertigen 8 Bits eines 24‑Bit‑ternären Rasteroperationswertes aus der WMF‑Ternary‑Raster‑Operation‑Aufzählung. Dieser Code definiert, wie die Vordergrundfarbdaten der Quell‑ und Ziel‑Bitmaps sowie des Pinselmusterns kombiniert werden.

Wert: Der Vordergrund‑ROP3.

**Returns:**
byte
