---
title: "Konfiguration"
second_title: "Aspose.Imaging för Java API-referens"
description: "Den globala konfigurationen för minneshantering"
type: docs
weight: 10
url: /sv/java/com.aspose.imaging.memorymanagement/configuration/
---
**Inheritance:**
java.lang.Object
```
public final class Configuration
```

Den globala konfigurationen för minneshantering
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getBufferSizeHint()](#getBufferSizeHint--) | Hämtar ledtråden för buffertstorlek som definierar maximal tillåten storlek för alla interna buffertar. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Ställer in ledtråden för buffertstorlek som definierar maximal tillåten storlek för alla interna buffertar. |
### getBufferSizeHint() {#getBufferSizeHint--}
```
public static int getBufferSizeHint()
```


Hämtar ledtråden för buffertstorlek som definierar maximal tillåten storlek för alla interna buffertar.

Värde: Buffertstorleksindikationen, i megabyte. Icke-positivt värde betyder ingen minnesbegränsning för interna buffertar

**Returns:**
int - buffertstorleksindikationen som definierar maximal tillåten storlek för alla interna buffertar.
### setBufferSizeHint(int value) {#setBufferSizeHint-int-}
```
public static void setBufferSizeHint(int value)
```


Ställer in ledtråden för buffertstorlek som definierar maximal tillåten storlek för alla interna buffertar.

Värde: Buffertstorleksindikationen, i megabyte. Icke-positivt värde betyder ingen minnesbegränsning för interna buffertar

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | buffertstorleksindikationen som definierar maximal tillåten storlek för alla interna buffertar. |

