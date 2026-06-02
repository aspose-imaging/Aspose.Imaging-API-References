---
title: "FeatheringSettings"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Una classe di impostazioni di sfumatura."
type: docs
weight: 13
url: /it/java/com.aspose.imaging.magicwand.imagemasks/featheringsettings/
---
**Inheritance:**
java.lang.Object
```
public class FeatheringSettings
```

Una classe di impostazioni di sfumatura.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [FeatheringSettings()](#FeatheringSettings--) | Inizializza una nuova istanza della classe [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings). |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getSize()](#getSize--) | Ottiene la dimensione della sfumatura. |
| [setSize(int value)](#setSize-int-) | Imposta la dimensione della sfumatura. |
| [getMode()](#getMode--) | Ottiene la modalità dell'algoritmo di sfumatura. |
| [setMode(int value)](#setMode-int-) | Imposta la modalità dell'algoritmo di sfumatura. |

## Example: The example shows how to select a complicated area of an image using Magic Wand tool and the ability to interact with masks (invert, union, subtract).

``` java
String imageFilePath = "input.png";
String outputFilePath = "masked-complex.png";
try (RasterImage image = (RasterImage)Image.load(imageFilePath))
{
    // Crea una nuova maschera usando lo strumento magic wand basata sul tono e sul colore del pixel (845, 128)
    MagicWandTool.select(image, new MagicWandSettings(845, 128))
            // Unisci la maschera esistente con quella specificata creata dallo strumento magic wand
            .union(new MagicWandSettings(416, 387))
            // Inverti la maschera esistente
            .invert()
            // Sottrai la maschera specificata creata dallo strumento magic wand con soglia specificata dalla maschera esistente
            .subtract(new MagicWandSettings(1482, 346) {{ setThreshold(69); }})
            // Sottrai quattro maschere rettangolari specificate dalla maschera esistente una alla volta
            .subtract(new RectangleMask(0, 0, 800, 150))
            .subtract(new RectangleMask(0, 380, 600, 220))
            .subtract(new RectangleMask(930, 520, 110, 40))
            .subtract(new RectangleMask(1370, 400, 120, 200))
            // Sfuma la maschera con le impostazioni specificate
            .getFeathered(new FeatheringSettings() {{ setSize(3); }})
            // Applica la maschera all'immagine
            .apply();

    // Salva immagine
    image.save(outputFilePath);
}

```

### FeatheringSettings() {#FeatheringSettings--}
```
public FeatheringSettings()
```


Inizializza una nuova istanza della classe [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings).

### getSize() {#getSize--}
```
public final int getSize()
```


Ottiene la dimensione della sfumatura.

Valore: La dimensione del pennello di sfumatura in pixel.

**Returns:**
int - la dimensione della sfumatura.
### setSize(int value) {#setSize-int-}
```
public final void setSize(int value)
```


Imposta la dimensione della sfumatura.

Valore: La dimensione del pennello di sfumatura in pixel.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | la dimensione della sfumatura. |

### getMode() {#getMode--}
```
public final int getMode()
```


Ottiene la modalità dell'algoritmo di sfumatura.

Valore: La modalità dell'algoritmo di sfumatura.

**Returns:**
int - la modalità dell'algoritmo di sfumatura.
### setMode(int value) {#setMode-int-}
```
public final void setMode(int value)
```


Imposta la modalità dell'algoritmo di sfumatura.

Valore: La modalità dell'algoritmo di sfumatura.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | la modalità dell'algoritmo di feathering. |

