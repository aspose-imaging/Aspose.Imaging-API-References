---
title: "EmfModifyWorldTransformMode Enumeration"
type: docs
weight: 240
url: /ru/python-net/aspose.imaging.fileformats.emf.emf.consts/emfmodifyworldtransformmode/
---

Перечисление ModifyWorldTransformMode определяет режимы использования указанных данных преобразования<br/>            для изменения преобразования из мирового пространства в пространство страницы, которое в данный момент определено в контексте устройства воспроизведения.

**Module:** [aspose.imaging.fileformats.emf.emf.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emf.consts.EmfModifyWorldTransformMode

## **Members**
| **Имя члена** | **Description** |
| :- | :- |
| MWT_IDENTITY | Сбросить текущую трансформацию, используя единичную матрицу. В этом режиме указанные данные трансформации игнорируются |
| MWT_LEFTMULTIPLY | Умножить текущую трансформацию. В этом режиме указанные данные трансформации являются левым множителем, а <br/>            трансформация, определённая в текущем контексте устройства воспроизведения, — правым множителем |
| MWT_RIGHTMULTIPLY | Умножьте текущую трансформацию. В этом режиме указанные данные трансформации являются правым множителем, <br/>            а трансформация, текущо определённая в контексте устройства воспроизведения, является левым множителем |
| MWT_SET | Выполните функцию записи EMR_SETWORLDTRANSFORM (раздел 2.3.12.2). |
