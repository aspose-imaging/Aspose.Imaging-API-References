---
title: "EmfPlusPenDataFlags"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Флаги PenData указывают свойства графических перьев, включая наличие опциональных полей данных."
type: docs
weight: 42
url: /ru/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfpluspendataflags/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusPenDataFlags extends System.Enum
```

Флаги PenData указывают свойства графических перьев, включая наличие опциональных полей данных. Эти флаги можно комбинировать, чтобы задать несколько вариантов.

--------------------

Графические перья задаются объектами [EmfPlusPen](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspen).
## Поля

| Поле | Описание |
| --- | --- |
| [PenDataTransform](#PenDataTransform) | Если установлен, 2x3 матрица преобразования ДОЛЖНА быть указана в поле OptionalData объекта [EmfPlusPenData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata). |
| [PenDataStartCap](#PenDataStartCap) | Если установлен, стиль начального окончания линии ДОЛЖЕН быть указан в поле OptionalData объекта [EmfPlusPenData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata). |
| [PenDataEndCap](#PenDataEndCap) | Указывает, должен ли стиль конечного окончания линии быть указан в поле OptionalData объекта [EmfPlusPenData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata). |
| [PenDataJoin](#PenDataJoin) | Указывает, должен ли тип соединения линий быть указан в поле OptionalData объекта [EmfPlusPenData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata). |
| [PenDataMiterLimit](#PenDataMiterLimit) | Указывает, должно ли ограничение среза (miter limit) быть указано в поле OptionalData объекта [EmfPlusPenData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata). |
| [PenDataLineStyle](#PenDataLineStyle) | Указывает, должен ли стиль линии быть указан в поле OptionalData объекта [EmfPlusPenData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata). |
| [PenDataDashedLineCap](#PenDataDashedLineCap) | Указывает, должно ли быть указано пунктирное окончание линии в поле OptionalData объекта [EmfPlusPenData](../../com.aspose.imaging/fileformats.emf.emfplus.objects/emfpluspendata). |
| [PenDataDashedLineOffset](#PenDataDashedLineOffset) | Указывает, должно ли быть указано смещение пунктирной линии в поле OptionalData объекта [EmfPlusPenData](../../com.aspose.imaging/fileformats.emf.emfplus.objects/emfpluspendata). |
| [PenDataDashedLine](#PenDataDashedLine) | Указывает, должен ли объект [EmfPlusDashedLineData](../../com.aspose.imaging/fileformats.emf.emfplus.objects/emfplusdashedlinedata) быть указан в поле OptionalData объекта [EmfPlusPenData](../../com.aspose.imaging/fileformats.emf.emfplus.objects/emfpluspendata). |
| [PenDataNonCenter](#PenDataNonCenter) | Указывает, должно ли выравнивание пера быть указано в поле OptionalData объекта [EmfPlusPenData](../../com.aspose.imaging/fileformats.emf.emfplus.objects/emfpluspendata). |
| [PenDataCompoundLine](#PenDataCompoundLine) | Указывает, присутствуют ли длина и содержимое объекта [EmfPlusCompoundLineData](../../com.aspose.imaging/fileformats.emf.emfplus.objects/emfpluscompoundlinedata) в поле OptionalData объекта [EmfPlusPenData](../../com.aspose.imaging/fileformats.emf.emfplus.objects/emfpluspendata). |
| [PenDataCustomStartCap](#PenDataCustomStartCap) | Указывает, должен ли объект [EmfPlusCustomStartCapData](../../com.aspose.imaging/fileformats.emf.emfplus.objects/emfpluscustomstartcapdata) быть указан в поле OptionalData объекта [EmfPlusPenData](../../com.aspose.imaging/fileformats.emf.emfplus.objects/emfpluspendata). |
| [PenDataCustomEndCap](#PenDataCustomEndCap) | Указывает, должен ли объект [EmfPlusCustomEndCapData](../../com.aspose.imaging/fileformats.emf.emfplus.objects/emfpluscustomendcapdata) быть указан в поле OptionalData объекта [EmfPlusPenData](../../com.aspose.imaging/fileformats.emf.emfplus.objects/emfpluspendata). |
### PenDataTransform {#PenDataTransform}
```
public static final int PenDataTransform
```


Если установлен, 2x3 матрица преобразования ДОЛЖНА быть указана в поле OptionalData объекта [EmfPlusPenData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata).

### PenDataStartCap {#PenDataStartCap}
```
public static final int PenDataStartCap
```


Если установлен, стиль начального окончания линии ДОЛЖЕН быть указан в поле OptionalData объекта [EmfPlusPenData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata).

### PenDataEndCap {#PenDataEndCap}
```
public static final int PenDataEndCap
```


Указывает, должен ли стиль конечного окончания линии быть указан в поле OptionalData объекта [EmfPlusPenData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata).

### PenDataJoin {#PenDataJoin}
```
public static final int PenDataJoin
```


Указывает, должен ли тип соединения линий быть указан в поле OptionalData объекта [EmfPlusPenData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata).

### PenDataMiterLimit {#PenDataMiterLimit}
```
public static final int PenDataMiterLimit
```


Указывает, должно ли ограничение среза (miter limit) быть указано в поле OptionalData объекта [EmfPlusPenData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata).

### PenDataLineStyle {#PenDataLineStyle}
```
public static final int PenDataLineStyle
```


Указывает, должен ли стиль линии быть указан в поле OptionalData объекта [EmfPlusPenData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata).

### PenDataDashedLineCap {#PenDataDashedLineCap}
```
public static final int PenDataDashedLineCap
```


Указывает, должно ли быть указано пунктирное окончание линии в поле OptionalData объекта [EmfPlusPenData](../../com.aspose.imaging/fileformats.emf.emfplus.objects/emfpluspendata).

### PenDataDashedLineOffset {#PenDataDashedLineOffset}
```
public static final int PenDataDashedLineOffset
```


Указывает, должно ли быть указано смещение пунктирной линии в поле OptionalData объекта [EmfPlusPenData](../../com.aspose.imaging/fileformats.emf.emfplus.objects/emfpluspendata).

### PenDataDashedLine {#PenDataDashedLine}
```
public static final int PenDataDashedLine
```


Указывает, должен ли объект [EmfPlusDashedLineData](../../com.aspose.imaging/fileformats.emf.emfplus.objects/emfplusdashedlinedata) быть указан в поле OptionalData объекта [EmfPlusPenData](../../com.aspose.imaging/fileformats.emf.emfplus.objects/emfpluspendata).

### PenDataNonCenter {#PenDataNonCenter}
```
public static final int PenDataNonCenter
```


Указывает, должно ли выравнивание пера быть указано в поле OptionalData объекта [EmfPlusPenData](../../com.aspose.imaging/fileformats.emf.emfplus.objects/emfpluspendata).

### PenDataCompoundLine {#PenDataCompoundLine}
```
public static final int PenDataCompoundLine
```


Указывает, присутствуют ли длина и содержимое объекта [EmfPlusCompoundLineData](../../com.aspose.imaging/fileformats.emf.emfplus.objects/emfpluscompoundlinedata) в поле OptionalData объекта [EmfPlusPenData](../../com.aspose.imaging/fileformats.emf.emfplus.objects/emfpluspendata).

### PenDataCustomStartCap {#PenDataCustomStartCap}
```
public static final int PenDataCustomStartCap
```


Указывает, должен ли объект [EmfPlusCustomStartCapData](../../com.aspose.imaging/fileformats.emf.emfplus.objects/emfpluscustomstartcapdata) быть указан в поле OptionalData объекта [EmfPlusPenData](../../com.aspose.imaging/fileformats.emf.emfplus.objects/emfpluspendata).

### PenDataCustomEndCap {#PenDataCustomEndCap}
```
public static final int PenDataCustomEndCap
```


Указывает, должен ли объект [EmfPlusCustomEndCapData](../../com.aspose.imaging/fileformats.emf.emfplus.objects/emfpluscustomendcapdata) быть указан в поле OptionalData объекта [EmfPlusPenData](../../com.aspose.imaging/fileformats.emf.emfplus.objects/emfpluspendata).

