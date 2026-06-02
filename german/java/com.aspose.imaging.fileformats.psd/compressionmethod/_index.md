---
title: "CompressionMethod"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Definiert die Komprimierungsmethode, die für Bilddaten verwendet wird."
type: docs
weight: 11
url: /de/java/com.aspose.imaging.fileformats.psd/compressionmethod/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class CompressionMethod extends System.Enum
```

Definiert die Komprimierungsmethode, die für Bilddaten verwendet wird.
## Felder

| Feld | Beschreibung |
| --- | --- |
| [Raw](#Raw) | Keine Kompression. |
| [RLE](#RLE) | RLE‑komprimierte Bilddaten beginnen mit den Byte‑Zählern für alle Scan‑Zeilen (Zeilen \* Kanäle), wobei jeder Zähler als zweibytes Wert gespeichert wird. |
| [ZipWithoutPrediction](#ZipWithoutPrediction) | ZIP ohne Prädiktion. |
| [ZipWithPrediction](#ZipWithPrediction) | ZIP mit Prädiktion. |
### Raw {#Raw}
```
public static final short Raw
```


Keine Kompression. Die Bilddaten werden als Rohbytes in RGBA‑planarer Reihenfolge gespeichert. Das bedeutet, dass zuerst alle R‑Daten geschrieben werden, dann alle G‑Daten, anschließend alle B‑Daten und zuletzt alle A‑Daten.

### RLE {#RLE}
```
public static final short RLE
```


RLE‑komprimierte Bilddaten beginnen mit den Byte‑Zählern für alle Scan‑Zeilen (Zeilen \* Kanäle), wobei jeder Zähler als zweibytes Wert gespeichert wird. Danach folgen die RLE‑komprimierten Daten, wobei jede Scan‑Zeile separat komprimiert wird. Die RLE‑Kompression ist derselbe Kompressionsalgorithmus, der von der Macintosh‑ROM‑Routine PackBits und dem TIFF‑Standard verwendet wird.

### ZipWithoutPrediction {#ZipWithoutPrediction}
```
public static final short ZipWithoutPrediction
```


ZIP ohne Prädiktion.

### ZipWithPrediction {#ZipWithPrediction}
```
public static final short ZipWithPrediction
```


ZIP mit Prädiktion.

