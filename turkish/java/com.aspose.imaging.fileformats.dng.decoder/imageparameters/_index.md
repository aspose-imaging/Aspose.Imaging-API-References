---
title: "ImageParameters"
second_title: "Aspose.Imaging for Java API Referansı"
description: "DNG görüntü parametreleri"
type: docs
weight: 11
url: /tr/java/com.aspose.imaging.fileformats.dng.decoder/imageparameters/
---
**Inheritance:**
java.lang.Object
```
public class ImageParameters
```

DNG görüntü parametreleri
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getDngVersion()](#getDngVersion--) | DNG sürümünü alır. |
| [getDescription()](#getDescription--) | Renk açıklamasını alır (RGBG, RGBE, GMCY veya GBTG). |
| [getModel()](#getModel--) | Kamera modelini alır. |
| [getCameraManufacturer()](#getCameraManufacturer--) | Kamera üreticisini alır. |
| [isFoveon()](#isFoveon--) | Foveon matrisini alır. |
| [getSoftware()](#getSoftware--) | Yazılımı alır. |
| [getRawCount()](#getRawCount--) | Dosyadaki RAW görüntü sayısını alır (0, dosyanın tanınmadığını gösterir). |
| [getFilters()](#getFilters--) | Matristeki renk piksel sırasını tanımlayan bit maskesini alır. |
| [getColorsCount()](#getColorsCount--) | Renkleri alır. |
| [getXmpData()](#getXmpData--) | XMP verisini alır. |
| [getTranslationCfaDng()](#getTranslationCfaDng--) | CFA mozaik DNG formatı için çeviri dizisini alır. |

## Example: This example shows how to load a DNG image from a file, print its properties and save it to PNG.

``` java
String dir = "c:\\temp\\";
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "test.dng");
try {
    com.aspose.imaging.fileformats.dng.DngImage dngImage = (com.aspose.imaging.fileformats.dng.DngImage) image;
    com.aspose.imaging.fileformats.dng.decoder.RawData rawData = dngImage.getImgData();
    com.aspose.imaging.fileformats.dng.decoder.ImageParameters parameters = rawData.getImageDataParameters();
    if (parameters != null) {
        System.out.println("The camera manufacturer:              " + parameters.getCameraManufacturer());
        System.out.println("The camera model:                     " + parameters.getModel());
        System.out.println("The colors count:                     " + parameters.getColorsCount());
        System.out.println("The colors description:               " + parameters.getDescription());
        System.out.println("The DNG version:                      " + parameters.getDngVersion());
        System.out.println("The number of RAW images in the file: " + parameters.getRawCount());
        System.out.println("The software:                         " + parameters.getSoftware());
        System.out.println("The order of the color pixels:        " + Long.toBinaryString(parameters.getFilters()));

        String[] translationCfaDng = parameters.getTranslationCfaDng();
        if (translationCfaDng != null) {
            System.out.printf("The translation array for CFA mosaic %s:\r\n", translationCfaDng.length);
            for (String s : translationCfaDng) {
                System.out.printf("- %s\r\n", s);
            }
        }
    }

    com.aspose.imaging.fileformats.dng.decoder.ImageOtherParameters otherParameters = rawData.getImageOtherParameters();
    if (otherParameters != null) {
        // Zaman damgasını insan tarafından okunabilir bir dizeye dönüştür.
        //java.text.SimpleDateFormat sf = new java.text.SimpleDateFormat("yyyy-MM-dd");
        java.util.Date date = new java.util.Date(otherParameters.getTimestamp());
        //System.out.println(sf.format(date));

        System.out.printf("The aperture:                         " + otherParameters.getAperture());
        System.out.printf("The description:                      " + otherParameters.getDescription());
        System.out.printf("The focal length:                     " + otherParameters.getFocalLength());
        System.out.printf("The ISO sensitivity:                  " + otherParameters.getIsoSpeed());
        System.out.printf("The serial number of the image:       " + otherParameters.getShotOrder());
        System.out.printf("The shutter speed:                    " + otherParameters.getShutterSpeed());
        System.out.printf("The date of shooting:                 " + date);
    }

    // Varsayılan seçeneklerle PNG olarak dışa aktar.
    dngImage.save(dir + "test.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

// Kamera üreticisi:              Leica
// Kamera modeli:                     M8 Digital Camera
// Renk sayısı:                     3
// Renk açıklaması:               RGBG
// DNG sürümü:                      16777216
// Dosyadaki RAW görüntü sayısı: 1
// Yazılım:                         1.107
// Renk piksel sırası:        10110100101101001011010010110100
// Diyafram:                         0
// Açıklama:
// Odak uzaklığı:                     50
// ISO hassasiyeti:                  160
// Görüntünün seri numarası:       0
// Enstantane hızı:                    12
// Çekim tarihi:                 8/3/2007 3:13:49 AM
```

### getDngVersion() {#getDngVersion--}
```
public long getDngVersion()
```


DNG sürümünü alır.

Değer: DNG sürümü.

**Returns:**
long
### getDescription() {#getDescription--}
```
public String getDescription()
```


Renk açıklamasını alır (RGBG, RGBE, GMCY veya GBTG).

Değer: cdesc.

**Returns:**
java.lang.String
### getModel() {#getModel--}
```
public String getModel()
```


Kamera modelini alır.

Değer: Model.

**Returns:**
java.lang.String
### getCameraManufacturer() {#getCameraManufacturer--}
```
public String getCameraManufacturer()
```


Kamera üreticisini alır.

Değer: üretici.

**Returns:**
java.lang.String
### isFoveon() {#isFoveon--}
```
public long isFoveon()
```


Foveon matrisini alır.

Değer: foveon.

**Returns:**
long
### getSoftware() {#getSoftware--}
```
public String getSoftware()
```


Yazılımı alır.

Değer: Yazılım.

**Returns:**
java.lang.String
### getRawCount() {#getRawCount--}
```
public long getRawCount()
```


Dosyadaki RAW görüntü sayısını alır (0, dosyanın tanınmadığını gösterir).

Değer: RAW sayısı.

**Returns:**
long
### getFilters() {#getFilters--}
```
public long getFilters()
```


Matristeki renk piksel sırasını tanımlayan bit maskesini alır.

Değer: filtreler.

**Returns:**
long
### getColorsCount() {#getColorsCount--}
```
public int getColorsCount()
```


Renkleri alır.

Değer: renkler.

**Returns:**
int
### getXmpData() {#getXmpData--}
```
public String getXmpData()
```


XMP verisini alır.

Değer: XMP verileri.

**Returns:**
java.lang.String
### getTranslationCfaDng() {#getTranslationCfaDng--}
```
public String[] getTranslationCfaDng()
```


CFA mozaik DNG formatı için çeviri dizisini alır.

Değer: xtrans.

**Returns:**
java.lang.String[]
