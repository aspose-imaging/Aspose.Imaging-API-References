---
title: "EmfEmrComment"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Die EmrComment‑Aufzählung definiert die Datentypen, die ein öffentlicher Kommentar‑Datensatz enthalten kann, wie in Abschnitt 2.3.3.4 angegeben."
type: docs
weight: 18
url: /de/java/com.aspose.imaging.fileformats.emf.emf.consts/emfemrcomment/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfEmrComment extends System.Enum
```

Die Aufzählung EmrComment definiert die Datentypen, die ein öffentlicher Kommentar-Datensatz enthalten kann, wie in Abschnitt 2.3.3.4 angegeben.
## Felder

| Feld | Beschreibung |
| --- | --- |
| [EMR_COMMENT_WINDOWS_METAFILE](#EMR-COMMENT-WINDOWS-METAFILE) | Dieser Kommentar‑Datensatz enthält eine Spezifikation eines Bildes im WMF-Format. |
| [EMR_COMMENT_BEGINGROUP](#EMR-COMMENT-BEGINGROUP) | Dieser Kommentar‑Datensatz identifiziert den Beginn einer Gruppe von Zeichen‑Datensätzen. |
| [EMR_COMMENT_ENDGROUP](#EMR-COMMENT-ENDGROUP) | Dieser Kommentar‑Datensatz identifiziert das Ende einer Gruppe von Zeichen‑Datensätzen. |
| [EMR_COMMENT_MULTIFORMATS](#EMR-COMMENT-MULTIFORMATS) | Dieser Kommentar‑Datensatz ermöglicht das Einbinden mehrerer Bilddefinitionen in die Metadatei. |
| [EMR_COMMENT_UNICODE_STRING](#EMR-COMMENT-UNICODE-STRING) | Dieser Kommentar‑Datensatz ist reserviert und MUSS NICHT in einer EMF‑Metadatei verwendet werden. |
| [EMR_COMMENT_UNICODE_END](#EMR-COMMENT-UNICODE-END) | Dieser Kommentar‑Datensatz ist reserviert und MUSS NICHT in einer EMF‑Metadatei verwendet werden. |
### EMR_COMMENT_WINDOWS_METAFILE {#EMR-COMMENT-WINDOWS-METAFILE}
```
public static final long EMR_COMMENT_WINDOWS_METAFILE
```


Dieser Kommentar‑Datensatz enthält eine Spezifikation eines Bildes im WMF-Format. Siehe [MS-WMF] für weitere Informationen.

### EMR_COMMENT_BEGINGROUP {#EMR-COMMENT-BEGINGROUP}
```
public static final long EMR_COMMENT_BEGINGROUP
```


Dieser Kommentar-Datensatz identifiziert den Beginn einer Gruppe von Zeichen-Datensätzen. Er identifiziert ein Objekt innerhalb einer EMF-Metadatei

### EMR_COMMENT_ENDGROUP {#EMR-COMMENT-ENDGROUP}
```
public static final long EMR_COMMENT_ENDGROUP
```


Dieser Kommentar-Datensatz identifiziert das Ende einer Gruppe von Zeichen-Datensätzen. Für jeden EMR\_COMMENT\_BEGINGROUP-Datensatz muss ein EMR\_COMMENT\_ENDGROUP-Datensatz MUST in die Metadatei aufgenommen werden, und sie MAY verschachtelt sein.

### EMR_COMMENT_MULTIFORMATS {#EMR-COMMENT-MULTIFORMATS}
```
public static final long EMR_COMMENT_MULTIFORMATS
```


Dieser Kommentar-Datensatz ermöglicht es, mehrere Definitionen eines Bildes in die Metadatei aufzunehmen. Mit diesem Kommentar kann beispielsweise eine Anwendung kapsulierten PostScript-Text sowie eine EMF-Definition eines Bildes einbinden.

### EMR_COMMENT_UNICODE_STRING {#EMR-COMMENT-UNICODE-STRING}
```
public static final long EMR_COMMENT_UNICODE_STRING
```


Dieser Kommentar‑Datensatz ist reserviert und MUSS NICHT in einer EMF‑Metadatei verwendet werden.

### EMR_COMMENT_UNICODE_END {#EMR-COMMENT-UNICODE-END}
```
public static final long EMR_COMMENT_UNICODE_END
```


Dieser Kommentar‑Datensatz ist reserviert und MUSS NICHT in einer EMF‑Metadatei verwendet werden.

