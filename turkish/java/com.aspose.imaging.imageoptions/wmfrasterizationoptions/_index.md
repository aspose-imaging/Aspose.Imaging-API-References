---
title: "WmfRasterizationOptions"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Wmf rasterleştirme seçenekleri."
type: docs
weight: 55
url: /tr/java/com.aspose.imaging.imageoptions/wmfrasterizationoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imageoptions.VectorRasterizationOptions](../../com.aspose.imaging.imageoptions/vectorrasterizationoptions), [com.aspose.imaging.imageoptions.MetafileRasterizationOptions](../../com.aspose.imaging.imageoptions/metafilerasterizationoptions)
```
public class WmfRasterizationOptions extends MetafileRasterizationOptions
```

Wmf rasterleştirme seçenekleri.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [WmfRasterizationOptions()](#WmfRasterizationOptions--) | Yeni bir `WmfRasterizationOptions` sınıfı örneği başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getRenderMode()](#getRenderMode--) | WMF render modunu alır veya ayarlar. |
| [setRenderMode(int value)](#setRenderMode-int-) | WMF render modunu alır veya ayarlar. |
| [copyTo(VectorRasterizationOptions vectorRasterizationOptions)](#copyTo-com.aspose.imaging.imageoptions.VectorRasterizationOptions-) | Bunu `vectorRasterizationOptions` öğesine kopyalar. |
### WmfRasterizationOptions() {#WmfRasterizationOptions--}
```
public WmfRasterizationOptions()
```


Yeni bir `WmfRasterizationOptions` sınıfı örneği başlatır.

### getRenderMode() {#getRenderMode--}
```
public int getRenderMode()
```


WMF render modunu alır veya ayarlar.

Değer: WMF render modu.

**Returns:**
int
### setRenderMode(int value) {#setRenderMode-int-}
```
public void setRenderMode(int value)
```


WMF render modunu alır veya ayarlar.

Değer: WMF render modu.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |


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

### copyTo(VectorRasterizationOptions vectorRasterizationOptions) {#copyTo-com.aspose.imaging.imageoptions.VectorRasterizationOptions-}
```
public void copyTo(VectorRasterizationOptions vectorRasterizationOptions)
```


Bunu `vectorRasterizationOptions` öğesine kopyalar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| vectorRasterizationOptions | [VectorRasterizationOptions](../../com.aspose.imaging.imageoptions/vectorrasterizationoptions) | vectorRasterizationOptions |

