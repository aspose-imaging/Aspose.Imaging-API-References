---
title: "EmfColorAdjustment Sınıfı"
type: docs
weight: 30
url: /tr/python-net/aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/
---

**Summary:** The ColorAdjustment object defines values for adjusting the colors in source bitmaps in bit-block transfers.

**Module:** [aspose.imaging.fileformats.emf.emf.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emf.objects.EmfColorAdjustment

**Inheritance:** EmfObject

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [EmfColorAdjustment()](#EmfColorAdjustment__1) | EmfColorAdjustment sınıfının yeni bir örneğini başlatır |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| blue_gamma | int | r/w | Alır veya ayarlar 16 bit işaretsiz tamsayı, kaynak renklerin <br/>            mavi birincil rengi için n'inci dereceden gama düzeltme değerini belirtir. Bu değer 2,500 ile 65,000 arasında OLMALIdır. <br/>            10,000 değeri gama düzeltmesinin YAPILMAMASI gerektiğini gösterir. |
| parlaklık | int | r/w | Alır veya ayarlar 16 bit işaretli tamsayı, kaynak nesneye uygulanacak parlaklık miktarını belirtir. <br/>            Bu değer –100 ile 100 arasında OLMALIdır.<br/>            Sıfır değeri parlaklık ayarlamasının YAPILMAMASI gerektiğini gösterir. |
| colorfullness | int | r/w | Alır veya ayarlar 16 bit işaretli tamsayı, kaynak nesneye uygulanacak renk doygunluğu miktarını belirtir. <br/>            Bu değer –100 ile 100 arasında OLMALIdır. <br/>            Sıfır değeri renk doygunluğu ayarlamasının YAPILMAMASI gerektiğini gösterir. |
| kontrast | int | r/w | Alır veya ayarlar 16 bit işaretli tamsayı, kaynak nesneye uygulanacak kontrast miktarını belirtir. <br/>            Bu değer –100 ile 100 arasında OLMALIdır. Sıfır değeri kontrast ayarlamasının YAPILMAMASI gerektiğini gösterir. |
| green_gamma | int | r/w | Alır veya ayarlar 16 bit işaretsiz tamsayı, kaynak renklerin yeşil birincil rengi için n'inci dereceden gama düzeltme değerini belirtir. Bu değer 2,500 ile 65,000 arasında OLMALIdır. <br/>            10,000 değeri gama düzeltmesinin YAPILMAMASI gerektiğini gösterir. |
| illuminant_index | [EmfIlluminant](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfilluminant/) | r/w | Alır veya ayarlar 16 bit işaretsiz tamsayı, görüntünün görüntülendiği standart ışık kaynağı tipini, Illuminill sayımından (bölüm 2.1.19) belirtir. |
| red_gamma | int | r/w | Alır veya ayarlar 16 bit işaretsiz tamsayı, kaynak renklerin kırmızı birincil rengi için n'inci dereceden gama düzeltme değerini belirtir. Bu değer 2,500 ile 65,000 arasında OLMALIdır.<br/>            10,000 değeri gama düzeltmesinin YAPILMAMASI gerektiğini gösterir. |
| red_green_tint | int | r/w | Alır veya ayarlar 16 bit işaretli tamsayı, kaynak nesneye uygulanacak kırmızı veya yeşil ton ayarlama miktarını belirtir. Bu değer –100 ile 100 arasında OLMALIdır. <br/>            Pozitif sayılar kırmızıya, negatif sayılar yeşile doğru ayarlar. <br/>            Sıfır değeri ton ayarlamasının YAPILMAMASI gerektiğini gösterir. |
| reference_black | int | r/w | Alır veya ayarlar 16 bit işaretsiz tamsayı, kaynak renkler için siyah referansını belirtir. <br/>            Bu değerden daha koyu renkler siyah olarak kabul edilir. <br/>            Bu değer sıfır ile 4,000 arasında OLMALIdır. |
| reference_white | int | r/w | Alır veya ayarlar 16 bit işaretsiz tamsayı, kaynak renkler için beyaz referansını belirtir. <br/>            Bu değerden daha açık renkler beyaz olarak kabul edilir. <br/>            Bu değer 6,000 ile 10,000 arasında OLMALIdır. |
| size | int | r/w | Alır veya ayarlar 16 bit işaretsiz tamsayı, bu nesnenin bayt cinsinden boyutunu belirtir. Bu DEĞER 0x0018 OLMALIDIR. |
| values | [EmfColorAdjustmentEnum](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfcoloradjustmentenum/) | r/w | Alır veya ayarlar 16 bit işaretsiz tamsayı, çıktı görüntüsünün nasıl hazırlanacağını belirtir. Bu alan NULL olarak ayarlanabilir veya ColorAdjustment sayımındaki (bölüm 2.1.5) değerlerin herhangi bir kombinasyonuna ayarlanabilir. |


### Constructor: EmfColorAdjustment() {#EmfColorAdjustment__1}


```
 EmfColorAdjustment() 
```

EmfColorAdjustment sınıfının yeni bir örneğini başlatır

