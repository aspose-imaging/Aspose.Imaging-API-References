---
title: "EmfModifyWorldTransformMode"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Перечисление ModifyWorldTransformMode определяет режимы использования указанных данных преобразования для изменения преобразования из мирового пространства в пространство страницы, которое в данный момент определено в контексте устройства воспроизведения."
type: docs
weight: 33
url: /ru/java/com.aspose.imaging.fileformats.emf.emf.consts/emfmodifyworldtransformmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfModifyWorldTransformMode extends System.Enum
```

Перечисление ModifyWorldTransformMode определяет режимы использования указанных данных преобразования для изменения преобразования из мирового пространства в пространство страницы, которое в данный момент определено в контексте устройства воспроизведения.
## Поля

| Поле | Описание |
| --- | --- |
| [MWT_IDENTITY](#MWT-IDENTITY) | Сбросить текущую трансформацию, используя единичную матрицу. |
| [MWT_LEFTMULTIPLY](#MWT-LEFTMULTIPLY) | Умножить текущую трансформацию. |
| [MWT_RIGHTMULTIPLY](#MWT-RIGHTMULTIPLY) | Умножить текущую трансформацию. |
| [MWT_SET](#MWT-SET) | Выполнить функцию записи EMR\_SETWORLDTRANSFORM (раздел 2.3.12.2). |
### MWT_IDENTITY {#MWT-IDENTITY}
```
public static final int MWT_IDENTITY
```


Сбросьте текущую трансформацию, используя единичную матрицу. В этом режиме указанные данные трансформации игнорируются

### MWT_LEFTMULTIPLY {#MWT-LEFTMULTIPLY}
```
public static final int MWT_LEFTMULTIPLY
```


Умножьте текущую трансформацию. В этом режиме указанные данные трансформации являются левым множителем, а трансформация, текущо определённая в контексте устройства воспроизведения, — правым множителем

### MWT_RIGHTMULTIPLY {#MWT-RIGHTMULTIPLY}
```
public static final int MWT_RIGHTMULTIPLY
```


Умножьте текущую трансформацию. В этом режиме указанные данные трансформации являются правым множителем, а трансформация, текущо определённая в контексте устройства воспроизведения, — левым множителем

### MWT_SET {#MWT-SET}
```
public static final int MWT_SET
```


Выполнить функцию записи EMR\_SETWORLDTRANSFORM (раздел 2.3.12.2).

