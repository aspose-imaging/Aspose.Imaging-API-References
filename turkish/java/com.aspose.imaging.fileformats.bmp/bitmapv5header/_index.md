---
title: "BitmapV5Header"
second_title: "Aspose.Imaging for Java API Referansı"
description: "BitmapV5Header yapısı bitmap bilgi başlık dosyasıdır."
type: docs
weight: 14
url: /tr/java/com.aspose.imaging.fileformats.bmp/bitmapv5header/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.bmp.BitmapCoreHeader](../../com.aspose.imaging.fileformats.bmp/bitmapcoreheader), [com.aspose.imaging.fileformats.bmp.BitmapInfoHeader](../../com.aspose.imaging.fileformats.bmp/bitmapinfoheader), [com.aspose.imaging.fileformats.bmp.BitmapV4Header](../../com.aspose.imaging.fileformats.bmp/bitmapv4header)
```
public class BitmapV5Header extends BitmapV4Header
```

BitmapV5Header yapısı bitmap bilgi başlık dosyasıdır. Bu, BITMAPINFOHEADER yapısının genişletilmiş bir sürümüdür.

Eğer bV5Height negatif ise ve bu bir üstten alta DIB'i gösteriyorsa, bV5Compression ya BI\_RGB ya da BI\_BITFIELDS olmalıdır. Üstten alta DIB'ler sıkıştırılamaz. Bağımsız Renk Yönetimi arayüzü (ICM) 2.0, Uluslararası Renk Konsorsiyumu (ICC) renk profillerinin DIB'lere (DIB'ler) bağlanmasına veya gömülmesine izin verir. Daha fazla bilgi için Using Structures bölümüne bakın. Bir DIB belleğe yüklendiğinde, profil verisi (varsa) renk tablosunun ardından gelmeli ve bV5ProfileData, profil verisinin BITMAPV5HEADER yapısının başlangıcından itibaren ofsetini sağlamalıdır. bV5ProfileData içinde saklanan değer, BITMAPV5HEADER argümanı verildiğinde sizeof operatörü tarafından döndürülen değerden farklı olacaktır, çünkü bV5ProfileData, BITMAPV5HEADER yapısının başlangıcından profil verisinin başlangıcına kadar olan bayt ofsetidir. (Bitmap bitleri bellekte renk tablosunun ardından gelmez). Uygulamalar, DIB belleğe yüklendikten sonra bV5ProfileData üyesini değiştirmelidir. Paketlenmiş DIB'lerde, profil verisi dosya formatına benzer şekilde bitmap bitlerinin ardından gelmelidir. bV5ProfileData üyesi hâlâ profil verisinin BITMAPV5HEADER başlangıcından ofsetini vermelidir. Uygulamalar, yalnızca bV5Size BITMAPV5HEADER boyutuna eşit olduğunda ve bV5CSType PROFILE\_EMBEDDED veya PROFILE\_LINKED olduğunda profil verisine erişmelidir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [BitmapV5Header()](#BitmapV5Header--) | Yeni bir `BitmapV5Header` sınıfı örneği başlatır. |
| [BitmapV5Header(byte[] bytes)](#BitmapV5Header-byte---) | Yeni bir `BitmapV5Header` sınıfı örneği başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getIntent()](#getIntent--) | Bitmap için renderleme amacını alır. |
| [setIntent(long value)](#setIntent-long-) | Bitmap için renderleme amacını ayarlar. |
| [getProfileData()](#getProfileData--) | Profil verisini alır. |
| [setProfileData(long value)](#setProfileData-long-) | Profil verisini ayarlar. |
| [getProfileSize()](#getProfileSize--) | Profilin boyutunu alır. |
| [setProfileSize(long value)](#setProfileSize-long-) | Profilin boyutunu ayarlar. |
| [getReserved()](#getReserved--) | Ayrılmış üye alır. |
| [setReserved(long value)](#setReserved-long-) | Ayrılmış üyeyi ayarlar. |
### BitmapV5Header() {#BitmapV5Header--}
```
public BitmapV5Header()
```


Yeni bir `BitmapV5Header` sınıfı örneği başlatır.

### BitmapV5Header(byte[] bytes) {#BitmapV5Header-byte---}
```
public BitmapV5Header(byte[] bytes)
```


Yeni bir `BitmapV5Header` sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| baytlar | byte[] | Baytlar. |

### getIntent() {#getIntent--}
```
public long getIntent()
```


Bitmap için renderleme amacını alır.

**Returns:**
long - Amaç.
### setIntent(long value) {#setIntent-long-}
```
public void setIntent(long value)
```


Bitmap için renderleme amacını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | long | Amaç. |

### getProfileData() {#getProfileData--}
```
public long getProfileData()
```


Profil verisini alır.

**Returns:**
long - Profil verileri.
### setProfileData(long value) {#setProfileData-long-}
```
public void setProfileData(long value)
```


Profil verisini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | long | Profil verileri. |

### getProfileSize() {#getProfileSize--}
```
public long getProfileSize()
```


Profilin boyutunu alır.

**Returns:**
long - Profilin boyutu.
### setProfileSize(long value) {#setProfileSize-long-}
```
public void setProfileSize(long value)
```


Profilin boyutunu ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | long | Profilin boyutu. |

### getReserved() {#getReserved--}
```
public long getReserved()
```


Ayrılmış üye alır.

**Returns:**
long - Ayrılmış değer.
### setReserved(long value) {#setReserved-long-}
```
public void setReserved(long value)
```


Ayrılmış üyeyi ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | long | Ayrılmış değer. |

