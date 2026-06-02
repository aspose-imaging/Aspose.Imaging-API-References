---
title: "EmfPlusCustomLineCapData Sınıf"
type: docs
weight: 270
url: /tr/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecapdata/
---

**Summary:** The EmfPlusCustomLineCapData object specifies default data for a custom line cap.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCustomLineCapData

**Inheritance:** EmfPlusCustomBaseLineCap

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [EmfPlusCustomLineCapData()](#EmfPlusCustomLineCapData__1) | EmfPlusCustomLineCapData sınıfının yeni bir örneğini başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| base_cap | [EmfPlusLineCapType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluslinecaptype/) | r/w | LineCap numaralandırmasından (section 2.1.1.18) değeri belirten 32-bit işaretsiz tamsayıyı alır veya ayarlar <br/>            özel çizgi kapağının temel alındığı. |
| base_inset | float | r/w | 32-bit kayan nokta değerini alır veya ayarlar, çizgi kapağının başlangıcı ile çizginin sonu arasındaki mesafeyi belirten <br/>            . |
| custom_line_cap_data_flags | [EmfPlusCustomLineCapDataFlags](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluscustomlinecapdataflags/) | r/w | OptionalData alanındaki veriyi belirten 32-bit işaretsiz tamsayıyı alır veya ayarlar. |
| fill_hot_spot | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r/w | Şu anda kullanılmayan bir EmfPlusPointF nesnesini alır veya ayarlar. {0.0, 0.0} olarak ayarlanması ZORUNLUDUR. |
| optional_data | [EmfPlusCustomLineCapOptionalData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecapoptionaldata/) | r/w | Opsiyonel EmfPlusCustomLineCapOptionalData nesnesini (section 2.2.2.14) alır veya ayarlar<br/>             özel grafik çizgi kapağı için ek verileri belirten. T<br/>            alanın belirli içeriği CustomLineCapDataFlags alanının değeri tarafından belirlenir <br/>            . |
| stroke_end_cap | int | r/w | Çizilecek çizginin sonunda kullanılacak çizgi kapağını gösteren LineCap numaralandırmasındaki değeri belirten 32-bit işaretsiz tamsayıyı alır veya ayarlar <br/>            . |
| stroke_hot_spot | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r/w | Şu anda kullanılmayan bir EmfPlusPointF nesnesini alır veya ayarlar. {0.0, 0.0} olarak ayarlanması ZORUNLUDUR. |
| stroke_join | [EmfPlusLineJoinType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluslinejointype/) | r/w | LineJoin numaralandırmasındaki (section 2.1.1.19) değeri belirten 32-bit işaretsiz tamsayıyı alır veya ayarlar <br/>            aynı kalemle çizilen ve uçları buluşan iki çizgiyi nasıl birleştirileceğini belirten. <br/>            iki çizgi ucunun kesişiminde, bir çizgi birleşimi bağlantıyı daha kesintisiz gösterir. |
| stroke_miter_limit | float | r/w | Miter köşesindeki birleşimin kalınlık sınırını, miter uzunluğunun çizgi genişliğine olan maksimum izin verilen oranını ayarlayarak içeren 32-bit kayan nokta değerini alır veya ayarlar <br/>             . |
| stroke_start_cap | int | r/w | Çizilecek çizginin başlangıcında kullanılan çizgi kapağını gösteren LineCap numaralandırmasındaki değeri belirten 32-bit işaretsiz tamsayıyı alır veya ayarlar <br/>            . |
| width_scale | float | r/w | Çizgileri çizmeye kullanılan EmfPlusPen nesnesinin (section 2.2.1.7) genişliğine göre özel çizgi kapağını ölçeklendirme miktarını belirten 32-bit kayan nokta değerini alır veya ayarlar <br/>             . |


### Constructor: EmfPlusCustomLineCapData() {#EmfPlusCustomLineCapData__1}


```
 EmfPlusCustomLineCapData() 
```

EmfPlusCustomLineCapData sınıfının yeni bir örneğini başlatır.

