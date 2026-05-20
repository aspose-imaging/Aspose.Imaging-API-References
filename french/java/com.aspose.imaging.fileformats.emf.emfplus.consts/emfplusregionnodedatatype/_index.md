---
title: "EmfPlusRegionNodeDataType"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'énumération RegionNodeDataType définit les types de données de nœud de région."
type: docs
weight: 46
url: /fr/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfplusregionnodedatatype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusRegionNodeDataType extends System.Enum
```

L'énumération RegionNodeDataType définit les types de données de nœud de région.

--------------------

Les données du nœud de région sont spécifiées par des objets [EmfPlusRegionNode](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnode) (section 2.2.2.40).
## Champs

| Champ | Description |
| --- | --- |
| [RegionNodeDataTypeAnd](#RegionNodeDataTypeAnd) | Spécifie un nœud de région avec des nœuds enfants. |
| [RegionNodeDataTypeOr](#RegionNodeDataTypeOr) | Spécifie un nœud de région avec des nœuds enfants. |
| [RegionNodeDataTypeXor](#RegionNodeDataTypeXor) | Spécifie un nœud de région avec des nœuds enfants. |
| [RegionNodeDataTypeExclude](#RegionNodeDataTypeExclude) | Spécifie un nœud de région avec des nœuds enfants. |
| [RegionNodeDataTypeComplement](#RegionNodeDataTypeComplement) | Spécifie un nœud de région avec des nœuds enfants. |
| [RegionNodeDataTypeRect](#RegionNodeDataTypeRect) | Spécifie un nœud de région sans nœuds enfants. |
| [RegionNodeDataTypePath](#RegionNodeDataTypePath) | Spécifie un nœud de région sans nœuds enfants. |
| [RegionNodeDataTypeEmpty](#RegionNodeDataTypeEmpty) | Spécifie un nœud de région sans nœuds enfants. |
| [RegionNodeDataTypeInfinite](#RegionNodeDataTypeInfinite) | Spécifie un nœud de région sans nœuds enfants, et ses limites ne sont pas définies. |
### RegionNodeDataTypeAnd {#RegionNodeDataTypeAnd}
```
public static final int RegionNodeDataTypeAnd
```


Spécifie un nœud de région avec des nœuds enfants. Une opération booléenne AND DOIT être appliquée aux nœuds enfants gauche et droit spécifiés par un objet [EmfPlusRegionNodeChildNodes](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnodechildnodes) (section 2.2.2.41).

### RegionNodeDataTypeOr {#RegionNodeDataTypeOr}
```
public static final int RegionNodeDataTypeOr
```


Spécifie un nœud de région avec des nœuds enfants. Une opération booléenne OR DOIT être appliquée aux nœuds enfants gauche et droit spécifiés par un objet [EmfPlusRegionNodeChildNodes](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnodechildnodes).

### RegionNodeDataTypeXor {#RegionNodeDataTypeXor}
```
public static final int RegionNodeDataTypeXor
```


Spécifie un nœud de région avec des nœuds enfants. Une opération booléenne XOR DOIT être appliquée aux nœuds enfants gauche et droit spécifiés par un objet [EmfPlusRegionNodeChildNodes](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnodechildnodes).

### RegionNodeDataTypeExclude {#RegionNodeDataTypeExclude}
```
public static final int RegionNodeDataTypeExclude
```


Spécifie un nœud de région avec des nœuds enfants. Une opération booléenne, définie comme « la partie de la région 1 qui est exclue de la région 2 », DOIT être appliquée aux nœuds enfants gauche et droit spécifiés par un objet [EmfPlusRegionNodeChildNodes](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnodechildnodes).

### RegionNodeDataTypeComplement {#RegionNodeDataTypeComplement}
```
public static final int RegionNodeDataTypeComplement
```


Spécifie un nœud de région avec des nœuds enfants. Une opération booléenne, définie comme « la partie de la région 2 qui est exclue de la région 1 », DOIT être appliquée aux nœuds enfants gauche et droit spécifiés par un objet [EmfPlusRegionNodeChildNodes](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnodechildnodes).

### RegionNodeDataTypeRect {#RegionNodeDataTypeRect}
```
public static final int RegionNodeDataTypeRect
```


Spécifie un nœud de région sans nœuds enfants. Le champ RegionNodeData DOIT spécifier une frontière avec un objet [EmfPlusRectF](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusrectf) (section 2.2.2.39).

### RegionNodeDataTypePath {#RegionNodeDataTypePath}
```
public static final int RegionNodeDataTypePath
```


Spécifie un nœud de région sans nœuds enfants. Le champ RegionNodeData DOIT spécifier une frontière avec un objet [EmfPlusRegionNodePath](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnodepath) (section 2.2.2.42).

### RegionNodeDataTypeEmpty {#RegionNodeDataTypeEmpty}
```
public static final int RegionNodeDataTypeEmpty
```


Spécifie un nœud de région sans nœuds enfants. Le champ RegionNodeData NE DOIT PAS être présent

### RegionNodeDataTypeInfinite {#RegionNodeDataTypeInfinite}
```
public static final int RegionNodeDataTypeInfinite
```


Spécifie un nœud de région sans nœuds enfants, et ses limites ne sont pas définies.

