---
title: "EmfLogPenEx Sınıfı"
type: docs
weight: 190
url: /tr/python-net/aspose.imaging.fileformats.emf.emf.objects/emflogpenex/
---

**Summary:** The LogPenEx object specifies the style, width, and color of an extended logical pen.

**Module:** [aspose.imaging.fileformats.emf.emf.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emf.objects.EmfLogPenEx

**Inheritance:** EmfBasePen

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [EmfLogPenEx()](#EmfLogPenEx__1) | EmfLogPenEx sınıfının yeni bir örneğini başlatır |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| argb_32_color_ref | int | r/w | WMF ColorRef nesnesini alır veya ayarlar ([MS-WMF] bölüm 2.2.2.8). Bu<br/>            alanın yorumlanması, bu bölümdeki tabloda gösterildiği gibi BrushStyle değerine bağlıdır. |
| brush_dib_pattern | [WmfDeviceIndependentBitmap](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap/) | r/w | Fırça dib desenini alır veya ayarlar. |
| brush_hatch | [EmfHatchStyle](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfhatchstyle/) | r/w | Fırça tarama desenini alır veya ayarlar. Bu alanın tanımı, bu bölümdeki tabloda gösterildiği gibi BrushStyle değerine bağlıdır. |
| brush_style | [WmfBrushStyle](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfbrushstyle/) | r/w | Kalem için fırça stilini belirten 32-bit işaretsiz tamsayıyı alır veya ayarlar, WMF BrushStyle numaralandırmasından (<br/>            [MS-WMF] bölüm 2.1.1.4). <br/>            PenStyle alanındaki kalem türü PS_GEOMETRIC ise, bu değer BS_SOLID veya BS_HATCHED OLMAK ZORUNDADIR. Bu alanın değeri BS_NULL olabilir, ancak yalnızca PenStyle'da belirtilen çizgi stili PS_NULL ise. BS_NULL stili, etkisi olmayan bir fırçayı tanımlamak için KULLANILMALIdır. |
| num_style_entities | int | r | StyleEntry alanında belirtilen dizideki öğe sayısını alır. <br/>            PenStyle PS_USERSTYLE belirtmezse bu değer SIFIR OLMALIdır. |
| pen_style | [EmfPenStyle](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfpenstyle/) | r/w | Kalem stilini alır veya ayarlar |
| style_entry | int[] | r/w | İsteğe bağlı 32-bit işaretsiz tamsayı dizisini alır veya ayarlar; bu dizi, <br/>            tire ve boşluk uzunluklarını tanımlar; PenStyle değeri <br/>            PS_USERSTYLE olduğunda. Dizi, <br/>            NumStyleEntries tarafından belirtilen giriş sayısını içerir, ancak sanki sınırsız tekrar ediyormuş gibi kullanılır <br/>            Dizideki ilk giriş ilk tire uzunluğunu belirtir. İkinci <br/>            giriş ilk boşluk uzunluğunu belirtir. Bundan sonra, tire ve boşluk uzunlukları dönüşümlü olarak gelir.<br/>            PenStyle alanındaki kalem türü PS_GEOMETRIC ise, uzunluklar mantıksal birimlerde; aksi takdirde cihaz birimlerinde belirtilir. |
| width | int | r/w | Kalemin çizdiği çizginin genişliğini belirten 32-bit işaretsiz tamsayıyı alır veya ayarlar.<br/>            PenStyle alanındaki kalem türü PS_GEOMETRIC ise, bu değer genişliği mantıksal birimlerde; aksi takdirde genişlik cihaz birimlerinde belirtilir. <br/>            PenStyle alanındaki kalem türü PS_COSMETIC ise, bu değer 0x00000001 OLMAK ZORUNDADIR. |


### Constructor: EmfLogPenEx() {#EmfLogPenEx__1}


```
 EmfLogPenEx() 
```

EmfLogPenEx sınıfının yeni bir örneğini başlatır

