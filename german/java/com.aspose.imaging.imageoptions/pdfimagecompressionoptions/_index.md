---
title: "PdfImageCompressionOptions"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "PDF-Bildkomprimierungsoptionen"
type: docs
weight: 35
url: /de/java/com.aspose.imaging.imageoptions/pdfimagecompressionoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PdfImageCompressionOptions extends System.Enum
```

PDF-Bildkomprimierungsoptionen
## Felder

| Feld | Beschreibung |
| --- | --- |
| [Auto](#Auto) | Wählt automatisch die am besten geeignete Komprimierung für jedes Bild aus. |
| [None](#None) | Speichert rohe Bildbytes, was zu größeren PDF-Dateigrößen führt. |
| [Rle](#Rle) | Run-Length-Komprimierung. |
| [Flate](#Flate) | Flate-Komprimierung. |
| [LzwBaselinePredictor](#LzwBaselinePredictor) | Die Prädiktorauswahl ist auf den PNG-Paeth-Prädiktor beschränkt, um den Vorgang zu beschleunigen. |
| [LzwOptimizedPredictor](#LzwOptimizedPredictor) | Die Prädiktorauswahl ist komplexer und sollte zu kleineren Bildgrößen führen, dauert jedoch länger. |
| [Jpeg](#Jpeg) | JPEG-Komprimierung. |
| [Ccitt3](#Ccitt3) | /CCITTFaxDecode/DecodeParms/K 0/Columns 173 Unterstützt keine Transparenz. |
| [Ccitt4](#Ccitt4) | /CCITTFaxDecode/DecodeParms/K -1/Columns 173 Unterstützt keine Transparenz. |
### Auto {#Auto}
```
public static final int Auto
```


Wählt automatisch die am besten geeignete Komprimierung für jedes Bild aus.

### None {#None}
```
public static final int None
```


Speichert rohe Bildbytes, was zu größeren PDF-Dateigrößen führt.

### Rle {#Rle}
```
public static final int Rle
```


Run-Length-Komprimierung.

### Flate {#Flate}
```
public static final int Flate
```


Flate-Komprimierung.

### LzwBaselinePredictor {#LzwBaselinePredictor}
```
public static final int LzwBaselinePredictor
```


Die Prädiktorauswahl ist auf den PNG-Paeth-Prädiktor beschränkt, um den Vorgang zu beschleunigen. In der Praxis funktioniert sie überraschend gut. Besser als [LzwOptimizedPredictor](../../com.aspose.imaging.imageoptions/pdfimagecompressionoptions\#LzwOptimizedPredictor).

### LzwOptimizedPredictor {#LzwOptimizedPredictor}
```
public static final int LzwOptimizedPredictor
```


Die Prädiktorauswahl ist komplexer und sollte zu kleineren Bildgrößen führen, dauert jedoch länger. RFC 2083 besagt, dass dies der beste Weg ist. Aber bei den Testdaten schlägt der Basisprädiktor [LzwBaselinePredictor](../../com.aspose.imaging.imageoptions/pdfimagecompressionoptions\#LzwBaselinePredictor) den optimierten Prädiktor um 25‑40 % bei der Komprimierungsrate.

### Jpeg {#Jpeg}
```
public static final int Jpeg
```


JPEG-Komprimierung. Unterstützt keine Transparenz.

### Ccitt3 {#Ccitt3}
```
public static final int Ccitt3
```


/CCITTFaxDecode/DecodeParms/K 0/Columns 173 Unterstützt keine Transparenz.

### Ccitt4 {#Ccitt4}
```
public static final int Ccitt4
```


/CCITTFaxDecode/DecodeParms/K -1/Columns 173 Unterstützt keine Transparenz.

