---
title: "Ölçümlü"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Entegrasyon için ölçülen yöntemler sağlar"
type: docs
weight: 74
url: /tr/java/com.aspose.imaging/metered/
---
**Inheritance:**
java.lang.Object
```
public class Metered
```

Entegrasyon için ölçülen yöntemler sağlar

Bu örnekte, ölçümlü genel ve özel anahtar ayarlamaya çalışılacaktır

`// the component jar file: Metered metered = new Metered(); metered.setMeteredKey("PublicKey", "PrivateKey"); `
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Metered()](#Metered--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getConsumptionQuantity()](#getConsumptionQuantity--) | Tüketim dosya boyutunu alır |
| [getConsumptionCredit()](#getConsumptionCredit--) | Tüketim kredisini alır |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | Ölçümlü genel ve özel anahtarı ayarlar. |
| [equals(Object obj)](#equals-java.lang.Object-) | Belirtilen Object'in bu örnekle eşit olup olmadığını belirler. |
### Metered() {#Metered--}
```
public Metered()
```


### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static BigDecimal getConsumptionQuantity()
```


Tüketim dosya boyutunu alır

**Returns:**
java.math.BigDecimal - tüketim dosya boyutu
### getConsumptionCredit() {#getConsumptionCredit--}
```
public static BigDecimal getConsumptionCredit()
```


Tüketim kredisini alır

**Returns:**
java.math.BigDecimal - tüketim miktarı
### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public void setMeteredKey(String publicKey, String privateKey)
```


Ölçümlü genel ve özel anahtarı ayarlar.

Ölçümlü lisansı satın alırsanız, uygulamayı başlattığınızda bu API çağrılmalıdır, genellikle bu yeterlidir. Ancak, tüketim verilerini yükleme sürekli başarısız olur ve 24 saati aşarsa, lisans değerlendirme durumuna ayarlanır; böyle bir durumu önlemek için lisans durumunu düzenli olarak kontrol etmelisiniz, eğer değerlendirme durumundaysa bu API'yi tekrar çağırın.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| publicKey | java.lang.String | genel anahtar |
| privateKey | java.lang.String | özel anahtar |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Belirtilen Object'in bu örnekle eşit olup olmadığını belirler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | java.lang.Object | Bu örnekle karşılaştırılacak Object. |

**Returns:**
boolean - belirtilen Object bu örnekle eşitse `true`; aksi takdirde `false`.
