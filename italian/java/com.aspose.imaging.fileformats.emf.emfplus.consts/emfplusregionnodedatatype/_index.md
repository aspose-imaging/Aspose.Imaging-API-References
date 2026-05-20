---
title: "EmfPlusRegionNodeDataType"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "L'enumerazione RegionNodeDataType definisce i tipi di dati dei nodi di regione."
type: docs
weight: 46
url: /it/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfplusregionnodedatatype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusRegionNodeDataType extends System.Enum
```

L'enumerazione RegionNodeDataType definisce i tipi di dati dei nodi di regione.

--------------------

I dati del nodo di regione sono specificati da oggetti [EmfPlusRegionNode](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnode) (sezione 2.2.2.40).
## Campi

| Campo | Descrizione |
| --- | --- |
| [RegionNodeDataTypeAnd](#RegionNodeDataTypeAnd) | Specifica un nodo di regione con nodi figli. |
| [RegionNodeDataTypeOr](#RegionNodeDataTypeOr) | Specifica un nodo di regione con nodi figli. |
| [RegionNodeDataTypeXor](#RegionNodeDataTypeXor) | Specifica un nodo di regione con nodi figli. |
| [RegionNodeDataTypeExclude](#RegionNodeDataTypeExclude) | Specifica un nodo di regione con nodi figli. |
| [RegionNodeDataTypeComplement](#RegionNodeDataTypeComplement) | Specifica un nodo di regione con nodi figli. |
| [RegionNodeDataTypeRect](#RegionNodeDataTypeRect) | Specifica un nodo di regione senza nodi figli. |
| [RegionNodeDataTypePath](#RegionNodeDataTypePath) | Specifica un nodo di regione senza nodi figli. |
| [RegionNodeDataTypeEmpty](#RegionNodeDataTypeEmpty) | Specifica un nodo di regione senza nodi figli. |
| [RegionNodeDataTypeInfinite](#RegionNodeDataTypeInfinite) | Specifica un nodo di regione senza nodi figli, e i suoi limiti non sono definiti. |
### RegionNodeDataTypeAnd {#RegionNodeDataTypeAnd}
```
public static final int RegionNodeDataTypeAnd
```


Specifica un nodo di regione con nodi figli. Un'operazione Boolean AND DEVE essere applicata ai nodi figli sinistro e destro specificati da un oggetto [EmfPlusRegionNodeChildNodes](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnodechildnodes) (sezione 2.2.2.41).

### RegionNodeDataTypeOr {#RegionNodeDataTypeOr}
```
public static final int RegionNodeDataTypeOr
```


Specifica un nodo di regione con nodi figli. Un'operazione Boolean OR DEVE essere applicata ai nodi figli sinistro e destro specificati da un oggetto [EmfPlusRegionNodeChildNodes](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnodechildnodes) (sezione 2.2.2.41).

### RegionNodeDataTypeXor {#RegionNodeDataTypeXor}
```
public static final int RegionNodeDataTypeXor
```


Specifica un nodo di regione con nodi figli. Un'operazione Boolean XOR DEVE essere applicata ai nodi figli sinistro e destro specificati da un oggetto [EmfPlusRegionNodeChildNodes](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnodechildnodes) (sezione 2.2.2.41).

### RegionNodeDataTypeExclude {#RegionNodeDataTypeExclude}
```
public static final int RegionNodeDataTypeExclude
```


Specifica un nodo di regione con nodi figli. Un'operazione Boolean, definita come \"la parte della regione 1 che è esclusa dalla regione 2\", DEVE essere applicata ai nodi figli sinistro e destro specificati da un oggetto [EmfPlusRegionNodeChildNodes](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnodechildnodes) .

### RegionNodeDataTypeComplement {#RegionNodeDataTypeComplement}
```
public static final int RegionNodeDataTypeComplement
```


Specifica un nodo di regione con nodi figli. Un'operazione Boolean, definita come \"la parte della regione 2 che è esclusa dalla regione 1\", DEVE essere applicata ai nodi figli sinistro e destro specificati da un oggetto [EmfPlusRegionNodeChildNodes](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnodechildnodes) .

### RegionNodeDataTypeRect {#RegionNodeDataTypeRect}
```
public static final int RegionNodeDataTypeRect
```


Specifica un nodo di regione senza nodi figli. Il campo RegionNodeData DEVE specificare un confine con un oggetto [EmfPlusRectF](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusrectf) (sezione 2.2.2.39).

### RegionNodeDataTypePath {#RegionNodeDataTypePath}
```
public static final int RegionNodeDataTypePath
```


Specifica un nodo di regione senza nodi figli. Il campo RegionNodeData DEVE specificare un confine con un oggetto [EmfPlusRegionNodePath](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnodepath) (sezione 2.2.2.42).

### RegionNodeDataTypeEmpty {#RegionNodeDataTypeEmpty}
```
public static final int RegionNodeDataTypeEmpty
```


Specifica un nodo di regione senza nodi figli. Il campo RegionNodeData NON DEVE essere presente

### RegionNodeDataTypeInfinite {#RegionNodeDataTypeInfinite}
```
public static final int RegionNodeDataTypeInfinite
```


Specifica un nodo di regione senza nodi figli, e i suoi limiti non sono definiti.

