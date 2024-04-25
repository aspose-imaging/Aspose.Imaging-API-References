---
title: WmfLogColorSpace
second_title: Aspose.Imaging for .NET API Referansı
description: LogColorSpace nesnesi ASCII karakterlerinde bir renk profilinin adı olabilen yürütme aygıtı bağlamı için mantıksal bir renk uzayı belirtir.
type: docs
weight: 8750
url: /tr/aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/
---
## WmfLogColorSpace class

LogColorSpace nesnesi, ASCII karakterlerinde bir renk profilinin adı olabilen, yürütme aygıtı bağlamı için mantıksal bir renk uzayı belirtir.

```csharp
public class WmfLogColorSpace : MetaObject
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [WmfLogColorSpace](wmflogcolorspace)() | Default_Constructor |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [ColorSpaceType](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/colorspacetype) { get; set; } | Renk alanı türünü belirten 32 bitlik işaretli bir tamsayı alır veya ayarlar. LogicalColorSpace numaralandırma içinde tanımlanmalıdır ZORUNLU (bölüm 2.1.1.14). Bu değer LCS_sRGB veya LCS_WINDOWS_COLOR_SPACE ise, sRGB renk alanı KULLANILMALIDIR. |
| [Endpoints](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/endpoints) { get; set; } | RGB'ye karşılık gelen üç rengin CIE kromatikliğini x, y ve z koordinatlarını tanımlayan bir CIEXYZTriple nesnesi (bölüm 2.2.2.7) alır veya ayarlarendpoints bitmap ile ilişkili logical renk alanı için. Eğer [`ColorSpaceType`](./colorspacetype) alan LCS_CALIBRATED_RGB belirtmiyor, bu alan MUTLAKA dikkate alınmamalıdır. |
| [Filename](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/filename) { get; set; } | Bir renk profili içeren bir dosyanın adını belirten isteğe bağlı, ASCII karakter dizesini alır veya ayarlar. Bir dosya adı ise ve[`ColorSpaceType`](./colorspacetype) alan LCS_CALIBRATED_RGB olarak ayarlanır, bu yapının diğer alanları yok sayılmalıdır. |
| [GammaBlue](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/gammablue) { get; set; } | Mavi için toned yanıt eğrisini tanımlayan 32 bitlik bir sabit nokta değeri alır veya ayarlar. Eğer[`ColorSpaceType`](./colorspacetype) field , LCS_CALIBRATED_RGB'yi belirtmiyor, bu alan MUTLAKA dikkate alınmamalıdır. |
| [GammaGreen](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/gammagreen) { get; set; } | Yeşil için toned yanıt eğrisini tanımlayan 32 bitlik bir sabit nokta değeri alır veya ayarlar. Eğer[`ColorSpaceType`](./colorspacetype) field , LCS_CALIBRATED_RGB'yi belirtmiyor, bu alan MUTLAKA dikkate alınmamalıdır. |
| [GammaRed](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/gammared) { get; set; } | Kırmızı için toned yanıt eğrisini tanımlayan 32 bitlik bir sabit nokta değeri alır veya ayarlar. Eğer[`ColorSpaceType`](./colorspacetype) field , LCS_CALIBRATED_RGB'yi belirtmiyor, bu alan MUTLAKA dikkate alınmamalıdır. |
| [Intent](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/intent) { get; set; } | Gamut eşleme amacını tanımlayan 32 bitlik işaretli bir tamsayı alır veya ayarlar. GamutMappingIntent numaralandırma (bölüm 2.1.1.11) içinde tanımlanmalıdır ZORUNLU. |
| [Signature](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/signature) { get; set; } | the öğesini belirten 32 bitlik işaretsiz bir tamsayı alır veya ayarlarsignature renk uzayı nesnelerinin; dize "PSOC"nin ASCII kodlaması olan 0x50534F43 değerine AYARLANMALIDIR. |
| [Size](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/size) { get; set; } | the öğesini tanımlayan 32 bitlik işaretsiz bir tamsayı alır veya ayarlarsize bu nesnenin bytes. cinsinden |
| [Version](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/version) { get; set; } | a öğesini tanımlayan 32 bitlik işaretsiz bir tamsayı alır veya ayarlarversion sayı; 0x00000400. OLMALIDIR |

### Notlar

Endpoints, GammaRed, GammaGreen ve GammaBlue alanları, mantıksal bir renk uzayı belirtmek için için kullanılır. Endpoints alanı, the renk uzayının RGB uç noktasının x, y ve z değerlerini içeren bir CIEXYZTriple nesnesidir. Üçlü uyaran değerleri X,Y,Z ve kromatiklik değerleri x,y,z arasındaki ilişki aşağıdaki gibi ifade edilir. x = X/(X+Y+Z) y = Y/(X+Y+Z) z = Z/(X+Y+Z) GammaRed, GammaGreen ve GammaBlue alanları "8.8 sabit nokta" içindeki değerleri içerir tamsayı olmayan sayıları temsil eden bir tekniği olan biçim. Her değer, 8 bit sola kaydırılan birleştirilmiş 16 bits ile birlikte 8 bitlik bir kesir tarafından takip edilen bir sıfır-genişletilmiş 8 bit büyüklüğünden oluşur. Bu nedenle, 32 bitte, NF'nin gerçek değeri 00000000nnnnnnnnffffffff00000000'dır, burada "nnnnnnnn" ve "ffffffff", sırasıyla N ve F'nin ikili temsilleridir. Örneğin, 10.5 gerçek sayısı için, nnnnnnnn 00001010 (ikili 10) ve ffffffff 00000101 (ikili 5) olur ve tam 32-bit ikili değer 00000000000010100000010100000000 olur, bu da 0x000A_50d onaltılık değerdir.

### Ayrıca bakınız

* class [MetaObject](../../aspose.imaging.fileformats.emf/metaobject)
* ad alanı [Aspose.Imaging.FileFormats.Wmf.Objects](../../aspose.imaging.fileformats.wmf.objects)
* toplantı [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
