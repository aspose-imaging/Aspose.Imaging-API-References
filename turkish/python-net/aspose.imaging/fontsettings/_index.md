---
title: "FontSettings Sınıfı"
type: docs
weight: 4850
url: /tr/python-net/aspose.imaging/fontsettings/
---

**Summary:** General imaging vector formats renderer font settings.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.FontSettings

## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| default_font_name [static] | string | r/w | Yazı tipinin varsayılan adını alır veya ayarlar. |
| get_system_alternative_font [static] | bool | r/w | Alternatif yazı tipinin alınacağını gösteren bir değeri alır veya ayarlar [get alternative font]. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [get_default_fonts_folders()](#get_default_fonts_folders__1) | Varsayılan yazı tipi klasörlerini alır. |
| [get_fonts_folders()](#get_fonts_folders__2) | Aspose.Words'ün TrueType yazı tiplerini aradığı klasörlerin listesini içeren dizinin bir kopyasını alır. |
| reset() | Yazı tipi klasörünü ve varsayılan yazı tipi adını sistem varsayılanına sıfırlar. |
| [set_fonts_folder(font_folder)](#set_fonts_folder_font_folder_3) | Bu, yalnızca bir yazı tipi dizini ayarlamak için [FontSettings.set_fonts_folders(fonts_folders, recursive)](/imaging/python-net/aspose.imaging/fontsettings/) kısayoludur.<br/>            Yazı tipi klasörü üzerinde hiçbir kontrol yapılmaz. |
| [set_fonts_folders(fonts_folders, recursive)](#set_fonts_folders_fonts_folders_recursive_4) | TrueType yazı tiplerinin yüklendiği klasörleri ayarlar ve tüm yüklü yazı tiplerini temizler.<br/>            Yazı tipi klasörleri üzerinde hiçbir kontrol yapılmaz. |
| update_fonts() | Metin katmanları içeren PSD dosyaları için yazı tipi önbelleğini günceller. Bu yöntem, fontsFolder klasöründen gelen yazı tiplerinin<br/>            FontSettings.SetFontsFolder(fontsFolder) yöntemiyle veya FontSettings.Reset() ile sıfırlandıktan sonra PSD dosyaları işlenirken dikkate alınacağını garanti eder. Lütfen bu yöntemi her seferinde <br/>            PSD görüntüleri için FontSettings.SetFontsFolder(fontsFolder) veya FontSettings.Reset() çağrıldığında kullanın. Bu yöntem çağrılmadan yazı tiplerinin güncelleneceği garantilenmez. |


### Method: get_default_fonts_folders()  [static] {#get_default_fonts_folders__1}


```
 get_default_fonts_folders() 
```

Varsayılan yazı tipi klasörlerini alır.

**Returns**

| Tür | Açıklama |
| :- | :- |
| string[] | Sistem klasörünü döndürür |


### Method: get_fonts_folders()  [static] {#get_fonts_folders__2}


```
 get_fonts_folders() 
```

Aspose.Words'ün TrueType yazı tiplerini aradığı klasörlerin listesini içeren dizinin bir kopyasını alır.

**Returns**

| Tür | Açıklama |
| :- | :- |
| string[] | Mevcut yazı tipi konumlarının bir kopyası. |


### Method: set_fonts_folder(font_folder)  [static] {#set_fonts_folder_font_folder_3}


```
 set_fonts_folder(font_folder) 
```

Bu, yalnızca bir yazı tipi dizini ayarlamak için [FontSettings.set_fonts_folders(fonts_folders, recursive)](/imaging/python-net/aspose.imaging/fontsettings/) kısayoludur.<br/>            Yazı tipi klasörü üzerinde hiçbir kontrol yapılmaz.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| font_folder | string | Yazı tipi klasörü. |

### Method: set_fonts_folders(fonts_folders, recursive)  [static] {#set_fonts_folders_fonts_folders_recursive_4}


```
 set_fonts_folders(fonts_folders, recursive) 
```

TrueType yazı tiplerinin yüklendiği klasörleri ayarlar ve tüm yüklü yazı tiplerini temizler.<br/>            Yazı tipi klasörleri üzerinde hiçbir kontrol yapılmaz.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| fonts_folders | string[] | Yazı tipi klasörleri. |
| recursive | bool | eğer <c>true</c> olarak ayarlanırsa [recursive]. |

