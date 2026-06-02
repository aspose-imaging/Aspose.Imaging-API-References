---
title: "WmfCompression"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Die Compression‑Aufzählung gibt den Kompressionstyp für ein Bitmap‑Bild an."
type: docs
weight: 16
url: /de/java/com.aspose.imaging.fileformats.wmf.consts/wmfcompression/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class WmfCompression extends System.Enum
```

Die Compression‑Aufzählung gibt den Kompressionstyp für ein Bitmap‑Bild an.
## Felder

| Feld | Beschreibung |
| --- | --- |
| [BI_RGB](#BI-RGB) | Das Bitmap liegt im unkomprimierten Rot‑Grün‑Blau (RGB)‑Format vor, das nicht komprimiert ist und keine Farbmasken verwendet. |
| [BI_RLE8](#BI-RLE8) | Ein RGB‑Format, das Run‑Length‑Encoding (RLE)‑Kompression für Bitmaps mit 8 Bit pro Pixel verwendet. |
| [BI_RLE4](#BI-RLE4) | Ein RGB‑Format, das RLE‑Kompression für Bitmaps mit 4 Bit pro Pixel verwendet. |
| [BI_BITFIELDS](#BI-BITFIELDS) | Das Bitmap ist nicht komprimiert und die Farbpalette besteht aus drei DWORD-Farbmasken, die jeweils die roten, grünen und blauen Komponenten jedes Pixels angeben. |
| [BI_JPEG](#BI-JPEG) | Das Bild ist ein JPEG-Bild, wie in [JFIF] angegeben. |
| [BI_PNG](#BI-PNG) | Das Bild ist ein PNG-Bild, wie in [RFC2083] angegeben. |
| [BI_CMYK](#BI-CMYK) | Das Bild ist ein unkomprimiertes CMYK-Format. |
| [BI_CMYKRLE8](#BI-CMYKRLE8) | Ein CMYK-Format, das RLE-Kompression für Bitmaps mit 8 Bit pro Pixel verwendet. |
| [BI_CMYKRLE4](#BI-CMYKRLE4) | Ein CMYK-Format, das RLE-Kompression für Bitmaps mit 4 Bit pro Pixel verwendet. |
### BI_RGB {#BI-RGB}
```
public static final int BI_RGB
```


Das Bitmap liegt im unkomprimierten Rot‑Grün‑Blau (RGB)‑Format vor, das nicht komprimiert ist und keine Farbmasken verwendet.

### BI_RLE8 {#BI-RLE8}
```
public static final int BI_RLE8
```


Ein RGB-Format, das Run-Length-Encoding (RLE)-Kompression für Bitmaps mit 8 Bit pro Pixel verwendet. Die Kompression nutzt ein 2-Byte-Format, das aus einem Zähler-Byte gefolgt von einem Byte mit einem Farbindex besteht.

### BI_RLE4 {#BI-RLE4}
```
public static final int BI_RLE4
```


Ein RGB-Format, das RLE-Kompression für Bitmaps mit 4 Bit pro Pixel verwendet. Die Kompression nutzt ein 2-Byte-Format, das aus einem Zähler-Byte gefolgt von zwei wortlangen Farbindizes besteht.

### BI_BITFIELDS {#BI-BITFIELDS}
```
public static final int BI_BITFIELDS
```


Das Bitmap ist nicht komprimiert und die Farbpalette besteht aus drei DWORD-Farbmasken, die jeweils die roten, grünen und blauen Komponenten jedes Pixels angeben. Dies ist gültig, wenn es mit Bitmaps von 16 bzw. 32 Bit pro Pixel verwendet wird.

### BI_JPEG {#BI-JPEG}
```
public static final int BI_JPEG
```


Das Bild ist ein JPEG-Bild, wie in [JFIF] angegeben. Dieser Wert SOLLTE nur in bestimmten Bitmap-Operationen verwendet werden, wie z. B. JPEG-Durchleitung. Die Anwendung MUSS nach der Durchleitungsunterstützung fragen, da nicht alle Geräte JPEG-Durchleitung unterstützen. Die Verwendung von Nicht-RGB-Bitmaps KANN die Portabilität der Metadatei zu anderen Geräten einschränken. Beispielsweise unterstützen Anzeige-Geräte-Kontexte im Allgemeinen diese Durchleitung nicht.

### BI_PNG {#BI-PNG}
```
public static final int BI_PNG
```


Das Bild ist ein PNG-Bild, wie in [RFC2083] angegeben. Dieser Wert SOLLTE nur in bestimmten Bitmap-Operationen verwendet werden, wie z. B. JPEG/PNG-Durchleitung. Die Anwendung MUSS nach der Durchleitungsunterstützung fragen, da nicht alle Geräte JPEG/PNG-Durchleitung unterstützen. Die Verwendung von Nicht-RGB-Bitmaps KANN die Portabilität der Metadatei zu anderen Geräten einschränken. Beispielsweise unterstützen Anzeige-Geräte-Kontexte im Allgemeinen diese Durchleitung nicht.

### BI_CMYK {#BI-CMYK}
```
public static final int BI_CMYK
```


Das Bild ist ein unkomprimiertes CMYK-Format.

### BI_CMYKRLE8 {#BI-CMYKRLE8}
```
public static final int BI_CMYKRLE8
```


Ein CMYK-Format, das RLE-Kompression für Bitmaps mit 8 Bit pro Pixel verwendet. Die Kompression nutzt ein 2-Byte-Format, das aus einem Zähler-Byte gefolgt von einem Byte mit einem Farbindex besteht.

### BI_CMYKRLE4 {#BI-CMYKRLE4}
```
public static final int BI_CMYKRLE4
```


Ein CMYK-Format, das RLE-Kompression für Bitmaps mit 4 Bit pro Pixel verwendet. Die Kompression nutzt ein 2-Byte-Format, das aus einem Zähler-Byte gefolgt von zwei wortlangen Farbindizes besteht.

