---
title: "EmfRasterizationOptions"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EMF rasterleştirme seçenekleri."
type: docs
weight: 20
url: /tr/java/com.aspose.imaging.imageoptions/emfrasterizationoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imageoptions.VectorRasterizationOptions](../../com.aspose.imaging.imageoptions/vectorrasterizationoptions), [com.aspose.imaging.imageoptions.MetafileRasterizationOptions](../../com.aspose.imaging.imageoptions/metafilerasterizationoptions)
```
public class EmfRasterizationOptions extends MetafileRasterizationOptions
```

EMF rasterleştirme seçenekleri.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfRasterizationOptions()](#EmfRasterizationOptions--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getRenderMode()](#getRenderMode--) | Render modunu alır veya ayarlar. |
| [setRenderMode(int value)](#setRenderMode-int-) | Render modunu alır veya ayarlar. |
| [copyTo(VectorRasterizationOptions vectorRasterizationOptions)](#copyTo-com.aspose.imaging.imageoptions.VectorRasterizationOptions-) | Bunu `vectorRasterizationOptions` öğesine kopyalar. |
### EmfRasterizationOptions() {#EmfRasterizationOptions--}
```
public EmfRasterizationOptions()
```


### getRenderMode() {#getRenderMode--}
```
public int getRenderMode()
```


Render modunu alır veya ayarlar.

**Returns:**
int - Render modu.
### setRenderMode(int value) {#setRenderMode-int-}
```
public void setRenderMode(int value)
```


Render modunu alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Render modu. |


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

### copyTo(VectorRasterizationOptions vectorRasterizationOptions) {#copyTo-com.aspose.imaging.imageoptions.VectorRasterizationOptions-}
```
public void copyTo(VectorRasterizationOptions vectorRasterizationOptions)
```


Bunu `vectorRasterizationOptions` öğesine kopyalar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| vectorRasterizationOptions | [VectorRasterizationOptions](../../com.aspose.imaging.imageoptions/vectorrasterizationoptions) | vectorRasterizationOptions |

