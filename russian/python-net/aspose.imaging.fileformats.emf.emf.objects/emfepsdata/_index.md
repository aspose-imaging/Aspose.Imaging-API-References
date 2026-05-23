---
title: "EmfEpsData Класс"
type: docs
weight: 50
url: /ru/python-net/aspose.imaging.fileformats.emf.emf.objects/emfepsdata/
---

**Summary:** The EpsData object is a container for EPS data

**Module:** [aspose.imaging.fileformats.emf.emf.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emf.objects.EmfEpsData

**Inheritance:** EmfObject

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfEpsData()](#EmfEpsData__1) | Инициализирует новый экземпляр класса EmfEpsData |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| points | [EmfPoint28To4[]](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emfpoint28to4/) | r/w | Получает или задает массив из трех объектов Point28_4 (раздел 2.2.23), который определяет <br/>            координаты выходного параллелограмма, используя 28.4‑битную FIX‑нотацию. |
| post_script_data | System.Byte | r/w | Получает или задает массив байтов данных PostScript. Длина этого массива может <br/> вычислена из поля SizeData. Эти данные МОГУТ использоваться для рендеринга изображения. |
| size_data | int | r/w | Получает или задает 32-битное беззнаковое целое, которое указывает общий размер этого объекта в байтах. |
| version | int | r/w | Получает или задает 32-битное беззнаковое целое, которое указывает уровень языка PostScript. Это <br/> значение ДОЛЖНО быть 0x00000001. |


### Constructor: EmfEpsData() {#EmfEpsData__1}


```
 EmfEpsData() 
```

Инициализирует новый экземпляр класса EmfEpsData

