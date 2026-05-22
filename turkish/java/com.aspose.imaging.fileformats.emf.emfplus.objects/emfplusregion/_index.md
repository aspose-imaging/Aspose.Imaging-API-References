---
title: "EmfPlusRegion"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EmfPlusRegion nesnesi, doğrusal olmayan bir şekli tanımlayan çizgi ve eğri segmentlerini belirtir."
type: docs
weight: 68
url: /tr/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusregion/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusGraphicsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsobjecttype)
```
public final class EmfPlusRegion extends EmfPlusGraphicsObjectType
```

EmfPlusRegion nesnesi, doğrusal olmayan bir şekli tanımlayan çizgi ve eğri segmentlerini belirtir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfPlusRegion()](#EmfPlusRegion--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getRegionNode()](#getRegionNode--) | RegionNodeCount+1 EmfPlusRegionNode nesnesinden oluşan bir dizi alır veya ayarlar (bölüm 2.2.2.40). |
| [setRegionNode(EmfPlusRegionNode[] value)](#setRegionNode-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusRegionNode---) | RegionNodeCount+1 EmfPlusRegionNode nesnesinden oluşan bir dizi alır veya ayarlar (bölüm 2.2.2.40). |
### EmfPlusRegion() {#EmfPlusRegion--}
```
public EmfPlusRegion()
```


### getRegionNode() {#getRegionNode--}
```
public EmfPlusRegionNode[] getRegionNode()
```


RegionNodeCount+1 EmfPlusRegionNode nesnesinden oluşan bir dizi alır veya ayarlar (bölüm 2.2.2.40). Bölgeler, bölge düğümlerinin ikili bir ağacı olarak tanımlanır ve her düğüm MUST ya bir terminal düğüm olmalı ya da bir ya da iki alt düğüm belirtmelidir. RegionNode MUST en az bir öğe içermelidir.

**Returns:**
com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusRegionNode[]
### setRegionNode(EmfPlusRegionNode[] value) {#setRegionNode-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusRegionNode---}
```
public void setRegionNode(EmfPlusRegionNode[] value)
```


RegionNodeCount+1 EmfPlusRegionNode nesnesinden oluşan bir dizi alır veya ayarlar (bölüm 2.2.2.40). Bölgeler, bölge düğümlerinin ikili bir ağacı olarak tanımlanır ve her düğüm MUST ya bir terminal düğüm olmalı ya da bir ya da iki alt düğüm belirtmelidir. RegionNode MUST en az bir öğe içermelidir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [EmfPlusRegionNode\[\]](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnode) |  |

