---
title: "EmfBeginPath"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Cet enregistrement ouvre un crochet de chemin dans le contexte de périphérique de lecture actuel."
type: docs
weight: 15
url: /fr/java/com.aspose.imaging.fileformats.emf.emf.records/emfbeginpath/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfPathBracketRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfpathbracketrecordtype)
```
public final class EmfBeginPath extends EmfPathBracketRecordType
```

Cet enregistrement ouvre une parenthèse de chemin dans le contexte de périphérique de lecture actuel. Après l'ouverture d'une parenthèse de chemin, une application peut commencer à traiter les enregistrements pour définir les points qui se trouvent dans le chemin. Une application DOIT fermer une parenthèse de chemin ouverte en traitant l'enregistrement EMR\_ENDPATH. Lorsqu'une application traite l'enregistrement EMR\_BEGINPATH, tous les chemins précédents DOIVENT être supprimés du contexte de périphérique de lecture.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfBeginPath()](#EmfBeginPath--) | Initialise une nouvelle instance de la classe `EmfBeginPath`. |
### EmfBeginPath() {#EmfBeginPath--}
```
public EmfBeginPath()
```


Initialise une nouvelle instance de la classe `EmfBeginPath`.

