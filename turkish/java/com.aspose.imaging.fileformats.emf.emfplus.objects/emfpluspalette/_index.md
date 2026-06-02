---
title: "EmfPlusPalette"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EmfPlusPalette nesnesi, bir paleti oluşturan renkleri belirtir."
type: docs
weight: 57
url: /tr/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspalette/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
```
public final class EmfPlusPalette extends EmfPlusStructureObjectType
```

EmfPlusPalette nesnesi, bir paleti oluşturan renkleri belirtir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfPlusPalette()](#EmfPlusPalette--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getPaletteStyleFlags()](#getPaletteStyleFlags--) | Palet stil bayraklarını alır veya ayarlar. |
| [setPaletteStyleFlags(int value)](#setPaletteStyleFlags-int-) | Palet stil bayraklarını alır veya ayarlar. |
| [getArgb32Entries()](#getArgb32Entries--) | Palet girişlerini alır veya ayarlar. |
| [setArgb32Entries(int[] value)](#setArgb32Entries-int---) | Palet girişlerini alır veya ayarlar. |
### EmfPlusPalette() {#EmfPlusPalette--}
```
public EmfPlusPalette()
```


### getPaletteStyleFlags() {#getPaletteStyleFlags--}
```
public int getPaletteStyleFlags()
```


Palet stil bayraklarını alır veya ayarlar.

Değer: PaletteStyleFlags (4 bayt): Palet içindeki verinin özelliklerini belirten 32 bit işaretsiz tam sayı. Bu değer, `EmfPlusPaletteStyleFlags` bayraklarından oluşmalıdır.

**Returns:**
int
### setPaletteStyleFlags(int value) {#setPaletteStyleFlags-int-}
```
public void setPaletteStyleFlags(int value)
```


Palet stil bayraklarını alır veya ayarlar.

Değer: PaletteStyleFlags (4 bayt): Palet içindeki verinin özelliklerini belirten 32 bit işaretsiz tam sayı. Bu değer, `EmfPlusPaletteStyleFlags` bayraklarından oluşmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getArgb32Entries() {#getArgb32Entries--}
```
public int[] getArgb32Entries()
```


Palet girişlerini alır veya ayarlar.

Değer: PaletteEntries (değişken): Palet içindeki veriyi belirten PaletteCount 32 bit ARGB nesnelerinden oluşan bir dizi.

**Returns:**
int[] - Palet girişlerinin kopyası.
### setArgb32Entries(int[] value) {#setArgb32Entries-int---}
```
public void setArgb32Entries(int[] value)
```


Palet girişlerini alır veya ayarlar.

Değer: PaletteEntries (değişken): Palet içindeki veriyi belirten PaletteCount 32 bit ARGB nesnelerinden oluşan bir dizi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int[] |  |

