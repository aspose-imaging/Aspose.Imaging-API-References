---
title: "EmfPlusRegionNodeDataType"
second_title: "Aspose.Imaging för Java API-referens"
description: "RegionNodeDataType‑enumerationen definierar typer av regionnoddata."
type: docs
weight: 46
url: /sv/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfplusregionnodedatatype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusRegionNodeDataType extends System.Enum
```

RegionNodeDataType‑enumerationen definierar typer av regionnoddata.

--------------------

Regionnoddata specificeras av [EmfPlusRegionNode](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnode) objekt (avsnitt 2.2.2.40).
## Fält

| Fält | Beskrivning |
| --- | --- |
| [RegionNodeDataTypeAnd](#RegionNodeDataTypeAnd) | Specificerar en regionnod med barnnoder. |
| [RegionNodeDataTypeOr](#RegionNodeDataTypeOr) | Specificerar en regionnod med barnnoder. |
| [RegionNodeDataTypeXor](#RegionNodeDataTypeXor) | Specificerar en regionnod med barnnoder. |
| [RegionNodeDataTypeExclude](#RegionNodeDataTypeExclude) | Specificerar en regionnod med barnnoder. |
| [RegionNodeDataTypeComplement](#RegionNodeDataTypeComplement) | Specificerar en regionnod med barnnoder. |
| [RegionNodeDataTypeRect](#RegionNodeDataTypeRect) | Specificerar en regionnod utan barnnoder. |
| [RegionNodeDataTypePath](#RegionNodeDataTypePath) | Specificerar en regionnod utan barnnoder. |
| [RegionNodeDataTypeEmpty](#RegionNodeDataTypeEmpty) | Specificerar en regionnod utan barnnoder. |
| [RegionNodeDataTypeInfinite](#RegionNodeDataTypeInfinite) | Specificerar en regionnod utan barnnoder, och dess gränser är inte definierade. |
### RegionNodeDataTypeAnd {#RegionNodeDataTypeAnd}
```
public static final int RegionNodeDataTypeAnd
```


Specificerar en regionnod med barnnoder. En Boolean AND‑operation SHOULD tillämpas på vänstra och högra barnnoderna som specificeras av ett [EmfPlusRegionNodeChildNodes](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnodechildnodes)‑objekt (avsnitt 2.2.2.41).

### RegionNodeDataTypeOr {#RegionNodeDataTypeOr}
```
public static final int RegionNodeDataTypeOr
```


Specificerar en regionnod med barnnoder. En Boolean OR‑operation SHOULD tillämpas på vänstra och högra barnnoderna som specificeras av ett [EmfPlusRegionNodeChildNodes](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnodechildnodes)‑objekt.

### RegionNodeDataTypeXor {#RegionNodeDataTypeXor}
```
public static final int RegionNodeDataTypeXor
```


Specificerar en regionnod med barnnoder. En Boolean XOR‑operation SHOULD tillämpas på vänstra och högra barnnoderna som specificeras av ett [EmfPlusRegionNodeChildNodes](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnodechildnodes)‑objekt.

### RegionNodeDataTypeExclude {#RegionNodeDataTypeExclude}
```
public static final int RegionNodeDataTypeExclude
```


Specificerar en regionnod med barnnoder. En Boolean‑operation, definierad som "delen av region 1 som utesluts från region 2", SHOULD tillämpas på vänstra och högra barnnoderna som specificeras av ett [EmfPlusRegionNodeChildNodes](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnodechildnodes)‑objekt.

### RegionNodeDataTypeComplement {#RegionNodeDataTypeComplement}
```
public static final int RegionNodeDataTypeComplement
```


Specificerar en regionnod med barnnoder. En Boolean‑operation, definierad som "delen av region 2 som utesluts från region 1", SHOULD tillämpas på vänstra och högra barnnoderna som specificeras av ett [EmfPlusRegionNodeChildNodes](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnodechildnodes)‑objekt.

### RegionNodeDataTypeRect {#RegionNodeDataTypeRect}
```
public static final int RegionNodeDataTypeRect
```


Specificerar en regionnod utan barnnoder. RegionNodeData‑fältet SHOULD specificera en gräns med ett [EmfPlusRectF](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusrectf)‑objekt (avsnitt 2.2.2.39).

### RegionNodeDataTypePath {#RegionNodeDataTypePath}
```
public static final int RegionNodeDataTypePath
```


Specificerar en regionnod utan barnnoder. RegionNodeData‑fältet SHOULD specificera en gräns med ett [EmfPlusRegionNodePath](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnodepath)‑objekt (avsnitt 2.2.2.42).

### RegionNodeDataTypeEmpty {#RegionNodeDataTypeEmpty}
```
public static final int RegionNodeDataTypeEmpty
```


Specificerar en regionnod utan barnnoder. RegionNodeData‑fältet SHOULD INTE vara närvarande

### RegionNodeDataTypeInfinite {#RegionNodeDataTypeInfinite}
```
public static final int RegionNodeDataTypeInfinite
```


Specificerar en regionnod utan barnnoder, och dess gränser är inte definierade.

