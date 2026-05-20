---
title: "EmfSaveDc"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Enregistre l'état actuel du contexte de périphérique de lecture sur une pile d'états sauvegardés par les enregistrements EMR_SAVEDC précédents, le cas échéant."
type: docs
weight: 112
url: /fr/java/com.aspose.imaging.fileformats.emf.emf.records/emfsavedc/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfSaveDc extends EmfStateRecordType
```

Enregistre l'état actuel du contexte de périphérique de lecture sur une pile d'états sauvegardés par les enregistrements EMR\_SAVEDC précédents, le cas échéant. L'état comprend les propriétés graphiques et les objets, y compris le bitmap, le pinceau, la palette, la police, le crayon et la région actuellement sélectionnés. Un enregistrement EMR\_RESTOREDC est utilisé pour restaurer l'état. Cet enregistrement EMF ne spécifie aucun paramètre.

La pile peut contenir des informations d'état pour plusieurs instances du contexte de périphérique de lecture. Lorsqu'un état est restauré, toutes les instances d'état sauvegardées plus récemment DOIVENT être abandonnées.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfSaveDc(EmfRecord source)](#EmfSaveDc-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialise une nouvelle instance de la classe `EmfSaveDc`. |
| [EmfSaveDc()](#EmfSaveDc--) | Initialise une nouvelle instance de la classe `EmfSaveDc`. |
### EmfSaveDc(EmfRecord source) {#EmfSaveDc-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSaveDc(EmfRecord source)
```


Initialise une nouvelle instance de la classe `EmfSaveDc`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La source. |

### EmfSaveDc() {#EmfSaveDc--}
```
public EmfSaveDc()
```


Initialise une nouvelle instance de la classe `EmfSaveDc`.

