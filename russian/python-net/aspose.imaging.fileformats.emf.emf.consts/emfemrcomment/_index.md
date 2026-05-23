---
title: "Перечисление EmfEmrComment"
type: docs
weight: 90
url: /ru/python-net/aspose.imaging.fileformats.emf.emf.consts/emfemrcomment/
---

Перечисление EmrComment определяет типы данных, которые может содержать публичная запись комментария<br/>            согласно разделу 2.3.3.4.

**Module:** [aspose.imaging.fileformats.emf.emf.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emf.consts.EmfEmrComment

## **Members**
| **Имя члена** | **Description** |
| :- | :- |
| EMR_COMMENT_BEGINGROUP | Эта запись комментария идентифицирует начало группы записей рисования. Она идентифицирует объект внутри метафайла EMF. |
| EMR_COMMENT_ENDGROUP | Эта запись комментария идентифицирует конец группы записей рисования. Для каждой записи EMR_COMMENT_BEGINGROUP<br/>            запись EMR_COMMENT_ENDGROUP ДОЛЖНА быть включена в метафайл, и они МОГУТ быть вложенными. |
| EMR_COMMENT_MULTIFORMATS | Эта запись комментария позволяет включать в метафайл несколько определений изображения. <br/>            Используя этот комментарий, например, приложение может включать инкапсулированный PostScript‑текст, а также определение изображения в формате EMF. |
| EMR_COMMENT_UNICODE_END | Эта запись комментария зарезервирована и НЕ ДОЛЖНА использоваться в метафайле EMF |
| EMR_COMMENT_UNICODE_STRING | Эта запись комментария зарезервирована и НЕ ДОЛЖНА использоваться в метафайле EMF |
| EMR_COMMENT_WINDOWS_METAFILE | Эта запись комментария содержит спецификацию изображения в WMF. См. [MS-WMF] для получения дополнительной информации |
