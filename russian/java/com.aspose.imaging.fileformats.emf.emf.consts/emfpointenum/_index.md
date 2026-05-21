---
title: "EmfPointEnum"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Перечисление Point используется для указания того, как точка должна использоваться в вызове рисования."
type: docs
weight: 35
url: /ru/java/com.aspose.imaging.fileformats.emf.emf.consts/emfpointenum/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPointEnum extends System.Enum
```

Перечисление Point используется для указания того, как точка должна использоваться в вызове рисования.
## Поля

| Поле | Описание |
| --- | --- |
| [PT_CLOSEFIGURE](#PT-CLOSEFIGURE) | Тип PT\_LINETO или PT\_BEZIERTO можно комбинировать с этим значением, используя побитовый оператор OR, чтобы указать, что соответствующая точка является последней точкой в фигуре и фигура замкнута. |
| [PT_LINETO](#PT-LINETO) | Указывает, что линия должна быть проведена от текущей позиции к этой точке, после чего она становится новой текущей позицией. |
| [PT_BEZIERTO](#PT-BEZIERTO) | Указывает, что эта точка является контрольной точкой или конечной точкой для кривой Безье. |
| [PT_MOVETO](#PT-MOVETO) | Указывает, что эта точка начинает отдельную фигуру. |
### PT_CLOSEFIGURE {#PT-CLOSEFIGURE}
```
public static final byte PT_CLOSEFIGURE
```


Тип PT\_LINETO или PT\_BEZIERTO можно комбинировать с этим значением, используя побитовый оператор OR, чтобы указать, что соответствующая точка является последней точкой в фигуре и фигура замкнута.

### PT_LINETO {#PT-LINETO}
```
public static final byte PT_LINETO
```


Указывает, что линия должна быть проведена от текущей позиции к этой точке, после чего она становится новой текущей позицией.

### PT_BEZIERTO {#PT-BEZIERTO}
```
public static final byte PT_BEZIERTO
```


Указывает, что эта точка является контрольной точкой или конечной точкой для кривой Безье.

### PT_MOVETO {#PT-MOVETO}
```
public static final byte PT_MOVETO
```


Указывает, что эта точка начинает отдельную фигуру. Эта точка становится новой текущей позицией.

