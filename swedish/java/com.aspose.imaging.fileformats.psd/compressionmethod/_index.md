---
title: "CompressionMethod"
second_title: "Aspose.Imaging för Java API-referens"
description: "Definierar komprimeringsmetoden som används för bilddata."
type: docs
weight: 11
url: /sv/java/com.aspose.imaging.fileformats.psd/compressionmethod/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class CompressionMethod extends System.Enum
```

Definierar komprimeringsmetoden som används för bilddata.
## Fält

| Fält | Beskrivning |
| --- | --- |
| [Raw](#Raw) | Ingen komprimering. |
| [RLE](#RLE) | RLE-komprimerad bilddata börjar med byteantalet för alla bildrader (rader \* kanaler), där varje antal lagras som ett tvåbytevärde. |
| [ZipWithoutPrediction](#ZipWithoutPrediction) | ZIP utan prediktion. |
| [ZipWithPrediction](#ZipWithPrediction) | ZIP med prediktion. |
### Raw {#Raw}
```
public static final short Raw
```


Ingen komprimering. Bilddata lagras som råa byte i RGBA-planar ordning. Det betyder att först all R‑data skrivs, sedan all G‑data, därefter all B‑data och slutligen all A‑data.

### RLE {#RLE}
```
public static final short RLE
```


RLE-komprimerad bilddata börjar med byteantalet för alla bildrader (rader \* kanaler), där varje antal lagras som ett tvåbytevärde. Därefter följer den RLE-komprimerade datan, där varje bildrad komprimeras separat. RLE-komprimeringen är samma komprimeringsalgoritm som används av Macintosh ROM‑rutinen PackBits och TIFF‑standarden.

### ZipWithoutPrediction {#ZipWithoutPrediction}
```
public static final short ZipWithoutPrediction
```


ZIP utan prediktion.

### ZipWithPrediction {#ZipWithPrediction}
```
public static final short ZipWithPrediction
```


ZIP med prediktion.

