---
title: "EmfPlusStringFormat"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EmfPlusStringFormat nesnesi, metin yerleşimi görüntüleme manipülasyonlarını ve dil tanımlamasını belirtir."
type: docs
weight: 74
url: /tr/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusGraphicsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsobjecttype)
```
public final class EmfPlusStringFormat extends EmfPlusGraphicsObjectType
```

EmfPlusStringFormat nesnesi, metin düzeni, görüntü manipülasyonları ve dil tanımlamasını belirtir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfPlusStringFormat()](#EmfPlusStringFormat--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getDigitLanguage()](#getDigitLanguage--) | Dizedeki sayısal rakamlar için kullanılacak dili belirten bir EmfPlusLanguageIdentifier nesnesini alır veya ayarlar. |
| [setDigitLanguage(short value)](#setDigitLanguage-short-) | Dizedeki sayısal rakamlar için kullanılacak dili belirten bir EmfPlusLanguageIdentifier nesnesini alır veya ayarlar. |
| [getDigitSubstitution()](#getDigitSubstitution--) | Yerel ayar veya dile göre dizedeki sayısal rakamların nasıl değiştirileceğini belirten 32 bit işaretsiz tamsayıyı alır veya ayarlar. |
| [setDigitSubstitution(int value)](#setDigitSubstitution-int-) | Yerel ayar veya dile göre dizedeki sayısal rakamların nasıl değiştirileceğini belirten 32 bit işaretsiz tamsayıyı alır veya ayarlar. |
| [getFirstTabOffset()](#getFirstTabOffset--) | Bir metin satırının başlangıcı ile ilk sekme durağı arasındaki boşluk sayısını belirten 32 bit kayan nokta değerini alır veya ayarlar. |
| [setFirstTabOffset(float value)](#setFirstTabOffset-float-) | Bir metin satırının başlangıcı ile ilk sekme durağı arasındaki boşluk sayısını belirten 32 bit kayan nokta değerini alır veya ayarlar. |
| [getHotkeyPrefix()](#getHotkeyPrefix--) | Bir klavye kısayol ön eki (yani, ampersand) ile karşılaşıldığında bir dize üzerinde gerçekleştirilen işleme türünü belirten 32 bit işaretli tamsayıyı alır veya ayarlar. |
| [setHotkeyPrefix(int value)](#setHotkeyPrefix-int-) | Bir klavye kısayol ön eki (yani, ampersand) ile karşılaşıldığında bir dize üzerinde gerçekleştirilen işleme türünü belirten 32 bit işaretli tamsayıyı alır veya ayarlar. |
| [getLanguage()](#getLanguage--) | Dize için kullanılacak dili belirten bir EmfPlusLanguageIdentifier nesnesini (bölüm 2.2.2.23) alır veya ayarlar. |
| [setLanguage(short value)](#setLanguage-short-) | Dize için kullanılacak dili belirten bir EmfPlusLanguageIdentifier nesnesini (bölüm 2.2.2.23) alır veya ayarlar. |
| [getLeadingMargin()](#getLeadingMargin--) | Bir dize'nin başlangıç konumuna eklenecek boşluğun uzunluğunu belirten 32 bit kayan nokta değerini alır veya ayarlar. |
| [setLeadingMargin(float value)](#setLeadingMargin-float-) | Bir dize'nin başlangıç konumuna eklenecek boşluğun uzunluğunu belirten 32 bit kayan nokta değerini alır veya ayarlar. |
| [getLineAlign()](#getLineAlign--) | Dizeyi yerleşim dikdörtgeninde dikey olarak nasıl hizalayacağını belirten 32 bit işaretsiz tamsayıyı alır veya ayarlar. |
| [setLineAlign(int value)](#setLineAlign-int-) | Dizeyi yerleşim dikdörtgeninde dikey olarak nasıl hizalayacağını belirten 32 bit işaretsiz tamsayıyı alır veya ayarlar. |
| [getRangeCount()](#getRangeCount--) | StringFormatData alanında tanımlanan EmfPlusCharacterRange nesnelerinin (bölüm 2.2.2.8) sayısını belirten 32 bit işaretli tamsayıyı alır veya ayarlar. |
| [setRangeCount(int value)](#setRangeCount-int-) | StringFormatData alanında tanımlanan EmfPlusCharacterRange nesnelerinin (bölüm 2.2.2.8) sayısını belirten 32 bit işaretli tamsayıyı alır veya ayarlar. |
| [getStringAlignment()](#getStringAlignment--) | Dizeyi yerleşim dikdörtgeninde yatay olarak nasıl hizalayacağını belirten 32 bit işaretsiz tamsayıyı alır veya ayarlar. |
| [setStringAlignment(int value)](#setStringAlignment-int-) | Dizeyi yerleşim dikdörtgeninde yatay olarak nasıl hizalayacağını belirten 32 bit işaretsiz tamsayıyı alır veya ayarlar. |
| [getStringFormatData()](#getStringFormatData--) | İsteğe bağlı metin yerleşimi verilerini belirten bir EmfPlusStringFormatData nesnesini (bölüm 2.2.2.44) alır veya ayarlar. |
| [setStringFormatData(EmfPlusStringFormatData value)](#setStringFormatData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStringFormatData-) | İsteğe bağlı metin yerleşimi verilerini belirten bir EmfPlusStringFormatData nesnesini (bölüm 2.2.2.44) alır veya ayarlar. |
| [getStringFormatFlags()](#getStringFormatFlags--) | Biçimlendirme, kırpma ve yazı tipi işleme için metin yerleşimi seçeneklerini belirten 32 bit işaretsiz tamsayıyı alır veya ayarlar. |
| [setStringFormatFlags(long value)](#setStringFormatFlags-long-) | Biçimlendirme, kırpma ve yazı tipi işleme için metin yerleşimi seçeneklerini belirten 32 bit işaretsiz tamsayıyı alır veya ayarlar. |
| [getTabstopCount()](#getTabstopCount--) | StringFormatData alanında tanımlanan sekme duraklarının sayısını belirten 32 bit işaretli tamsayıyı alır veya ayarlar. |
| [setTabstopCount(int value)](#setTabstopCount-int-) | StringFormatData alanında tanımlanan sekme duraklarının sayısını belirten 32 bit işaretli tamsayıyı alır veya ayarlar. |
| [getTracking()](#getTracking--) | Belirtilen bir dizedeki her karaktere ayrılan yatay boşluğun, karakterin yazı tipi tanımlı genişliğine oranını belirten 32 bit kayan nokta değerini alır veya ayarlar. |
| [setTracking(float value)](#setTracking-float-) | Belirtilen bir dizedeki her karaktere ayrılan yatay boşluğun, karakterin yazı tipi tanımlı genişliğine oranını belirten 32 bit kayan nokta değerini alır veya ayarlar. |
| [getTrailingMargin()](#getTrailingMargin--) | Bir dizeden sonra bırakılacak boşluğun uzunluğunu belirten 32 bit kayan nokta değerini alır veya ayarlar. |
| [setTrailingMargin(float value)](#setTrailingMargin-float-) | Bir dizeden sonra bırakılacak boşluğun uzunluğunu belirten 32 bit kayan nokta değerini alır veya ayarlar. |
| [getTrimming()](#getTrimming--) | Yerleşim dikdörtgenine sığamayacak kadar büyük bir dizeden karakterlerin nasıl kırpılacağını belirten özelliği alır veya ayarlar. |
| [setTrimming(int value)](#setTrimming-int-) | Yerleşim dikdörtgenine sığamayacak kadar büyük bir dizeden karakterlerin nasıl kırpılacağını belirten özelliği alır veya ayarlar. |
### EmfPlusStringFormat() {#EmfPlusStringFormat--}
```
public EmfPlusStringFormat()
```


### getDigitLanguage() {#getDigitLanguage--}
```
public short getDigitLanguage()
```


Dizedeki sayısal rakamlar için kullanılacak dili belirten bir EmfPlusLanguageIdentifier nesnesini alır veya ayarlar. Örneğin, bu dize Arap rakamları içeriyorsa, bu alan Arap dili belirten bir dil tanımlayıcısı içermelidir.

**Returns:**
short
### setDigitLanguage(short value) {#setDigitLanguage-short-}
```
public void setDigitLanguage(short value)
```


Dizedeki sayısal rakamlar için kullanılacak dili belirten bir EmfPlusLanguageIdentifier nesnesini alır veya ayarlar. Örneğin, bu dize Arap rakamları içeriyorsa, bu alan Arap dili belirten bir dil tanımlayıcısı içermelidir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | short |  |

### getDigitSubstitution() {#getDigitSubstitution--}
```
public int getDigitSubstitution()
```


Yerel ayar veya dile göre dizedeki sayısal rakamların nasıl değiştirileceğini belirten 32 bit işaretsiz tamsayıyı alır veya ayarlar. Bu değer, StringDigitSubstitution numaralandırmasında (bölüm 2.1.1.30) tanımlanmalıdır.

**Returns:**
int
### setDigitSubstitution(int value) {#setDigitSubstitution-int-}
```
public void setDigitSubstitution(int value)
```


Yerel ayar veya dile göre dizedeki sayısal rakamların nasıl değiştirileceğini belirten 32 bit işaretsiz tamsayıyı alır veya ayarlar. Bu değer, StringDigitSubstitution numaralandırmasında (bölüm 2.1.1.30) tanımlanmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getFirstTabOffset() {#getFirstTabOffset--}
```
public float getFirstTabOffset()
```


Bir metin satırının başlangıcı ile ilk sekme durağı arasındaki boşluk sayısını belirten 32 bit kayan nokta değerini alır veya ayarlar.

**Returns:**
float
### setFirstTabOffset(float value) {#setFirstTabOffset-float-}
```
public void setFirstTabOffset(float value)
```


Bir metin satırının başlangıcı ile ilk sekme durağı arasındaki boşluk sayısını belirten 32 bit kayan nokta değerini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float |  |

### getHotkeyPrefix() {#getHotkeyPrefix--}
```
public int getHotkeyPrefix()
```


Bir klavye kısayol ön eki (yani, ampersand) ile karşılaşıldığında bir dize üzerinde gerçekleştirilen işleme türünü belirten 32 bit işaretli tamsayıyı alır veya ayarlar. Temelde, bu alan metinle ilişkili klavye kısayol ön eklerinin gösterilip gösterilmeyeceğini belirler. Değer, HotkeyPrefix numaralandırmasında (bölüm 2.1.1.14) tanımlanmalıdır.

**Returns:**
int
### setHotkeyPrefix(int value) {#setHotkeyPrefix-int-}
```
public void setHotkeyPrefix(int value)
```


Bir klavye kısayol ön eki (yani, ampersand) ile karşılaşıldığında bir dize üzerinde gerçekleştirilen işleme türünü belirten 32 bit işaretli tamsayıyı alır veya ayarlar. Temelde, bu alan metinle ilişkili klavye kısayol ön eklerinin gösterilip gösterilmeyeceğini belirler. Değer, HotkeyPrefix numaralandırmasında (bölüm 2.1.1.14) tanımlanmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getLanguage() {#getLanguage--}
```
public short getLanguage()
```


Dize için kullanılacak dili belirten bir EmfPlusLanguageIdentifier nesnesini (bölüm 2.2.2.23) alır veya ayarlar.

**Returns:**
short
### setLanguage(short value) {#setLanguage-short-}
```
public void setLanguage(short value)
```


Dize için kullanılacak dili belirten bir EmfPlusLanguageIdentifier nesnesini (bölüm 2.2.2.23) alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | short |  |

### getLeadingMargin() {#getLeadingMargin--}
```
public float getLeadingMargin()
```


Bir dize'nin başlangıç konumuna eklenecek boşluğun uzunluğunu belirten 32 bit kayan nokta değerini alır veya ayarlar. Varsayılan değer 1/6 inçtir; tipografik yazı tipleri için varsayılan değer 0'dır.

**Returns:**
float
### setLeadingMargin(float value) {#setLeadingMargin-float-}
```
public void setLeadingMargin(float value)
```


Bir dize'nin başlangıç konumuna eklenecek boşluğun uzunluğunu belirten 32 bit kayan nokta değerini alır veya ayarlar. Varsayılan değer 1/6 inçtir; tipografik yazı tipleri için varsayılan değer 0'dır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float |  |

### getLineAlign() {#getLineAlign--}
```
public int getLineAlign()
```


Dizeyi yerleşim dikdörtgeninde dikey olarak nasıl hizalayacağını belirten 32 bit işaretsiz tamsayıyı alır veya ayarlar. Bu değer, StringAlignment numaralandırmasında tanımlanmalıdır.

**Returns:**
int
### setLineAlign(int value) {#setLineAlign-int-}
```
public void setLineAlign(int value)
```


Dizeyi yerleşim dikdörtgeninde dikey olarak nasıl hizalayacağını belirten 32 bit işaretsiz tamsayıyı alır veya ayarlar. Bu değer, StringAlignment numaralandırmasında tanımlanmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getRangeCount() {#getRangeCount--}
```
public int getRangeCount()
```


StringFormatData alanında tanımlanan EmfPlusCharacterRange nesnelerinin (bölüm 2.2.2.8) sayısını belirten 32 bit işaretli tamsayıyı alır veya ayarlar.

**Returns:**
int
### setRangeCount(int value) {#setRangeCount-int-}
```
public void setRangeCount(int value)
```


StringFormatData alanında tanımlanan EmfPlusCharacterRange nesnelerinin (bölüm 2.2.2.8) sayısını belirten 32 bit işaretli tamsayıyı alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getStringAlignment() {#getStringAlignment--}
```
public int getStringAlignment()
```


Düzen dikdörtgeninde dizeyi yatay olarak nasıl hizalayacağını belirten 32 bit işaretsiz tam sayı değerini alır veya ayarlar. Bu değer StringAlignment sayımında (bölüm 2.1.1.29) tanımlanmalıdır.

**Returns:**
int
### setStringAlignment(int value) {#setStringAlignment-int-}
```
public void setStringAlignment(int value)
```


Düzen dikdörtgeninde dizeyi yatay olarak nasıl hizalayacağını belirten 32 bit işaretsiz tam sayı değerini alır veya ayarlar. Bu değer StringAlignment sayımında (bölüm 2.1.1.29) tanımlanmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getStringFormatData() {#getStringFormatData--}
```
public EmfPlusStringFormatData getStringFormatData()
```


İsteğe bağlı metin yerleşimi verilerini belirten bir EmfPlusStringFormatData nesnesini (bölüm 2.2.2.44) alır veya ayarlar.

**Returns:**
[EmfPlusStringFormatData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformatdata)
### setStringFormatData(EmfPlusStringFormatData value) {#setStringFormatData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStringFormatData-}
```
public void setStringFormatData(EmfPlusStringFormatData value)
```


İsteğe bağlı metin yerleşimi verilerini belirten bir EmfPlusStringFormatData nesnesini (bölüm 2.2.2.44) alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [EmfPlusStringFormatData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformatdata) |  |

### getStringFormatFlags() {#getStringFormatFlags--}
```
public long getStringFormatFlags()
```


Biçimlendirme, kırpma ve yazı tipi işleme için metin yerleşim seçeneklerini belirten 32 bit işaretsiz tam sayı değerini alır veya ayarlar. Bu değer StringFormat bayraklarından (bölüm 2.1.2.8) oluşmalıdır.

**Returns:**
long
### setStringFormatFlags(long value) {#setStringFormatFlags-long-}
```
public void setStringFormatFlags(long value)
```


Biçimlendirme, kırpma ve yazı tipi işleme için metin yerleşim seçeneklerini belirten 32 bit işaretsiz tam sayı değerini alır veya ayarlar. Bu değer StringFormat bayraklarından (bölüm 2.1.2.8) oluşmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | long |  |

### getTabstopCount() {#getTabstopCount--}
```
public int getTabstopCount()
```


StringFormatData alanında tanımlanan sekme duraklarının sayısını belirten 32 bit işaretli tamsayıyı alır veya ayarlar.

**Returns:**
int
### setTabstopCount(int value) {#setTabstopCount-int-}
```
public void setTabstopCount(int value)
```


StringFormatData alanında tanımlanan sekme duraklarının sayısını belirten 32 bit işaretli tamsayıyı alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getTracking() {#getTracking--}
```
public float getTracking()
```


Belirli bir dizedeki her karaktere ayrılan yatay alanın, karakterin yazı tipi tanımlı genişliğine oranını belirten 32 bit kayan nokta değerini alır veya ayarlar. Bu özellik için büyük değerler karakterler arasında geniş boşluk sağlar; 1'den küçük değerler karakter çakışmasına neden olabilir. Varsayılan değer 1.03'tür; tipografik yazı tipleri için varsayılan değer 1.00'dir.

**Returns:**
float
### setTracking(float value) {#setTracking-float-}
```
public void setTracking(float value)
```


Belirli bir dizedeki her karaktere ayrılan yatay alanın, karakterin yazı tipi tanımlı genişliğine oranını belirten 32 bit kayan nokta değerini alır veya ayarlar. Bu özellik için büyük değerler karakterler arasında geniş boşluk sağlar; 1'den küçük değerler karakter çakışmasına neden olabilir. Varsayılan değer 1.03'tür; tipografik yazı tipleri için varsayılan değer 1.00'dir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float |  |

### getTrailingMargin() {#getTrailingMargin--}
```
public float getTrailingMargin()
```


Bir dizeden sonra bırakılacak boşluk uzunluğunu belirten 32 bit kayan nokta değerini alır veya ayarlar. Varsayılan değer 1/6 inçtir; tipografik yazı tipleri için varsayılan değer 0'dır.

**Returns:**
float
### setTrailingMargin(float value) {#setTrailingMargin-float-}
```
public void setTrailingMargin(float value)
```


Bir dizeden sonra bırakılacak boşluk uzunluğunu belirten 32 bit kayan nokta değerini alır veya ayarlar. Varsayılan değer 1/6 inçtir; tipografik yazı tipleri için varsayılan değer 0'dır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float |  |

### getTrimming() {#getTrimming--}
```
public int getTrimming()
```


Düzen dikdörtgenine sığamayacak kadar büyük bir dizeden karakterlerin nasıl kırpılacağını belirten değeri alır veya ayarlar. Bu değer StringTrimming sayımında (bölüm 2.1.1.31) tanımlanmalıdır.

**Returns:**
int
### setTrimming(int value) {#setTrimming-int-}
```
public void setTrimming(int value)
```


Düzen dikdörtgenine sığamayacak kadar büyük bir dizeden karakterlerin nasıl kırpılacağını belirten değeri alır veya ayarlar. Bu değer StringTrimming sayımında (bölüm 2.1.1.31) tanımlanmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

