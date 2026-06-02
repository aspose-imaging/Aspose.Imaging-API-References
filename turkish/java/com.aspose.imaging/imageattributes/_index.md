---
title: "ImageAttributes"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Bir com.aspose.imaging.ImageAttributes nesnesi, bitmap ve metafile renklerinin işleme sırasında nasıl manipüle edildiği hakkında bilgi içerir."
type: docs
weight: 57
url: /tr/java/com.aspose.imaging/imageattributes/
---
**Inheritance:**
java.lang.Object
```
public final class ImageAttributes
```

Bir `com.aspose.imaging.ImageAttributes` nesnesi, bitmap ve metafile renklerinin işleme sırasında nasıl değiştirildiği hakkında bilgi içerir. Bir `com.aspose.imaging.ImageAttributes` nesnesi, renk ayarı matrisleri, gri tonlama ayarı matrisleri, gama düzeltme değerleri, renk haritası tabloları ve renk eşiği değerleri dahil olmak üzere çeşitli renk ayarı ayarlarını tutar. İşleme sırasında renkler düzeltilebilir, karartılabilir, aydınlatılabilir ve kaldırılabilir. Bu manipülasyonları uygulamak için bir `com.aspose.imaging.ImageAttributes` nesnesi başlatın ve bu `com.aspose.imaging.ImageAttributes` nesnesinin yolunu (bir [Image](../../com.aspose.imaging/image) yoluyla birlikte) drawImage yöntemine geçirin.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [ImageAttributes()](#ImageAttributes--) | Yeni bir `com.aspose.imaging.ImageAttributes` sınıfı örneği başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [setColorMatrix(ColorMatrix newColorMatrix)](#setColorMatrix-com.aspose.imaging.ColorMatrix-) | Varsayılan kategori için renk ayarı matrisini ayarlar. |
| [setColorMatrix(ColorMatrix newColorMatrix, int flags)](#setColorMatrix-com.aspose.imaging.ColorMatrix-int-) | Varsayılan kategori için renk ayarı matrisini ayarlar. |
| [setColorMatrix(ColorMatrix newColorMatrix, int mode, int type)](#setColorMatrix-com.aspose.imaging.ColorMatrix-int-int-) | Belirtilen kategori için renk ayarı matrisini ayarlar. |
| [clearColorMatrix()](#clearColorMatrix--) | Varsayılan kategori için renk ayarı matrisini temizler. |
| [clearColorMatrix(int type)](#clearColorMatrix-int-) | Belirtilen kategori için renk ayarı matrisini temizler. |
| [setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix)](#setColorMatrices-com.aspose.imaging.ColorMatrix-com.aspose.imaging.ColorMatrix-) | Varsayılan kategori için renk ayarı matrisini ve gri tonlama ayarı matrisini ayarlar. |
| [setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int flags)](#setColorMatrices-com.aspose.imaging.ColorMatrix-com.aspose.imaging.ColorMatrix-int-) | Varsayılan kategori için renk ayarı matrisini ve gri tonlama ayarı matrisini ayarlar. |
| [setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int mode, int type)](#setColorMatrices-com.aspose.imaging.ColorMatrix-com.aspose.imaging.ColorMatrix-int-int-) | Belirtilen kategori için renk ayarı matrisini ve gri tonlama ayarı matrisini ayarlar. |
| [setThreshold(float threshold)](#setThreshold-float-) | Varsayılan kategori için eşik (şeffaflık aralığı) ayarlar. |
| [setThreshold(float threshold, int type)](#setThreshold-float-int-) | Belirtilen kategori için eşik (şeffaflık aralığı) ayarlar. |
| [clearThreshold()](#clearThreshold--) | Varsayılan kategori için eşik değerini temizler. |
| [clearThreshold(int type)](#clearThreshold-int-) | Belirtilen kategori için eşik değerini temizler. |
| [setGamma(float gamma)](#setGamma-float-) | Varsayılan kategori için gama değerini ayarlar. |
| [setGamma(float gamma, int type)](#setGamma-float-int-) | Belirtilen kategori için gama değerini ayarlar. |
| [clearGamma()](#clearGamma--) | Varsayılan kategori için gama düzeltmesini devre dışı bırakır. |
| [clearGamma(int type)](#clearGamma-int-) | Belirtilen kategori için gama düzeltmesini devre dışı bırakır. |
| [setNoOp()](#setNoOp--) | Varsayılan kategori için renk ayarını kapatır. |
| [setNoOp(int type)](#setNoOp-int-) | Belirtilen kategori için renk ayarını kapatır. |
| [clearNoOp()](#clearNoOp--) | Varsayılan kategori için NoOp ayarını temizler. |
| [clearNoOp(int type)](#clearNoOp-int-) | Belirtilen kategori için NoOp ayarını temizler. |
| [setColorKey(Color colorLow, Color colorHigh)](#setColorKey-com.aspose.imaging.Color-com.aspose.imaging.Color-) | Varsayılan kategori için renk anahtarını ayarlar. |
| [setColorKey(Color colorLow, Color colorHigh, int type)](#setColorKey-com.aspose.imaging.Color-com.aspose.imaging.Color-int-) | Belirtilen kategori için renk anahtarını (şeffaflık aralığı) ayarlar. |
| [clearColorKey()](#clearColorKey--) | Varsayılan kategori için renk anahtarını (şeffaflık aralığı) temizler. |
| [clearColorKey(int type)](#clearColorKey-int-) | Belirtilen kategori için renk anahtarını (şeffaflık aralığı) temizler. |
| [setOutputChannel(int flags)](#setOutputChannel-int-) | Varsayılan kategori için CMYK (camgöbeği-mor-sarı-siyah) çıkış kanalını ayarlar. |
| [setOutputChannel(int flags, int type)](#setOutputChannel-int-int-) | Belirli bir kategori için CMYK (cyan-magenta-yellow-black) çıkış kanalını ayarlar. |
| [clearOutputChannel()](#clearOutputChannel--) | Varsayılan kategori için CMYK (cyan-magenta-yellow-black) çıkış kanalı ayarını temizler. |
| [clearOutputChannel(int type)](#clearOutputChannel-int-) | Belirli bir kategori için (cyan-magenta-yellow-black) çıkış kanalı ayarını temizler. |
| [setOutputChannelColorProfile(String colorProfileFilename)](#setOutputChannelColorProfile-java.lang.String-) | Varsayılan kategori için çıkış kanalı renk profili dosyasını ayarlar. |
| [setOutputChannelColorProfile(String colorProfileFilename, int type)](#setOutputChannelColorProfile-java.lang.String-int-) | Belirli bir kategori için çıkış kanalı renk profili dosyasını ayarlar. |
| [clearOutputChannelColorProfile()](#clearOutputChannelColorProfile--) | Varsayılan kategori için çıkış kanalı renk profili ayarını temizler. |
| [clearOutputChannelColorProfile(int type)](#clearOutputChannelColorProfile-int-) | Belirli bir kategori için çıkış kanalı renk profili ayarını temizler. |
| [setRemapTable(ColorMap[] map)](#setRemapTable-com.aspose.imaging.ColorMap---) | Varsayılan kategori için renk yeniden eşleme tablosunu ayarlar. |
| [setRemapTable(ColorMap[] map, int type)](#setRemapTable-com.aspose.imaging.ColorMap---int-) | Belirli bir kategori için renk yeniden eşleme tablosunu ayarlar. |
| [clearRemapTable()](#clearRemapTable--) | Varsayılan kategori için renk yeniden eşleme tablosunu temizler. |
| [clearRemapTable(int type)](#clearRemapTable-int-) | Belirli bir kategori için renk yeniden eşleme tablosunu temizler. |
| [setBrushRemapTable(ColorMap[] map)](#setBrushRemapTable-com.aspose.imaging.ColorMap---) | Fırça kategorisi için renk yeniden eşleme tablosunu ayarlar. |
| [clearBrushRemapTable()](#clearBrushRemapTable--) | Bu `com.aspose.imaging.ImageAttributes` nesnesinin fırça renk yeniden eşleme tablosunu temizler. |
| [setWrapMode(int mode)](#setWrapMode-int-) | Bir dokunun bir şekil boyunca veya şekil sınırlarında nasıl döşeneceğine karar vermek için kullanılan sarma modunu ayarlar. |
| [setWrapMode(int mode, Color color)](#setWrapMode-int-com.aspose.imaging.Color-) | Bir dokunun bir şekil boyunca veya şekil sınırlarında nasıl döşeneceğine karar vermek için kullanılan sarma modunu ve rengi ayarlar. |
| [setWrapMode(int mode, Color color, boolean clamp)](#setWrapMode-int-com.aspose.imaging.Color-boolean-) | Bir dokunun bir şekil boyunca veya şekil sınırlarında nasıl döşeneceğine karar vermek için kullanılan sarma modunu ve rengi ayarlar. |
| [equals(Object o)](#equals-java.lang.Object-) |  |
| [hashCode()](#hashCode--) |  |
### ImageAttributes() {#ImageAttributes--}
```
public ImageAttributes()
```


Yeni bir `com.aspose.imaging.ImageAttributes` sınıfı örneği başlatır.

### setColorMatrix(ColorMatrix newColorMatrix) {#setColorMatrix-com.aspose.imaging.ColorMatrix-}
```
public void setColorMatrix(ColorMatrix newColorMatrix)
```


Varsayılan kategori için renk ayarı matrisini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.imaging/colormatrix) | Renk ayarlama matrisi. |

### setColorMatrix(ColorMatrix newColorMatrix, int flags) {#setColorMatrix-com.aspose.imaging.ColorMatrix-int-}
```
public void setColorMatrix(ColorMatrix newColorMatrix, int flags)
```


Varsayılan kategori için renk ayarı matrisini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.imaging/colormatrix) | Renk ayarlama matrisi. |
| bayraklar | int | `Aspose.Imaging.ColorMatrixFlag` öğesi, renk ayarlama matrisi tarafından etkilenecek görüntü ve renk türünü belirtir. |

### setColorMatrix(ColorMatrix newColorMatrix, int mode, int type) {#setColorMatrix-com.aspose.imaging.ColorMatrix-int-int-}
```
public void setColorMatrix(ColorMatrix newColorMatrix, int mode, int type)
```


Belirtilen kategori için renk ayarı matrisini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.imaging/colormatrix) | Renk ayarlama matrisi. |
| mod | int | `Aspose.Imaging.ColorMatrixFlag` öğesi, renk ayarlama matrisi tarafından etkilenecek görüntü ve renk türünü belirtir. |
| tür | int | `Aspose.Imaging.ColorAdjustType` öğesi, renk ayarlama matrisinin ayarlandığı kategoriyi belirtir. |

### clearColorMatrix() {#clearColorMatrix--}
```
public void clearColorMatrix()
```


Varsayılan kategori için renk ayarı matrisini temizler.

### clearColorMatrix(int type) {#clearColorMatrix-int-}
```
public void clearColorMatrix(int type)
```


Belirtilen kategori için renk ayarı matrisini temizler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tür | int | `Aspose.Imaging.ColorAdjustType` öğesi, renk ayarlama matrisinin temizlendiği kategoriyi belirtir. |

### setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix) {#setColorMatrices-com.aspose.imaging.ColorMatrix-com.aspose.imaging.ColorMatrix-}
```
public void setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix)
```


Varsayılan kategori için renk ayarı matrisini ve gri tonlama ayarı matrisini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.imaging/colormatrix) | Renk ayarlama matrisi. |
| grayMatrix | [ColorMatrix](../../com.aspose.imaging/colormatrix) | Gri tonlama ayarlama matrisi. |

### setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int flags) {#setColorMatrices-com.aspose.imaging.ColorMatrix-com.aspose.imaging.ColorMatrix-int-}
```
public void setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int flags)
```


Varsayılan kategori için renk ayarı matrisini ve gri tonlama ayarı matrisini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.imaging/colormatrix) | Renk ayarlama matrisi. |
| grayMatrix | [ColorMatrix](../../com.aspose.imaging/colormatrix) | Gri tonlama ayarlama matrisi. |
| bayraklar | int | `Aspose.Imaging.ColorMatrixFlag` öğesi, renk ayarlama ve gri tonlama ayarlama matrisleri tarafından etkilenecek görüntü ve renk türünü belirtir. |

### setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int mode, int type) {#setColorMatrices-com.aspose.imaging.ColorMatrix-com.aspose.imaging.ColorMatrix-int-int-}
```
public void setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int mode, int type)
```


Belirtilen kategori için renk ayarı matrisini ve gri tonlama ayarı matrisini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.imaging/colormatrix) | Renk ayarlama matrisi. |
| grayMatrix | [ColorMatrix](../../com.aspose.imaging/colormatrix) | Gri tonlama ayarlama matrisi. |
| mod | int | `Aspose.Imaging.ColorMatrixFlag` öğesi, renk ayarlama ve gri tonlama ayarlama matrisleri tarafından etkilenecek görüntü ve renk türünü belirtir. |
| tür | int | `Aspose.Imaging.ColorAdjustType` öğesi, renk ayarlama ve gri tonlama ayarlama matrislerinin ayarlandığı kategoriyi belirtir. |

### setThreshold(float threshold) {#setThreshold-float-}
```
public void setThreshold(float threshold)
```


Varsayılan kategori için eşik (şeffaflık aralığı) ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| threshold | float | Eşik değerini belirten gerçek bir sayı. |

### setThreshold(float threshold, int type) {#setThreshold-float-int-}
```
public void setThreshold(float threshold, int type)
```


Belirtilen kategori için eşik (şeffaflık aralığı) ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| threshold | float | 0.0 ile 1.0 arasında bir eşik değeri; bu değer, renkleri maksimum ya da minimum bir değere eşlenecek şekilde sıralamak için bir kırılma noktası olarak kullanılır. |
| tür | int | `Aspose.Imaging.ColorAdjustType` öğesi; renk eşiğinin ayarlandığı kategoriyi belirtir. |

### clearThreshold() {#clearThreshold--}
```
public void clearThreshold()
```


Varsayılan kategori için eşik değerini temizler.

### clearThreshold(int type) {#clearThreshold-int-}
```
public void clearThreshold(int type)
```


Belirtilen kategori için eşik değerini temizler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tür | int | `Aspose.Imaging.ColorAdjustType` öğesi; eşik değerinin temizlendiği kategoriyi belirtir. |

### setGamma(float gamma) {#setGamma-float-}
```
public void setGamma(float gamma)
```


Varsayılan kategori için gama değerini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| gamma | float | Gama düzeltme değeri. |

### setGamma(float gamma, int type) {#setGamma-float-int-}
```
public void setGamma(float gamma, int type)
```


Belirtilen kategori için gama değerini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| gamma | float | Gama düzeltme değeri. |
| tür | int | `Aspose.Imaging.ColorAdjustType` enum öğesi; gama değerinin ayarlandığı kategoriyi belirtir. |

### clearGamma() {#clearGamma--}
```
public void clearGamma()
```


Varsayılan kategori için gama düzeltmesini devre dışı bırakır.

### clearGamma(int type) {#clearGamma-int-}
```
public void clearGamma(int type)
```


Belirtilen kategori için gama düzeltmesini devre dışı bırakır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tür | int | `Aspose.Imaging.ColorAdjustType` öğesi; gama düzeltmesinin devre dışı bırakıldığı kategoriyi belirtir. |

### setNoOp() {#setNoOp--}
```
public void setNoOp()
```


Varsayılan kategori için renk ayarını kapatır.

### setNoOp(int type) {#setNoOp-int-}
```
public void setNoOp(int type)
```


Belirtilen kategori için renk ayarını kapatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tür | int | `Aspose.Imaging.ColorAdjustType` öğesi; renk düzeltmesinin kapatıldığı kategoriyi belirtir. |

### clearNoOp() {#clearNoOp--}
```
public void clearNoOp()
```


Varsayılan kategori için NoOp ayarını temizler.

### clearNoOp(int type) {#clearNoOp-int-}
```
public void clearNoOp(int type)
```


Belirtilen kategori için NoOp ayarını temizler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tür | int | `Aspose.Imaging.ColorAdjustType` öğesi; NoOp ayarının temizlendiği kategoriyi belirtir. |

### setColorKey(Color colorLow, Color colorHigh) {#setColorKey-com.aspose.imaging.Color-com.aspose.imaging.Color-}
```
public void setColorKey(Color colorLow, Color colorHigh)
```


Varsayılan kategori için renk anahtarını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| colorLow | [Color](../../com.aspose.imaging/color) | Düşük renk anahtarı değeri. |
| colorHigh | [Color](../../com.aspose.imaging/color) | Yüksek renk anahtarı değeri. |

### setColorKey(Color colorLow, Color colorHigh, int type) {#setColorKey-com.aspose.imaging.Color-com.aspose.imaging.Color-int-}
```
public void setColorKey(Color colorLow, Color colorHigh, int type)
```


Belirtilen kategori için renk anahtarını (şeffaflık aralığı) ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| colorLow | [Color](../../com.aspose.imaging/color) | Düşük renk anahtarı değeri. |
| colorHigh | [Color](../../com.aspose.imaging/color) | Yüksek renk anahtarı değeri. |
| tür | int | `Aspose.Imaging.ColorAdjustType` öğesi; renk anahtarının ayarlandığı kategoriyi belirtir. |

### clearColorKey() {#clearColorKey--}
```
public void clearColorKey()
```


Varsayılan kategori için renk anahtarını (şeffaflık aralığı) temizler.

### clearColorKey(int type) {#clearColorKey-int-}
```
public void clearColorKey(int type)
```


Belirtilen kategori için renk anahtarını (şeffaflık aralığı) temizler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tür | int | `Aspose.Imaging.ColorAdjustType` öğesi; renk anahtarının temizlendiği kategoriyi belirtir. |

### setOutputChannel(int flags) {#setOutputChannel-int-}
```
public void setOutputChannel(int flags)
```


Varsayılan kategori için CMYK (camgöbeği-mor-sarı-siyah) çıkış kanalını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bayraklar | int | `Aspose.Imaging.ColorChannelFlag` öğesi; çıkış kanalını belirtir. |

### setOutputChannel(int flags, int type) {#setOutputChannel-int-int-}
```
public void setOutputChannel(int flags, int type)
```


Belirli bir kategori için CMYK (cyan-magenta-yellow-black) çıkış kanalını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bayraklar | int | `Aspose.Imaging.ColorChannelFlag` öğesi; çıkış kanalını belirtir. |
| tür | int | `Aspose.Imaging.ColorAdjustType` öğesi; çıkış kanalının ayarlandığı kategoriyi belirtir. |

### clearOutputChannel() {#clearOutputChannel--}
```
public void clearOutputChannel()
```


Varsayılan kategori için CMYK (cyan-magenta-yellow-black) çıkış kanalı ayarını temizler.

### clearOutputChannel(int type) {#clearOutputChannel-int-}
```
public void clearOutputChannel(int type)
```


Belirli bir kategori için (cyan-magenta-yellow-black) çıkış kanalı ayarını temizler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tür | int | `Aspose.Imaging.ColorAdjustType` öğesi; çıkış kanalı ayarının temizlendiği kategoriyi belirtir. |

### setOutputChannelColorProfile(String colorProfileFilename) {#setOutputChannelColorProfile-java.lang.String-}
```
public void setOutputChannelColorProfile(String colorProfileFilename)
```


Varsayılan kategori için çıkış kanalı renk profili dosyasını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| colorProfileFilename | java.lang.String | Bir renk profili dosyasının yol adı. Renk profili dosyası %SystemRoot%\\System32\\Spool\\Drivers\\Color dizininde ise, bu parametre dosya adı olabilir. Aksi takdirde, bu parametre tam nitelikli yol adı olmalıdır. |

### setOutputChannelColorProfile(String colorProfileFilename, int type) {#setOutputChannelColorProfile-java.lang.String-int-}
```
public void setOutputChannelColorProfile(String colorProfileFilename, int type)
```


Belirli bir kategori için çıkış kanalı renk profili dosyasını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| colorProfileFilename | java.lang.String | Bir renk profili dosyasının yol adı. Renk profili dosyası %SystemRoot%\\System32\\Spool\\Drivers\\Color dizininde ise, bu parametre dosya adı olabilir. Aksi takdirde, bu parametre tam nitelikli yol adı olmalıdır. |
| tür | int | `Aspose.Imaging.ColorAdjustType` öğesi; çıkış kanalının renk profili dosyasının ayarlandığı kategoriyi belirtir. |

### clearOutputChannelColorProfile() {#clearOutputChannelColorProfile--}
```
public void clearOutputChannelColorProfile()
```


Varsayılan kategori için çıkış kanalı renk profili ayarını temizler.

### clearOutputChannelColorProfile(int type) {#clearOutputChannelColorProfile-int-}
```
public void clearOutputChannelColorProfile(int type)
```


Belirli bir kategori için çıkış kanalı renk profili ayarını temizler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tür | int | `Aspose.Imaging.ColorAdjustType` öğesi; çıkış kanalının profil ayarının temizlendiği kategoriyi belirtir. |

### setRemapTable(ColorMap[] map) {#setRemapTable-com.aspose.imaging.ColorMap---}
```
public void setRemapTable(ColorMap[] map)
```


Varsayılan kategori için renk yeniden eşleme tablosunu ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| map | [ColorMap\[\]](../../com.aspose.imaging/colormap) | `com.aspose.imaging.ColorMap` türünde renk çiftlerinden oluşan bir dizi. Her renk çifti, mevcut bir rengi (ilk değer) ve ona eşlenecek rengi (ikinci değer) içerir. |

### setRemapTable(ColorMap[] map, int type) {#setRemapTable-com.aspose.imaging.ColorMap---int-}
```
public void setRemapTable(ColorMap[] map, int type)
```


Belirli bir kategori için renk yeniden eşleme tablosunu ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| map | [ColorMap\[\]](../../com.aspose.imaging/colormap) | `com.aspose.imaging.ColorMap` türünde renk çiftlerinden oluşan bir dizi. Her renk çifti, mevcut bir rengi (ilk değer) ve ona eşlenecek rengi (ikinci değer) içerir. |
| tür | int | `Aspose.Imaging.ColorAdjustType` öğesi; renk yeniden eşleme tablosunun ayarlandığı kategoriyi belirtir. |

### clearRemapTable() {#clearRemapTable--}
```
public void clearRemapTable()
```


Varsayılan kategori için renk yeniden eşleme tablosunu temizler.

### clearRemapTable(int type) {#clearRemapTable-int-}
```
public void clearRemapTable(int type)
```


Belirli bir kategori için renk yeniden eşleme tablosunu temizler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tür | int | `Aspose.Imaging.ColorAdjustType` öğesi; yeniden eşleme tablosunun temizlendiği kategoriyi belirtir. |

### setBrushRemapTable(ColorMap[] map) {#setBrushRemapTable-com.aspose.imaging.ColorMap---}
```
public void setBrushRemapTable(ColorMap[] map)
```


Fırça kategorisi için renk yeniden eşleme tablosunu ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| map | [ColorMap\[\]](../../com.aspose.imaging/colormap) | `com.aspose.imaging.ColorMap` nesnelerinden oluşan bir dizi. |

### clearBrushRemapTable() {#clearBrushRemapTable--}
```
public void clearBrushRemapTable()
```


Bu `com.aspose.imaging.ImageAttributes` nesnesinin fırça renk yeniden eşleme tablosunu temizler.

### setWrapMode(int mode) {#setWrapMode-int-}
```
public void setWrapMode(int mode)
```


Bir şekil üzerinde veya şekil sınırlarında bir dokunun nasıl döşeneceğini belirlemek için kullanılan sarma modunu ayarlar. Doku, dolduracağı şekilden daha küçük olduğunda, şekli doldurmak için döşenir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mod | int | Bir `Aspose.Imaging.WrapMode` öğesi, bir görüntünün yinelenen kopyalarının bir alanı döşemek için nasıl kullanıldığını belirtir. |

### setWrapMode(int mode, Color color) {#setWrapMode-int-com.aspose.imaging.Color-}
```
public void setWrapMode(int mode, Color color)
```


Bir dokunun bir şekil boyunca veya şekil sınırlarında nasıl döşeneceğine karar vermek için kullanılan sarma modunu ve rengi ayarlar. Doku, doldurduğu şekilden daha küçük olduğunda, şekli doldurmak için şekil boyunca döşenir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mod | int | Bir `Aspose.Imaging.WrapMode` öğesi, bir görüntünün yinelenen kopyalarının bir alanı döşemek için nasıl kullanıldığını belirtir. |
| color | [Color](../../com.aspose.imaging/color) | Bir `com.aspose.imaging.ImageAttributes` nesnesi, oluşturulan bir görüntünün dışındaki piksellerin rengini belirtir. Bu renk, mod parametresi `WrapMode.Clamp` olarak ayarlandığında ve DrawImage'e geçirilen kaynak dikdörtgen görüntünün kendisinden daha büyük olduğunda görünür. |

### setWrapMode(int mode, Color color, boolean clamp) {#setWrapMode-int-com.aspose.imaging.Color-boolean-}
```
public void setWrapMode(int mode, Color color, boolean clamp)
```


Bir dokunun bir şekil boyunca veya şekil sınırlarında nasıl döşeneceğine karar vermek için kullanılan sarma modunu ve rengi ayarlar. Doku, doldurduğu şekilden daha küçük olduğunda, şekli doldurmak için şekil boyunca döşenir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mod | int | Bir `Aspose.Imaging.WrapMode` öğesi, bir görüntünün yinelenen kopyalarının bir alanı döşemek için nasıl kullanıldığını belirtir. |
| color | [Color](../../com.aspose.imaging/color) | Oluşturulan bir görüntünün dışındaki piksellerin rengini belirten bir renk nesnesi. Bu renk, mod parametresi `WrapMode.Clamp` olarak ayarlandığında ve DrawImage'e geçirilen kaynak dikdörtgen görüntünün kendisinden daha büyük olduğunda görünür. |
| clamp | boolean | Bu parametrenin hiçbir etkisi yoktur. False olarak ayarlayın. |

### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| o | java.lang.Object |  |

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int
