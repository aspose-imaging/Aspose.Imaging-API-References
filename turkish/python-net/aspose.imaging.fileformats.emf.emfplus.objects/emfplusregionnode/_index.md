---
title: "EmfPlusRegionNode Sınıfı"
type: docs
weight: 600
url: /tr/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnode/
---

**Summary:** The EmfPlusRegionNode object specifies nodes of a graphics region.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusRegionNode

**Inheritance:** EmfPlusStructureObjectType

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [EmfPlusRegionNode()](#EmfPlusRegionNode__1) | EmfPlusRegionNode sınıfının yeni bir örneğini başlatır |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| region_node_data | [EmfPlusStructureObjectType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype/) | r/w | İsteğe bağlı, değişken uzunlukta veri alır veya ayarlar; bu veri Type alanında belirtilen bölge düğümü veri nesnesini tanımlar.<br/>            Verinin içeriği ve biçimi her bölge düğümü türü için farklı olabilir. Bu alan, düğüm türü RegionNodeDataTypeEmpty veya RegionNodeDataTypeInfinite ise BULUNMAMALIDIR.<br/>            Bu nesne genel amaçlıdır ve aşağıdakiler dahil olmak üzere farklı bölge düğümü veri türlerini belirtmek için kullanılır:<br/>            Terminal bir düğüm için bir EmfPlusRegionNodePath nesnesi (bölüm 2.2.2.42);<br/>            Terminal bir düğüm için bir EmfPlusRectF nesnesi (bölüm 2.2.2.39); ve<br/>            Terminal olmayan bir düğüm için bir EmfPlusRegionNodeChildNodes nesnesi (bölüm 2.2.2.41). |
| type | [EmfPlusRegionNodeDataType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusregionnodedatatype/) | r/w | RegionNodeData alanındaki verinin tipini belirten 32-bit işaretsiz tamsayıyı alır veya ayarlar. Bu değer RegionNodeDataType sayım kümesinde (bölüm 2.1.1.27) tanımlanmış OLMAK ZORUNDADIR. |


### Constructor: EmfPlusRegionNode() {#EmfPlusRegionNode__1}


```
 EmfPlusRegionNode() 
```

EmfPlusRegionNode sınıfının yeni bir örneğini başlatır

