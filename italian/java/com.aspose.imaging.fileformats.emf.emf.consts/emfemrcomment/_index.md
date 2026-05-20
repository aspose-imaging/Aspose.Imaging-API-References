---
title: "EmfEmrComment"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "L'enumerazione EmrComment definisce i tipi di dati che un record di commento pubblico può contenere come specificato nella sezione 2.3.3.4."
type: docs
weight: 18
url: /it/java/com.aspose.imaging.fileformats.emf.emf.consts/emfemrcomment/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfEmrComment extends System.Enum
```

L'enumerazione EmrComment definisce i tipi di dati che un record di commento pubblico può contenere, come specificato nella sezione 2.3.3.4.
## Campi

| Campo | Descrizione |
| --- | --- |
| [EMR_COMMENT_WINDOWS_METAFILE](#EMR-COMMENT-WINDOWS-METAFILE) | Questo record di commento contiene una specifica di un'immagine in WMF. |
| [EMR_COMMENT_BEGINGROUP](#EMR-COMMENT-BEGINGROUP) | Questo record di commento identifica l'inizio di un gruppo di record di disegno. |
| [EMR_COMMENT_ENDGROUP](#EMR-COMMENT-ENDGROUP) | Questo record di commento identifica la fine di un gruppo di record di disegno. |
| [EMR_COMMENT_MULTIFORMATS](#EMR-COMMENT-MULTIFORMATS) | Questo record di commento consente di includere più definizioni di un'immagine nel metafile. |
| [EMR_COMMENT_UNICODE_STRING](#EMR-COMMENT-UNICODE-STRING) | Questo record di commento è riservato e NON DEVE essere utilizzato in un metafile EMF |
| [EMR_COMMENT_UNICODE_END](#EMR-COMMENT-UNICODE-END) | Questo record di commento è riservato e NON DEVE essere utilizzato in un metafile EMF |
### EMR_COMMENT_WINDOWS_METAFILE {#EMR-COMMENT-WINDOWS-METAFILE}
```
public static final long EMR_COMMENT_WINDOWS_METAFILE
```


Questo record di commento contiene una specifica di un'immagine in WMF. Vedi [MS-WMF] per ulteriori informazioni

### EMR_COMMENT_BEGINGROUP {#EMR-COMMENT-BEGINGROUP}
```
public static final long EMR_COMMENT_BEGINGROUP
```


Questo record di commento identifica l'inizio di un gruppo di record di disegno. Identifica un oggetto all'interno di un metafile EMF

### EMR_COMMENT_ENDGROUP {#EMR-COMMENT-ENDGROUP}
```
public static final long EMR_COMMENT_ENDGROUP
```


Questo record di commento identifica la fine di un gruppo di record di disegno. Per ogni record EMR\_COMMENT\_BEGINGROUP, un record EMR\_COMMENT\_ENDGROUP DEVE essere incluso nel metafile, e possono essere annidati.

### EMR_COMMENT_MULTIFORMATS {#EMR-COMMENT-MULTIFORMATS}
```
public static final long EMR_COMMENT_MULTIFORMATS
```


Questo record di commento consente di includere più definizioni di un'immagine nel metafile. Utilizzando questo commento, ad esempio, un'applicazione può includere testo PostScript incapsulato così come una definizione EMF di un'immagine.

### EMR_COMMENT_UNICODE_STRING {#EMR-COMMENT-UNICODE-STRING}
```
public static final long EMR_COMMENT_UNICODE_STRING
```


Questo record di commento è riservato e NON DEVE essere utilizzato in un metafile EMF

### EMR_COMMENT_UNICODE_END {#EMR-COMMENT-UNICODE-END}
```
public static final long EMR_COMMENT_UNICODE_END
```


Questo record di commento è riservato e NON DEVE essere utilizzato in un metafile EMF

