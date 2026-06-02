---
title: "WmfBinaryRasterOperation"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "La sezione dell'enumerazione BinaryRasterOperation elenca i codici di operazione raster binaria."
type: docs
weight: 11
url: /it/java/com.aspose.imaging.fileformats.wmf.consts/wmfbinaryrasteroperation/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class WmfBinaryRasterOperation extends System.Enum
```

La sezione Enumerazione BinaryRasterOperation elenca i codici di operazione raster binari. I codici di operazione raster definiscono come l'elaborazione del metafile combina i bit della penna selezionata con i bit nella bitmap di destinazione.

--------------------

Ogni codice di operazione raster rappresenta un'operazione booleana in cui i valori dei pixel nella penna selezionata e nella bitmap di destinazione vengono combinati. Di seguito sono riportati i due operandi utilizzati in queste operazioni. Operando Significato P Penna selezionata D Bitmap di destinazione a AND bitwise n NOT bitwise (inverso) o OR bitwise x XOR bitwise (XOR)
## Campi

| Campo | Descrizione |
| --- | --- |
| [Black](#Black) | 0, il pixel è sempre 0. |
| [Notmergepen](#Notmergepen) | DPon, il pixel è l'inverso del colore MERGEPEN |
| [Masknotpen](#Masknotpen) | DPna, il pixel è una combinazione del colore dello schermo e dell'inverso del colore della penna. |
| [Notcopypen](#Notcopypen) | Pn, il pixel è l'inverso del colore della penna. |
| [Maskpennot](#Maskpennot) | PDna, il pixel è una combinazione dei colori comuni sia alla penna sia all'inverso dello schermo. |
| [Not](#Not) | Dn, il pixel è l'inverso del colore dello schermo. |
| [Xorpen](#Xorpen) | DPx, il pixel è una combinazione dei colori nella penna o nello schermo, ma non in entrambi. |
| [Notmaskpen](#Notmaskpen) | DPan, il pixel è l'inverso del colore MASKPEN. |
| [Maskpen](#Maskpen) | DPa, il pixel è una combinazione dei colori comuni sia alla penna sia allo schermo. |
| [Notxorpen](#Notxorpen) | DPxn, il pixel è l'inverso del colore XORPEN. |
| [Nop](#Nop) | D, il pixel rimane invariato. |
| [Mergenotpen](#Mergenotpen) | DPno, il pixel è una combinazione dei colori comuni sia allo schermo sia all'inverso della penna. |
| [Copypen](#Copypen) | P, Pixel è il colore della penna. |
| [Mergepennot](#Mergepennot) | PDno, Pixel è una combinazione del colore della penna e dell'inverso del colore dello schermo. |
| [Mergepen](#Mergepen) | DPo, Pixel è una combinazione del colore della penna e del colore dello schermo. |
| [White](#White) | 1, Pixel è sempre 1 |
### Black {#Black}
```
public static final int Black
```


0, il pixel è sempre 0.

### Notmergepen {#Notmergepen}
```
public static final int Notmergepen
```


DPon, il pixel è l'inverso del colore MERGEPEN

### Masknotpen {#Masknotpen}
```
public static final int Masknotpen
```


DPna, il pixel è una combinazione del colore dello schermo e dell'inverso del colore della penna.

### Notcopypen {#Notcopypen}
```
public static final int Notcopypen
```


Pn, il pixel è l'inverso del colore della penna.

### Maskpennot {#Maskpennot}
```
public static final int Maskpennot
```


PDna, il pixel è una combinazione dei colori comuni sia alla penna sia all'inverso dello schermo.

### Not {#Not}
```
public static final int Not
```


Dn, il pixel è l'inverso del colore dello schermo.

### Xorpen {#Xorpen}
```
public static final int Xorpen
```


DPx, il pixel è una combinazione dei colori nella penna o nello schermo, ma non in entrambi.

### Notmaskpen {#Notmaskpen}
```
public static final int Notmaskpen
```


DPan, il pixel è l'inverso del colore MASKPEN.

### Maskpen {#Maskpen}
```
public static final int Maskpen
```


DPa, il pixel è una combinazione dei colori comuni sia alla penna sia allo schermo.

### Notxorpen {#Notxorpen}
```
public static final int Notxorpen
```


DPxn, il pixel è l'inverso del colore XORPEN.

### Nop {#Nop}
```
public static final int Nop
```


D, il pixel rimane invariato.

### Mergenotpen {#Mergenotpen}
```
public static final int Mergenotpen
```


DPno, il pixel è una combinazione dei colori comuni sia allo schermo sia all'inverso della penna.

### Copypen {#Copypen}
```
public static final int Copypen
```


P, Pixel è il colore della penna.

### Mergepennot {#Mergepennot}
```
public static final int Mergepennot
```


PDno, Pixel è una combinazione del colore della penna e dell'inverso del colore dello schermo.

### Mergepen {#Mergepen}
```
public static final int Mergepen
```


DPo, Pixel è una combinazione del colore della penna e del colore dello schermo.

### White {#White}
```
public static final int White
```


1, Pixel è sempre 1

