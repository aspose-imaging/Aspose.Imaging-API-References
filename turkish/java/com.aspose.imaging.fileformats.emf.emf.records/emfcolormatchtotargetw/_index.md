---
title: "EmfColorMatchToTargetW"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EMR_COLORMATCHTOTargetW kaydı, Unicode karakterlerinden oluşan bir dosya adında belirtilen bir renk profiliyle renk eşleştirmesi yapılıp yapılmayacağını belirler."
type: docs
weight: 24
url: /tr/java/com.aspose.imaging.fileformats.emf.emf.records/emfcolormatchtotargetw/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfColorMatchToTargetW extends EmfStateRecordType
```

EMR\_COLORMATCHTOTargetW kaydı, Unicode karakterlerinden oluşan bir dosya adıyla belirtilen bir renk profiliyle renk eşleştirme yapılıp yapılmayacağını belirtir.

EMR\_COLORMATCHTOTargetW kaydı, oynatma aygıtı bağlamında geçerli renk dönüşümünün uygulanıp uygulanmayacağını kontrol etmek için kullanılabilir. dwAction değeri CS\_ENABLE ise renk eşleştirme etkinleştirilir ve geçerli renk dönüşümü sonraki grafik işlemlerine uygulanmalıdır. dwAction CS\_DISABLE olarak ayarlanırsa renk dönüşümü uygulanmamalıdır. Hedefe renk eşleştirme CS\_ENABLE değeriyle etkinleştirildiğinde, renk uzayı veya renk gamı eşleştirmesindeki değişiklikler uygulanmaz. Ancak bu değişiklikler, hedefe renk eşleştirme devre dışı bırakıldığında yürürlüğe girmelidir. dwAction alanı, renk yönetimi zaten bir EMR\_SETICMMODE kaydı (bölüm 2.3.11.14) ile etkinleştirilmediği sürece CS\_DELETE\_TRANSFORM olarak ayarlanmamalıdır.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfColorMatchToTargetW(EmfRecord source)](#EmfColorMatchToTargetW-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | `EmfColorMatchToTargetW` sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getDwAction()](#getDwAction--) | 32-bit işaretsiz tamsayı alır veya ayarlar ve ColorSpace numaralandırmasından (bölüm 2.1.7) bir değeri belirtir. |
| [setDwAction(int value)](#setDwAction-int-) | 32-bit işaretsiz tamsayı alır veya ayarlar ve ColorSpace numaralandırmasından (bölüm 2.1.7) bir değeri belirtir. |
| [getDwFlags()](#getDwFlags--) | 32-bit işaretsiz tamsayı alır veya ayarlar ve ColorMatchToTarget numaralandırmasından (bölüm 2.1.6) bir değeri belirtir. |
| [setDwFlags(int value)](#setDwFlags-int-) | 32-bit işaretsiz tamsayı alır veya ayarlar ve ColorMatchToTarget numaralandırmasından (bölüm 2.1.6) bir değeri belirtir. |
| [getCbName()](#getCbName--) | 32-bit işaretsiz tamsayı alır veya ayarlar ve istenen renk profilinin Unicode UTF16-LE adındaki bayt sayısını belirtir. |
| [setCbName(int value)](#setCbName-int-) | 32-bit işaretsiz tamsayı alır veya ayarlar ve istenen renk profilinin Unicode UTF16-LE adındaki bayt sayısını belirtir. |
| [getCbData()](#getCbData--) | 32-bit işaretsiz tamsayı alır veya ayarlar ve hedef renk profilinin ham verisinin boyutunu belirtir, eğer Veri alanında bulunuyorsa. |
| [setCbData(int value)](#setCbData-int-) | 32-bit işaretsiz tamsayı alır veya ayarlar ve hedef renk profilinin ham verisinin boyutunu belirtir, eğer Veri alanında bulunuyorsa. |
| [getData()](#getData--) | Alır veya ayarlar, bayt cinsinden (cbName + cbData) boyutunda bir dizi, bu dizi istenen renk profilinin UTF16-LE adını ve ham verisini belirtir. |
| [setData(byte[] value)](#setData-byte---) | Alır veya ayarlar, bayt cinsinden (cbName + cbData) boyutunda bir dizi, bu dizi istenen renk profilinin UTF16-LE adını ve ham verisini belirtir. |
| [getName()](#getName--) | Adı alır |
| [getRawData()](#getRawData--) | Ham veriyi alır |
### EmfColorMatchToTargetW(EmfRecord source) {#EmfColorMatchToTargetW-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfColorMatchToTargetW(EmfRecord source)
```


`EmfColorMatchToTargetW` sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Kaynak. |

### getDwAction() {#getDwAction--}
```
public int getDwAction()
```


32-bit işaretsiz tamsayı alır veya ayarlar ve ColorSpace numaralandırmasından (bölüm 2.1.7) bir değeri belirtir.

**Returns:**
int
### setDwAction(int value) {#setDwAction-int-}
```
public void setDwAction(int value)
```


32-bit işaretsiz tamsayı alır veya ayarlar ve ColorSpace numaralandırmasından (bölüm 2.1.7) bir değeri belirtir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getDwFlags() {#getDwFlags--}
```
public int getDwFlags()
```


32-bit işaretsiz tamsayı alır veya ayarlar ve ColorMatchToTarget numaralandırmasından (bölüm 2.1.6) bir değeri belirtir.

**Returns:**
int
### setDwFlags(int value) {#setDwFlags-int-}
```
public void setDwFlags(int value)
```


32-bit işaretsiz tamsayı alır veya ayarlar ve ColorMatchToTarget numaralandırmasından (bölüm 2.1.6) bir değeri belirtir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getCbName() {#getCbName--}
```
public int getCbName()
```


32-bit işaretsiz tamsayı alır veya ayarlar ve istenen renk profilinin Unicode UTF16-LE adındaki bayt sayısını belirtir.

**Returns:**
int
### setCbName(int value) {#setCbName-int-}
```
public void setCbName(int value)
```


32-bit işaretsiz tamsayı alır veya ayarlar ve istenen renk profilinin Unicode UTF16-LE adındaki bayt sayısını belirtir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getCbData() {#getCbData--}
```
public int getCbData()
```


32-bit işaretsiz tamsayı alır veya ayarlar ve hedef renk profilinin ham verisinin boyutunu belirtir, eğer Veri alanında bulunuyorsa.

**Returns:**
int
### setCbData(int value) {#setCbData-int-}
```
public void setCbData(int value)
```


32-bit işaretsiz tamsayı alır veya ayarlar ve hedef renk profilinin ham verisinin boyutunu belirtir, eğer Veri alanında bulunuyorsa.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getData() {#getData--}
```
public byte[] getData()
```


Alır veya ayarlar, bayt cinsinden (cbName + cbData) boyutunda bir dizi, bu dizi istenen renk profilinin UTF16-LE adını ve ham verisini belirtir.

**Returns:**
byte[]
### setData(byte[] value) {#setData-byte---}
```
public void setData(byte[] value)
```


Alır veya ayarlar, bayt cinsinden (cbName + cbData) boyutunda bir dizi, bu dizi istenen renk profilinin UTF16-LE adını ve ham verisini belirtir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte[] |  |

### getName() {#getName--}
```
public String getName()
```


Adı alır

**Returns:**
java.lang.String
### getRawData() {#getRawData--}
```
public byte[] getRawData()
```


Ham veriyi alır

**Returns:**
byte[]
