---
title: "EmfPlusColorBalanceEffect"
second_title: "Aspose.Imaging for Java API Referansı"
description: "ColorBalanceEffect nesnesi, bir görüntüdeki kırmızı, yeşil ve mavi oranlarına ilişkin ayarlamaları belirtir."
type: docs
weight: 26
url: /tr/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscolorbalanceeffect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImageEffectsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageeffectsobjecttype)
```
public final class EmfPlusColorBalanceEffect extends EmfPlusImageEffectsObjectType
```

ColorBalanceEffect nesnesi, bir görüntüdeki kırmızı, yeşil ve mavi oranlarına yapılan ayarlamaları belirtir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfPlusColorBalanceEffect()](#EmfPlusColorBalanceEffect--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getCyanRed()](#getCyanRed--) | Görüntüdeki kırmızı miktarındaki değişikliği belirten 32 bit işaretli tam sayı alır veya ayarlar. |
| [setCyanRed(int value)](#setCyanRed-int-) | Görüntüdeki kırmızı miktarındaki değişikliği belirten 32 bit işaretli tam sayı alır veya ayarlar. |
| [getMagentaGreen()](#getMagentaGreen--) | Görüntüdeki yeşil miktarındaki değişikliği belirten 32 bit işaretli tam sayı alır veya ayarlar. |
| [setMagentaGreen(int value)](#setMagentaGreen-int-) | Görüntüdeki yeşil miktarındaki değişikliği belirten 32 bit işaretli tam sayı alır veya ayarlar. |
| [getYellowBlue()](#getYellowBlue--) | Görüntüdeki mavi miktarındaki değişikliği belirten 32 bit işaretli tam sayı alır veya ayarlar. |
| [setYellowBlue(int value)](#setYellowBlue-int-) | Görüntüdeki mavi miktarındaki değişikliği belirten 32 bit işaretli tam sayı alır veya ayarlar. |
### EmfPlusColorBalanceEffect() {#EmfPlusColorBalanceEffect--}
```
public EmfPlusColorBalanceEffect()
```


### getCyanRed() {#getCyanRed--}
```
public int getCyanRed()
```


Görüntüdeki kırmızı miktarındaki değişikliği belirten 32 bit işaretli tam sayı alır veya ayarlar. Bu değer -100 ile 100 arasında olmalıdır; etkileri aşağıdaki gibidir: -100 ≤ değer < 0 Değer azaldıkça, görüntüdeki kırmızı miktarı azalmalı ve camgöbeği miktarı artmalıdır. 0 Değer 0, kırmızı ve camgöbeği miktarlarının değişmemesi gerektiğini belirtir. 0 < değer ≤ 100 Değer arttıkça, görüntüdeki kırmızı miktarı artmalı ve camgöbeği miktarı azalmalıdır.

**Returns:**
int
### setCyanRed(int value) {#setCyanRed-int-}
```
public void setCyanRed(int value)
```


Görüntüdeki kırmızı miktarındaki değişikliği belirten 32 bit işaretli tam sayı alır veya ayarlar. Bu değer -100 ile 100 arasında olmalıdır; etkileri aşağıdaki gibidir: -100 ≤ değer < 0 Değer azaldıkça, görüntüdeki kırmızı miktarı azalmalı ve camgöbeği miktarı artmalıdır. 0 Değer 0, kırmızı ve camgöbeği miktarlarının değişmemesi gerektiğini belirtir. 0 < değer ≤ 100 Değer arttıkça, görüntüdeki kırmızı miktarı artmalı ve camgöbeği miktarı azalmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getMagentaGreen() {#getMagentaGreen--}
```
public int getMagentaGreen()
```


Görüntüdeki yeşil miktarındaki değişikliği belirten 32 bit işaretli tam sayı alır veya ayarlar. Bu değer -100 ile 100 arasında olmalıdır; etkileri aşağıdaki gibidir: -100 ≤ değer < 0 Değer azaldıkça, görüntüdeki yeşil miktarı azalmalı ve macenta miktarı artmalıdır. 0 Değer 0, yeşil ve macenta miktarlarının değişmemesi gerektiğini belirtir. 0 < değer ≤ 100 Değer arttıkça, görüntüdeki yeşil miktarı artmalı ve macenta miktarı azalmalıdır.

**Returns:**
int
### setMagentaGreen(int value) {#setMagentaGreen-int-}
```
public void setMagentaGreen(int value)
```


Görüntüdeki yeşil miktarındaki değişikliği belirten 32 bit işaretli tam sayı alır veya ayarlar. Bu değer -100 ile 100 arasında olmalıdır; etkileri aşağıdaki gibidir: -100 ≤ değer < 0 Değer azaldıkça, görüntüdeki yeşil miktarı azalmalı ve macenta miktarı artmalıdır. 0 Değer 0, yeşil ve macenta miktarlarının değişmemesi gerektiğini belirtir. 0 < değer ≤ 100 Değer arttıkça, görüntüdeki yeşil miktarı artmalı ve macenta miktarı azalmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getYellowBlue() {#getYellowBlue--}
```
public int getYellowBlue()
```


Görüntüdeki mavi miktarındaki değişikliği belirten 32 bit işaretli tam sayı alır veya ayarlar. Bu değer -100 ile 100 arasında olmalıdır; etkileri aşağıdaki gibidir: -100 ≤ değer < 0 Değer azaldıkça, görüntüdeki mavi miktarı azalmalı ve sarı miktarı artmalıdır. 0 Değer 0, mavi ve sarı miktarlarının değişmemesi gerektiğini belirtir. 0 < değer ≤ 100 Değer arttıkça, görüntüdeki mavi miktarı artmalı ve sarı miktarı azalmalıdır.

**Returns:**
int
### setYellowBlue(int value) {#setYellowBlue-int-}
```
public void setYellowBlue(int value)
```


Görüntüdeki mavi miktarındaki değişikliği belirten 32 bit işaretli tam sayı alır veya ayarlar. Bu değer -100 ile 100 arasında olmalıdır; etkileri aşağıdaki gibidir: -100 ≤ değer < 0 Değer azaldıkça, görüntüdeki mavi miktarı azalmalı ve sarı miktarı artmalıdır. 0 Değer 0, mavi ve sarı miktarlarının değişmemesi gerektiğini belirtir. 0 < değer ≤ 100 Değer arttıkça, görüntüdeki mavi miktarı artmalı ve sarı miktarı azalmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

