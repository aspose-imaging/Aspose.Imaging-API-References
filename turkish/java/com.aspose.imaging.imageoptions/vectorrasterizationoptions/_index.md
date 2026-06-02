---
title: "VectorRasterizationOptions"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Vektör rasterleştirme seçenekleri."
type: docs
weight: 52
url: /tr/java/com.aspose.imaging.imageoptions/vectorrasterizationoptions/
---
**Inheritance:**
java.lang.Object
```
public class VectorRasterizationOptions
```

Vektör rasterleştirme seçenekleri. Lütfen, Aspose.Imaging 24.12 sürümünden itibaren [VectorRasterizationOptions](../../com.aspose.imaging.imageoptions/vectorrasterizationoptions) artık [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) sınıfından türemeyeceğini unutmayın.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [VectorRasterizationOptions()](#VectorRasterizationOptions--) |  |
| [VectorRasterizationOptions(VectorRasterizationOptions imageOptions)](#VectorRasterizationOptions-com.aspose.imaging.imageoptions.VectorRasterizationOptions-) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getSmoothingMode()](#getSmoothingMode--) | Düzleştirme modunu alır. |
| [setSmoothingMode(int value)](#setSmoothingMode-int-) | Düzleştirme modunu ayarlar. |
| [getBorderX()](#getBorderX--) | X kenarını alır veya ayarlar. |
| [setBorderX(float value)](#setBorderX-float-) | X kenarını alır veya ayarlar. |
| [getBorderY()](#getBorderY--) | Y kenarını alır veya ayarlar. |
| [setBorderY(float value)](#setBorderY-float-) | Y kenarını alır veya ayarlar. |
| [getCenterDrawing()](#getCenterDrawing--) | Merkez çizim olup olmadığını gösteren bir değeri alır. |
| [setCenterDrawing(boolean value)](#setCenterDrawing-boolean-) | Merkez çizimini gösterip göstermediğini belirten bir değeri ayarlar. |
| [getPageHeight()](#getPageHeight--) | Sayfa yüksekliğini alır. |
| [setPageHeight(float value)](#setPageHeight-float-) | Sayfa yüksekliğini ayarlar. |
| [getPageSize()](#getPageSize--) | Sayfa boyutunu alır. |
| [setPageSize(SizeF value)](#setPageSize-com.aspose.imaging.SizeF-) | Sayfa boyutunu ayarlar. |
| [getPageWidth()](#getPageWidth--) | Sayfa genişliğini alır. |
| [setPageWidth(float value)](#setPageWidth-float-) | Sayfa genişliğini ayarlar. |
| [getBackgroundColor()](#getBackgroundColor--) | Arka plan rengini alır. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.imaging.Color-) | Arka plan rengini ayarlar. |
| [getDrawColor()](#getDrawColor--) | Ön plan rengini alır. |
| [setDrawColor(Color value)](#setDrawColor-com.aspose.imaging.Color-) | Ön plan rengini ayarlar. |
| [getTextRenderingHint()](#getTextRenderingHint--) | Metin renderleme ipucunu alır. |
| [setTextRenderingHint(int value)](#setTextRenderingHint-int-) | Metin renderleme ipucunu ayarlar. |
| [getPositioning()](#getPositioning--) | Konumlandırmayı alır. |
| [setPositioning(int value)](#setPositioning-int-) | Konumlandırmayı ayarlar. |
| [getReplaceTextMapping()](#getReplaceTextMapping--) | Metin değiştirme eşlemesini alır. |
| [setReplaceTextMapping(HashMap<String,String> value)](#setReplaceTextMapping-java.util.HashMap-java.lang.String-java.lang.String--) | Metin değiştirme eşlemesini ayarlar. |
| [copyTo(VectorRasterizationOptions vectorRasterizationOptions)](#copyTo-com.aspose.imaging.imageoptions.VectorRasterizationOptions-) | Bu örneği `vectorRasterizationOptions`'a kopyalar. |
| [deepClone()](#deepClone--) | Nesnenin yüzeysel bir klonunu oluşturur. |
### VectorRasterizationOptions() {#VectorRasterizationOptions--}
```
public VectorRasterizationOptions()
```


### VectorRasterizationOptions(VectorRasterizationOptions imageOptions) {#VectorRasterizationOptions-com.aspose.imaging.imageoptions.VectorRasterizationOptions-}
```
public VectorRasterizationOptions(VectorRasterizationOptions imageOptions)
```


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| imageOptions | [VectorRasterizationOptions](../../com.aspose.imaging.imageoptions/vectorrasterizationoptions) |  |

### getSmoothingMode() {#getSmoothingMode--}
```
public final int getSmoothingMode()
```


Düzleştirme modunu alır.

**Returns:**
int - yumuşatma modu.
### setSmoothingMode(int value) {#setSmoothingMode-int-}
```
public final void setSmoothingMode(int value)
```


Düzleştirme modunu ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | yumuşatma modu. |


**Example: This example shows how to load an SVG image from a file and rasterize it to PNG using various options.**

``` java
String dir = "c:\\temp\\";

// Aspose.Imaging.Image.Load kullanmak, görüntü yüklemenin birleşik bir yoludur.
com.aspose.imaging.fileformats.svg.SvgImage svgImage = (com.aspose.imaging.fileformats.svg.SvgImage) com.aspose.imaging.Image.load(dir + "test.svg");
try {
    // SVG'yi rasterleştirmek için rasterleştirme seçeneklerini belirtmemiz gerekir.
    com.aspose.imaging.imageoptions.SvgRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.SvgRasterizationOptions();

    // Bir görüntü için arka planın varsayılan rengini ayarlayın. Varsayılan değer beyazdır.
    rasterizationOptions.setBackgroundColor(com.aspose.imaging.Color.getGray());

    // Sayfa boyutunu ayarla
    rasterizationOptions.setPageSize(new com.aspose.imaging.SizeF(svgImage.getWidth(), svgImage.getHeight()));

    // Antialiasing, çizgilere, eğrilere ve doldurulmuş alanların kenarlarına uygulanır.
    rasterizationOptions.setSmoothingMode(com.aspose.imaging.SmoothingMode.AntiAlias);

    // Her karakter, ipucu olmadan antialias'li glif bitmap'i kullanılarak çizilir.
    rasterizationOptions.setTextRenderingHint(com.aspose.imaging.TextRenderingHint.AntiAlias);

    // Görüntü boyutunu 10 kat küçültün, yani çıktı boyutu orijinal boyutun %10'u olacaktır.
    rasterizationOptions.setScaleX(0.1f);
    rasterizationOptions.setScaleY(0.1f);

    com.aspose.imaging.imageoptions.PngOptions saveOptions = new com.aspose.imaging.imageoptions.PngOptions();
    saveOptions.setVectorRasterizationOptions(rasterizationOptions);

    // PNG dosyasına kaydet
    svgImage.save(dir + "test.output.png", saveOptions);
} finally {
    svgImage.dispose();
}
```

### getBorderX() {#getBorderX--}
```
public float getBorderX()
```


X kenarını alır veya ayarlar.

**Returns:**
float - Kenar X.
### setBorderX(float value) {#setBorderX-float-}
```
public void setBorderX(float value)
```


X kenarını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float | Kenar X. |

### getBorderY() {#getBorderY--}
```
public float getBorderY()
```


Y kenarını alır veya ayarlar.

**Returns:**
float - Kenar Y.
### setBorderY(float value) {#setBorderY-float-}
```
public void setBorderY(float value)
```


Y kenarını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float | Kenar Y. |

### getCenterDrawing() {#getCenterDrawing--}
```
public boolean getCenterDrawing()
```


Merkez çizim olup olmadığını gösteren bir değeri alır.

**Returns:**
boolean - merkez çizimini gösterip göstermediğini belirten bir değer.
### setCenterDrawing(boolean value) {#setCenterDrawing-boolean-}
```
public void setCenterDrawing(boolean value)
```


Merkez çizimini gösterip göstermediğini belirten bir değeri ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | merkez çizimini gösterip göstermediğini belirten bir değer. |

### getPageHeight() {#getPageHeight--}
```
public float getPageHeight()
```


Sayfa yüksekliğini alır.

**Returns:**
float - sayfa yüksekliği.
### setPageHeight(float value) {#setPageHeight-float-}
```
public void setPageHeight(float value)
```


Sayfa yüksekliğini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float | sayfa yüksekliği. |

### getPageSize() {#getPageSize--}
```
public SizeF getPageSize()
```


Sayfa boyutunu alır.

**Returns:**
[SizeF](../../com.aspose.imaging/sizef) - the page size.
### setPageSize(SizeF value) {#setPageSize-com.aspose.imaging.SizeF-}
```
public void setPageSize(SizeF value)
```


Sayfa boyutunu ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.imaging/sizef) | sayfa boyutu. |


**Example: This example shows how to load a WMF image from a file and convert it to SVG using WmfRasterizationOptions.**

``` java
String dir = "c:\\temp\\";

// Aspose.Imaging.Image.Load kullanmak, WMF dahil tüm görüntü türlerini yüklemenin birleşik bir yoludur.
try (com.aspose.imaging.fileformats.wmf.WmfImage wmfImage = (com.aspose.imaging.fileformats.wmf.WmfImage)com.aspose.imaging.Image.load(dir + "test.wmf"))
{
    com.aspose.imaging.imageoptions.SvgOptions saveOptions = new com.aspose.imaging.imageoptions.SvgOptions();
                    
    // Metin şekillere dönüştürülecek.
    saveOptions.setTextAsShapes(true);

    com.aspose.imaging.imageoptions.WmfRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.WmfRasterizationOptions();

    // Çizim yüzeyinin arka plan rengi.
    rasterizationOptions.setBackgroundColor(com.aspose.imaging.Color.getWhiteSmoke());

    // Sayfa boyutu.
    rasterizationOptions.setPageSize(Size.to_SizeF(wmfImage.getSize()));

    // Gömülü emf varsa emf işlenir; aksi takdirde wmf işlenir.
    rasterizationOptions.setRenderMode(com.aspose.imaging.fileformats.wmf.WmfRenderMode.Auto);

    saveOptions.setVectorRasterizationOptions(rasterizationOptions);

    wmfImage.save(dir + "test.output.svg", saveOptions);
}
```


**Example: This example shows how to load a EMF image from a file and convert it to SVG using EmfRasterizationOptions.**

``` java
String dir = "c:\\temp\\";

// Aspose.Imaging.Image.Load kullanmak, EMF dahil tüm görüntü türlerini yüklemenin birleşik bir yoludur.
com.aspose.imaging.fileformats.emf.EmfImage emfImage = (com.aspose.imaging.fileformats.emf.EmfImage) com.aspose.imaging.Image.load(dir + "test.emf");
try {
    com.aspose.imaging.imageoptions.SvgOptions saveOptions = new com.aspose.imaging.imageoptions.SvgOptions();

    // Metin şekillere dönüştürülecek.
    saveOptions.setTextAsShapes(true);

    com.aspose.imaging.imageoptions.EmfRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.EmfRasterizationOptions();

    // Çizim yüzeyinin arka plan rengi.
    rasterizationOptions.setBackgroundColor(com.aspose.imaging.Color.getWhiteSmoke());

    // Sayfa boyutu.
    rasterizationOptions.setPageSize(new com.aspose.imaging.SizeF(emfImage.getWidth(), emfImage.getHeight()));

    // Gömülü emf varsa emf işlenir; aksi takdirde wmf işlenir.
    rasterizationOptions.setRenderMode(com.aspose.imaging.fileformats.emf.EmfRenderMode.Auto);

    // Yatay kenar boşluğunu ayarlayın
    rasterizationOptions.setBorderX(50);

    // Dikey kenar boşluğunu ayarlayın
    rasterizationOptions.setBorderY(50);

    saveOptions.setVectorRasterizationOptions(rasterizationOptions);

    emfImage.save(dir + "test.output.svg", saveOptions);
} finally {
    emfImage.dispose();
}
```

### getPageWidth() {#getPageWidth--}
```
public float getPageWidth()
```


Sayfa genişliğini alır.

**Returns:**
float - sayfa genişliği.
### setPageWidth(float value) {#setPageWidth-float-}
```
public void setPageWidth(float value)
```


Sayfa genişliğini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float | sayfa genişliği. |

### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Arka plan rengini alır.

**Returns:**
[Color](../../com.aspose.imaging/color) - a background color.
### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.imaging.Color-}
```
public void setBackgroundColor(Color value)
```


Arka plan rengini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | bir arka plan rengi. |


**Example: This example shows how to load a WMF image from a file and convert it to SVG using WmfRasterizationOptions.**

``` java
String dir = "c:\\temp\\";

// Aspose.Imaging.Image.Load kullanmak, WMF dahil tüm görüntü türlerini yüklemenin birleşik bir yoludur.
try (com.aspose.imaging.fileformats.wmf.WmfImage wmfImage = (com.aspose.imaging.fileformats.wmf.WmfImage)com.aspose.imaging.Image.load(dir + "test.wmf"))
{
    com.aspose.imaging.imageoptions.SvgOptions saveOptions = new com.aspose.imaging.imageoptions.SvgOptions();
                    
    // Metin şekillere dönüştürülecek.
    saveOptions.setTextAsShapes(true);

    com.aspose.imaging.imageoptions.WmfRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.WmfRasterizationOptions();

    // Çizim yüzeyinin arka plan rengi.
    rasterizationOptions.setBackgroundColor(com.aspose.imaging.Color.getWhiteSmoke());

    // Sayfa boyutu.
    rasterizationOptions.setPageSize(Size.to_SizeF(wmfImage.getSize()));

    // Gömülü emf varsa emf işlenir; aksi takdirde wmf işlenir.
    rasterizationOptions.setRenderMode(com.aspose.imaging.fileformats.wmf.WmfRenderMode.Auto);

    saveOptions.setVectorRasterizationOptions(rasterizationOptions);

    wmfImage.save(dir + "test.output.svg", saveOptions);
}
```


**Example: This example shows how to load a EMF image from a file and convert it to SVG using EmfRasterizationOptions.**

``` java
String dir = "c:\\temp\\";

// Aspose.Imaging.Image.Load kullanmak, EMF dahil tüm görüntü türlerini yüklemenin birleşik bir yoludur.
com.aspose.imaging.fileformats.emf.EmfImage emfImage = (com.aspose.imaging.fileformats.emf.EmfImage) com.aspose.imaging.Image.load(dir + "test.emf");
try {
    com.aspose.imaging.imageoptions.SvgOptions saveOptions = new com.aspose.imaging.imageoptions.SvgOptions();

    // Metin şekillere dönüştürülecek.
    saveOptions.setTextAsShapes(true);

    com.aspose.imaging.imageoptions.EmfRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.EmfRasterizationOptions();

    // Çizim yüzeyinin arka plan rengi.
    rasterizationOptions.setBackgroundColor(com.aspose.imaging.Color.getWhiteSmoke());

    // Sayfa boyutu.
    rasterizationOptions.setPageSize(new com.aspose.imaging.SizeF(emfImage.getWidth(), emfImage.getHeight()));

    // Gömülü emf varsa emf işlenir; aksi takdirde wmf işlenir.
    rasterizationOptions.setRenderMode(com.aspose.imaging.fileformats.emf.EmfRenderMode.Auto);

    // Yatay kenar boşluğunu ayarlayın
    rasterizationOptions.setBorderX(50);

    // Dikey kenar boşluğunu ayarlayın
    rasterizationOptions.setBorderY(50);

    saveOptions.setVectorRasterizationOptions(rasterizationOptions);

    emfImage.save(dir + "test.output.svg", saveOptions);
} finally {
    emfImage.dispose();
}
```

### getDrawColor() {#getDrawColor--}
```
public Color getDrawColor()
```


Ön plan rengini alır.

**Returns:**
[Color](../../com.aspose.imaging/color) - a foreground color.
### setDrawColor(Color value) {#setDrawColor-com.aspose.imaging.Color-}
```
public void setDrawColor(Color value)
```


Ön plan rengini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | bir ön plan rengi. |

### getTextRenderingHint() {#getTextRenderingHint--}
```
public final int getTextRenderingHint()
```


Metin renderleme ipucunu alır.

Değer: Metin renderleme ipucu.

**Returns:**
int - metin renderleme ipucu.
### setTextRenderingHint(int value) {#setTextRenderingHint-int-}
```
public final void setTextRenderingHint(int value)
```


Metin renderleme ipucunu ayarlar.

Değer: Metin renderleme ipucu.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | metin renderleme ipucu. |


**Example: This example shows how to load an SVG image from a file and rasterize it to PNG using various options.**

``` java
String dir = "c:\\temp\\";

// Aspose.Imaging.Image.Load kullanmak, görüntü yüklemenin birleşik bir yoludur.
com.aspose.imaging.fileformats.svg.SvgImage svgImage = (com.aspose.imaging.fileformats.svg.SvgImage) com.aspose.imaging.Image.load(dir + "test.svg");
try {
    // SVG'yi rasterleştirmek için rasterleştirme seçeneklerini belirtmemiz gerekir.
    com.aspose.imaging.imageoptions.SvgRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.SvgRasterizationOptions();

    // Bir görüntü için arka planın varsayılan rengini ayarlayın. Varsayılan değer beyazdır.
    rasterizationOptions.setBackgroundColor(com.aspose.imaging.Color.getGray());

    // Sayfa boyutunu ayarla
    rasterizationOptions.setPageSize(new com.aspose.imaging.SizeF(svgImage.getWidth(), svgImage.getHeight()));

    // Antialiasing, çizgilere, eğrilere ve doldurulmuş alanların kenarlarına uygulanır.
    rasterizationOptions.setSmoothingMode(com.aspose.imaging.SmoothingMode.AntiAlias);

    // Her karakter, ipucu olmadan antialias'li glif bitmap'i kullanılarak çizilir.
    rasterizationOptions.setTextRenderingHint(com.aspose.imaging.TextRenderingHint.AntiAlias);

    // Görüntü boyutunu 10 kat küçültün, yani çıktı boyutu orijinal boyutun %10'u olacaktır.
    rasterizationOptions.setScaleX(0.1f);
    rasterizationOptions.setScaleY(0.1f);

    com.aspose.imaging.imageoptions.PngOptions saveOptions = new com.aspose.imaging.imageoptions.PngOptions();
    saveOptions.setVectorRasterizationOptions(rasterizationOptions);

    // PNG dosyasına kaydet
    svgImage.save(dir + "test.output.png", saveOptions);
} finally {
    svgImage.dispose();
}
```

### getPositioning() {#getPositioning--}
```
public final int getPositioning()
```


Konumlandırmayı alır.

Değer: Konumlandırma.

**Returns:**
int - konumlandırma.
### setPositioning(int value) {#setPositioning-int-}
```
public final void setPositioning(int value)
```


Konumlandırmayı ayarlar.

Değer: Konumlandırma.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | konumlandırma. |

### getReplaceTextMapping() {#getReplaceTextMapping--}
```
public final HashMap<String,String> getReplaceTextMapping()
```


Metin değiştirme eşlemesini alır.

Değer: Metin değiştirme eşlemesi.

**Returns:**
java.util.HashMap<java.lang.String,java.lang.String> - metin değiştirme eşlemesi.
### setReplaceTextMapping(HashMap<String,String> value) {#setReplaceTextMapping-java.util.HashMap-java.lang.String-java.lang.String--}
```
public final void setReplaceTextMapping(HashMap<String,String> value)
```


Metin değiştirme eşlemesini ayarlar.

Değer: Metin değiştirme eşlemesi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.util.HashMap<java.lang.String,java.lang.String> | metin değiştirme eşlemesi. |

### copyTo(VectorRasterizationOptions vectorRasterizationOptions) {#copyTo-com.aspose.imaging.imageoptions.VectorRasterizationOptions-}
```
public void copyTo(VectorRasterizationOptions vectorRasterizationOptions)
```


Bu örneği `vectorRasterizationOptions`'a kopyalar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| vectorRasterizationOptions | [VectorRasterizationOptions](../../com.aspose.imaging.imageoptions/vectorrasterizationoptions) | Vektör rasterleştirme seçenekleri. |

### deepClone() {#deepClone--}
```
public VectorRasterizationOptions deepClone()
```


Nesnenin yüzeysel bir klonunu oluşturur.

**Returns:**
[VectorRasterizationOptions](../../com.aspose.imaging.imageoptions/vectorrasterizationoptions) - The shallow clone of object.
