---
title: "WmfClipPrecisionFlags"
second_title: "Aspose.Imaging for Java API Referansı"
description: "ClipPrecision Bayrakları, bir kırpma bölgesinin kısmen dışındaki karakterlerin nasıl kırpılacağını tanımlayan kırpma hassasiyetini belirtir."
type: docs
weight: 14
url: /tr/java/com.aspose.imaging.fileformats.wmf.consts/wmfclipprecisionflags/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class WmfClipPrecisionFlags extends System.Enum
```

ClipPrecision Bayrakları, bir kırpma bölgesinin kısmen dışındaki karakterlerin nasıl kırpılacağını tanımlayan kırpma hassasiyetini belirtir. Bu bayraklar birden fazla seçeneği belirtmek için birleştirilebilir.
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [Default](#Default) | Varsayılan kırpmanın KULLANILMASI GEREKİLDİĞİNİ belirtir. |
| [Character](#Character) | Bu değer KULLANILMAMALIDIR. |
| [Stroke](#Stroke) | Bu değer, rasterleştirilmiş, TrueType ve vektör yazı tipleri listelenirken DÖNDÜRÜLEBİLİR. |
| [LhAngles](#LhAngles) | Bu değer, yazı tipi döndürmesini kontrol etmek için aşağıdaki şekilde kullanılır: - Ayarlıysa, tüm yazı tiplerinin döndürmesi KOORDİNAT SİSTEMİNİN YÖNELENDİRMESİNE göre belirlenmelidir; yani yönün solak mı yoksa sağlak mı olduğuna. |
| [TtAlways](#TtAlways) | Bu değer KULLANILMAMALIDIR [34]. |
| [DfaDisable](#DfaDisable) | Bu değer, yazı tipi ilişkilendirmenin KAPATILMASI GEREKİLDİĞİNİ [35] belirtir. |
| [Embedded](#Embedded) | Bu değer, belge içeriğini oluşturmak için yazı tipi gömmenin KULLANILMASI GEREKİLDİĞİNİ belirtir; gömülü yazı tipleri yalnızca okunabilir. |
### Default {#Default}
```
public static final byte Default
```


Varsayılan kırpmanın KULLANILMASI GEREKİLDİĞİNİ belirtir.

### Character {#Character}
```
public static final byte Character
```


Bu değer KULLANILMAMALIDIR.

### Stroke {#Stroke}
```
public static final byte Stroke
```


Bu değer, rasterleştirilmiş, TrueType ve vektör yazı tipleri listelenirken DÖNDÜRÜLEBİLİR. [33] (Windows NT 3.1, Windows NT 3.5, Windows NT 3.51, Windows NT 4.0, Windows 2000 ve Windows XP: Bu değer, yazı tipleri listelendiğinde her zaman döndürülür.)

### LhAngles {#LhAngles}
```
public static final byte LhAngles
```


Bu değer, yazı tipi döndürmesini kontrol etmek için aşağıdaki şekilde kullanılır: - Ayarlıysa, tüm yazı tiplerinin döndürmesi KOORDİNAT SİSTEMİNİN YÖNELENDİRMESİNE göre belirlenmelidir; yani yönün solak mı yoksa sağlak mı olduğuna. - Temizlenmişse, cihaz yazı tipleri saat yönünün tersine döndürülmelidir, ancak diğer yazı tiplerinin döndürmesi KOORDİNAT SİSTEMİNİN YÖNELENDİRMESİNE göre belirlenmelidir.

### TtAlways {#TtAlways}
```
public static final byte TtAlways
```


Bu değer KULLANILMAMALIDIR [34]. [34] Bu değer aşağıdaki Windows sürümlerinde yok sayılır: - Windows Vista - Windows Server 2008 - Windows 7 - Windows Server 2008 R2 - Windows 8 - Windows Server 2012 - Windows 8.1 - Windows Server 2012 R2

### DfaDisable {#DfaDisable}
```
public static final byte DfaDisable
```


Bu değer, yazı tipi ilişkilendirmenin KAPATILMASI GEREKİLDİĞİNİ [35] belirtir. [35] Bu değer Windows 95, Windows 98 ve Windows Millennium Edition'da desteklenmez. Yazı tipi ilişkilendirme Windows 2000, Windows XP ve Windows Server 2003'te kapatılmıştır. Bu değer aşağıdaki Windows sürümlerinde yok sayılır: - Windows Vista - Windows Server 2008 - Windows 7 - Windows Server 2008 R2 - Windows 8 - Windows Server 2012 - Windows 8.1 - Windows Server 2012 R2

### Embedded {#Embedded}
```
public static final byte Embedded
```


Bu değer, belge içeriğini oluşturmak için yazı tipi gömmenin KULLANILMASI GEREKİLDİĞİNİ belirtir; gömülü yazı tipleri yalnızca okunabilir.

