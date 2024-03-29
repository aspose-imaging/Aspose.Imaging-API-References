---
title: EmfModifyWorldTransform
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Lenregistrement EMR_MODIFYWORLDTRANSFORM modifie la transformation actuelle de lespace mondial en espace de page dans le contexte du périphérique de lecture.
type: docs
weight: 3840
url: /fr/net/aspose.imaging.fileformats.emf.emf.records/emfmodifyworldtransform/
---
## EmfModifyWorldTransform class

L'enregistrement EMR_MODIFYWORLDTRANSFORM modifie la transformation actuelle de l'espace mondial en espace de page dans le contexte du périphérique de lecture.

```csharp
public sealed class EmfModifyWorldTransform : EmfTransformRecordType
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [EmfModifyWorldTransform](emfmodifyworldtransform#constructor)() | Initialise une nouvelle instance du[`EmfModifyWorldTransform`](../emfmodifyworldtransform) classe. |
| [EmfModifyWorldTransform](emfmodifyworldtransform#constructor_1)(EmfRecord) | Initialise une nouvelle instance du[`EmfModifyWorldTransform`](../emfmodifyworldtransform) classe. |

## Propriétés

| Nom | La description |
| --- | --- |
| [ModifyWorldTransformMode](../../aspose.imaging.fileformats.emf.emf.records/emfmodifyworldtransform/modifyworldtransformmode) { get; set; } | Obtient ou définit un entier non signé 32 bits qui spécifie comment la transformation spécifiée dans Xform est utilisée. Cette valeur DOIT figurer dans l'énumération ModifyWorldTransformMode (section 2.1.24). |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size) { get; set; } | Obtient ou définit la taille de l'enregistrement |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type) { get; set; } | Obtient ou définit le type. |
| [Xform](../../aspose.imaging.fileformats.emf.emf.records/emftransformrecordtype/xform) { get; set; } | Obtient ou définit un objet XForm (section 2.2.28), qui définit une transformation de l'espace universel en espace de page. |

### Remarques

Pour plus d'informations concernant les transformations et les espaces de coordonnées, voir [MSDN-WRLDPGSPC]. Voir section 2.3.12 pour la spécification d'autres types d'enregistrements de transformation.

### Voir également

* class [EmfTransformRecordType](../emftransformrecordtype)
* espace de noms [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* Assemblée [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
