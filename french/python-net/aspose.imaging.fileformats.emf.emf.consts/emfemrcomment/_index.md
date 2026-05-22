---
title: "Énumération EmfEmrComment"
type: docs
weight: 90
url: /fr/python-net/aspose.imaging.fileformats.emf.emf.consts/emfemrcomment/
---

L'énumération EmrComment définit les types de données qu'un enregistrement de commentaire public peut<br/>            contenir, comme indiqué dans la section 2.3.3.4.

**Module:** [aspose.imaging.fileformats.emf.emf.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emf.consts.EmfEmrComment

## **Members**
| **Nom du membre** | **Description** |
| :- | :- |
| EMR_COMMENT_BEGINGROUP | Cet enregistrement de commentaire identifie le début d'un groupe d'enregistrements de dessin. Il identifie un objet dans un métafichier EMF |
| EMR_COMMENT_ENDGROUP | Cet enregistrement de commentaire identifie la fin d'un groupe d'enregistrements de dessin. Pour chaque EMR_COMMENT_BEGINGROUP<br/>            enregistrement, un EMR_COMMENT_ENDGROUP DOIT être inclus dans le métafichier, et ils PEUVENT être imbriqués. |
| EMR_COMMENT_MULTIFORMATS | Cet enregistrement de commentaire permet d'inclure plusieurs définitions d'une image dans le métafichier. <br/>            En utilisant ce commentaire, par exemple, une application peut inclure du texte PostScript encapsulé ainsi qu'une définition EMF d'une image. |
| EMR_COMMENT_UNICODE_END | Cet enregistrement de commentaire est réservé et NE DOIT PAS être utilisé dans un métafichier EMF |
| EMR_COMMENT_UNICODE_STRING | Cet enregistrement de commentaire est réservé et NE DOIT PAS être utilisé dans un métafichier EMF |
| EMR_COMMENT_WINDOWS_METAFILE | Cet enregistrement de commentaire contient une spécification d'une image en WMF. Voir [MS-WMF] pour plus d'informations |
