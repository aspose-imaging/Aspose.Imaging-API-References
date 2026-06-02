---
title: "EmfPlusLineCapType"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Перечисление LineCapType определяет типы окончаний линий, используемых на концах линий, рисуемых графическими перьями."
type: docs
weight: 31
url: /ru/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfpluslinecaptype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusLineCapType extends System.Enum
```

Перечисление LineCapType определяет типы окончаний линий, используемых на концах линий, рисуемых графическими перьями.

--------------------

Graphics line caps are specified by [EmfPlusPen](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspen) objects (section 2.2.1.7).
## Поля

| Поле | Описание |
| --- | --- |
| [LineCapTypeFlat](#LineCapTypeFlat) | Указывает квадратное окончание линии. |
| [LineCapTypeSquare](#LineCapTypeSquare) | Указывает квадратное окончание линии. |
| [LineCapTypeRound](#LineCapTypeRound) | Указывает круглое окончание линии. |
| [LineCapTypeTriangle](#LineCapTypeTriangle) | Указывает треугольное окончание линии. |
| [LineCapTypeNoAnchor](#LineCapTypeNoAnchor) | Указывает, что конец линии не закреплён. |
| [LineCapTypeSquareAnchor](#LineCapTypeSquareAnchor) | Указывает, что конец линии закреплён квадратным окончанием линии. |
| [LineCapTypeRoundAnchor](#LineCapTypeRoundAnchor) | Указывает, что конец линии закреплён круглым окончанием линии. |
| [LineCapTypeDiamondAnchor](#LineCapTypeDiamondAnchor) | Указывает, что конец линии закреплён ромбовидным окончанием линии, представляющим собой квадрат, повернутый на 45 градусов. |
| [LineCapTypeArrowAnchor](#LineCapTypeArrowAnchor) | Указывает, что конец линии закреплён в виде стрелки. |
| [LineCapTypeAnchorMask](#LineCapTypeAnchorMask) | Маска, используемая для проверки, является ли окончание линии закрепляющим. |
| [LineCapTypeCustom](#LineCapTypeCustom) | Указывает пользовательскую заглушку линии. |
### LineCapTypeFlat {#LineCapTypeFlat}
```
public static final int LineCapTypeFlat
```


Указывает квадратное окончание линии. Конец линии ДОЛЖЕН быть последней точкой линии.

### LineCapTypeSquare {#LineCapTypeSquare}
```
public static final int LineCapTypeSquare
```


Указывает квадратное окончание линии. Центр квадрата ДОЛЖЕН находиться в последней точке линии. Ширина квадрата равна ширине линии.

### LineCapTypeRound {#LineCapTypeRound}
```
public static final int LineCapTypeRound
```


Указывает круглое окончание линии. Центр круга ДОЛЖЕН находиться в последней точке линии. Диаметр круга равен ширине линии.

### LineCapTypeTriangle {#LineCapTypeTriangle}
```
public static final int LineCapTypeTriangle
```


Указывает треугольное окончание линии. Основание треугольника ДОЛЖНО находиться в последней точке линии. Основание треугольника равно ширине линии.

### LineCapTypeNoAnchor {#LineCapTypeNoAnchor}
```
public static final int LineCapTypeNoAnchor
```


Указывает, что конец линии не закреплён.

### LineCapTypeSquareAnchor {#LineCapTypeSquareAnchor}
```
public static final int LineCapTypeSquareAnchor
```


Указывает, что конец линии закреплён квадратным окончанием линии. Центр квадрата ДОЛЖЕН находиться в последней точке линии. Высота и ширина квадрата равны ширине линии.

### LineCapTypeRoundAnchor {#LineCapTypeRoundAnchor}
```
public static final int LineCapTypeRoundAnchor
```


Указывает, что конец линии закреплён круглым окончанием линии. Центр круга ДОЛЖЕН находиться в последней точке линии. Круг ДОЛЖЕН БЫТЬ шире линии.

### LineCapTypeDiamondAnchor {#LineCapTypeDiamondAnchor}
```
public static final int LineCapTypeDiamondAnchor
```


Указывает, что конец линии закреплён ромбовидным окончанием линии, представляющим собой квадрат, повернутый на 45 градусов. Центр ромба ДОЛЖЕН находиться в последней точке линии. Ромб ДОЛЖЕН БЫТЬ шире линии.

### LineCapTypeArrowAnchor {#LineCapTypeArrowAnchor}
```
public static final int LineCapTypeArrowAnchor
```


Указывает, что конец линии закреплён в виде стрелки. Острие стрелки ДОЛЖНО находиться в последней точке линии. Стрелка ДОЛЖНА БЫТЬ шире линии.

### LineCapTypeAnchorMask {#LineCapTypeAnchorMask}
```
public static final int LineCapTypeAnchorMask
```


Маска, используемая для проверки, является ли окончание линии закрепляющим.

### LineCapTypeCustom {#LineCapTypeCustom}
```
public static final int LineCapTypeCustom
```


Указывает пользовательскую заглушку линии.

