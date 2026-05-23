---
title: "Enumerazione EmfEmrComment"
type: docs
weight: 90
url: /it/python-net/aspose.imaging.fileformats.emf.emf.consts/emfemrcomment/
---

L'enumerazione EmrComment definisce i tipi di dati che un record di commento pubblico può<br/>            contenere, come specificato nella sezione 2.3.3.4.

**Module:** [aspose.imaging.fileformats.emf.emf.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emf.consts.EmfEmrComment

## **Members**
| **Member name** | **Descrizione** |
| :- | :- |
| EMR_COMMENT_BEGINGROUP | Questo record di commento identifica l'inizio di un gruppo di record di disegno. Identifica un oggetto all'interno di un metafile EMF |
| EMR_COMMENT_ENDGROUP | Questo record di commento identifica la fine di un gruppo di record di disegno. Per ogni record EMR_COMMENT_BEGINGROUP<br/>            un record EMR_COMMENT_ENDGROUP DEVE essere incluso nel metafile, e possono essere annidati. |
| EMR_COMMENT_MULTIFORMATS | Questo record di commento consente di includere più definizioni di un'immagine nel metafile. <br/>            Utilizzando questo commento, ad esempio, un'applicazione può includere testo PostScript incapsulato così come una definizione EMF di un'immagine. |
| EMR_COMMENT_UNICODE_END | Questo record di commento è riservato e NON DEVE essere usato in un metafile EMF |
| EMR_COMMENT_UNICODE_STRING | Questo record di commento è riservato e NON DEVE essere usato in un metafile EMF |
| EMR_COMMENT_WINDOWS_METAFILE | Questo record di commento contiene una specifica di un'immagine in WMF. Vedi [MS-WMF] per ulteriori informazioni |
