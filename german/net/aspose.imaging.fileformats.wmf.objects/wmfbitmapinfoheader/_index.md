---
title: WmfBitmapInfoHeader
second_title: Aspose.Imaging für .NET-API-Referenz
description: Das BitmapInfoHeader-Objekt enthält Informationen über die Abmessungen und das Farbformat einer geräteunabhängigen Bitmap DIB.
type: docs
weight: 8470
url: /de/net/aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/
---
## WmfBitmapInfoHeader class

Das BitmapInfoHeader-Objekt enthält Informationen über die Abmessungen und das Farbformat einer geräteunabhängigen Bitmap (DIB).

```csharp
public class WmfBitmapInfoHeader : WmfBitmapBaseHeader
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [WmfBitmapInfoHeader](wmfbitmapinfoheader)() | Default_Constructor |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [BitCount](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapbaseheader/bitcount) { get; set; } | Ruft eine 16-Bit-Ganzzahl ohne Vorzeichen ab oder legt diese fest, die das Format von für jedes Pixel und die maximale Anzahl von Farben in der DIB definiert. Dieser Wert MUSS im sein[`BitCount`](../wmfbitmapbaseheader/bitcount) Aufzählung (Abschnitt 2.1.1.3). |
| [ColorImportant](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/colorimportant) { get; set; } | Ruft eine 32-Bit-Ganzzahl ohne Vorzeichen ab oder legt sie fest, die die Anzahl der Farbindizes definiert, die für die Anzeige der DIB erforderlich sind. Wenn dieser Wert Null ist, sind alle Farbindizes erforderlich |
| [ColorUsed](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/colorused) { get; set; } | Ruft eine 32-Bit-Ganzzahl ohne Vorzeichen ab oder legt diese fest, die die Anzahl der Indizes in der von der DIB verwendeten Farbtabelle angibt, wie folgt: Wenn dieser Wert Null ist, verwendet die DIB die maximale Anzahl von Farben, die dem BitCount-Wert entsprechen. Wenn dieser Wert ungleich Null und der BitCount-Wert kleiner als 16 ist, gibt dieser Wert die Anzahl der Farben an, die von der DIB verwendet werden. Wenn dieser Wert ungleich Null ist und der BitCount-Wert 16 oder größer ist, gibt dieser Wert die Größe der Farbe an table wird verwendet, um die Leistung der Systempalette zu optimieren. Hinweis Wenn dieser Wert ungleich Null und größer als die maximal mögliche Größe der Farbtabelle basierend auf dem BitCount -Wert ist, SOLLTE die maximale Farbtabellengröße angenommen werden. |
| [Compression](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/compression) { get; set; } | Ruft eine 32-Bit-Ganzzahl ohne Vorzeichen ab oder legt diese fest, die den Komprimierungsmodus der DIB definiert. Dieser Wert MUSS in der Compression Enumeration (Abschnitt 2.1.1.7) enthalten sein. Dieser Wert DARF KEIN komprimiertes Format spezifizieren, wenn die DIB eine Top-down-Bitmap ist, wie durch den Height-Wert angegeben. |
| [HeaderSize](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapbaseheader/headersize) { get; set; } | Ruft eine 32-Bit-Ganzzahl ohne Vorzeichen ab oder legt sie fest, die die Größe dieses -Objekts in Byte definiert. |
| [Height](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/height) { get; set; } | Ruft eine 32-Bit-Ganzzahl mit Vorzeichen ab oder legt diese fest, die die Höhe der DIB in Pixel definiert. Dieser Wert DARF NICHT Null sein. Wenn dieser Wert positiv ist, ist die DIB eine Bitmap von unten nach oben und ihr Ursprung ist die untere linke Ecke. Wenn dieser Wert negativ ist, ist die DIB eine Bitmap von oben nach unten, und sein Ursprung ist die obere linke Ecke. Top-Down-Bitmaps unterstützen keine Komprimierung. Dieses Feld SOLLTE die Höhe der dekomprimierten Bilddatei angeben, wenn der Komprimierungswert das JPEG- oder PNG -Format angibt. |
| [ImageSize](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/imagesize) { get; set; } | Ruft eine 32-Bit-Ganzzahl ohne Vorzeichen ab oder legt sie fest, die die Größe des Bilds in Bytes definiert. Wenn der Komprimierungswert BI_RGB ist, SOLLTE dieser Wert Null sein und MUSS ignoriert werden. Wenn der Komprimierungswert BI_JPEG oder BI_PNG ist, Dieser Wert MUSS die Größe des JPEG- oder PNG-Bildpuffers angeben, bzw. |
| [Planes](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapbaseheader/planes) { get; set; } | Ruft eine 16-Bit-Ganzzahl ohne Vorzeichen ab oder legt sie fest, die die Anzahl von definiertplanes für das Zielgerät. Dieser Wert MUSS 0x0001. sein |
| [Width](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/width) { get; set; } | Ruft eine 32-Bit-Ganzzahl mit Vorzeichen ab oder legt diese fest, die die Breite der DIB in Pixel definiert. Dieser Wert MUSS positiv sein. Dieses Feld SOLLTE die Breite der dekomprimierten Bilddatei angeben, wenn der Komprimierungswert das JPEG- oder PNG -Format angibt. |
| [XPelsPerMeter](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/xpelspermeter) { get; set; } | Ruft eine 32-Bit-Ganzzahl mit Vorzeichen ab oder legt diese fest, die die horizontale Auflösung des target -Geräts für die DIB in Pixel pro Meter definiert. |
| [YPelsPerMeter](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/ypelspermeter) { get; set; } | Ruft eine 32-Bit-Ganzzahl mit Vorzeichen ab oder legt diese fest, die die vertikale Auflösung des target -Geräts für die DIB in Pixel pro Meter definiert. |

## Felder

| Name | Beschreibung |
| --- | --- |
| const [StructureSize](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/structuresize) | Die Strukturgröße |

### Siehe auch

* class [WmfBitmapBaseHeader](../wmfbitmapbaseheader)
* namensraum [Aspose.Imaging.FileFormats.Wmf.Objects](../../aspose.imaging.fileformats.wmf.objects)
* Montage [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
