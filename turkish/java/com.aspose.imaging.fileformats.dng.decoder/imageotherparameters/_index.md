---
title: "ImageOtherParameters"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Diğer görüntü parametreleri"
type: docs
weight: 10
url: /tr/java/com.aspose.imaging.fileformats.dng.decoder/imageotherparameters/
---
**Inheritance:**
java.lang.Object
```
public class ImageOtherParameters
```

Diğer görüntü parametreleri
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getDescription()](#getDescription--) | Görüntü açıklamasını alır. |
| [getArtist()](#getArtist--) | Görüntünün yazarını alır. |
| [getTimestamp()](#getTimestamp--) | Çekim tarihini alır. |
| [getShotOrder()](#getShotOrder--) | Görüntünün seri numarasını alır. |
| [getAperture()](#getAperture--) | Diyaframı alır. |
| [getShutterSpeed()](#getShutterSpeed--) | Deklanşör hızını alır. |
| [getGpsData()](#getGpsData--) | GPS verilerini alır. |
| [getFocalLength()](#getFocalLength--) | Odak uzunluğunu alır. |
| [getIsoSpeed()](#getIsoSpeed--) | ISO hassasiyetini alır. |

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

### getDescription() {#getDescription--}
```
public String getDescription()
```


Görüntü açıklamasını alır.

Değer: Açıklama.

**Returns:**
java.lang.String
### getArtist() {#getArtist--}
```
public String getArtist()
```


Görüntünün yazarını alır.

Değer: Sanatçı.

**Returns:**
java.lang.String
### getTimestamp() {#getTimestamp--}
```
public long getTimestamp()
```


Çekim tarihini alır.

Değer: Zaman damgası.

**Returns:**
long
### getShotOrder() {#getShotOrder--}
```
public long getShotOrder()
```


Görüntünün seri numarasını alır.

Değer: Çekim sırası.

**Returns:**
long
### getAperture() {#getAperture--}
```
public float getAperture()
```


Diyaframı alır.

Değer: Diyafram.

**Returns:**
float
### getShutterSpeed() {#getShutterSpeed--}
```
public float getShutterSpeed()
```


Deklanşör hızını alır.

Değer: Deklanşör.

**Returns:**
float
### getGpsData() {#getGpsData--}
```
public long[] getGpsData()
```


GPS verilerini alır.

Değer: GPS verileri.

**Returns:**
long[]
### getFocalLength() {#getFocalLength--}
```
public float getFocalLength()
```


Odak uzunluğunu alır.

Değer: odak uzunluğu.

**Returns:**
float
### getIsoSpeed() {#getIsoSpeed--}
```
public float getIsoSpeed()
```


ISO hassasiyetini alır.

Değer: ISO hızı.

**Returns:**
float
