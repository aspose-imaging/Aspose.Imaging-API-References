---
title: "WmfBinaryRasterOperation"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "La sección de la enumeración BinaryRasterOperation enumera los códigos de operación raster binaria."
type: docs
weight: 11
url: /es/java/com.aspose.imaging.fileformats.wmf.consts/wmfbinaryrasteroperation/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class WmfBinaryRasterOperation extends System.Enum
```

La sección de enumeración BinaryRasterOperation enumera los códigos de operación raster binaria. Los códigos de operación raster definen cómo el procesamiento de metafiles combina los bits del lápiz seleccionado con los bits del mapa de bits de destino.

--------------------

Cada código de operación raster representa una operación booleana en la que se combinan los valores de los píxeles del lápiz seleccionado y del mapa de bits de destino. A continuación se presentan los dos operandos utilizados en estas operaciones. Operando Significado P Lápiz seleccionado D Mapa de bits de destino a AND a nivel de bits n NOT a nivel de bits (inverso) o OR a nivel de bits x XOR a nivel de bits (XOR)
## Campos

| Campo | Descripción |
| --- | --- |
| [Black](#Black) | 0, el píxel siempre es 0. |
| [Notmergepen](#Notmergepen) | DPon, el píxel es el inverso del color MERGEPEN |
| [Masknotpen](#Masknotpen) | DPna, el píxel es una combinación del color de pantalla y el inverso del color del lápiz. |
| [Notcopypen](#Notcopypen) | Pn, el píxel es el inverso del color del lápiz. |
| [Maskpennot](#Maskpennot) | PDna, el píxel es una combinación de los colores comunes tanto al lápiz como al inverso de la pantalla. |
| [Not](#Not) | Dn, el píxel es el inverso del color de la pantalla. |
| [Xorpen](#Xorpen) | DPx, el píxel es una combinación de los colores en el lápiz o en la pantalla, pero no en ambos. |
| [Notmaskpen](#Notmaskpen) | DPan, el píxel es el inverso del color MASKPEN. |
| [Maskpen](#Maskpen) | DPa, el píxel es una combinación de los colores comunes tanto al lápiz como a la pantalla. |
| [Notxorpen](#Notxorpen) | DPxn, el píxel es el inverso del color XORPEN. |
| [Nop](#Nop) | D, el píxel permanece sin cambios. |
| [Mergenotpen](#Mergenotpen) | DPno, el píxel es una combinación de los colores comunes tanto a la pantalla como al inverso del lápiz. |
| [Copypen](#Copypen) | P, Pixel es el color del lápiz. |
| [Mergepennot](#Mergepennot) | PDno, Pixel es una combinación del color del lápiz y el inverso del color de pantalla. |
| [Mergepen](#Mergepen) | DPo, Pixel es una combinación del color del lápiz y el color de pantalla. |
| [White](#White) | 1, Pixel siempre es 1 |
### Black {#Black}
```
public static final int Black
```


0, el píxel siempre es 0.

### Notmergepen {#Notmergepen}
```
public static final int Notmergepen
```


DPon, el píxel es el inverso del color MERGEPEN

### Masknotpen {#Masknotpen}
```
public static final int Masknotpen
```


DPna, el píxel es una combinación del color de pantalla y el inverso del color del lápiz.

### Notcopypen {#Notcopypen}
```
public static final int Notcopypen
```


Pn, el píxel es el inverso del color del lápiz.

### Maskpennot {#Maskpennot}
```
public static final int Maskpennot
```


PDna, el píxel es una combinación de los colores comunes tanto al lápiz como al inverso de la pantalla.

### Not {#Not}
```
public static final int Not
```


Dn, el píxel es el inverso del color de la pantalla.

### Xorpen {#Xorpen}
```
public static final int Xorpen
```


DPx, el píxel es una combinación de los colores en el lápiz o en la pantalla, pero no en ambos.

### Notmaskpen {#Notmaskpen}
```
public static final int Notmaskpen
```


DPan, el píxel es el inverso del color MASKPEN.

### Maskpen {#Maskpen}
```
public static final int Maskpen
```


DPa, el píxel es una combinación de los colores comunes tanto al lápiz como a la pantalla.

### Notxorpen {#Notxorpen}
```
public static final int Notxorpen
```


DPxn, el píxel es el inverso del color XORPEN.

### Nop {#Nop}
```
public static final int Nop
```


D, el píxel permanece sin cambios.

### Mergenotpen {#Mergenotpen}
```
public static final int Mergenotpen
```


DPno, el píxel es una combinación de los colores comunes tanto a la pantalla como al inverso del lápiz.

### Copypen {#Copypen}
```
public static final int Copypen
```


P, Pixel es el color del lápiz.

### Mergepennot {#Mergepennot}
```
public static final int Mergepennot
```


PDno, Pixel es una combinación del color del lápiz y el inverso del color de pantalla.

### Mergepen {#Mergepen}
```
public static final int Mergepen
```


DPo, Pixel es una combinación del color del lápiz y el color de pantalla.

### White {#White}
```
public static final int White
```


1, Pixel siempre es 1

