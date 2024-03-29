---
title: EmfPointEnum
second_title: Справочник по Aspose.Imaging for .NET API
description: Перечисление Point используется для указания того как точка должна использоваться в вызове рисования.
type: docs
weight: 2790
url: /ru/net/aspose.imaging.fileformats.emf.emf.consts/emfpointenum/
---
## EmfPointEnum enumeration

Перечисление Point используется для указания того, как точка должна использоваться в вызове рисования.

```csharp
[Flags]
public enum EmfPointEnum : byte
```

### Ценности

| Имя | Ценность | Описание |
| --- | --- | --- |
| PT_CLOSEFIGURE | `1` | Тип PT_LINETO или PT_BEZIERTO можно комбинировать с этим значением, используя побитовый оператор ИЛИ, чтобы указать, что соответствующая точка является последней точкой фигуры и фигура закрыта |
| PT_LINETO | `2` | Указывает, что линия должна быть проведена от текущей позиции до этой точки, , которая затем становится новой текущей позицией |
| PT_BEZIERTO | `4` | Указывает, что эта точка является контрольной или конечной точкой кривой Безье. |
| PT_MOVETO | `6` | Указывает, что эта точка начинает непересекающуюся фигуру. Эта точка становится новой текущей позицией. |

### Смотрите также

* пространство имен [Aspose.Imaging.FileFormats.Emf.Emf.Consts](../../aspose.imaging.fileformats.emf.emf.consts)
* сборка [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
