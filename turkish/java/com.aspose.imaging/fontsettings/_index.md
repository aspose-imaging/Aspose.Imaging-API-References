---
title: "FontSettings"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Genel görüntü vektör formatları renderlayıcı yazı tipi ayarları."
type: docs
weight: 49
url: /tr/java/com.aspose.imaging/fontsettings/
---
**Inheritance:**
java.lang.Object
```
public final class FontSettings
```

Genel görüntü vektör formatları renderlayıcı yazı tipi ayarları.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getGetSystemAlternativeFont()](#getGetSystemAlternativeFont--) | Bir değeri alır; bu değer [get alternative font] olup olmadığını gösterir. |
| [setGetSystemAlternativeFont(boolean value)](#setGetSystemAlternativeFont-boolean-) | Bir değeri ayarlar; bu değer [get alternative font] olup olmadığını gösterir. |
| [getDefaultFontName()](#getDefaultFontName--) | Varsayılan yazı tipi adını alır. |
| [setDefaultFontName(String fontName)](#setDefaultFontName-java.lang.String-) | Varsayılan yazı tipi adını ayarlar. |
| [getFontsFolders()](#getFontsFolders--) | Aspose.Imaging'in TrueType yazı tiplerini aradığı klasörlerin listesini içeren dizinin bir kopyasını alır. |
| [getDefaultFontsFolders()](#getDefaultFontsFolders--) | Varsayılan yazı tipi klasörlerini alır. |
| [setFontsFolder(String folder)](#setFontsFolder-java.lang.String-) | `folder` için yazı tipi klasör listesini geçersiz kıl. |
| [setFontsFolders(String[] folders)](#setFontsFolders-java.lang.String---) | `folders` için yazı tipi klasör listesini geçersiz kıl. |
| [setFontsFolders(String[] folders, boolean recursive)](#setFontsFolders-java.lang.String---boolean-) | TrueType yazı tiplerinin yüklendiği klasörleri ayarlar ve tüm yüklü yazı tiplerini temizler. |
| [reset()](#reset--) | Yazı tipleri klasörünü ve varsayılan yazı tipi adını sistem varsayılanına sıfırlar. |
| [updateFonts()](#updateFonts--) | Metin katmanları içeren PSD dosyaları için yazı tipi önbelleğini günceller. |
| [addFontsFolder(String fontFolder)](#addFontsFolder-java.lang.String-) | `fontFolder`'ı yazı tipi dizin listesine ekler ve yazı tipi araması için ilk klasör olarak işaretler |
| [removeFontsFolder(String folder)](#removeFontsFolder-java.lang.String-) | `folder`'ı klasör listesinden kaldırır |
### getGetSystemAlternativeFont() {#getGetSystemAlternativeFont--}
```
public static boolean getGetSystemAlternativeFont()
```


Bir değeri alır; bu değer [get alternative font] olup olmadığını gösterir.

Değer: `true` eğer [get alternative font]; aksi takdirde `false`.

**Returns:**
boolean - [get alternative font] olup olmadığını gösteren bir değer.
### setGetSystemAlternativeFont(boolean value) {#setGetSystemAlternativeFont-boolean-}
```
public static void setGetSystemAlternativeFont(boolean value)
```


Bir değeri ayarlar; bu değer [get alternative font] olup olmadığını gösterir.

Değer: `true` eğer [get alternative font]; aksi takdirde `false`.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | [get alternative font] olup olmadığını gösteren bir değer. |

### getDefaultFontName() {#getDefaultFontName--}
```
public static String getDefaultFontName()
```


Varsayılan yazı tipi adını alır.

**Returns:**
java.lang.String - varsayılan yazı tipinin adı
### setDefaultFontName(String fontName) {#setDefaultFontName-java.lang.String-}
```
public static void setDefaultFontName(String fontName)
```


Varsayılan yazı tipi adını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fontName | java.lang.String | Yazı tipinin varsayılan adı. |

### getFontsFolders() {#getFontsFolders--}
```
public static String[] getFontsFolders()
```


Aspose.Imaging'in TrueType yazı tiplerini aradığı klasörlerin listesini içeren dizinin bir kopyasını alır.

Dönen değer, Aspose.Imaging'in kullandığı verinin bir kopyasıdır. Döndürülen dizideki öğeleri değiştirirseniz, belge renderlemesine hiçbir etkisi olmaz. Yeni yazı tipi konumlarını belirtmek için `setFontsFolders` metodunu kullanın.

**Returns:**
java.lang.String[] - mevcut yazı tipi konumlarının bir kopyası.
### getDefaultFontsFolders() {#getDefaultFontsFolders--}
```
public static String[] getDefaultFontsFolders()
```


Varsayılan yazı tipi klasörlerini alır.

**Returns:**
java.lang.String[] - Sistem klasörünü döndürür
### setFontsFolder(String folder) {#setFontsFolder-java.lang.String-}
```
public static void setFontsFolder(String folder)
```


`folder` için yazı tipi klasör listesini geçersiz kıl.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| folder | java.lang.String | TrueType yazı tiplerini içeren klasör. |

### setFontsFolders(String[] folders) {#setFontsFolders-java.lang.String---}
```
public static void setFontsFolders(String[] folders)
```


`folders` için yazı tipi klasör listesini geçersiz kıl.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| folders | java.lang.String[] | Klasör dizisi |

### setFontsFolders(String[] folders, boolean recursive) {#setFontsFolders-java.lang.String---boolean-}
```
public static void setFontsFolders(String[] folders, boolean recursive)
```


TrueType yazı tiplerinin yüklendiği klasörleri ayarlar ve tüm yüklü yazı tiplerini temizler. Yazı tipi klasörleri üzerinde hiçbir kontrol yapılmaz.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| folders | java.lang.String[] | Yazı tipi klasörleri. |
| recursive | boolean | eğer `true` olarak ayarlanırsa [recursive]. |

### reset() {#reset--}
```
public static void reset()
```


Yazı tipleri klasörünü ve varsayılan yazı tipi adını sistem varsayılanına sıfırlar.

### updateFonts() {#updateFonts--}
```
public static void updateFonts()
```


Metin katmanları içeren PSD dosyaları için yazı tipi önbelleğini günceller. Bu yöntem, FontSettings.setFontsFolder(fontsFolder) yöntemiyle fontsFolder klasöründen gelen yazı tiplerinin veya FontSettings.reset() ile sıfırlandıktan sonra yazı tiplerinin PSD dosyaları işlenirken dikkate alınmasını garanti eder. Lütfen PSD görüntüleri için FontSettings.setFontsFolder(fontsFolder) veya FontSettings.reset() her çağrıldığında bu yöntemi kullanın. Bu yöntem çağrılmadan yazı tiplerinin güncelleneceği garantilenmez.

### addFontsFolder(String fontFolder) {#addFontsFolder-java.lang.String-}
```
public static void addFontsFolder(String fontFolder)
```


`fontFolder`'ı yazı tipi dizin listesine ekler ve yazı tipi araması için ilk klasör olarak işaretler

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fontFolder | java.lang.String | Klasör, TrueType yazı tiplerini veya tek bir yazı tipi dosyası yolunu içerir. |

### removeFontsFolder(String folder) {#removeFontsFolder-java.lang.String-}
```
public static void removeFontsFolder(String folder)
```


`folder`'ı klasör listesinden kaldırır

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| folder | java.lang.String | Kaldırılacak klasör |

