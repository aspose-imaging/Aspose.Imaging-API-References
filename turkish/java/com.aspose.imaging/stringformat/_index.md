---
title: "StringFormat"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Hizalama yönelimi ve sekme durakları gibi metin yerleşim bilgilerini, üç nokta ekleme ve ulusal rakam ikamesi gibi görüntüleme manipülasyonlarını ve OpenType özelliklerini kapsar."
type: docs
weight: 112
url: /tr/java/com.aspose.imaging/stringformat/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject)
```
public final class StringFormat extends DisposableObject
```

Metin yerleşim bilgilerini (örneğin hizalama, yönelim ve sekme durakları), görüntüleme manipülasyonlarını (örneğin üç nokta ekleme ve ulusal rakam ikamesi) ve OpenType özelliklerini kapsar. Bu sınıf miras alınamaz.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [StringFormat()](#StringFormat--) | Yeni bir `com.aspose.imaging.StringFormat` nesnesi başlatır. |
| [StringFormat(int options)](#StringFormat-int-) | Belirtilen `com.aspose.imaging.StringFormatFlags` enumarasyonu ve dil ile yeni bir `com.aspose.imaging.StringFormat` nesnesi başlatır. |
| [StringFormat(StringFormat format)](#StringFormat-com.aspose.imaging.StringFormat-) | Belirtilen mevcut `com.aspose.imaging.StringFormat` nesnesinden yeni bir `com.aspose.imaging.StringFormat` nesnesi başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getGenericDefault()](#getGenericDefault--) | Genel bir varsayılan `com.aspose.imaging.StringFormat` nesnesi alır. |
| [getGenericTypographic()](#getGenericTypographic--) | Genel tipografik `com.aspose.imaging.StringFormat` nesnesini alır. |
| [getFormatFlags()](#getFormatFlags--) | `com.aspose.imaging.StringFormatFlags` biçimlendirme bilgilerini içeren bir enumerasyonu alır. |
| [setFormatFlags(int value)](#setFormatFlags-int-) | `com.aspose.imaging.StringFormatFlags` biçimlendirme bilgilerini içeren bir enumerasyonu ayarlar. |
| [getAlignment()](#getAlignment--) | Dikey düzlemde metin hizalama bilgilerini alır. |
| [setAlignment(int value)](#setAlignment-int-) | Dikey düzlemde metin hizalama bilgilerini ayarlar. |
| [getLineAlignment()](#getLineAlignment--) | Yatay düzlemde satır hizalamasını alır. |
| [setLineAlignment(int value)](#setLineAlignment-int-) | Yatay düzlemde satır hizalamasını ayarlar. |
| [getHotkeyPrefix()](#getHotkeyPrefix--) | Bu `com.aspose.imaging.StringFormat` nesnesi için `com.aspose.imaging.HotkeyPrefix` nesnesini alır. |
| [setHotkeyPrefix(int value)](#setHotkeyPrefix-int-) | Bu `com.aspose.imaging.StringFormat` nesnesi için `com.aspose.imaging.HotkeyPrefix` nesnesini ayarlar. |
| [getTrimming()](#getTrimming--) | Bu `com.aspose.imaging.StringFormat` nesnesi için `com.aspose.imaging.StringTrimming` enumerasyonunu alır. |
| [setTrimming(int value)](#setTrimming-int-) | Bu `com.aspose.imaging.StringFormat` nesnesi için `com.aspose.imaging.StringTrimming` enumerasyonunu ayarlar. |
| [getDigitSubstitutionMethod()](#getDigitSubstitutionMethod--) | Rakam ikamesi için kullanılacak yöntemi alır. |
| [setDigitSubstitutionMethod(int value)](#setDigitSubstitutionMethod-int-) | Rakam ikamesi için kullanılacak yöntemi ayarlar. |
| [getDigitSubstitutionLanguage()](#getDigitSubstitutionLanguage--) | Yerel rakamların batı rakamlarıyla ikame edildiği durumda kullanılan dili alır. |
| [setDigitSubstitutionLanguage(int value)](#setDigitSubstitutionLanguage-int-) | Yerel rakamların batı rakamlarıyla ikame edildiği durumda kullanılan dili ayarlar. |
| [getFirstTabOffset()](#getFirstTabOffset--) | Bir metin satırının başlangıcı ile ilk sekme durağı arasındaki boşluk sayısını alır. |
| [getTabStops()](#getTabStops--) | `P:Aspose.Imaging.getGraphics().PageUnit` özelliği tarafından belirtilen birimlerde sekme durakları arasındaki mesafelerin bir dizisini alır. |
| [getCustomCharIdent()](#getCustomCharIdent--) | Özel karakter kimliğini alır. |
| [setCustomCharIdent(PointF value)](#setCustomCharIdent-com.aspose.imaging.PointF-) | Özel karakter kimliğini ayarlar. |
| [deepClone()](#deepClone--) | Bu `com.aspose.imaging.StringFormat` nesnesinin derin bir klonunu oluşturur. |
| [setTabStops(float firstTabOffset, float[] tabStops)](#setTabStops-float-float---) | Bu `com.aspose.imaging.StringFormat` nesnesi için sekme duraklarını ayarlar. |
| [toString()](#toString--) | Bu `com.aspose.imaging.StringFormat` nesnesini insan tarafından okunabilir bir dizeye dönüştürür. |
| [equals(Object o)](#equals-java.lang.Object-) | Nesnelerin eşit olup olmadığını kontrol et. |
| [hashCode()](#hashCode--) | Geçerli nesnenin karma kodunu al. |
### StringFormat() {#StringFormat--}
```
public StringFormat()
```


Yeni bir `com.aspose.imaging.StringFormat` nesnesi başlatır.

### StringFormat(int options) {#StringFormat-int-}
```
public StringFormat(int options)
```


Belirtilen `com.aspose.imaging.StringFormatFlags` enumarasyonu ve dil ile yeni bir `com.aspose.imaging.StringFormat` nesnesi başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| seçenekler | int | Yeni `com.aspose.imaging.StringFormat` nesnesi için `com.aspose.imaging.StringFormatFlags` enumerasyonu. |

### StringFormat(StringFormat format) {#StringFormat-com.aspose.imaging.StringFormat-}
```
public StringFormat(StringFormat format)
```


Belirtilen mevcut `com.aspose.imaging.StringFormat` nesnesinden yeni bir `com.aspose.imaging.StringFormat` nesnesi başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| format | [StringFormat](../../com.aspose.imaging/stringformat) | Yeni `com.aspose.imaging.StringFormat` nesnesini başlatmak için kullanılacak `com.aspose.imaging.StringFormat` nesnesi. |

### getGenericDefault() {#getGenericDefault--}
```
public static StringFormat getGenericDefault()
```


Genel bir varsayılan `com.aspose.imaging.StringFormat` nesnesi alır.

**Returns:**
[StringFormat](../../com.aspose.imaging/stringformat) - The generic default `com.aspose.imaging.StringFormat` object.
### getGenericTypographic() {#getGenericTypographic--}
```
public static StringFormat getGenericTypographic()
```


Genel tipografik `com.aspose.imaging.StringFormat` nesnesini alır.

**Returns:**
[StringFormat](../../com.aspose.imaging/stringformat) - A generic typographic `com.aspose.imaging.StringFormat` object.
### getFormatFlags() {#getFormatFlags--}
```
public int getFormatFlags()
```


`com.aspose.imaging.StringFormatFlags` biçimlendirme bilgilerini içeren bir enumerasyonu alır.

**Returns:**
int - `com.aspose.imaging.StringFormatFlags` adlı biçimlendirme bilgilerini içeren bir enum.
### setFormatFlags(int value) {#setFormatFlags-int-}
```
public void setFormatFlags(int value)
```


`com.aspose.imaging.StringFormatFlags` biçimlendirme bilgilerini içeren bir enumerasyonu ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | `com.aspose.imaging.StringFormatFlags` adlı biçimlendirme bilgilerini içeren bir enum. |

### getAlignment() {#getAlignment--}
```
public int getAlignment()
```


Dikey düzlemde metin hizalama bilgilerini alır.

**Returns:**
int - `com.aspose.imaging.StringAlignment` adlı metin hizalama bilgilerini belirten bir enum.
### setAlignment(int value) {#setAlignment-int-}
```
public void setAlignment(int value)
```


Dikey düzlemde metin hizalama bilgilerini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | `com.aspose.imaging.StringAlignment` adlı metin hizalama bilgilerini belirten bir enum. |

### getLineAlignment() {#getLineAlignment--}
```
public int getLineAlignment()
```


Yatay düzlemde satır hizalamasını alır.

**Returns:**
int - `com.aspose.imaging.StringAlignment` adlı satır hizalamasını temsil eden bir enum.
### setLineAlignment(int value) {#setLineAlignment-int-}
```
public void setLineAlignment(int value)
```


Yatay düzlemde satır hizalamasını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | `com.aspose.imaging.StringAlignment` adlı satır hizalamasını temsil eden bir enum. |

### getHotkeyPrefix() {#getHotkeyPrefix--}
```
public int getHotkeyPrefix()
```


Bu `com.aspose.imaging.StringFormat` nesnesi için `com.aspose.imaging.HotkeyPrefix` nesnesini alır.

**Returns:**
int - Bu `com.aspose.imaging.StringFormat` nesnesi için `com.aspose.imaging.HotkeyPrefix` nesnesi, varsayılan değer `F:Aspose.Imaging.HotkeyPrefix.None`.
### setHotkeyPrefix(int value) {#setHotkeyPrefix-int-}
```
public void setHotkeyPrefix(int value)
```


Bu `com.aspose.imaging.StringFormat` nesnesi için `com.aspose.imaging.HotkeyPrefix` nesnesini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | `com.aspose.imaging.StringFormat` nesnesi için `com.aspose.imaging.HotkeyPrefix` nesnesi, varsayılan değer `F:Aspose.Imaging.HotkeyPrefix.None`. |

### getTrimming() {#getTrimming--}
```
public int getTrimming()
```


Bu `com.aspose.imaging.StringFormat` nesnesi için `com.aspose.imaging.StringTrimming` enumerasyonunu alır.

**Returns:**
int - Bu `com.aspose.imaging.StringFormat` nesnesiyle çizilen metnin, yerleşim dikdörtgeninin kenarlarını aştığında nasıl kırpılacağını gösteren `com.aspose.imaging.StringTrimming` adlı bir enum.
### setTrimming(int value) {#setTrimming-int-}
```
public void setTrimming(int value)
```


Bu `com.aspose.imaging.StringFormat` nesnesi için `com.aspose.imaging.StringTrimming` enumerasyonunu ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Bu `com.aspose.imaging.StringFormat` nesnesiyle çizilen metnin, yerleşim dikdörtgeninin kenarlarını aştığında nasıl kırpılacağını gösteren `com.aspose.imaging.StringTrimming` adlı bir enum. |

### getDigitSubstitutionMethod() {#getDigitSubstitutionMethod--}
```
public int getDigitSubstitutionMethod()
```


Rakam ikamesi için kullanılacak yöntemi alır.

**Returns:**
int - Geçerli yazı tipi tarafından desteklenmediği için görüntülenemeyen bir dizedeki karakterlerin nasıl değiştirileceğini belirten `com.aspose.imaging.StringDigitSubstitute` adlı bir enum değeri.

SetDigitSubstitution adlı eski yöntem için ayarlayıcı eklenmiştir.
### setDigitSubstitutionMethod(int value) {#setDigitSubstitutionMethod-int-}
```
public void setDigitSubstitutionMethod(int value)
```


Rakam ikamesi için kullanılacak yöntemi ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | int | `com.aspose.imaging.StringDigitSubstitute` adlı bir enum değeri, geçerli yazı tipi tarafından desteklenmediği için görüntülenemeyen bir dizedeki karakterlerin nasıl değiştirileceğini belirler. |

SetDigitSubstitution adlı eski yöntem için ayarlayıcı eklenmiştir. |

### getDigitSubstitutionLanguage() {#getDigitSubstitutionLanguage--}
```
public int getDigitSubstitutionLanguage()
```


Yerel rakamların batı rakamlarıyla ikame edildiği durumda kullanılan dili alır.

**Returns:**
int - Yerel rakamlar batı rakamlarıyla değiştirildiğinde kullanılacak dili tanımlayan bir Ulusal Dil Desteği (NLS) dil tanımlayıcısı. Bir `System.Globalization.CultureInfo` nesnesinin `P:System.Globalization.CultureInfo.LCID` özelliğini NLS dil tanımlayıcısı olarak geçirebilirsiniz. Örneğin, "ar-EG" yerel ayarını oluşturup ayarladığınızı varsayalım. `com.aspose.imaging.StringDigitSubstitute.Traditional` değerini `com.aspose.imaging.StringFormat.setDigitSubstitution(int)` yöntemine geçirirseniz, gösterim sırasında Arapça-Hint rakamları batı rakamlarıyla değiştirilecektir.
### setDigitSubstitutionLanguage(int value) {#setDigitSubstitutionLanguage-int-}
```
public void setDigitSubstitutionLanguage(int value)
```


Yerel rakamların batı rakamlarıyla ikame edildiği durumda kullanılan dili ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Yerel rakamlar batı rakamlarıyla değiştirildiğinde kullanılacak dili tanımlayan bir Ulusal Dil Desteği (NLS) dil tanımlayıcısı. Bir `System.Globalization.CultureInfo` nesnesinin `P:System.Globalization.CultureInfo.LCID` özelliğini NLS dil tanımlayıcısı olarak geçirebilirsiniz. Örneğin, "ar-EG" yerel ayarını oluşturup ayarladığınızı varsayalım. `com.aspose.imaging.StringDigitSubstitute.Traditional` değerini `com.aspose.imaging.StringFormat.setDigitSubstitution(int)` yöntemine geçirirseniz, gösterim sırasında Arapça-Hint rakamları batı rakamlarıyla değiştirilecektir. |

### getFirstTabOffset() {#getFirstTabOffset--}
```
public float getFirstTabOffset()
```


Bir metin satırının başlangıcı ile ilk sekme durağı arasındaki boşluk sayısını alır.

**Returns:**
float - İlk sekme ofseti.

GetTabStops yöntemi kaldırıldığı için bu özellik eklenmiştir.
### getTabStops() {#getTabStops--}
```
public float[] getTabStops()
```


`P:Aspose.Imaging.getGraphics().PageUnit` özelliği tarafından belirtilen birimlerde sekme durakları arasındaki mesafelerin bir dizisini alır.

**Returns:**
float[] - Sekme durakları.

GetTabStops yöntemi kaldırıldığı için bu özellik eklenmiştir.
### getCustomCharIdent() {#getCustomCharIdent--}
```
public PointF getCustomCharIdent()
```


Özel karakter kimliğini alır.

Değer: Özel karakter tanımlayıcısı.

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - the custom character ident.
### setCustomCharIdent(PointF value) {#setCustomCharIdent-com.aspose.imaging.PointF-}
```
public void setCustomCharIdent(PointF value)
```


Özel karakter kimliğini ayarlar.

Değer: Özel karakter tanımlayıcısı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [PointF](../../com.aspose.imaging/pointf) | özel karakter tanımlayıcısı. |

### deepClone() {#deepClone--}
```
public StringFormat deepClone()
```


Bu `com.aspose.imaging.StringFormat` nesnesinin derin bir klonunu oluşturur.

**Returns:**
[StringFormat](../../com.aspose.imaging/stringformat) - The deep clone of the current `com.aspose.imaging.StringFormat`.
### setTabStops(float firstTabOffset, float[] tabStops) {#setTabStops-float-float---}
```
public void setTabStops(float firstTabOffset, float[] tabStops)
```


Bu `com.aspose.imaging.StringFormat` nesnesi için sekme duraklarını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| firstTabOffset | float | Bir metin satırının başlangıcı ile ilk sekme durağı arasındaki boşluk sayısı. |
| tabStops | float[] | `com.aspose.imaging.Graphics.PageUnit` özelliği tarafından belirtilen birimlerde sekme durakları arasındaki mesafelerin bir dizisi. |

### toString() {#toString--}
```
public String toString()
```


Bu `com.aspose.imaging.StringFormat` nesnesini insan tarafından okunabilir bir dizeye dönüştürür.

**Returns:**
java.lang.String - Bu `com.aspose.imaging.StringFormat` nesnesinin bir dize temsili.
### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


Nesnelerin eşit olup olmadığını kontrol et.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| o | java.lang.Object | Diğer nesne. |

**Returns:**
boolean - Eşitlik karşılaştırma sonucu.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Geçerli nesnenin karma kodunu al.

**Returns:**
int - Hash kodu.
