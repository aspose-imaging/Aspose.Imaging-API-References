---
title: "MagicWandSettings"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Magic Wand seçim ayarları sınıfı."
type: docs
weight: 13
url: /tr/java/com.aspose.imaging.magicwand/magicwandsettings/
---
**Inheritance:**
java.lang.Object
```
public class MagicWandSettings
```

Magic Wand seçim ayarları sınıfı.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [MagicWandSettings(Point point)](#MagicWandSettings-com.aspose.imaging.Point-) | [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings) sınıfının yeni bir örneğini başlatır. |
| [MagicWandSettings(int x, int y)](#MagicWandSettings-int-int-) | [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings) sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getAreaOfInterest()](#getAreaOfInterest--) | Algoritma çalışması için alanın sınırlarını alır. |
| [setAreaOfInterest(Rectangle value)](#setAreaOfInterest-com.aspose.imaging.Rectangle-) | Algoritma çalışması için alanın sınırlarını ayarlar. |
| [getPoint()](#getPoint--) | Algoritma çalışması için referans noktasını alır. |
| [getThreshold()](#getThreshold--) | Piksel renk karşılaştırması için tolerans seviyesini alır. |
| [setThreshold(int value)](#setThreshold-int-) | Piksel renk karşılaştırması için tolerans seviyesini ayarlar. |
| [getContiguousMode()](#getContiguousMode--) | magic wand yalnızca bitişik pikselleri tanımlayıp tanımlamayacağını gösteren bir değeri alır. |
| [setContiguousMode(boolean value)](#setContiguousMode-boolean-) | Sihirli değnek yalnızca bitişik pikselleri tanımlayıp tanımlamayacağını gösteren bir değeri ayarlar. |
| [getDirectionalMode()](#getDirectionalMode--) | Dolgu doldurma arama algoritmasının modunu alır: dört ya da sekiz yön araması. |
| [setDirectionalMode(int value)](#setDirectionalMode-int-) | Dolgu doldurma arama algoritmasının modunu ayarlar: dört ya da sekiz yön araması. |
| [getColorCompareMode()](#getColorCompareMode--) | Renklerin nasıl karşılaştırıldığını gösteren algoritmayı alır. |
| [setColorCompareMode(int value)](#setColorCompareMode-int-) | Renklerin nasıl karşılaştırıldığını gösteren algoritmayı ayarlar. |
| [getColorComparisonDelegate()](#getColorComparisonDelegate--) | `ColorCompareMode`(\\#getColorCompareMode.getColorCompareMode/\\#setColorCompareMode(int).setColorCompareMode(int)) ayarlandığında [ColorComparisonMode.Custom](../../com.aspose.imaging.magicwand/colorcomparisonmode\\#Custom) ise özel renk karşılaştırma algoritmasını alır. |
| [setColorComparisonDelegate(MagicWandSettings.ColorComparison value)](#setColorComparisonDelegate-com.aspose.imaging.magicwand.MagicWandSettings.ColorComparison-) | `ColorCompareMode`(\\#getColorCompareMode.getColorCompareMode/\\#setColorCompareMode(int).setColorCompareMode(int)) ayarlandığında [ColorComparisonMode.Custom](../../com.aspose.imaging.magicwand/colorcomparisonmode\\#Custom) ise özel renk karşılaştırma algoritmasını ayarlar. |

## Example: The example shows how to select a simple area of an image based on tone and color of any pixel using Magic Wand tool.

``` java
String imageFilePath = "input.png";
String outputFilePath = "masked.png";
try (RasterImage image = (RasterImage)Image.load(imageFilePath))
{
    // Özel eşik değeri 150 olan, (120, 100) pikselinin ton ve rengine dayanarak magic wand aracıyla yeni bir maske oluşturun.
    MagicWandTool
            .select(image, new MagicWandSettings(120, 100) {{ setThreshold(150); }})
            // Maskeyi görüntüye uygula
            .apply();

    // Zorunlu şeffaflık renk tipi seçeneğiyle görüntüyü kaydet
    image.save(outputFilePath, new PngOptions()
    {{
        setColorType(PngColorType.TruecolorWithAlpha);
    }});
}

```


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

### MagicWandSettings(Point point) {#MagicWandSettings-com.aspose.imaging.Point-}
```
public MagicWandSettings(Point point)
```


[MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings) sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | Referans noktası. |

### MagicWandSettings(int x, int y) {#MagicWandSettings-int-int-}
```
public MagicWandSettings(int x, int y)
```


[MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings) sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | int | Referans noktasının x koordinatı. |
| y | int | Referans noktasının y koordinatı. |

### getAreaOfInterest() {#getAreaOfInterest--}
```
public final Rectangle getAreaOfInterest()
```


Algoritma çalışması için alanın sınırlarını alır.

Değer: İlgi alanının sınırlarını temsil eden dikdörtgen.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - the bounds of the area for algorithm work.
### setAreaOfInterest(Rectangle value) {#setAreaOfInterest-com.aspose.imaging.Rectangle-}
```
public final void setAreaOfInterest(Rectangle value)
```


Algoritma çalışması için alanın sınırlarını ayarlar.

Değer: İlgi alanının sınırlarını temsil eden dikdörtgen.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) | algoritmanın çalışacağı alanın sınırları. |

### getPoint() {#getPoint--}
```
public final Point getPoint()
```


Algoritma çalışması için referans noktasını alır.

Değer: `Point` değeri.

**Returns:**
[Point](../../com.aspose.imaging/point) - the reference point for algorithm work.
### getThreshold() {#getThreshold--}
```
public final int getThreshold()
```


Piksel renk karşılaştırması için tolerans seviyesini alır.

Değer: Renk karşılaştırması için eşik.

**Returns:**
int - piksel renk karşılaştırması için tolerans seviyesi.
### setThreshold(int value) {#setThreshold-int-}
```
public final void setThreshold(int value)
```


Piksel renk karşılaştırması için tolerans seviyesini ayarlar.

Değer: Renk karşılaştırması için eşik.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | piksel renk karşılaştırması için tolerans seviyesi. |

### getContiguousMode() {#getContiguousMode--}
```
public final boolean getContiguousMode()
```


magic wand yalnızca bitişik pikselleri tanımlayıp tanımlamayacağını gösteren bir değeri alır.

Değer: öğe etkinse `true`; aksi takdirde `false`. Varsayılan değer `true`.

**Returns:**
boolean - sihirli değnek yalnızca bitişik pikselleri tanımlayıp tanımlamayacağını gösteren bir değer.
### setContiguousMode(boolean value) {#setContiguousMode-boolean-}
```
public final void setContiguousMode(boolean value)
```


Sihirli değnek yalnızca bitişik pikselleri tanımlayıp tanımlamayacağını gösteren bir değeri ayarlar.

Değer: öğe etkinse `true`; aksi takdirde `false`. Varsayılan değer `true`.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | sihirli değnek yalnızca bitişik pikselleri tanımlayıp tanımlamayacağını gösteren bir değer. |

### getDirectionalMode() {#getDirectionalMode--}
```
public final int getDirectionalMode()
```


Dolgu doldurma arama algoritmasının modunu alır: dört ya da sekiz yön araması.

Değer: Dolgu doldurma arama algoritmasının modu.

**Returns:**
int - dolgu doldurma arama algoritmasının modu: dört ya da sekiz yön araması.
### setDirectionalMode(int value) {#setDirectionalMode-int-}
```
public final void setDirectionalMode(int value)
```


Dolgu doldurma arama algoritmasının modunu ayarlar: dört ya da sekiz yön araması.

Değer: Dolgu doldurma arama algoritmasının modu.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | dolgu doldurma arama algoritmasının modu: dört ya da sekiz yön araması. |

### getColorCompareMode() {#getColorCompareMode--}
```
public final int getColorCompareMode()
```


Renklerin nasıl karşılaştırıldığını gösteren algoritmayı alır.

Değer: Renk karşılaştırma modu.

**Returns:**
int - renklerin nasıl karşılaştırıldığını gösteren algoritma.
### setColorCompareMode(int value) {#setColorCompareMode-int-}
```
public final void setColorCompareMode(int value)
```


Renklerin nasıl karşılaştırıldığını gösteren algoritmayı ayarlar.

Değer: Renk karşılaştırma modu.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | renklerin nasıl karşılaştırıldığını gösteren algoritma. |

### getColorComparisonDelegate() {#getColorComparisonDelegate--}
```
public final MagicWandSettings.ColorComparison getColorComparisonDelegate()
```


`ColorCompareMode`(\\#getColorCompareMode.getColorCompareMode/\\#setColorCompareMode(int).setColorCompareMode(int)) ayarlandığında [ColorComparisonMode.Custom](../../com.aspose.imaging.magicwand/colorcomparisonmode\\#Custom) ise özel renk karşılaştırma algoritmasını alır.

Değer: Renk karşılaştırma temsilcisi.

**Returns:**
[ColorComparison](../../com.aspose.imaging.magicwand/colorcomparison) - the custom color comparison algorithm if `ColorCompareMode`(\#getColorCompareMode.getColorCompareMode/\#setColorCompareMode(int).setColorCompareMode(int)) is set to [ColorComparisonMode.Custom](../../com.aspose.imaging.magicwand/colorcomparisonmode\#Custom).
### setColorComparisonDelegate(MagicWandSettings.ColorComparison value) {#setColorComparisonDelegate-com.aspose.imaging.magicwand.MagicWandSettings.ColorComparison-}
```
public final void setColorComparisonDelegate(MagicWandSettings.ColorComparison value)
```


`ColorCompareMode`(\\#getColorCompareMode.getColorCompareMode/\\#setColorCompareMode(int).setColorCompareMode(int)) ayarlandığında [ColorComparisonMode.Custom](../../com.aspose.imaging.magicwand/colorcomparisonmode\\#Custom) ise özel renk karşılaştırma algoritmasını ayarlar.

Değer: Renk karşılaştırma temsilcisi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [ColorComparison](../../com.aspose.imaging.magicwand/colorcomparison) | özel renk karşılaştırma algoritması, `ColorCompareMode`(\\#getColorCompareMode.getColorCompareMode/\\#setColorCompareMode(int).setColorCompareMode(int)) [ColorComparisonMode.Custom](../../com.aspose.imaging.magicwand/colorcomparisonmode\\#Custom) olarak ayarlanmışsa. |

