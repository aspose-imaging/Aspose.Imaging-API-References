---
title: "WmfBitmapInfoHeader Klasse"
type: docs
weight: 70
url: /de/python-net/aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/
---

**Summary:** The BitmapInfoHeader Object contains information about the dimensions and color format of a device-independent<br/>                bitmap (DIB).

**Module:** [aspose.imaging.fileformats.wmf.objects](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/)

**Full Name:** aspose.imaging.fileformats.wmf.objects.WmfBitmapInfoHeader

**Inheritance:** WmfBitmapBaseHeader

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [WmfBitmapInfoHeader()](#WmfBitmapInfoHeader__1) | Initialisiert eine neue Instanz der WmfBitmapInfoHeader Klasse |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| STRUCTURE_SIZE [statisch] | int | r | Die Strukturgröße |
| bit_count | [DibBitCount](/imaging/python-net/aspose.imaging.apsbuilder.dib/dibbitcount/) | r/w | Liest oder setzt ein 16‑Bit vorzeichenloser Integer, der das Format von<br/>                jedem Pixel und die maximale Anzahl von Farben im DIB definiert. Dieser Wert<br/>                MUSS in der [WmfBitmapBaseHeader.bit_count](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfbitmapbaseheader/) Aufzählung (Abschnitt 2.1.1.3) liegen. |
| color_important | int | r/w | Ruft den Wert ab oder legt ihn fest, eine 32‑Bit vorzeichenlose Ganzzahl, die die Anzahl der Farbindizes definiert, die für die Anzeige<br/>                des DIB erforderlich sind.<br/>                Wenn dieser Wert null ist, werden alle Farbindizes benötigt. |
| color_used | int | r/w | Ruft den Wert ab oder legt ihn fest, eine 32‑Bit vorzeichenlose Ganzzahl, die die Anzahl der Indizes in der Farbpalette angibt, die vom DIB verwendet wird, wie<br/>                folgt:<br/>                Wenn dieser Wert null ist, verwendet das DIB die maximale Anzahl von Farben, die dem BitCount‑Wert entsprechen.<br/>                Wenn dieser Wert ungleich null ist und der BitCount‑Wert kleiner als 16 ist, gibt dieser Wert die Anzahl der vom DIB verwendeten Farben an.<br/>                Wenn dieser Wert ungleich null ist und der BitCount‑Wert 16 oder größer ist, gibt dieser Wert die Größe der Farbpalette an,<br/>                die zur Optimierung der Systempalette verwendet wird.<br/>                Hinweis: Wenn dieser Wert ungleich null ist und größer als die maximal mögliche Größe der Farbpalette basierend auf dem BitCount‑Wert, sollte die maximale Farbpalettengröße angenommen werden. |
| compression | [WmfCompression](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfcompression/) | r/w | Ruft den Wert ab oder legt ihn fest, eine 32‑Bit vorzeichenlose Ganzzahl, die den Komprimierungsmodus des DIB definiert. Dieser Wert MUSS in der<br/>                Komprimierungs‑Enumeration (Abschnitt 2.1.1.7) liegen.<br/>                Dieser Wert DARF kein komprimiertes Format angeben, wenn das DIB ein Top‑Down‑Bitmap ist, wie durch den Height‑Wert angegeben. |
| header_size | int | r/w | Liest oder setzt ein 32‑Bit vorzeichenloser Integer, der die Größe dieses<br/>                Objekts in Bytes definiert. |
| height | int | r/w | Ruft den Wert ab oder legt ihn fest, eine 32‑Bit vorzeichenbehaftete Ganzzahl, die die Höhe des DIB in Pixeln definiert. Dieser Wert DARF NICHT null sein.<br/>                Wenn dieser Wert positiv ist, ist das DIB ein Bottom‑Up‑Bitmap und sein Ursprung ist die linke untere Ecke.<br/>                Wenn dieser Wert negativ ist, ist das DIB ein Top‑Down‑Bitmap und sein Ursprung ist die linke obere Ecke. Top‑Down‑Bitmaps<br/>                unterstützen keine Komprimierung.<br/>                Dieses Feld SOLLTE die Höhe der dekomprimierten Bilddatei angeben, wenn der Komprimierungswert JPEG oder PNG<br/>                angibt. |
| image_size | int | r/w | Ruft den Wert ab oder legt ihn fest, eine 32‑Bit vorzeichenlose Ganzzahl, die die Größe des Bildes in Bytes definiert.<br/>                Wenn der Komprimierungswert BI_RGB ist, sollte dieser Wert null sein und MUSS ignoriert werden.<br/>                Wenn der Komprimierungswert BI_JPEG oder BI_PNG ist, MUSS dieser Wert die Größe des JPEG‑ bzw. PNG‑Bildpuffers angeben,<br/>                jeweils. |
| planes | int | r/w | Liest oder setzt ein 16‑Bit vorzeichenloser Integer, der die Anzahl der<br/>                [None](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfbitmapbaseheader/) für das Zielgerät definiert. Dieser Wert MUSS<br/>                0x0001 sein. |
| width | int | r/w | Ruft den Wert ab oder legt ihn fest, eine 32‑Bit vorzeichenbehaftete Ganzzahl, die die Breite des DIB in Pixeln definiert. Dieser Wert MUSS positiv sein.<br/>                Dieses Feld SOLLTE die Breite der dekomprimierten Bilddatei angeben, wenn der Komprimierungswert JPEG oder PNG<br/>                angibt. |
| x_pels_per_meter | int | r/w | Ruft den Wert ab oder legt ihn fest, eine 32‑Bit vorzeichenbehaftete Ganzzahl, die die horizontale Auflösung in Pixel‑pro‑Meter des Zielgeräts für das DIB definiert. |
| y_pels_per_meter | int | r/w | Ruft den Wert ab oder legt ihn fest, eine 32‑Bit vorzeichenbehaftete Ganzzahl, die die vertikale Auflösung in Pixel‑pro‑Meter des Zielgeräts für das DIB definiert. |


### Constructor: WmfBitmapInfoHeader() {#WmfBitmapInfoHeader__1}


```
 WmfBitmapInfoHeader() 
```

Initialisiert eine neue Instanz der WmfBitmapInfoHeader Klasse

