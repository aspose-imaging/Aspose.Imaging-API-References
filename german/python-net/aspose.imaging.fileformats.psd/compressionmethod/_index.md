---
title: "CompressionMethod Aufzählung"
type: docs
weight: 20
url: /de/python-net/aspose.imaging.fileformats.psd/compressionmethod/
---

Definiert die Komprimierungsmethode, die für Bilddaten verwendet wird.

**Module:** [aspose.imaging.fileformats.psd](/imaging/python-net/aspose.imaging.fileformats.psd/)

**Full Name:** aspose.imaging.fileformats.psd.CompressionMethod

## **Members**
| **Member name** | **Beschreibung** |
| :- | :- |
| RAW | Keine Kompression. Die Bilddaten werden als Rohbytes in RGBA-Planarreihenfolge gespeichert.<br/>            Das bedeutet, dass zuerst alle R-Daten geschrieben werden, dann alle G-Daten, dann alle B- und schließlich alle A-Daten. |
| RLE | Bei RLE-komprimierten Bilddaten beginnt es mit den Byte‑Zählern für alle Scan‑Zeilen (Zeilen * Kanäle), wobei jeder<br/>            Zähler als Zweibyte‑Wert gespeichert wird. Darauf folgen die RLE‑komprimierten Daten, wobei jede Scan‑Zeile separat komprimiert wird.<br/>            Die RLE‑Kompression ist derselbe Kompressionsalgorithmus, der von der Macintosh‑ROM‑Routine PackBits und dem TIFF‑Standard verwendet wird. |
| ZIP_WITHOUT_PREDICTION | ZIP ohne Vorhersage. |
| ZIP_WITH_PREDICTION | ZIP mit Vorhersage. |
