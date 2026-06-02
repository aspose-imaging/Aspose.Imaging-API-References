---
title: "EmfPlusObject Sınıfı"
type: docs
weight: 330
url: /tr/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusobject/
---

**Summary:** The EmfPlusObject record specifies an object for use in graphics operations. The object definition<br/>            can span multiple records, which is indicated by the value of the Flags field.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusObject

**Inheritance:** EmfPlusObjectRecordType

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [EmfPlusObject(source)](#EmfPlusObject_source_1) | Yeni bir [EmfPlusObject](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusobject/) sınıfı örneği başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| data_size | int | r/w | Takip eden RecordData alanındaki veri baytlarının 32-bit hizalı sayısını TANIMLAMASI gereken 32-bit işaretsiz tam sayıyı alır veya ayarlar.<br/>            Bu sayı 12 baytlık kayıt başlığını içermez. |
| flags | int | r/w | İşlemin nasıl gerçekleştirileceği ve kaydın yapısı hakkında bilgi içeren 16-bit işaretsiz tam sayıyı alır veya ayarlar.<br/>             |
| is_continuable | bool | r/w | Bu örneğin devam edilebilir olup olmadığını gösteren bir değeri alır veya ayarlar.<br/>            Nesne tanımının bir sonraki EmfPlusObject kaydında devam ettiğini gösterir.<br/>            Bu bayrak, nesneyi tanımlayan son kayıtta asla ayarlanmaz. |
| object_data | [EmfPlusGraphicsObjectType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsobjecttype/) | r/w | Bayraklar alanında belirtilen nesne türü için verileri içeren bir bayt dizisini alır veya ayarlar.<br/>            Verinin içeriği ve biçimi her nesne türü için farklı olabilir. Ek bilgi için bölüm 2.2.1'deki bireysel nesne tanımlarına bakın. |
| object_id | System.Byte | r/w | Nesne tanımlayıcısını alır veya ayarlar.<br/>            Bu kayıt tarafından oluşturulan nesneyle ilişkilendirilecek EMF+ Nesne Tablosundaki dizin.<br/>            Değer 0 ile 63 arasında, dahil olmak üzere olmalıdır. |
| object_type | [EmfPlusObjectType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusobjecttype/) | r/w | Nesnenin türünü alır veya ayarlar. |
| size | int | r/w | 12 baytlık kayıt başlığı ve kayda özgü verileri dahil olmak üzere, tüm kayıttaki 32-bit hizalı bayt sayısını belirten 32-bit işaretsiz tam sayıyı alır veya ayarlar.<br/>             |
| total_object_size | int | r/w | Nesnenin toplam boyutunu alır veya ayarlar.<br/>            Kayıt devam edilebilir ise, devam biti ayarlandığında bu alan bulunur.<br/>            Devam eden nesneler, EmfPlusContineudObjectRecord ile başlayan birden çok EMF+ kaydına sahiptir. Her EmfPlusContinuedObjectRecord bir TotalObjectSize içerir. TotalObjectSize kadar bayt okunduktan sonra, sonraki EMF+ kaydı devam eden nesnenin bir parçası olarak ele alınmaz. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Kayıt türünü tanımlayan 16-bit işaretsiz tam sayıyı alır. |


### Constructor: EmfPlusObject(source) {#EmfPlusObject_source_1}


```
 EmfPlusObject(source) 
```

Yeni bir [EmfPlusObject](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusobject/) sınıfı örneği başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | Kaynak. |

