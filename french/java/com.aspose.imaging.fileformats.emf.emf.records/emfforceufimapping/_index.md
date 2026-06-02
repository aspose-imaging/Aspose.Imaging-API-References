---
title: "EmfForceUfiMapping"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'enregistrement EMR_FORCEUFIMAPPING force le mappeur de polices à faire correspondre les polices en fonction de leur UniversalFontId, préférant cela aux informations de leur LogFont (section 2.2.13)."
type: docs
weight: 61
url: /fr/java/com.aspose.imaging.fileformats.emf.emf.records/emfforceufimapping/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfForceUfiMapping extends EmfStateRecordType
```

L'enregistrement EMR\_FORCEUFIMAPPING force le mappeur de polices à faire correspondre les polices en fonction de leur UniversalFontId plutôt qu'en fonction de leurs informations LogFont (section 2.2.13).
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfForceUfiMapping(EmfRecord source)](#EmfForceUfiMapping-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialise une nouvelle instance de la classe `EmfForceUfiMapping`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getUfi()](#getUfi--) | Obtient ou définit l'identifiant de police à utiliser, spécifié comme un UniversalFontId (section 2.2.27). |
| [setUfi(EmfUniversalFontId value)](#setUfi-com.aspose.imaging.fileformats.emf.emf.objects.EmfUniversalFontId-) | Obtient ou définit l'identifiant de police à utiliser, spécifié comme un UniversalFontId (section 2.2.27). |
### EmfForceUfiMapping(EmfRecord source) {#EmfForceUfiMapping-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfForceUfiMapping(EmfRecord source)
```


Initialise une nouvelle instance de la classe `EmfForceUfiMapping`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La source. |

### getUfi() {#getUfi--}
```
public EmfUniversalFontId getUfi()
```


Obtient ou définit l'identifiant de police à utiliser, spécifié comme un UniversalFontId (section 2.2.27).

**Returns:**
[EmfUniversalFontId](../../com.aspose.imaging.fileformats.emf.emf.objects/emfuniversalfontid)
### setUfi(EmfUniversalFontId value) {#setUfi-com.aspose.imaging.fileformats.emf.emf.objects.EmfUniversalFontId-}
```
public void setUfi(EmfUniversalFontId value)
```


Obtient ou définit l'identifiant de police à utiliser, spécifié comme un UniversalFontId (section 2.2.27).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [EmfUniversalFontId](../../com.aspose.imaging.fileformats.emf.emf.objects/emfuniversalfontid) |  |

