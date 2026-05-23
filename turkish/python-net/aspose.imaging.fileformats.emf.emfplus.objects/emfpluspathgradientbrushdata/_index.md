---
title: "EmfPlusPathGradientBrushData Sınıfı"
type: docs
weight: 500
url: /tr/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata/
---

**Summary:** The EmfPlusPathGradientBrushData object specifies a path gradient for a graphics brush.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPathGradientBrushData

**Inheritance:** EmfPlusBaseBrushData

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [EmfPlusPathGradientBrushData()](#EmfPlusPathGradientBrushData__1) | EmfPlusPathGradientBrushData sınıfının yeni bir örneğini başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| boundary_data | [EmfPlusBoundaryBase](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusboundarybase/) | r/w | Yol degrade fırçasının sınırını alır veya ayarlar; bu sınır bir yol ya da kapalı bir kardinal spline ile belirtilir. <br/>            BrushDataFlags alanında BrushDataPath bayrağı ayarlıysa, bu alan ZORUNLU olarak bir EmfPlusBoundaryPathData nesnesi (bölüm 2.2.2.6) içermelidir; <br/>            aksi takdirde, bu alan ZORUNLU olarak bir EmfPlusBoundaryPointData nesnesi (bölüm 2.2.2.7) içermelidir. |
| brush_data_flags | [EmfPlusBrushDataFlags](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusbrushdataflags/) | r/w | OptionalData alanındaki veriyi belirten 32-bit işaretsiz tam sayıyı alır veya ayarlar.<br/>            Bu değer ZORUNLU olarak BrushData bayraklarından (bölüm 2.1.2.1) oluşmalıdır. Aşağıdaki bayraklar bir yol degrade fırçası için ilgilidir: |
| center_argb_32_color | int | r/w | EmfPlusARGB nesnesini (bölüm 2.2.2.1) alır veya ayarlar; bu nesne yol degrade fırçasının merkez rengini belirtir, yani fırçanın merkez noktasında görülen renk. <br/>            Fırçanın rengi, sınır renginden merkez rengine doğru, sınırdan merkez noktasına doğru hareket ederken kademeli olarak değişir. |
| center_point_f | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r/w | EmfPlusARGB nesnesini (bölüm 2.2.2.1) alır veya ayarlar; bu nesne yol degrade fırçasının merkez rengini belirtir, <br/>            yani fırçanın merkez noktasında görülen renk. Fırçanın rengi, sınır renginden merkez rengine doğru, sınırdan merkez noktasına doğru hareket ederken kademeli olarak değişir. |
| optional_data | [EmfPlusPathGradientBrushOptionalData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushoptionaldata/) | r/w | İsteğe bağlı bir EmfPlusPathGradientBrushOptionalData nesnesini (bölüm 2.2.2.30) alır veya ayarlar; bu nesne yol degrade fırçası için ek verileri belirtir. <br/>            Bu alanın belirli içeriği, BrushDataFlags alanının değerine göre belirlenir. |
| surrounding_argb_32_colors | int[] | r/w | Brush sınırındaki ayrık noktalara renkleri belirten SurroundingColorCount EmfPlusARGB nesnelerinden oluşan bir dizi alır veya ayarlar. |
| wrap_mode | [EmfPlusWrapMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluswrapmode/) | r/w | WrapMode numaralandırmasından (bölüm 2.1.1.34) 32-bit işaretli tam sayıyı alır veya ayarlar; bu değer fırçanın sınırının dışındaki alanın boyanıp boyanmayacağını belirtir. Sınırın dışı boyanırken, sarma modu renk degrade'nin nasıl tekrarlandığını belirler. |


### Constructor: EmfPlusPathGradientBrushData() {#EmfPlusPathGradientBrushData__1}


```
 EmfPlusPathGradientBrushData() 
```

EmfPlusPathGradientBrushData sınıfının yeni bir örneğini başlatır.

