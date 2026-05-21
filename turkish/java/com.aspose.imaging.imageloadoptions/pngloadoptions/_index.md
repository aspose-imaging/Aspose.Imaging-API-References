---
title: "PngLoadOptions"
second_title: "Aspose.Imaging for Java API Referansı"
description: "png yükleme seçenekleri."
type: docs
weight: 18
url: /tr/java/com.aspose.imaging.imageloadoptions/pngloadoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.LoadOptions](../../com.aspose.imaging/loadoptions)
```
public class PngLoadOptions extends LoadOptions
```

png yükleme seçenekleri.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [PngLoadOptions()](#PngLoadOptions--) | Yeni bir `PngLoadOptions` sınıfı örneği başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getStrictMode()](#getStrictMode--) | Sıkı modun etkin olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [setStrictMode(boolean value)](#setStrictMode-boolean-) | Sıkı modun etkin olup olmadığını gösteren bir değeri alır veya ayarlar. |
### PngLoadOptions() {#PngLoadOptions--}
```
public PngLoadOptions()
```


Yeni bir `PngLoadOptions` sınıfı örneği başlatır.

### getStrictMode() {#getStrictMode--}
```
public boolean getStrictMode()
```


Sıkı modun etkin olup olmadığını gösteren bir değeri alır veya ayarlar.

**Returns:**
boolean - sıkı modun etkin olup olmadığını gösteren bir değer.
### setStrictMode(boolean value) {#setStrictMode-boolean-}
```
public void setStrictMode(boolean value)
```


Sıkı modun etkin olup olmadığını gösteren bir değeri alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | sıkı modun etkin olup olmadığını gösteren bir değer. |


**Example: The following example shows how to read PNG file : a strict mode.**
Aşağıdaki örnek, PNG dosyasını nasıl okuyacağınızı gösterir: sıkı mod. Sıkı mod, potansiyel sorunları bulmayı sağlar: PNG görüntüleri, ör. tanınmayan veri blokları, beklenmeyen dosya sonu. Bu tür dosyalar hâlâ varsayılan (sıkı olmayan) modda Aspose.Imaging ve yaygın görüntüleyiciler tarafından açılabilir. Ancak onları açma girişimleri: sıkı modda ilgili bir istisna oluşturur.
``` java
String dir = "c:\\aspose.imaging\\java\\issues\\1442\\";
String inputImage = dir + "FC5F1998104EB92469CB14070628073616BB28F9.png";
String outputImage = inputImage + ".png";

// Varsayılan mod (sıkı olmayan) - başarılı okuma.
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputImage);
try {
    image.save(outputImage, new com.aspose.imaging.imageoptions.PngOptions());
}
finally {
    image.close();
}

// Sıkı mod - ImageLoadException : Beklenmeyen dosya sonu.
com.aspose.imaging.Image image2 = com.aspose.imaging.Image.load(inputImage, new com.aspose.imaging.imageloadoptions.PngLoadOptions() {{
    setStrictMode(true);
    }});
                
try {
    image2.save(outputImage, new com.aspose.imaging.imageoptions.PngOptions());
}
finally {
    image2.close();
}
```

