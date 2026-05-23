---
title: "WmfCompression Aufzählung"
type: docs
weight: 70
url: /de/python-net/aspose.imaging.fileformats.wmf.consts/wmfcompression/
---

Die Compression‑Enumeration gibt den Kompressionstyp für ein Bitmap‑Bild an.

**Module:** [aspose.imaging.fileformats.wmf.consts](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/)

**Full Name:** aspose.imaging.fileformats.wmf.consts.WmfCompression

## **Members**
| **Member name** | **Beschreibung** |
| :- | :- |
| BI_BITFIELDS | Die Bitmap ist nicht komprimiert und die Farbpalette besteht aus drei DWORD-Farbmasken, die<br/>                jeweils die Rot-, Grün- und Blaukomponenten jedes Pixels angeben.<br/>                Dies ist gültig, wenn es mit 16‑ und 32‑Bit‑pro‑Pixel‑Bitmaps verwendet wird. |
| BI_CMYK | Das Bild ist in einem unkomprimierten CMYK‑Format. |
| BI_CMYKRLE4 | Ein CMYK‑Format, das RLE‑Kompression für Bitmaps mit 4 Bit pro Pixel verwendet.<br/>                Die Kompression nutzt ein 2‑Byte‑Format, das aus einem Zähler‑Byte gefolgt von zwei wortlangen Farb‑Indizes besteht. |
| BI_CMYKRLE8 | Ein CMYK‑Format, das RLE‑Kompression für Bitmaps mit 8 Bit pro Pixel verwendet.<br/>                Die Kompression nutzt ein 2‑Byte‑Format, das aus einem Zähler‑Byte gefolgt von einem Byte mit einem Farb‑Index besteht. |
| BI_JPEG | Das Bild ist ein JPEG‑Bild, wie in [JFIF] angegeben. Dieser Wert SOLLTE nur in bestimmten Bitmap‑<br/>                Vorgängen verwendet werden, wie z. B. JPEG‑Durchleitung. Die Anwendung MUSS die Unterstützung für die Durchleitung abfragen,<br/>                da nicht alle Geräte JPEG‑Durchleitung unterstützen. Die Verwendung von Nicht‑RGB‑Bitmaps KANN die Portabilität<br/>                der Metadatei zu anderen Geräten einschränken. Beispielsweise unterstützen Anzeige‑Geräte‑Kontexte diese Durchleitung in der Regel nicht. |
| BI_PNG | Das Bild ist ein PNG‑Bild, wie in [RFC2083] angegeben. Dieser Wert SOLLTE nur in bestimmten Bitmap‑<br/>                Vorgängen verwendet werden, wie z. B. JPEG/PNG‑Durchleitung. Die Anwendung MUSS die Unterstützung für die Durchleitung abfragen, weil nicht alle Geräte<br/>                JPEG/PNG‑Durchleitung unterstützen. Die Verwendung von Nicht‑RGB‑Bitmaps KANN die Portabilität der Metadatei zu anderen Geräten einschränken.<br/>                Beispielsweise unterstützen Anzeige‑Geräte‑Kontexte diese Durchleitung in der Regel nicht. |
| BI_RGB | Das Bitmap befindet sich im unkomprimierten Rot-Grün-Blau (RGB)-Format, das nicht komprimiert ist und keine Farbmasken verwendet. |
| BI_RLE4 | Ein RGB-Format, das RLE-Kompression für Bitmaps mit 4 Bit pro Pixel verwendet.<br/>                Die Kompression verwendet ein 2-Byte-Format, das aus einem Zählerbyte gefolgt von zwei wortlangen Farbindizes besteht. |
| BI_RLE8 | Ein RGB-Format, das Run-Length-Encoding (RLE)-Kompression für Bitmaps mit 8 Bit pro Pixel verwendet.<br/>                Die Kompression verwendet ein 2-Byte-Format, das aus einem Zählerbyte gefolgt von einem Byte besteht, das einen Farbindex enthält. |
