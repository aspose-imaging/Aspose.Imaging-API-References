---
title: "Класс EmfFormat"
type: docs
weight: 60
url: /ru/python-net/aspose.imaging.fileformats.emf.emf.objects/emfformat/
---

**Summary:** The EmrFormat object contains information that identifies the format of image data in an<br/>            EMR_COMMENT_MULTIFORMATS record(section 2.3.3.4.3).

**Module:** [aspose.imaging.fileformats.emf.emf.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emf.objects.EmfFormat

**Inheritance:** EmfObject

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfFormat()](#EmfFormat__1) | Инициализирует новый экземпляр класса EmfFormat |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| off_data | int | r/w | Получает или задает 32‑битное беззнаковое целое, которое указывает смещение данных от <br/>            начала поля идентификатора в записи EMR_COMMENT_PUBLIC (раздел 2.3.3.4). <br/>            Смещение ДОЛЖНО быть выровнено по 32‑битам. |
| signature | [EmfFormatSignature](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfformatsignature/) | r/w | Получает или задает 32‑битное беззнаковое целое, которое указывает формат данных изображения. <br/>            Это значение ДОЛЖНО находиться в перечислении FormatSignature (раздел 2.1.14). |
| size_data | int | r/w | Получает или задает 32‑битное беззнаковое целое, которое указывает размер данных в байтах |
| version | int | r/w | Получает или задает 32‑битное беззнаковое целое, которое указывает номер версии формата. <br/>            Если поле Signature указывает encapsulated PostScript (EPS), <br/>            это значение ДОЛЖНО быть 0x00000001; в противном случае это значение ДОЛЖНО игнорироваться. |


### Constructor: EmfFormat() {#EmfFormat__1}


```
 EmfFormat() 
```

Инициализирует новый экземпляр класса EmfFormat

