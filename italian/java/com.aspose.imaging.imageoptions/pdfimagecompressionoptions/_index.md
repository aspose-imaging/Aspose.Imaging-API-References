---
title: "PdfImageCompressionOptions"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Opzioni di compressione immagine PDF"
type: docs
weight: 35
url: /it/java/com.aspose.imaging.imageoptions/pdfimagecompressionoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PdfImageCompressionOptions extends System.Enum
```

Opzioni di compressione immagine PDF
## Campi

| Campo | Descrizione |
| --- | --- |
| [Auto](#Auto) | Seleziona automaticamente la compressione più appropriata per ogni immagine. |
| [None](#None) | Salva i byte dell'immagine grezza, risultando in file PDF più grandi. |
| [Rle](#Rle) | Compressione Run Length. |
| [Flate](#Flate) | Compressione Flate. |
| [LzwBaselinePredictor](#LzwBaselinePredictor) | La selezione del predittore è limitata al predittore PNG Paeth per velocizzare il processo. |
| [LzwOptimizedPredictor](#LzwOptimizedPredictor) | La selezione del predittore è più complicata e dovrebbe produrre immagini più piccole, ma richiede più tempo. |
| [Jpeg](#Jpeg) | Compressione Jpeg. |
| [Ccitt3](#Ccitt3) | /CCITTFaxDecode/DecodeParms/K 0/Columns 173 Non supporta la trasparenza. |
| [Ccitt4](#Ccitt4) | /CCITTFaxDecode/DecodeParms/K -1/Columns 173 Non supporta la trasparenza. |
### Auto {#Auto}
```
public static final int Auto
```


Seleziona automaticamente la compressione più appropriata per ogni immagine.

### None {#None}
```
public static final int None
```


Salva i byte dell'immagine grezza, risultando in file PDF più grandi.

### Rle {#Rle}
```
public static final int Rle
```


Compressione Run Length.

### Flate {#Flate}
```
public static final int Flate
```


Compressione Flate.

### LzwBaselinePredictor {#LzwBaselinePredictor}
```
public static final int LzwBaselinePredictor
```


La selezione del predittore è limitata al predittore PNG Paeth per velocizzare il processo. In pratica funziona sorprendentemente bene. Meglio di [LzwOptimizedPredictor](../../com.aspose.imaging.imageoptions/pdfimagecompressionoptions\\#LzwOptimizedPredictor).

### LzwOptimizedPredictor {#LzwOptimizedPredictor}
```
public static final int LzwOptimizedPredictor
```


La selezione del predittore è più complicata e dovrebbe produrre immagini più piccole, ma richiede più tempo. RFC 2083 afferma che è la soluzione migliore. Tuttavia, sui dati di test il predittore di base [LzwBaselinePredictor](../../com.aspose.imaging.imageoptions/pdfimagecompressionoptions\\#LzwBaselinePredictor) è eccezionale, lasciando il predittore ottimizzato indietro con un guadagno del 25‑40% nel tasso di compressione.

### Jpeg {#Jpeg}
```
public static final int Jpeg
```


Compressione Jpeg. Non supporta la trasparenza.

### Ccitt3 {#Ccitt3}
```
public static final int Ccitt3
```


/CCITTFaxDecode/DecodeParms/K 0/Columns 173 Non supporta la trasparenza.

### Ccitt4 {#Ccitt4}
```
public static final int Ccitt4
```


/CCITTFaxDecode/DecodeParms/K -1/Columns 173 Non supporta la trasparenza.

