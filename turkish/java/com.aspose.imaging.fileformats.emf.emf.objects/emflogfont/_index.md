---
title: "EmfLogFont"
second_title: "Aspose.Imaging for Java API Referansı"
description: "LogFont nesnesi, mantıksal bir fontun temel özelliklerini belirtir."
type: docs
weight: 22
url: /tr/java/com.aspose.imaging.fileformats.emf.emf.objects/emflogfont/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public class EmfLogFont extends EmfObject
```

LogFont nesnesi, mantıksal bir fontun temel özelliklerini belirtir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfLogFont()](#EmfLogFont--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getHeight()](#getHeight--) | 32 bit işaretli tam sayı alır veya ayarlar; bu, yazı tipinin karakter hücresi veya karakterinin yüksekliğini mantıksal birimlerde belirtir. |
| [setHeight(int value)](#setHeight-int-) | 32 bit işaretli tam sayı alır veya ayarlar; bu, yazı tipinin karakter hücresi veya karakterinin yüksekliğini mantıksal birimlerde belirtir. |
| [getWidth()](#getWidth--) | 32 bit işaretli tam sayı alır veya ayarlar; bu, yazı tipindeki karakterlerin ortalama genişliğini mantıksal birimlerde belirtir. |
| [setWidth(int value)](#setWidth-int-) | 32 bit işaretli tam sayı alır veya ayarlar; bu, yazı tipindeki karakterlerin ortalama genişliğini mantıksal birimlerde belirtir. |
| [getEscapement()](#getEscapement--) | 32 bit işaretli tam sayı alır veya ayarlar; bu, kaçış vektörü ile cihazın x ekseni arasındaki açıyı derece ondalıklarıyla belirtir. |
| [setEscapement(int value)](#setEscapement-int-) | 32 bit işaretli tam sayı alır veya ayarlar; bu, kaçış vektörü ile cihazın x ekseni arasındaki açıyı derece ondalıklarıyla belirtir. |
| [getOrientation()](#getOrientation--) | 32 bit işaretli tam sayı alır veya ayarlar; bu, her karakterin taban çizgisi ile cihazın x ekseni arasındaki açıyı derece ondalıklarıyla belirtir. |
| [setOrientation(int value)](#setOrientation-int-) | 32 bit işaretli tam sayı alır veya ayarlar; bu, her karakterin taban çizgisi ile cihazın x ekseni arasındaki açıyı derece ondalıklarıyla belirtir. |
| [getWeight()](#getWeight--) | 32 bit işaretli tam sayı alır veya ayarlar; bu, yazı tipinin ağırlığını 0 ile 1000 arasında bir değer olarak belirtir. |
| [setWeight(int value)](#setWeight-int-) | 32 bit işaretli tam sayı alır veya ayarlar; bu, yazı tipinin ağırlığını 0 ile 1000 arasında bir değer olarak belirtir. |
| [getItalic()](#getItalic--) | 8 bit işaretsiz tam sayı alır veya ayarlar; bu, 0x01 olarak ayarlanırsa italik bir yazı tipini belirtir; aksi takdirde 0x00 olmalıdır. |
| [setItalic(byte value)](#setItalic-byte-) | 8 bit işaretsiz tam sayı alır veya ayarlar; bu, 0x01 olarak ayarlanırsa italik bir yazı tipini belirtir; aksi takdirde 0x00 olmalıdır. |
| [getUnderline()](#getUnderline--) | 8 bit işaretsiz tam sayı alır veya ayarlar; bu, 0x01 olarak ayarlanırsa altı çizili bir yazı tipini belirtir; aksi takdirde 0x00 olmalıdır. |
| [setUnderline(byte value)](#setUnderline-byte-) | 8 bit işaretsiz tam sayı alır veya ayarlar; bu, 0x01 olarak ayarlanırsa altı çizili bir yazı tipini belirtir; aksi takdirde 0x00 olmalıdır. |
| [getStrikeout()](#getStrikeout--) | 8 bit işaretsiz tam sayı alır veya ayarlar; bu, 0x01 olarak ayarlanırsa üstü çizili bir yazı tipini belirtir; aksi takdirde 0x00 olmalıdır. |
| [setStrikeout(byte value)](#setStrikeout-byte-) | 8 bit işaretsiz tam sayı alır veya ayarlar; bu, 0x01 olarak ayarlanırsa üstü çizili bir yazı tipini belirtir; aksi takdirde 0x00 olmalıdır. |
| [getCharSet()](#getCharSet--) | 8 bit işaretsiz tam sayı alır veya ayarlar; bu, karakter gliflerinin kümesini belirtir. |
| [setCharSet(byte value)](#setCharSet-byte-) | 8 bit işaretsiz tam sayı alır veya ayarlar; bu, karakter gliflerinin kümesini belirtir. |
| [getOutPrecision()](#getOutPrecision--) | 8 bit işaretsiz tam sayı alır veya ayarlar; bu, çıktı hassasiyetini belirtir. |
| [setOutPrecision(byte value)](#setOutPrecision-byte-) | 8 bit işaretsiz tam sayı alır veya ayarlar; bu, çıktı hassasiyetini belirtir. |
| [getClipPrecision()](#getClipPrecision--) | 8 bit işaretsiz tam sayı alır veya ayarlar; bu, kırpma hassasiyetini belirtir. |
| [setClipPrecision(byte value)](#setClipPrecision-byte-) | 8 bit işaretsiz tam sayı alır veya ayarlar; bu, kırpma hassasiyetini belirtir. |
| [getQuality()](#getQuality--) | 8 bit işaretsiz tam sayı alır veya ayarlar; bu, çıktı kalitesini belirtir. |
| [setQuality(byte value)](#setQuality-byte-) | 8 bit işaretsiz tam sayı alır veya ayarlar; bu, çıktı kalitesini belirtir. |
| [getPitchAndFamily()](#getPitchAndFamily--) | WMF PitchAndFamily nesnesi ([MS-WMF] bölüm 2.2.2.14) alır veya ayarlar; bu nesne, yazı tipinin pitch ve familyasını belirtir. |
| [setPitchAndFamily(WmfPitchAndFamily value)](#setPitchAndFamily-com.aspose.imaging.fileformats.wmf.objects.WmfPitchAndFamily-) | WMF PitchAndFamily nesnesi ([MS-WMF] bölüm 2.2.2.14) alır veya ayarlar; bu nesne, yazı tipinin pitch ve familyasını belirtir. |
| [getFacename()](#getFacename--) | Facename (64 bayt) alır veya ayarlar: Yazı tipinin tip adı belirten, 32 Unicode karakteri geçmeyen bir dizedir. |
| [setFacename(String value)](#setFacename-java.lang.String-) | Facename (64 bayt) alır veya ayarlar: Yazı tipinin tip adı belirten, 32 Unicode karakteri geçmeyen bir dizedir. |
### EmfLogFont() {#EmfLogFont--}
```
public EmfLogFont()
```


### getHeight() {#getHeight--}
```
public int getHeight()
```


32 bit işaretli tam sayı alır veya ayarlar; bu, yazı tipinin karakter hücresi veya karakterinin yüksekliğini mantıksal birimlerde belirtir. Karakter yüksekliği değeri, em boyutu olarak da bilinir, karakter hücresi yüksekliği değerinden iç önderlik değerinin çıkarılmasıyla elde edilir. Yazı tipi eşleyicisi, Height alanında belirtilen değeri aşağıdaki şekilde yorumlamalıdır.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public void setHeight(int value)
```


