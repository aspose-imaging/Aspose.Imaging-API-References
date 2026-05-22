---
title: "EmfPlusRegionNode"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EmfPlusRegionNode nesnesi, bir grafik bölgesinin düğümlerini belirtir."
type: docs
weight: 69
url: /tr/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnode/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
```
public final class EmfPlusRegionNode extends EmfPlusStructureObjectType
```

EmfPlusRegionNode nesnesi, bir grafik bölgesinin düğümlerini belirtir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfPlusRegionNode()](#EmfPlusRegionNode--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getRegionNodeData()](#getRegionNodeData--) | İsteğe bağlı, değişken uzunlukta bir veri alır veya ayarlar; bu veri, Type alanında belirtilen bölge düğümü veri nesnesini tanımlar. |
| [setRegionNodeData(EmfPlusStructureObjectType value)](#setRegionNodeData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType-) | İsteğe bağlı, değişken uzunlukta bir veri alır veya ayarlar; bu veri, Type alanında belirtilen bölge düğümü veri nesnesini tanımlar. |
| [getType()](#getType--) | RegionNodeData alanındaki veri tipini belirten 32 bit işaretsiz tam sayı alır veya ayarlar. |
| [setType(int value)](#setType-int-) | RegionNodeData alanındaki veri tipini belirten 32 bit işaretsiz tam sayı alır veya ayarlar. |
### EmfPlusRegionNode() {#EmfPlusRegionNode--}
```
public EmfPlusRegionNode()
```


### getRegionNodeData() {#getRegionNodeData--}
```
public EmfPlusStructureObjectType getRegionNodeData()
```


İsteğe bağlı, değişken uzunlukta bir veri alır veya ayarlar; bu veri, Type alanında belirtilen bölge düğümü veri nesnesini tanımlar. Verinin içeriği ve biçimi her bölge düğümü türü için farklı olabilir. Bu alan, düğüm türü RegionNodeDataTypeEmpty veya RegionNodeDataTypeInfinite ise bulunmamalıdır. Bu nesne geneldir ve farklı bölge düğümü veri türlerini belirtmek için kullanılır; şunları içerir: Terminal bir düğüm için bir EmfPlusRegionNodePath nesnesi (bölüm 2.2.2.42); terminal bir düğüm için bir EmfPlusRectF nesnesi (bölüm 2.2.2.39); ve terminal olmayan bir düğüm için bir EmfPlusRegionNodeChildNodes nesnesi (bölüm 2.2.2.41).

**Returns:**
[EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
### setRegionNodeData(EmfPlusStructureObjectType value) {#setRegionNodeData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType-}
```
public void setRegionNodeData(EmfPlusStructureObjectType value)
```


İsteğe bağlı, değişken uzunlukta bir veri alır veya ayarlar; bu veri, Type alanında belirtilen bölge düğümü veri nesnesini tanımlar. Verinin içeriği ve biçimi her bölge düğümü türü için farklı olabilir. Bu alan, düğüm türü RegionNodeDataTypeEmpty veya RegionNodeDataTypeInfinite ise bulunmamalıdır. Bu nesne geneldir ve farklı bölge düğümü veri türlerini belirtmek için kullanılır; şunları içerir: Terminal bir düğüm için bir EmfPlusRegionNodePath nesnesi (bölüm 2.2.2.42); terminal bir düğüm için bir EmfPlusRectF nesnesi (bölüm 2.2.2.39); ve terminal olmayan bir düğüm için bir EmfPlusRegionNodeChildNodes nesnesi (bölüm 2.2.2.41).

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype) |  |

### getType() {#getType--}
```
public int getType()
```


RegionNodeData alanındaki veri tipini belirten 32 bit işaretsiz tam sayı alır veya ayarlar. Bu değer, RegionNodeDataType numaralandırmasında (bölüm 2.1.1.27) tanımlanmalıdır.

**Returns:**
int
### setType(int value) {#setType-int-}
```
public void setType(int value)
```


RegionNodeData alanındaki veri tipini belirten 32 bit işaretsiz tam sayı alır veya ayarlar. Bu değer, RegionNodeDataType numaralandırmasında (bölüm 2.1.1.27) tanımlanmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

