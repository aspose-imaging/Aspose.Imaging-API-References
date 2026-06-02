---
title: "ColorPalette"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Definisce un array di colori che compone una tavolozza di colori."
type: docs
weight: 28
url: /it/java/com.aspose.imaging/colorpalette/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.IColorPalette](../../com.aspose.imaging/icolorpalette)
```
public final class ColorPalette implements IColorPalette
```

Definisce un array di colori che compongono una tavolozza di colori. I colori sono colori ARGB a 32 bit. Non ereditabile.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [ColorPalette(int[] argb32Entries, boolean isCompactPalette)](#ColorPalette-int---boolean-) | Inizializza una nuova istanza della classe `ColorPalette`. |
| [ColorPalette(int[] argb32Entries)](#ColorPalette-int---) | Inizializza una nuova istanza della classe `ColorPalette` e IsCompactPalette è false. |
| [ColorPalette(Color[] entries, boolean isCompactPalette)](#ColorPalette-com.aspose.imaging.Color---boolean-) | Inizializza una nuova istanza della classe `ColorPalette`. |
| [ColorPalette(Color[] entries)](#ColorPalette-com.aspose.imaging.Color---) | Inizializza una nuova istanza della classe `ColorPalette` e IsCompactPalette è false. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getEntriesCount()](#getEntriesCount--) | Ottiene il conteggio delle voci. |
| [getArgb32Entries()](#getArgb32Entries--) | Ottiene un array di strutture ARGB a 32 bit. |
| [getEntries()](#getEntries--) | Ottiene un array di strutture `com.aspose.imaging.Color`. |
| [isCompactPalette()](#isCompactPalette--) | Ottiene o imposta un valore che indica se è utilizzata una tavolozza compatta. |
| [copyPalette(IColorPalette colorPalette, boolean useCompactPalette)](#copyPalette-com.aspose.imaging.IColorPalette-boolean-) | Copia la tavolozza. |
| [copyPalette(IColorPalette colorPalette)](#copyPalette-com.aspose.imaging.IColorPalette-) | Copia la tavolozza. |
| [getNearestColorIndex(int argb32Color)](#getNearestColorIndex-int-) | Ottiene l'indice del colore più vicino. |
| [getNearestColorIndex(Color color)](#getNearestColorIndex-com.aspose.imaging.Color-) | Ottiene l'indice del colore più vicino. |
| [getArgb32Color(int index)](#getArgb32Color-int-) | Ottiene il colore della tavolozza ARGB a 32 bit per indice. |
| [getColor(int index)](#getColor-int-) | Ottiene il colore della tavolozza per indice. |
| [hashCode()](#hashCode--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
### ColorPalette(int[] argb32Entries, boolean isCompactPalette) {#ColorPalette-int---boolean-}
```
public ColorPalette(int[] argb32Entries, boolean isCompactPalette)
```


Inizializza una nuova istanza della classe `ColorPalette`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| argb32Entries | int[] | Le voci della tavolozza dei colori ARGB a 32 bit. |
| isCompactPalette | boolean | Indica se la tavolozza è compatta. |

### ColorPalette(int[] argb32Entries) {#ColorPalette-int---}
```
public ColorPalette(int[] argb32Entries)
```


Inizializza una nuova istanza della classe `ColorPalette` e IsCompactPalette è false.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| argb32Entries | int[] | Le voci della tavolozza dei colori ARGB a 32 bit. |

### ColorPalette(Color[] entries, boolean isCompactPalette) {#ColorPalette-com.aspose.imaging.Color---boolean-}
```
public ColorPalette(Color[] entries, boolean isCompactPalette)
```


Inizializza una nuova istanza della classe `ColorPalette`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| entries | [Color\[\]](../../com.aspose.imaging/color) | Le voci della tavolozza dei colori. |
| isCompactPalette | boolean | Indica se la tavolozza è compatta. |

### ColorPalette(Color[] entries) {#ColorPalette-com.aspose.imaging.Color---}
```
public ColorPalette(Color[] entries)
```


Inizializza una nuova istanza della classe `ColorPalette` e IsCompactPalette è false.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| entries | [Color\[\]](../../com.aspose.imaging/color) | Le voci della tavolozza dei colori. |

### getEntriesCount() {#getEntriesCount--}
```
public int getEntriesCount()
```


Ottiene il conteggio delle voci.

**Returns:**
int - Il conteggio delle voci.
### getArgb32Entries() {#getArgb32Entries--}
```
public int[] getArgb32Entries()
```


Ottiene un array di strutture ARGB a 32 bit.

**Returns:**
int[] - Le voci. La copia dell'array dei valori ARGB a 32 bit che compongono questa [ColorPalette](../../com.aspose.imaging/colorpalette).
### getEntries() {#getEntries--}
```
public Color[] getEntries()
```


Ottiene un array di strutture `com.aspose.imaging.Color`.

**Returns:**
com.aspose.imaging.Color[] - Le voci. La copia dell'array delle strutture [Color](../../com.aspose.imaging/color) che compongono questa [ColorPalette](../../com.aspose.imaging/colorpalette).
### isCompactPalette() {#isCompactPalette--}
```
public boolean isCompactPalette()
```


Ottiene o imposta un valore che indica se è utilizzata una tavolozza compatta.

**Returns:**
boolean - `true` se viene usata una tavolozza compatta; altrimenti, `false`.

Una tavolozza compatta significa che l'immagine conterrà solo le voci di tavolozza specificate, se possibile, in altre parole l'immagine sarà più compatta e occuperà meno spazio; altrimenti ci saranno 2^BitsPerPixel voci e l'immagine riserverà più spazio per tutte le possibili voci di tavolozza. Impostare questo valore su true e modificare le voci della tavolozza può comportare una penalità di prestazioni poiché potrebbe verificarsi lo spostamento dei dati, quindi usarlo con attenzione.
### copyPalette(IColorPalette colorPalette, boolean useCompactPalette) {#copyPalette-com.aspose.imaging.IColorPalette-boolean-}
```
public static ColorPalette copyPalette(IColorPalette colorPalette, boolean useCompactPalette)
```


Copia la tavolozza.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| colorPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | La tavolozza dei colori. |
| useCompactPalette | boolean | Indica se la tavolozza è compatta. |

**Returns:**
[ColorPalette](../../com.aspose.imaging/colorpalette) - The newly created and copied palette or null if null palette passed.
### copyPalette(IColorPalette colorPalette) {#copyPalette-com.aspose.imaging.IColorPalette-}
```
public static ColorPalette copyPalette(IColorPalette colorPalette)
```


Copia la tavolozza.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| colorPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | La tavolozza dei colori. |

**Returns:**
[ColorPalette](../../com.aspose.imaging/colorpalette) - The newly created and copied palette or null if null palette passed.
### getNearestColorIndex(int argb32Color) {#getNearestColorIndex-int-}
```
public int getNearestColorIndex(int argb32Color)
```


Ottiene l'indice del colore più vicino.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| argb32Color | int | Il colore ARGB a 32 bit. |

**Returns:**
int - L'indice del colore più vicino.
### getNearestColorIndex(Color color) {#getNearestColorIndex-com.aspose.imaging.Color-}
```
public int getNearestColorIndex(Color color)
```


Ottiene l'indice del colore più vicino.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| color | [Color](../../com.aspose.imaging/color) | Il colore. |

**Returns:**
int - L'indice del colore più vicino.
### getArgb32Color(int index) {#getArgb32Color-int-}
```
public int getArgb32Color(int index)
```


Ottiene il colore della tavolozza ARGB a 32 bit per indice.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | L'indice del colore della tavolozza ARGB a 32 bit. |

**Returns:**
int - La voce della tavolozza dei colori specificata dall'`index`.
### getColor(int index) {#getColor-int-}
```
public Color getColor(int index)
```


Ottiene il colore della tavolozza per indice.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | L'indice del colore della tavolozza. |

**Returns:**
[Color](../../com.aspose.imaging/color) - The color palette entry specified by the `index`.
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
