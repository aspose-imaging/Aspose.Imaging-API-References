---
title: "EmfPlusPixelFormat"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "L'enumerazione PixelFormat definisce i formati pixel supportati nei bitmap EMF."
type: docs
weight: 43
url: /it/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfpluspixelformat/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusPixelFormat extends System.Enum
```

L'enumerazione PixelFormat definisce i formati pixel supportati nei bitmap EMF+.
## Campi

| Campo | Descrizione |
| --- | --- |
| [PixelFormatUndefined](#PixelFormatUndefined) | Il formato non è specificato. |
| [PixelFormat1bppIndexed](#PixelFormat1bppIndexed) | Il formato è monocromatico e viene utilizzata una tabella di ricerca della palette dei colori. |
| [PixelFormat4bppIndexed](#PixelFormat4bppIndexed) | Il formato è a 16 colori e viene utilizzata una tabella di ricerca della palette dei colori. |
| [PixelFormat8bppIndexed](#PixelFormat8bppIndexed) | Il formato è a 256 colori e viene utilizzata una tabella di ricerca della palette dei colori. |
| [PixelFormat16bppGrayScale](#PixelFormat16bppGrayScale) | Il formato è a 16 bit per pixel, in scala di grigi. |
| [PixelFormat16bppRGB555](#PixelFormat16bppRGB555) | Il formato è a 16 bit per pixel; 5 bit per ciascuno dei componenti rosso, verde e blu sono utilizzati. |
| [PixelFormat16bppRGB565](#PixelFormat16bppRGB565) | Il formato è a 16 bit per pixel; 5 bit sono utilizzati per il componente rosso, 6 bit per il componente verde e 5 bit per il componente blu. |
| [PixelFormat16bppARGB1555](#PixelFormat16bppARGB1555) | Il formato è a 16 bit per pixel; 1 bit è utilizzato per il componente alfa e 5 bit per ciascuno dei componenti rosso, verde e blu. |
| [PixelFormat24bppRGB](#PixelFormat24bppRGB) | Il formato è a 24 bit per pixel; 8 bit per ciascuno dei componenti rosso, verde e blu sono utilizzati. |
| [PixelFormat32bppRGB](#PixelFormat32bppRGB) | Il formato è a 32 bit per pixel; 8 bit per ciascuno dei componenti rosso, verde e blu sono utilizzati. |
| [PixelFormat32bppARGB](#PixelFormat32bppARGB) | Il formato è a 32 bit per pixel; 8 bit per ciascuno dei componenti alfa, rosso, verde e blu sono utilizzati. |
| [PixelFormat32bppPARGB](#PixelFormat32bppPARGB) | Il formato è a 32 bit per pixel; 8 bit per ciascuno dei componenti alfa, rosso, verde e blu sono utilizzati. |
| [PixelFormat48bppRGB](#PixelFormat48bppRGB) | Il formato è a 48 bit per pixel; 16 bit per ciascuno dei componenti rosso, verde e blu sono utilizzati. |
| [PixelFormat64bppARGB](#PixelFormat64bppARGB) | Il formato è a 64 bit per pixel; 16 bit per ciascuno dei componenti alfa, rosso, verde e blu sono utilizzati. |
| [PixelFormat64bppPARGB](#PixelFormat64bppPARGB) | Il formato è a 64 bit per pixel; 16 bit per ciascuno dei componenti alfa, rosso, verde e blu sono utilizzati. |
### PixelFormatUndefined {#PixelFormatUndefined}
```
public static final int PixelFormatUndefined
```


Il formato non è specificato.

--------------------

I formati pixel sono specificati dagli oggetti [EmfPlusBitmap](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbitmap). Sono codificati come segue: - Bits 0-7: Enumerazione delle costanti del formato pixel, a partire da zero. - Bits 8-15: Numero totale di bit per pixel. - Bit 16: Se impostato, il valore del colore è indicizzato in una palette. - Bit 17: Se impostato, il valore del colore è in un formato supportato da GDI. - Bit 18: Se impostato, il valore del colore ha un componente alfa. - Bit 19: Se impostato, il valore del colore ha un componente alfa premoltiplicato. - Bit 20: Se impostato, sono supportati colori estesi, 16 bit per canale. - Bits 21-31: Riservati.

### PixelFormat1bppIndexed {#PixelFormat1bppIndexed}
```
public static final int PixelFormat1bppIndexed
```


Il formato è monocromatico e viene utilizzata una tabella di ricerca della palette dei colori.

### PixelFormat4bppIndexed {#PixelFormat4bppIndexed}
```
public static final int PixelFormat4bppIndexed
```


Il formato è a 16 colori e viene utilizzata una tabella di ricerca della palette dei colori.

### PixelFormat8bppIndexed {#PixelFormat8bppIndexed}
```
public static final int PixelFormat8bppIndexed
```


Il formato è a 256 colori e viene utilizzata una tabella di ricerca della palette dei colori.

### PixelFormat16bppGrayScale {#PixelFormat16bppGrayScale}
```
public static final int PixelFormat16bppGrayScale
```


Il formato è a 16 bit per pixel, in scala di grigi.

### PixelFormat16bppRGB555 {#PixelFormat16bppRGB555}
```
public static final int PixelFormat16bppRGB555
```


Il formato è a 16 bit per pixel; 5 bit per ciascuno dei componenti rosso, verde e blu sono utilizzati. Il bit rimanente non è utilizzato.

### PixelFormat16bppRGB565 {#PixelFormat16bppRGB565}
```
public static final int PixelFormat16bppRGB565
```


Il formato è a 16 bit per pixel; 5 bit sono utilizzati per il componente rosso, 6 bit per il componente verde e 5 bit per il componente blu.

### PixelFormat16bppARGB1555 {#PixelFormat16bppARGB1555}
```
public static final int PixelFormat16bppARGB1555
```


Il formato è a 16 bit per pixel; 1 bit è utilizzato per il componente alfa e 5 bit per ciascuno dei componenti rosso, verde e blu.

### PixelFormat24bppRGB {#PixelFormat24bppRGB}
```
public static final int PixelFormat24bppRGB
```


Il formato è a 24 bit per pixel; 8 bit per ciascuno dei componenti rosso, verde e blu sono utilizzati.

### PixelFormat32bppRGB {#PixelFormat32bppRGB}
```
public static final int PixelFormat32bppRGB
```


Il formato è a 32 bit per pixel; 8 bit per ciascuno dei componenti rosso, verde e blu sono utilizzati. Gli 8 bit rimanenti non sono utilizzati.

### PixelFormat32bppARGB {#PixelFormat32bppARGB}
```
public static final int PixelFormat32bppARGB
```


Il formato è a 32 bit per pixel; 8 bit per ciascuno dei componenti alfa, rosso, verde e blu sono utilizzati.

### PixelFormat32bppPARGB {#PixelFormat32bppPARGB}
```
public static final int PixelFormat32bppPARGB
```


Il formato è a 32 bit per pixel; 8 bit per ciascuno dei componenti alfa, rosso, verde e blu sono utilizzati. I componenti rosso, verde e blu sono premoltiplicati in base al componente alfa.

### PixelFormat48bppRGB {#PixelFormat48bppRGB}
```
public static final int PixelFormat48bppRGB
```


Il formato è a 48 bit per pixel; 16 bit per ciascuno dei componenti rosso, verde e blu sono utilizzati.

### PixelFormat64bppARGB {#PixelFormat64bppARGB}
```
public static final int PixelFormat64bppARGB
```


Il formato è a 64 bit per pixel; 16 bit per ciascuno dei componenti alfa, rosso, verde e blu sono utilizzati.

### PixelFormat64bppPARGB {#PixelFormat64bppPARGB}
```
public static final int PixelFormat64bppPARGB
```


Il formato è a 64 bit per pixel; 16 bit per ciascuno dei componenti alfa, rosso, verde e blu sono utilizzati. I componenti rosso, verde e blu sono premoltiplicati in base al componente alfa.