32 bit işaretli tam sayı alır veya ayarlar; bu, yazı tipinin karakter hücresi veya karakterinin yüksekliğini mantıksal birimlerde belirtir. Karakter yüksekliği değeri, em boyutu olarak da bilinir, karakter hücresi yüksekliği değerinden iç önderlik değerinin çıkarılmasıyla elde edilir. Yazı tipi eşleyicisi, Height alanında belirtilen değeri aşağıdaki şekilde yorumlamalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getWidth() {#getWidth--}
```
public int getWidth()
```


32 bit işaretli tam sayı alır veya ayarlar; bu, yazı tipindeki karakterlerin ortalama genişliğini mantıksal birimlerde belirtir. Width alanı değeri sıfır ise, tipografinin istediği en-boy oranına sahip bir yazı tipi bulmak için diğer LogFont değerlerinden uygun bir değer hesaplanmalı.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public void setWidth(int value)
```


32 bit işaretli tam sayı alır veya ayarlar; bu, yazı tipindeki karakterlerin ortalama genişliğini mantıksal birimlerde belirtir. Width alanı değeri sıfır ise, tipografinin istediği en-boy oranına sahip bir yazı tipi bulmak için diğer LogFont değerlerinden uygun bir değer hesaplanmalı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getEscapement() {#getEscapement--}
```
public int getEscapement()
```


Cihazın x ekseni ile kaçış vektörü arasındaki açıyı, derece ondalıkları cinsinden belirten 32 bit işaretli bir tamsayıyı alır veya ayarlar. Kaçış vektörü, bir metin satırının temel çizgisine paraleldir.

**Returns:**
int
### setEscapement(int value) {#setEscapement-int-}
```
public void setEscapement(int value)
```


Cihazın x ekseni ile kaçış vektörü arasındaki açıyı, derece ondalıkları cinsinden belirten 32 bit işaretli bir tamsayıyı alır veya ayarlar. Kaçış vektörü, bir metin satırının temel çizgisine paraleldir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getOrientation() {#getOrientation--}
```
public int getOrientation()
```


32 bit işaretli tam sayı alır veya ayarlar; bu, her karakterin taban çizgisi ile cihazın x ekseni arasındaki açıyı derece ondalıklarıyla belirtir.

**Returns:**
int
### setOrientation(int value) {#setOrientation-int-}
```
public void setOrientation(int value)
```


32 bit işaretli tam sayı alır veya ayarlar; bu, her karakterin taban çizgisi ile cihazın x ekseni arasındaki açıyı derece ondalıklarıyla belirtir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getWeight() {#getWeight--}
```
public int getWeight()
```


Sıfır ile 1000 arasında bir aralıkta fontun ağırlığını belirten 32 bit işaretli bir tamsayıyı alır veya ayarlar. Örneğin, 400 normal ve 700 kalındır. Bu değer sıfır ise, varsayılan bir ağırlık kullanılabilir.

**Returns:**
int
### setWeight(int value) {#setWeight-int-}
```
public void setWeight(int value)
```


Sıfır ile 1000 arasında bir aralıkta fontun ağırlığını belirten 32 bit işaretli bir tamsayıyı alır veya ayarlar. Örneğin, 400 normal ve 700 kalındır. Bu değer sıfır ise, varsayılan bir ağırlık kullanılabilir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getItalic() {#getItalic--}
```
public byte getItalic()
```


8 bit işaretsiz tam sayı alır veya ayarlar; bu, 0x01 olarak ayarlanırsa italik bir yazı tipini belirtir; aksi takdirde 0x00 olmalıdır.

**Returns:**
byte
### setItalic(byte value) {#setItalic-byte-}
```
public void setItalic(byte value)
```


8 bit işaretsiz tam sayı alır veya ayarlar; bu, 0x01 olarak ayarlanırsa italik bir yazı tipini belirtir; aksi takdirde 0x00 olmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte |  |

### getUnderline() {#getUnderline--}
```
public byte getUnderline()
```


8 bit işaretsiz tam sayı alır veya ayarlar; bu, 0x01 olarak ayarlanırsa altı çizili bir yazı tipini belirtir; aksi takdirde 0x00 olmalıdır.

**Returns:**
byte
### setUnderline(byte value) {#setUnderline-byte-}
```
public void setUnderline(byte value)
```


8 bit işaretsiz tam sayı alır veya ayarlar; bu, 0x01 olarak ayarlanırsa altı çizili bir yazı tipini belirtir; aksi takdirde 0x00 olmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte |  |

### getStrikeout() {#getStrikeout--}
```
public byte getStrikeout()
```


8 bit işaretsiz tam sayı alır veya ayarlar; bu, 0x01 olarak ayarlanırsa üstü çizili bir yazı tipini belirtir; aksi takdirde 0x00 olmalıdır.

**Returns:**
byte
### setStrikeout(byte value) {#setStrikeout-byte-}
```
public void setStrikeout(byte value)
```


8 bit işaretsiz tam sayı alır veya ayarlar; bu, 0x01 olarak ayarlanırsa üstü çizili bir yazı tipini belirtir; aksi takdirde 0x00 olmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte |  |

### getCharSet() {#getCharSet--}
```
public byte getCharSet()
```


Karakter glif kümesini belirten 8 bit işaretsiz bir tamsayıyı alır veya ayarlar. Bu, WMF CharacterSet numaralandırmasındaki bir değer OLmalıdır ([MS-WMF] bölüm 2.1.1.5). Karakter kümesi bilinmiyorsa, metafile işleme OLUŞTURULAN fontla render edilen dizeleri çevirmeye veya yorumlamaya çalışmamalıdır.

**Returns:**
byte
### setCharSet(byte value) {#setCharSet-byte-}
```
public void setCharSet(byte value)
```


Karakter glif kümesini belirten 8 bit işaretsiz bir tamsayıyı alır veya ayarlar. Bu, WMF CharacterSet numaralandırmasındaki bir değer OLmalıdır ([MS-WMF] bölüm 2.1.1.5). Karakter kümesi bilinmiyorsa, metafile işleme OLUŞTURULAN fontla render edilen dizeleri çevirmeye veya yorumlamaya çalışmamalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte |  |

### getOutPrecision() {#getOutPrecision--}
```
public byte getOutPrecision()
```


Çıktı hassasiyetini belirten 8 bit işaretsiz bir tamsayıyı alır veya ayarlar. Çıktı hassasiyeti, fontun istenen yükseklik, genişlik, karakter yönelimi, kaçış, pitch ve font türüyle ne kadar yakından eşleşmesi gerektiğini tanımlar. Bu, WMF OutPrecision numaralandırmasından bir değer OLmalıdır.

**Returns:**
byte
### setOutPrecision(byte value) {#setOutPrecision-byte-}
```
public void setOutPrecision(byte value)
```


Çıktı hassasiyetini belirten 8 bit işaretsiz bir tamsayıyı alır veya ayarlar. Çıktı hassasiyeti, fontun istenen yükseklik, genişlik, karakter yönelimi, kaçış, pitch ve font türüyle ne kadar yakından eşleşmesi gerektiğini tanımlar. Bu, WMF OutPrecision numaralandırmasından bir değer OLmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte |  |

### getClipPrecision() {#getClipPrecision--}
```
public byte getClipPrecision()
```


Kırpma hassasiyetini belirten 8 bit işaretsiz bir tamsayıyı alır veya ayarlar. Kırpma hassasiyeti, kırpma bölgesinin dışına kısmen çıkan karakterlerin nasıl kırpılacağını tanımlar. Bu, WMF ClipPrecision bayraklarından bir veya daha fazlası olabilir.

**Returns:**
byte
### setClipPrecision(byte value) {#setClipPrecision-byte-}
```
public void setClipPrecision(byte value)
```


Kırpma hassasiyetini belirten 8 bit işaretsiz bir tamsayıyı alır veya ayarlar. Kırpma hassasiyeti, kırpma bölgesinin dışına kısmen çıkan karakterlerin nasıl kırpılacağını tanımlar. Bu, WMF ClipPrecision bayraklarından bir veya daha fazlası olabilir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte |  |

### getQuality() {#getQuality--}
```
public byte getQuality()
```


Çıktı kalitesini belirten 8 bit işaretsiz bir tamsayıyı alır veya ayarlar. Çıktı kalitesi, mantıksal font özelliklerini gerçek bir fiziksel fontun özelliklerine ne kadar yakından eşleştirmeye çalışılacağını tanımlar. Bu, WMF FontQuality numaralandırmasındaki değerlerden biri OLmalıdır ([MS-WMF] bölüm 2.1.1.10).

**Returns:**
byte
### setQuality(byte value) {#setQuality-byte-}
```
public void setQuality(byte value)
```


Çıktı kalitesini belirten 8 bit işaretsiz bir tamsayıyı alır veya ayarlar. Çıktı kalitesi, mantıksal font özelliklerini gerçek bir fiziksel fontun özelliklerine ne kadar yakından eşleştirmeye çalışılacağını tanımlar. Bu, WMF FontQuality numaralandırmasındaki değerlerden biri OLmalıdır ([MS-WMF] bölüm 2.1.1.10).

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte |  |

### getPitchAndFamily() {#getPitchAndFamily--}
```
public WmfPitchAndFamily getPitchAndFamily()
```


Fontun pitch ve ailesini belirten bir WMF PitchAndFamily nesnesi ([MS-WMF] bölüm 2.2.2.14) alır veya ayarlar. Font aileleri, bir fontun görünümünü genel bir şekilde tanımlar. Belirtilen yazı tipi mevcut olmadığında bir font belirtmek için tasarlanmıştır.

**Returns:**
[WmfPitchAndFamily](../../com.aspose.imaging.fileformats.wmf.objects/wmfpitchandfamily)
### setPitchAndFamily(WmfPitchAndFamily value) {#setPitchAndFamily-com.aspose.imaging.fileformats.wmf.objects.WmfPitchAndFamily-}
```
public void setPitchAndFamily(WmfPitchAndFamily value)
```


Fontun pitch ve ailesini belirten bir WMF PitchAndFamily nesnesi ([MS-WMF] bölüm 2.2.2.14) alır veya ayarlar. Font aileleri, bir fontun görünümünü genel bir şekilde tanımlar. Belirtilen yazı tipi mevcut olmadığında bir font belirtmek için tasarlanmıştır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [WmfPitchAndFamily](../../com.aspose.imaging.fileformats.wmf.objects/wmfpitchandfamily) |  |

### getFacename() {#getFacename--}
```
public String getFacename()
```


Bir Facename (64 bayt) alır veya ayarlar: Fontun yazı tipi adını belirten en fazla 32 Unicode karakterden oluşan bir dizedir. Bu dizenin uzunluğu 32 karakterden az ise, sonlandırıcı NULL bulunmalı ve bu NULL'dan sonraki alanın geri kalanı YOK SAYILMALIDIR.

**Returns:**
java.lang.String
### setFacename(String value) {#setFacename-java.lang.String-}
```
public void setFacename(String value)
```


Bir Facename (64 bayt) alır veya ayarlar: Fontun yazı tipi adını belirten en fazla 32 Unicode karakterden oluşan bir dizedir. Bu dizenin uzunluğu 32 karakterden az ise, sonlandırıcı NULL bulunmalı ve bu NULL'dan sonraki alanın geri kalanı YOK SAYILMALIDIR.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

