---
title: "EmfEmrComment"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Перечисление EmrComment определяет типы данных, которые может содержать публичная запись комментария, как указано в разделе 2.3.3.4."
type: docs
weight: 18
url: /ru/java/com.aspose.imaging.fileformats.emf.emf.consts/emfemrcomment/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfEmrComment extends System.Enum
```

Перечисление EmrComment определяет типы данных, которые может содержать запись публичного комментария, как указано в разделе 2.3.3.4.
## Поля

| Поле | Описание |
| --- | --- |
| [EMR_COMMENT_WINDOWS_METAFILE](#EMR-COMMENT-WINDOWS-METAFILE) | Эта запись комментария содержит спецификацию изображения в формате WMF. |
| [EMR_COMMENT_BEGINGROUP](#EMR-COMMENT-BEGINGROUP) | Эта запись комментария указывает начало группы записей рисования. |
| [EMR_COMMENT_ENDGROUP](#EMR-COMMENT-ENDGROUP) | Эта запись комментария указывает конец группы записей рисования. |
| [EMR_COMMENT_MULTIFORMATS](#EMR-COMMENT-MULTIFORMATS) | Эта запись комментария позволяет включать в метафайл несколько определений изображения. |
| [EMR_COMMENT_UNICODE_STRING](#EMR-COMMENT-UNICODE-STRING) | Эта запись комментария зарезервирована и НЕ ДОЛЖНА ИСПОЛЬЗОВАТЬСЯ в EMF метафайле |
| [EMR_COMMENT_UNICODE_END](#EMR-COMMENT-UNICODE-END) | Эта запись комментария зарезервирована и НЕ ДОЛЖНА ИСПОЛЬЗОВАТЬСЯ в EMF метафайле |
### EMR_COMMENT_WINDOWS_METAFILE {#EMR-COMMENT-WINDOWS-METAFILE}
```
public static final long EMR_COMMENT_WINDOWS_METAFILE
```


Эта запись комментария содержит спецификацию изображения в формате WMF. См. [MS-WMF] для получения дополнительной информации

### EMR_COMMENT_BEGINGROUP {#EMR-COMMENT-BEGINGROUP}
```
public static final long EMR_COMMENT_BEGINGROUP
```


Эта запись комментария определяет начало группы записей рисования. Она определяет объект внутри метафайла EMF

### EMR_COMMENT_ENDGROUP {#EMR-COMMENT-ENDGROUP}
```
public static final long EMR_COMMENT_ENDGROUP
```


Эта запись комментария определяет конец группы записей рисования. Для каждой записи EMR\_COMMENT\_BEGINGROUP запись EMR\_COMMENT\_ENDGROUP ДОЛЖНА быть включена в метафайл, и они МОГУТ быть вложенными.

### EMR_COMMENT_MULTIFORMATS {#EMR-COMMENT-MULTIFORMATS}
```
public static final long EMR_COMMENT_MULTIFORMATS
```


Эта запись комментария позволяет включать в метафайл несколько определений изображения. Используя этот комментарий, например, приложение может включать инкапсулированный PostScript‑текст, а также определение изображения в формате EMF.

### EMR_COMMENT_UNICODE_STRING {#EMR-COMMENT-UNICODE-STRING}
```
public static final long EMR_COMMENT_UNICODE_STRING
```


Эта запись комментария зарезервирована и НЕ ДОЛЖНА ИСПОЛЬЗОВАТЬСЯ в EMF метафайле

### EMR_COMMENT_UNICODE_END {#EMR-COMMENT-UNICODE-END}
```
public static final long EMR_COMMENT_UNICODE_END
```


Эта запись комментария зарезервирована и НЕ ДОЛЖНА ИСПОЛЬЗОВАТЬСЯ в EMF метафайле

