---
title: "EmfCloseFigure"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Cet enregistrement ferme une figure ouverte dans un chemin."
type: docs
weight: 22
url: /fr/java/com.aspose.imaging.fileformats.emf.emf.records/emfclosefigure/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfPathBracketRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfpathbracketrecordtype)
```
public final class EmfCloseFigure extends EmfPathBracketRecordType
```

Cet enregistrement ferme une figure ouverte dans un chemin. Le traitement de l'enregistrement EMR\_CLOSEFIGURE DOIT fermer la figure en traçant une ligne depuis la position actuelle jusqu'au premier point de la figure, puis il DOIT connecter les lignes en utilisant le style de jointure de ligne. Si une figure est fermée en traitant l'enregistrement EMR\_LINETO au lieu de l'enregistrement EMR\_CLOSEFIGURE, des embouts sont utilisés pour créer le coin au lieu d'une jointure. EMR\_LINETO est spécifié dans la section 2.3.5.13. L'enregistrement EMR\_CLOSEFIGURE NE DOIT être utilisé que s'il existe une accolade de chemin ouverte dans le contexte du dispositif de lecture. Une figure dans un chemin reste ouverte à moins d'être explicitement fermée en traitant cet enregistrement.

Remarque : une figure peut être ouverte même si le point actuel et le point de départ de la figure sont identiques. Après le traitement de l'enregistrement EMR\_CLOSEFIGURE, l'ajout d'une ligne ou d'une courbe au chemin DOIT démarrer une nouvelle figure.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfCloseFigure()](#EmfCloseFigure--) | Initialise une nouvelle instance de la classe `EmfCloseFigure`. |
### EmfCloseFigure() {#EmfCloseFigure--}
```
public EmfCloseFigure()
```


Initialise une nouvelle instance de la classe `EmfCloseFigure`.

