---
title: "Ölçülen Sınıf"
type: docs
weight: 6150
url: /tr/python-net/aspose.imaging/metered/
---

**Summary:** Provides metered methods for integration

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.Metered

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [Metered()](#Metered__1) | Bu sınıfın yeni bir örneğini başlatır. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [get_consumption_credit()](#get_consumption_credit__1) | Tüketim kredisini alır |
| [get_consumption_quantity()](#get_consumption_quantity__2) | Tüketim dosya boyutunu alır |
| [set_metered_key(public_key, private_key)](#set_metered_key_public_key_private_key_3) | Ayarlar ölçülen public ve private anahtar.<br/>            Ölçülen lisansı satın alırsanız, uygulamayı başlattığınızda bu API çağrılmalıdır, genellikle bu yeterlidir. <br/>            Ancak, tüketim verilerini yükleme sürekli başarısız olur ve 24 saati aşarsa, lisans değerlendirme durumuna ayarlanır, <br/>            bu durumu önlemek için lisans durumunu düzenli olarak kontrol etmelisiniz, eğer değerlendirme durumundaysa, bu API'yi tekrar çağırın. |


### Constructor: Metered() {#Metered__1}


```
 Metered() 
```

Bu sınıfın yeni bir örneğini başlatır.

### Method: get_consumption_credit()  [static] {#get_consumption_credit__1}


```
 get_consumption_credit() 
```

Tüketim kredisini alır

**Returns**

| Tür | Açıklama |
| :- | :- |
| System.Decimal | tüketim miktarı |


### Method: get_consumption_quantity()  [static] {#get_consumption_quantity__2}


```
 get_consumption_quantity() 
```

Tüketim dosya boyutunu alır

**Returns**

| Tür | Açıklama |
| :- | :- |
| System.Decimal | tüketim miktarı |


### Method: set_metered_key(public_key, private_key) {#set_metered_key_public_key_private_key_3}


```
 set_metered_key(public_key, private_key) 
```

Ayarlar ölçülen public ve private anahtar.<br/>            Ölçülen lisansı satın alırsanız, uygulamayı başlattığınızda bu API çağrılmalıdır, genellikle bu yeterlidir. <br/>            Ancak, tüketim verilerini yükleme sürekli başarısız olur ve 24 saati aşarsa, lisans değerlendirme durumuna ayarlanır, <br/>            bu durumu önlemek için lisans durumunu düzenli olarak kontrol etmelisiniz, eğer değerlendirme durumundaysa, bu API'yi tekrar çağırın.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| public_key | string | public anahtar |
| private_key | string | private anahtar |

