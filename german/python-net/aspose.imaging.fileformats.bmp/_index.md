---
title: "aspose.imaging.fileformats.bmp"
type: docs
weight: 140
url: /de/python-net/aspose.imaging.fileformats.bmp/
---


Das Modul verarbeitet das Bmp-Dateiformat.

## **Classes**
| **Klasse** | **Beschreibung** |
| :- | :- |
| [BitmapCoreHeader](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcoreheader/) | Abmessungen und Farbformat von DIB.<br/>            Header-Name BITMAPCOREHEADER, auch bekannt als OS21XBITMAPHEADER. |
| [BitmapInfoHeader](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapinfoheader/) | Gibt BITMAPINFOHEADER an. <br/>                Betriebssystemunterstützung: Windows NT, 3.1x oder später.<br/>                Funktionen: Fügt 16‑bpp‑ und 32‑bpp‑Formate hinzu. Fügt RLE‑Kompression hinzu. |
| [BitmapV4Header](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapv4header/) | Die BitmapV4Header‑Struktur ist die Bitmap‑Informations‑Headerdatei. Sie ist eine erweiterte Version der BITMAPINFOHEADER‑Struktur.<br/>            <br/>Die BitmapV4Header‑Struktur ist erweitert, um ein JPEG‑ oder PNG‑Bild als Quellbild an StretchDIBits zu übergeben.<br/> |
| [BitmapV5Header](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapv5header/) | Die BitmapV5Header‑Struktur ist die Bitmap‑Informations‑Headerdatei. Sie ist eine erweiterte Version der BITMAPINFOHEADER‑Struktur.<br/>            <br/>Ist bV5Height negativ, was auf ein Top‑Down‑DIB hinweist, muss bV5Compression entweder BI_RGB oder BI_BITFIELDS sein. Top‑Down‑DIBs können nicht komprimiert werden.<br/>            Die Independent Color Management‑Schnittstelle (ICM) 2.0 ermöglicht es, International Color Consortium (ICC)‑Farbprofile mit DIBs (DIBs) zu verknüpfen oder einzubetten. <br/>            Siehe „Using Structures“ für weitere Informationen. Wenn ein DIB in den Speicher geladen wird, sollten die Profildaten (falls vorhanden) der Farbtafel folgen, <br/>            und bV5ProfileData sollte den Offset der Profildaten vom Beginn der BITMAPV5HEADER‑Struktur angeben. <br/>            Der in bV5ProfileData gespeicherte Wert unterscheidet sich vom Wert, der vom sizeof‑Operator für das BITMAPV5HEADER‑Argument zurückgegeben wird, <br/>            weil bV5ProfileData der Offset in Bytes vom Beginn der BITMAPV5HEADER‑Struktur bis zum Beginn der Profildaten ist. <br/>            (Bitmap‑Bits folgen nicht der Farbtafel im Speicher). Anwendungen sollten das bV5ProfileData‑Mitglied nach dem Laden des DIBs in den Speicher ändern.<br/>            Bei gepackten DIBs sollten die Profildaten den Bitmap‑Bits ähnlich dem Dateiformat folgen. <br/>            Das bV5ProfileData‑Mitglied sollte weiterhin den Offset der Profildaten vom Beginn der BITMAPV5HEADER angeben.<br/>            Anwendungen sollten auf die Profildaten nur zugreifen, wenn bV5Size der Größe des BITMAPV5HEADER entspricht und bV5CSType gleich PROFILE_EMBEDDED oder PROFILE_LINKED ist.<br/> |
| [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) | Sie können Bitmap (BMP)- und Device Independent Bitmap<br/>            (DIB)-Dateien mühelos handhaben, was eine effiziente Manipulation und Verarbeitung von Raster<br/>            Bildern ermöglicht. Durch die Durchführung verschiedener Operationen an Bildern optimiert diese API den<br/>            Arbeitsablauf und bietet Entwicklern ein zuverlässiges Toolkit für die Arbeit mit BMP und<br/>            DIB-Formaten in ihren Softwareanwendungen. |
| [Os22XBitmapHeader](/imaging/python-net/aspose.imaging.fileformats.bmp/os22xbitmapheader/) | Ein OS/2 2.x OS22XBITMAPHEADER, auch bekannt als BITMAPCOREHEADER2. |
## **Enumerations**
| **Aufzählung** | **Beschreibung** |
| :- | :- |
| [BitmapCompression](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcompression/) | Gibt verschiedene Bitmap‑Kompressionsmethoden an. |
