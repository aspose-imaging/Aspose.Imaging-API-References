---
title: "EmfPlusPathPointFlags Перечисление"
type: docs
weight: 290
url: /ru/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluspathpointflags/
---

32-битное беззнаковое целое, определяющее, как интерпретировать точки и связанные с ними типы точек, определённые этим объектом.<br/>            C  (1 бит): Если установлен, массив PathPoints задаёт абсолютные координаты в пространстве с 16-битными целочисленными координатами.<br/>             Если сброшен, массив PathPoints задаёт абсолютные координаты в пространстве с 32-битными координатами с плавающей точкой.<br/>             Примечание: если флаг P (ниже) установлен, этот флаг МОЖЕТ быть сброшен и ДОЛЖЕН игнорироваться.<br/>            R (1 бит): Если установлен, типы точек в массиве PathPointTypes задаются объектами EmfPlusPathPointTypeRle (раздел 2.2.2.32), <br/>             которые используют сжатие RLE (run‑length encoding), и/или объектами EmfPlusPathPointType (раздел 2.2.2.31). См. раздел 3.1.6 [MS‑WMF] для получения дополнительной информации о сжатии RLE.<br/>             Если сброшен, типы точек в массиве PathPointTypes задаются объектами EmfPlusPathPointType.<br/>            P (1 бит): Если установлен, каждый элемент массива PathPoints задаёт расположение в пространстве координат, относительное к<br/>             расположению, указанному предыдущим элементом массива. Для первого элемента массива PathPoints предполагается предыдущее расположение с координатами (0,0).<br/>             Если сброшен, каждый элемент массива PathPoints задаёт абсолютное расположение.

**Module:** [aspose.imaging.fileformats.emf.emfplus.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.consts.EmfPlusPathPointFlags

## **Members**
| **Имя члена** | **Description** |
| :- | :- |
| C | Флаг c |
| P | Флаг p |
| R | Флаг r |
