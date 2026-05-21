---
title: "FeatheringSettings"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Bir tüyleme ayarları sınıfı."
type: docs
weight: 13
url: /tr/java/com.aspose.imaging.magicwand.imagemasks/featheringsettings/
---
**Inheritance:**
java.lang.Object
```
public class FeatheringSettings
```

Bir tüyleme ayarları sınıfı.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [FeatheringSettings()](#FeatheringSettings--) | [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings) sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getSize()](#getSize--) | Tüyleme boyutunu alır. |
| [setSize(int value)](#setSize-int-) | Tüyleme boyutunu ayarlar. |
| [getMode()](#getMode--) | Tüyleme algoritma modunu alır. |
| [setMode(int value)](#setMode-int-) | Tüyleme algoritma modunu ayarlar. |

## Example: The example shows how to select a complicated area of an image using Magic Wand tool and the ability to interact with masks (invert, union, subtract).

``` java
String imageFilePath = "input.png";
String outputFilePath = "masked-complex.png";
try (RasterImage image = (RasterImage)Image.load(imageFilePath))
{
    // (845, 128) pikselinin ton ve rengine dayanarak magic wand aracıyla yeni bir maske oluşturun.
    MagicWandTool.select(image, new MagicWandSettings(845, 128))
            // Mevcut maskeyi, magic wand aracıyla oluşturulan belirtilen maske ile birleştir
            .union(new MagicWandSettings(416, 387))
            // Mevcut maskeyi tersine çevir
            .invert()
            // Belirtilen eşik değeriyle magic wand aracıyla oluşturulan maskeyi mevcut maskeden çıkar
            .subtract(new MagicWandSettings(1482, 346) {{ setThreshold(69); }})
            // Belirtilen dört dikdörtgen maskeyi mevcut maskeden tek tek çıkar
            .subtract(new RectangleMask(0, 0, 800, 150))
            .subtract(new RectangleMask(0, 380, 600, 220))
            .subtract(new RectangleMask(930, 520, 110, 40))
            .subtract(new RectangleMask(1370, 400, 120, 200))
            // Maskeyi belirtilen ayarlarla yumuşat
            .getFeathered(new FeatheringSettings() {{ setSize(3); }})
            // Maskeyi görüntüye uygula
            .apply();

    // Görüntüyü kaydet
    image.save(outputFilePath);
}

```

### FeatheringSettings() {#FeatheringSettings--}
```
public FeatheringSettings()
```


[MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings) sınıfının yeni bir örneğini başlatır.

### getSize() {#getSize--}
```
public final int getSize()
```


Tüyleme boyutunu alır.

Değer: Tüyleme fırçasının piksel cinsinden boyutu.

**Returns:**
int - tüyleme boyutu.
### setSize(int value) {#setSize-int-}
```
public final void setSize(int value)
```


Tüyleme boyutunu ayarlar.

Değer: Tüyleme fırçasının piksel cinsinden boyutu.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | tüyleme boyutu. |

### getMode() {#getMode--}
```
public final int getMode()
```


Tüyleme algoritma modunu alır.

Değer: Tüyleme algoritma modu.

**Returns:**
int - tüyleme algoritma modu.
### setMode(int value) {#setMode-int-}
```
public final void setMode(int value)
```


Tüyleme algoritma modunu ayarlar.

Değer: Tüyleme algoritma modu.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | tüyleme algoritması modu. |

