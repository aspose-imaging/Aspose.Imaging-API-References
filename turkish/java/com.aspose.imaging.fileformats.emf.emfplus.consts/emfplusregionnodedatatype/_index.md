---
title: "EmfPlusRegionNodeDataType"
second_title: "Aspose.Imaging for Java API Referansı"
description: "RegionNodeDataType sayımı, bölge düğüm verisinin türlerini tanımlar."
type: docs
weight: 46
url: /tr/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfplusregionnodedatatype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusRegionNodeDataType extends System.Enum
```

RegionNodeDataType sayımı, bölge düğüm verisinin türlerini tanımlar.

--------------------

Bölge düğüm verileri [EmfPlusRegionNode](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnode) nesneleri (bölüm 2.2.2.40) tarafından belirtilir.
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [RegionNodeDataTypeAnd](#RegionNodeDataTypeAnd) | Alt düğümleri olan bir bölge düğümünü belirtir. |
| [RegionNodeDataTypeOr](#RegionNodeDataTypeOr) | Alt düğümleri olan bir bölge düğümünü belirtir. |
| [RegionNodeDataTypeXor](#RegionNodeDataTypeXor) | Alt düğümleri olan bir bölge düğümünü belirtir. |
| [RegionNodeDataTypeExclude](#RegionNodeDataTypeExclude) | Alt düğümleri olan bir bölge düğümünü belirtir. |
| [RegionNodeDataTypeComplement](#RegionNodeDataTypeComplement) | Alt düğümleri olan bir bölge düğümünü belirtir. |
| [RegionNodeDataTypeRect](#RegionNodeDataTypeRect) | Alt düğümü olmayan bir bölge düğümünü belirtir. |
| [RegionNodeDataTypePath](#RegionNodeDataTypePath) | Alt düğümü olmayan bir bölge düğümünü belirtir. |
| [RegionNodeDataTypeEmpty](#RegionNodeDataTypeEmpty) | Alt düğümü olmayan bir bölge düğümünü belirtir. |
| [RegionNodeDataTypeInfinite](#RegionNodeDataTypeInfinite) | Alt düğümü olmayan bir bölge düğümünü belirtir ve sınırları tanımlı değildir. |
### RegionNodeDataTypeAnd {#RegionNodeDataTypeAnd}
```
public static final int RegionNodeDataTypeAnd
```


Alt düğümleri olan bir bölge düğümünü belirtir. Bir Boolean AND işlemi, [EmfPlusRegionNodeChildNodes](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnodechildnodes) nesnesi (bölüm 2.2.2.41) tarafından belirtilen sol ve sağ alt düğümlere uygulanmalıdır.

### RegionNodeDataTypeOr {#RegionNodeDataTypeOr}
```
public static final int RegionNodeDataTypeOr
```


Alt düğümleri olan bir bölge düğümünü belirtir. Bir Boolean OR işlemi, [EmfPlusRegionNodeChildNodes](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnodechildnodes) nesnesi tarafından belirtilen sol ve sağ alt düğümlere uygulanmalıdır.

### RegionNodeDataTypeXor {#RegionNodeDataTypeXor}
```
public static final int RegionNodeDataTypeXor
```


Alt düğümleri olan bir bölge düğümünü belirtir. Bir Boolean XOR işlemi, [EmfPlusRegionNodeChildNodes](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnodechildnodes) nesnesi tarafından belirtilen sol ve sağ alt düğümlere uygulanmalıdır.

### RegionNodeDataTypeExclude {#RegionNodeDataTypeExclude}
```
public static final int RegionNodeDataTypeExclude
```


Alt düğümleri olan bir bölge düğümünü belirtir. "region 1'in region 2'den çıkarılan kısmı" olarak tanımlanan bir Boolean işlemi, [EmfPlusRegionNodeChildNodes](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnodechildnodes) nesnesi tarafından belirtilen sol ve sağ alt düğümlere uygulanmalıdır.

### RegionNodeDataTypeComplement {#RegionNodeDataTypeComplement}
```
public static final int RegionNodeDataTypeComplement
```


Alt düğümleri olan bir bölge düğümünü belirtir. "region 2'nin region 1'den çıkarılan kısmı" olarak tanımlanan bir Boolean işlemi, [EmfPlusRegionNodeChildNodes](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnodechildnodes) nesnesi tarafından belirtilen sol ve sağ alt düğümlere uygulanmalıdır.

### RegionNodeDataTypeRect {#RegionNodeDataTypeRect}
```
public static final int RegionNodeDataTypeRect
```


Alt düğümü olmayan bir bölge düğümünü belirtir. RegionNodeData alanı, bir [EmfPlusRectF](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusrectf) nesnesi (bölüm 2.2.2.39) ile bir sınır belirtmelidir.

### RegionNodeDataTypePath {#RegionNodeDataTypePath}
```
public static final int RegionNodeDataTypePath
```


Alt düğümü olmayan bir bölge düğümünü belirtir. RegionNodeData alanı, bir [EmfPlusRegionNodePath](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnodepath) nesnesi (bölüm 2.2.2.42) ile bir sınır belirtmelidir.

### RegionNodeDataTypeEmpty {#RegionNodeDataTypeEmpty}
```
public static final int RegionNodeDataTypeEmpty
```


Alt düğümü olmayan bir bölge düğümünü belirtir. RegionNodeData alanı bulunmamalıdır.

### RegionNodeDataTypeInfinite {#RegionNodeDataTypeInfinite}
```
public static final int RegionNodeDataTypeInfinite
```


Alt düğümü olmayan bir bölge düğümünü belirtir ve sınırları tanımlı değildir.

