---
title: "PdfImageCompressionOptions"
second_title: "Aspose.Imaging för Java API-referens"
description: "Pdf-bildkomprimeringsalternativ."
type: docs
weight: 35
url: /sv/java/com.aspose.imaging.imageoptions/pdfimagecompressionoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PdfImageCompressionOptions extends System.Enum
```

Pdf-bildkomprimeringsalternativ.
## Fält

| Fält | Beskrivning |
| --- | --- |
| [Auto](#Auto) | Väljer automatiskt den mest lämpliga komprimeringen för varje bild. |
| [None](#None) | Sparar råa bildbytes vilket resulterar i större pdf-filstorlekar. |
| [Rle](#Rle) | Run Length-komprimering. |
| [Flate](#Flate) | Flate-komprimering. |
| [LzwBaselinePredictor](#LzwBaselinePredictor) | Prediktorvalet är begränsat till PNG Paeth-prediktor för att påskynda processen. |
| [LzwOptimizedPredictor](#LzwOptimizedPredictor) | Prediktorvalet är mer komplicerat och bör resultera i mindre bildstorlekar men tar mer tid. |
| [Jpeg](#Jpeg) | Jpeg-komprimering. |
| [Ccitt3](#Ccitt3) | /CCITTFaxDecode/DecodeParms/K 0/Columns 173 Stöder inte transparens. |
| [Ccitt4](#Ccitt4) | /CCITTFaxDecode/DecodeParms/K -1/Columns 173 Stöder inte transparens. |
### Auto {#Auto}
```
public static final int Auto
```


Väljer automatiskt den mest lämpliga komprimeringen för varje bild.

### None {#None}
```
public static final int None
```


Sparar råa bildbytes vilket resulterar i större pdf-filstorlekar.

### Rle {#Rle}
```
public static final int Rle
```


Run Length-komprimering.

### Flate {#Flate}
```
public static final int Flate
```


Flate-komprimering.

### LzwBaselinePredictor {#LzwBaselinePredictor}
```
public static final int LzwBaselinePredictor
```


Prediktorvalet är begränsat till PNG Paeth-prediktor för att påskynda processen. I praktiken fungerar det förvånansvärt bra. Bättre än [LzwOptimizedPredictor](../../com.aspose.imaging.imageoptions/pdfimagecompressionoptions\#LzwOptimizedPredictor).

### LzwOptimizedPredictor {#LzwOptimizedPredictor}
```
public static final int LzwOptimizedPredictor
```


Prediktorvalet är mer komplicerat och bör resultera i mindre bildstorlekar men tar mer tid. RFC 2083 säger att det är det bästa sättet. Men på testdata slår baseline-prediktorn [LzwBaselinePredictor](../../com.aspose.imaging.imageoptions/pdfimagecompressionoptions\#LzwBaselinePredictor) den optimerade prediktorn och ger 25‑40 % högre komprimeringsgrad.

### Jpeg {#Jpeg}
```
public static final int Jpeg
```


Jpeg-komprimering. Stöder inte transparens.

### Ccitt3 {#Ccitt3}
```
public static final int Ccitt3
```


/CCITTFaxDecode/DecodeParms/K 0/Columns 173 Stöder inte transparens.

### Ccitt4 {#Ccitt4}
```
public static final int Ccitt4
```


/CCITTFaxDecode/DecodeParms/K -1/Columns 173 Stöder inte transparens.

