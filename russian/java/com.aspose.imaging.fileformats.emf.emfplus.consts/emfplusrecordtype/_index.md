---
title: "EmfPlusRecordType"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Перечисление RecordType определяет типы записей, используемые в метафайлах EMF."
type: docs
weight: 45
url: /ru/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusRecordType extends System.Enum
```

Перечисление RecordType определяет типы записей, используемые в метафайлах EMF+.
## Поля

| Поле | Описание |
| --- | --- |
| [EmfPlusHeader](#EmfPlusHeader) | Эта запись указывает начало данных EMF+ в метафайле. |
| [EmfPlusEndOfFile](#EmfPlusEndOfFile) | Эта запись указывает конец данных EMF+ в метафайле. |
| [EmfPlusComment](#EmfPlusComment) | Эта запись задаёт произвольные закрытые данные. |
| [EmfPlusGetDC](#EmfPlusGetDC) | Эта запись указывает, что последующие записи EMF, найденные в метафайле, ДОЛЖНЫ обрабатываться. |
| [EmfPlusMultiFormatStart](#EmfPlusMultiFormatStart) | Эта запись зарезервирована и НЕ ДОЛЖНА использоваться. |
| [EmfPlusMultiFormatSection](#EmfPlusMultiFormatSection) | Эта запись зарезервирована и НЕ ДОЛЖНА использоваться. |
| [EmfPlusMultiFormatEnd](#EmfPlusMultiFormatEnd) | Эта запись зарезервирована и НЕ ДОЛЖНА использоваться. |
| [EmfPlusObject](#EmfPlusObject) | Эта запись указывает объект для использования в графических операциях. |
| [EmfPlusClear](#EmfPlusClear) | Эта запись очищает выходное `coordinate space` и инициализирует его указанным фоновым цветом и прозрачностью. |
| [EmfPlusFillRects](#EmfPlusFillRects) | Эта запись определяет, как заполнять внутренние области серии прямоугольников, используя указанную кисть. |
| [EmfPlusDrawRects](#EmfPlusDrawRects) | Эта запись определяет штрихи пера для рисования серии прямоугольников. |
| [EmfPlusFillPolygon](#EmfPlusFillPolygon) | Эта запись определяет данные для заполнения внутренней области многоугольника, используя указанную кисть. |
| [EmfPlusDrawLines](#EmfPlusDrawLines) | Эта запись определяет штрихи пера для рисования серии соединённых линий. |
| [EmfPlusFillEllipse](#EmfPlusFillEllipse) | Эта запись определяет, как заполнять внутренние области эллипса, используя указанную кисть. |
| [EmfPlusDrawEllipse](#EmfPlusDrawEllipse) | Эта запись определяет штрихи пера для рисования эллипса. |
| [EmfPlusFillPie](#EmfPlusFillPie) | Эта запись определяет, как заполнить секцию внутренней части эллипса с помощью указанной кисти. |
| [EmfPlusDrawPie](#EmfPlusDrawPie) | Эта запись определяет штрихи пера для рисования секции эллипса. |
| [EmfPlusDrawArc](#EmfPlusDrawArc) | Запись определяет штрихи пера для рисования дуги эллипса. |
| [EmfPlusFillRegion](#EmfPlusFillRegion) | Эта запись определяет, как заполнить внутреннюю часть области с помощью указанной кисти. |
| [EmfPlusFillPath](#EmfPlusFillPath) | Запись определяет, как заполнить внутренние части фигур, определенных в графическом пути, с помощью указанной кисти. |
| [EmfPlusDrawPath](#EmfPlusDrawPath) | Запись определяет штрихи пера для рисования фигур в графическом пути. |
| [EmfPlusFillClosedCurve](#EmfPlusFillClosedCurve) | Эта запись определяет, как заполнить внутреннюю часть замкнутого кардинального сплайна с помощью указанной кисти. |
| [EmfPlusDrawClosedCurve](#EmfPlusDrawClosedCurve) | Эта запись определяет перо и штрихи для рисования замкнутого кардинального сплайна. |
| [EmfPlusDrawCurve](#EmfPlusDrawCurve) | Эта запись определяет штрихи пера для рисования кардинального сплайна. |
| [EmfPlusDrawBeziers](#EmfPlusDrawBeziers) | Эта запись определяет штрихи пера для рисования сплайна Безье. |
| [EmfPlusDrawImage](#EmfPlusDrawImage) | Эта запись определяет масштабированный объект [EmfPlusImage](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimage) (раздел 2.2.1.4). |
| [EmfPlusDrawImagePoints](#EmfPlusDrawImagePoints) | Эта запись определяет масштабированный объект EmfPlusImage внутри параллелограмма. |
| [EmfPlusDrawString](#EmfPlusDrawString) | Эта запись определяет текстовую строку на основе шрифта, прямоугольника макета и формата. |
| [EmfPlusSetRenderingOrigin](#EmfPlusSetRenderingOrigin) | Эта запись определяет начало рендеринга в указанные горизонтальные и вертикальные координаты. |
| [EmfPlusSetAntiAliasMode](#EmfPlusSetAntiAliasMode) | Эта запись определяет, включить или отключить сглаживание текста. |
| [EmfPlusSetTextRenderingHint](#EmfPlusSetTextRenderingHint) | Эта запись определяет процесс, используемый для рендеринга текста. |
| [EmfPlusSetTextContrast](#EmfPlusSetTextContrast) | Эта запись устанавливает контраст текста в соответствии с указанным значением гаммы текста. |
| [EmfPlusSetInterpolationMode](#EmfPlusSetInterpolationMode) | Эта запись определяет режим интерполяции объекта в соответствии с указанным типом фильтрации изображения. |
| [EmfPlusSetPixelOffsetMode](#EmfPlusSetPixelOffsetMode) | Эта запись определяет режим смещения пикселей в соответствии с указанным значением центрирования пикселей. |
| [EmfPlusSetCompositingMode](#EmfPlusSetCompositingMode) | Эта запись определяет режим композитинга в соответствии с состоянием альфа-смешивания, которое указывает, как исходные цвета комбинируются с цветами фона. |
| [EmfPlusSetCompositingQuality](#EmfPlusSetCompositingQuality) | Эта запись определяет качество композитинга, которое описывает желаемый уровень качества при создании составных изображений из нескольких объектов. |
| [EmfPlusSave](#EmfPlusSave) | Эта запись сохраняет состояние графики, идентифицированное указанным индексом, в стеке сохранённых состояний графики. |
| [EmfPlusRestore](#EmfPlusRestore) | Эта запись восстанавливает состояние графики, идентифицированное указанным индексом, из стека сохранённых состояний графики. |
| [EmfPlusBeginContainer](#EmfPlusBeginContainer) | Эта запись открывает новый контейнер состояния графики и задаёт для него преобразование. |
| [EmfPlusBeginContainerNoParams](#EmfPlusBeginContainerNoParams) | Эта запись открывает новый контейнер состояния графики. |
| [EmfPlusEndContainer](#EmfPlusEndContainer) | Эта запись закрывает контейнер графического состояния, который ранее был открыт операцией начала контейнера. |
| [EmfPlusSetWorldTransform](#EmfPlusSetWorldTransform) | Эта запись определяет текущую трансформацию мирового пространства в объекте playback device\_context согласно указанной матрице трансформации. |
| [EmfPlusResetWorldTransform](#EmfPlusResetWorldTransform) | Эта запись сбрасывает текущую трансформацию мирового пространства к единичной матрице. |
| [EmfPlusMultiplyWorldTransform](#EmfPlusMultiplyWorldTransform) | Эта запись умножает текущее мировое пространство на указанную матрицу трансформации. |
| [EmfPlusTranslateWorldTransform](#EmfPlusTranslateWorldTransform) | Эта запись применяет трансформацию переноса к текущему мировому пространству с заданными горизонтальными и вертикальными смещениями. |
| [EmfPlusScaleWorldTransform](#EmfPlusScaleWorldTransform) | Эта запись применяет масштабирующую трансформацию к текущему мировому пространству с заданными горизонтальными и вертикальными коэффициентами масштабирования. |
| [EmfPlusRotateWorldTransform](#EmfPlusRotateWorldTransform) | Эта запись вращает текущее мировое пространство на указанный угол. |
| [EmfPlusSetPageTransform](#EmfPlusSetPageTransform) | Эта запись задает дополнительные коэффициенты масштабирования для текущей трансформации мирового пространства. |
| [EmfPlusResetClip](#EmfPlusResetClip) | Эта запись сбрасывает текущий регион отсечения для мирового пространства до бесконечности. |
| [EmfPlusSetClipRect](#EmfPlusSetClipRect) | Эта запись объединяет текущий регион отсечения с прямоугольником. |
| [EmfPlusSetClipPath](#EmfPlusSetClipPath) | Эта запись объединяет текущий регион отсечения с графическим путем. |
| [EmfPlusSetClipRegion](#EmfPlusSetClipRegion) | Эта запись объединяет текущий регион отсечения с другим графическим регионом. |
| [EmfPlusOffsetClip](#EmfPlusOffsetClip) | Эта запись применяет трансформацию переноса к текущему региону отсечения мирового пространства. |
| [EmfPlusDrawDriverString](#EmfPlusDrawDriverString) | Эта запись задает вывод текста с позициями символов. |
| [EmfPlusStrokeFillPath](#EmfPlusStrokeFillPath) | Эта запись закрывает все открытые фигуры в пути, обводит контур пути, используя текущую ручку, и заполняет его внутренность, используя текущую кисть. |
| [EmfPlusSerializableObject](#EmfPlusSerializableObject) | Эта запись определяет блок параметров эффектов изображения, который был сериализован в буфер данных. |
| [EmfPlusSetTSGraphics](#EmfPlusSetTSGraphics) | Эта запись задает состояние контекста графического устройства для терминального сервера. |
| [EmfPlusSetTSClip](#EmfPlusSetTSClip) | Эта запись задает области отсечения в контексте графического устройства для терминального сервера. |
### EmfPlusHeader {#EmfPlusHeader}
```
public static final short EmfPlusHeader
```


Эта запись указывает начало данных EMF+ в метафайле. Она ДОЛЖНА быть встроена в первую запись EMF после записи [EmfMetafileHeader](../../com.aspose.imaging.fileformats.emf.emf.records/emfmetafileheader) ([MS-EMF] раздел 2.3.4.2).

### EmfPlusEndOfFile {#EmfPlusEndOfFile}
```
public static final short EmfPlusEndOfFile
```


Эта запись указывает конец данных EMF+ в метафайле.

### EmfPlusComment {#EmfPlusComment}
```
public static final short EmfPlusComment
```


Эта запись задаёт произвольные закрытые данные.

### EmfPlusGetDC {#EmfPlusGetDC}
```
public static final short EmfPlusGetDC
```


Эта запись указывает, что последующие записи EMF, встреченные в метафайле, ДОЛЖНЫ обрабатываться. Обработка записей EMF прекращается, когда встречается следующая запись EMF+.

### EmfPlusMultiFormatStart {#EmfPlusMultiFormatStart}
```
public static final short EmfPlusMultiFormatStart
```


Эта запись зарезервирована и НЕ ДОЛЖНА использоваться.

### EmfPlusMultiFormatSection {#EmfPlusMultiFormatSection}
```
public static final short EmfPlusMultiFormatSection
```


Эта запись зарезервирована и НЕ ДОЛЖНА использоваться.

### EmfPlusMultiFormatEnd {#EmfPlusMultiFormatEnd}
```
public static final short EmfPlusMultiFormatEnd
```


Эта запись зарезервирована и НЕ ДОЛЖНА использоваться.

### EmfPlusObject {#EmfPlusObject}
```
public static final short EmfPlusObject
```


Эта запись указывает объект для использования в графических операциях.

### EmfPlusClear {#EmfPlusClear}
```
public static final short EmfPlusClear
```


Эта запись очищает выходное `coordinate space` и инициализирует его указанным фоновым цветом и прозрачностью.

### EmfPlusFillRects {#EmfPlusFillRects}
```
public static final short EmfPlusFillRects
```


Эта запись определяет, как заполнять внутренние области серии прямоугольников, используя указанную кисть.

### EmfPlusDrawRects {#EmfPlusDrawRects}
```
public static final short EmfPlusDrawRects
```


Эта запись определяет штрихи пера для рисования серии прямоугольников.

### EmfPlusFillPolygon {#EmfPlusFillPolygon}
```
public static final short EmfPlusFillPolygon
```


Эта запись определяет данные для заполнения внутренней области многоугольника, используя указанную кисть.

### EmfPlusDrawLines {#EmfPlusDrawLines}
```
public static final short EmfPlusDrawLines
```


Эта запись определяет штрихи пера для рисования серии соединённых линий.

### EmfPlusFillEllipse {#EmfPlusFillEllipse}
```
public static final short EmfPlusFillEllipse
```


Эта запись определяет, как заполнять внутренние области эллипса, используя указанную кисть.

### EmfPlusDrawEllipse {#EmfPlusDrawEllipse}
```
public static final short EmfPlusDrawEllipse
```


Эта запись определяет штрихи пера для рисования эллипса.

### EmfPlusFillPie {#EmfPlusFillPie}
```
public static final short EmfPlusFillPie
```


Эта запись определяет, как заполнить секцию внутренней части эллипса с помощью указанной кисти.

### EmfPlusDrawPie {#EmfPlusDrawPie}
```
public static final short EmfPlusDrawPie
```


Эта запись определяет штрихи пера для рисования секции эллипса.

### EmfPlusDrawArc {#EmfPlusDrawArc}
```
public static final short EmfPlusDrawArc
```


Запись определяет штрихи пера для рисования дуги эллипса.

### EmfPlusFillRegion {#EmfPlusFillRegion}
```
public static final short EmfPlusFillRegion
```


Эта запись определяет, как заполнить внутреннюю часть области с помощью указанной кисти.

### EmfPlusFillPath {#EmfPlusFillPath}
```
public static final short EmfPlusFillPath
```


Запись определяет, как заполнять внутренние области фигур, определённых в графическом пути, указанной кистью. Путь — это объект, определяющий произвольную последовательность линий, кривых и фигур.

### EmfPlusDrawPath {#EmfPlusDrawPath}
```
public static final short EmfPlusDrawPath
```


Запись определяет штрихи пера для рисования фигур в графическом пути. Путь — это объект, определяющий произвольную последовательность линий, кривых и фигур.

### EmfPlusFillClosedCurve {#EmfPlusFillClosedCurve}
```
public static final short EmfPlusFillClosedCurve
```


Эта запись определяет, как заполнить внутреннюю часть замкнутого кардинального сплайна с помощью указанной кисти.

### EmfPlusDrawClosedCurve {#EmfPlusDrawClosedCurve}
```
public static final short EmfPlusDrawClosedCurve
```


Эта запись определяет перо и штрихи для рисования замкнутого кардинального сплайна.

### EmfPlusDrawCurve {#EmfPlusDrawCurve}
```
public static final short EmfPlusDrawCurve
```


Эта запись определяет штрихи пера для рисования кардинального сплайна.

### EmfPlusDrawBeziers {#EmfPlusDrawBeziers}
```
public static final short EmfPlusDrawBeziers
```


Эта запись определяет штрихи пера для рисования сплайна Безье.

### EmfPlusDrawImage {#EmfPlusDrawImage}
```
public static final short EmfPlusDrawImage
```


Эта запись определяет масштабированный объект [EmfPlusImage](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimage) (раздел 2.2.1.4). Изображение может состоять либо из растровых данных, либо из данных метафайла.

### EmfPlusDrawImagePoints {#EmfPlusDrawImagePoints}
```
public static final short EmfPlusDrawImagePoints
```


Эта запись определяет масштабированный объект EmfPlusImage внутри параллелограмма. Изображение может состоять либо из растровых данных, либо из данных метафайла.

### EmfPlusDrawString {#EmfPlusDrawString}
```
public static final short EmfPlusDrawString
```


Эта запись определяет текстовую строку на основе шрифта, прямоугольника макета и формата.

### EmfPlusSetRenderingOrigin {#EmfPlusSetRenderingOrigin}
```
public static final short EmfPlusSetRenderingOrigin
```


Эта запись определяет начало отрисовки в указанных горизонтальных и вертикальных координатах. Это применяется к штриховым кистям и к 8‑ и 16‑битным шаблонам дизеринга.

### EmfPlusSetAntiAliasMode {#EmfPlusSetAntiAliasMode}
```
public static final short EmfPlusSetAntiAliasMode
```


Эта запись определяет, включать или отключать сглаживание текста. Сглаживание текста — это метод, позволяющий сделать линии и края глифов символов более плавными при отрисовке на выводной поверхности.

### EmfPlusSetTextRenderingHint {#EmfPlusSetTextRenderingHint}
```
public static final short EmfPlusSetTextRenderingHint
```


Эта запись определяет процесс, используемый для рендеринга текста.

### EmfPlusSetTextContrast {#EmfPlusSetTextContrast}
```
public static final short EmfPlusSetTextContrast
```


Эта запись устанавливает контраст текста в соответствии с указанным значением гаммы текста.

### EmfPlusSetInterpolationMode {#EmfPlusSetInterpolationMode}
```
public static final short EmfPlusSetInterpolationMode
```


Эта запись определяет режим интерполяции объекта в соответствии с указанным типом фильтрации изображения. Режим интерполяции влияет на то, как выполняется масштабирование (растягивание и сжатие).

### EmfPlusSetPixelOffsetMode {#EmfPlusSetPixelOffsetMode}
```
public static final short EmfPlusSetPixelOffsetMode
```


Эта запись определяет режим смещения пикселей в соответствии с указанным значением центрирования пикселей.

### EmfPlusSetCompositingMode {#EmfPlusSetCompositingMode}
```
public static final short EmfPlusSetCompositingMode
```


Эта запись определяет режим композитинга в соответствии с состоянием альфа-смешивания, которое указывает, как исходные цвета комбинируются с цветами фона.

### EmfPlusSetCompositingQuality {#EmfPlusSetCompositingQuality}
```
public static final short EmfPlusSetCompositingQuality
```


Эта запись определяет качество композитинга, которое описывает желаемый уровень качества при создании составных изображений из нескольких объектов.

### EmfPlusSave {#EmfPlusSave}
```
public static final short EmfPlusSave
```


Эта запись сохраняет состояние графики, идентифицированное указанным индексом, в стеке сохранённых состояний графики. Каждый индекс стека связан с конкретным сохранённым состоянием, и индекс используется записью [EmfPlusRestore](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrestore) (section 2.3.7.4) для восстановления состояния.

### EmfPlusRestore {#EmfPlusRestore}
```
public static final short EmfPlusRestore
```


Эта запись восстанавливает состояние графики, идентифицированное указанным индексом, из стека сохранённых состояний графики. Каждый индекс стека связан с конкретным сохранённым состоянием, и индекс определяется записью [EmfPlusSave](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplussave) (section 2.3.7.5) для сохранения состояния.

### EmfPlusBeginContainer {#EmfPlusBeginContainer}
```
public static final short EmfPlusBeginContainer
```


Эта запись открывает новый контейнер состояния графики и задаёт для него преобразование. Контейнеры графики используются для сохранения элементов состояния графики.

### EmfPlusBeginContainerNoParams {#EmfPlusBeginContainerNoParams}
```
public static final short EmfPlusBeginContainerNoParams
```


Эта запись открывает новый контейнер состояния графики.

### EmfPlusEndContainer {#EmfPlusEndContainer}
```
public static final short EmfPlusEndContainer
```


Эта запись закрывает контейнер графического состояния, который ранее был открыт операцией начала контейнера.

### EmfPlusSetWorldTransform {#EmfPlusSetWorldTransform}
```
public static final short EmfPlusSetWorldTransform
```


Эта запись определяет текущую трансформацию мирового пространства в объекте playback device\_context согласно указанной матрице трансформации.

### EmfPlusResetWorldTransform {#EmfPlusResetWorldTransform}
```
public static final short EmfPlusResetWorldTransform
```


Эта запись сбрасывает текущую трансформацию мирового пространства к единичной матрице.

### EmfPlusMultiplyWorldTransform {#EmfPlusMultiplyWorldTransform}
```
public static final short EmfPlusMultiplyWorldTransform
```


Эта запись умножает текущее мировое пространство на указанную матрицу трансформации.

### EmfPlusTranslateWorldTransform {#EmfPlusTranslateWorldTransform}
```
public static final short EmfPlusTranslateWorldTransform
```


Эта запись применяет трансформацию переноса к текущему мировому пространству с заданными горизонтальными и вертикальными смещениями.

### EmfPlusScaleWorldTransform {#EmfPlusScaleWorldTransform}
```
public static final short EmfPlusScaleWorldTransform
```


Эта запись применяет масштабирующую трансформацию к текущему мировому пространству с заданными горизонтальными и вертикальными коэффициентами масштабирования.

### EmfPlusRotateWorldTransform {#EmfPlusRotateWorldTransform}
```
public static final short EmfPlusRotateWorldTransform
```


Эта запись вращает текущее мировое пространство на указанный угол.

### EmfPlusSetPageTransform {#EmfPlusSetPageTransform}
```
public static final short EmfPlusSetPageTransform
```


Эта запись задает дополнительные коэффициенты масштабирования для текущей трансформации мирового пространства.

### EmfPlusResetClip {#EmfPlusResetClip}
```
public static final short EmfPlusResetClip
```


Эта запись сбрасывает текущий регион отсечения для мирового пространства до бесконечности.

### EmfPlusSetClipRect {#EmfPlusSetClipRect}
```
public static final short EmfPlusSetClipRect
```


Эта запись объединяет текущий регион отсечения с прямоугольником.

### EmfPlusSetClipPath {#EmfPlusSetClipPath}
```
public static final short EmfPlusSetClipPath
```


Эта запись объединяет текущий регион отсечения с графическим путем.

### EmfPlusSetClipRegion {#EmfPlusSetClipRegion}
```
public static final short EmfPlusSetClipRegion
```


Эта запись объединяет текущий регион отсечения с другим графическим регионом.

### EmfPlusOffsetClip {#EmfPlusOffsetClip}
```
public static final short EmfPlusOffsetClip
```


Эта запись применяет трансформацию переноса к текущему региону отсечения мирового пространства.

### EmfPlusDrawDriverString {#EmfPlusDrawDriverString}
```
public static final short EmfPlusDrawDriverString
```


Эта запись задает вывод текста с позициями символов.

### EmfPlusStrokeFillPath {#EmfPlusStrokeFillPath}
```
public static final short EmfPlusStrokeFillPath
```


Эта запись закрывает все открытые фигуры в пути, обводит контур пути, используя текущую ручку, и заполняет его внутренность, используя текущую кисть.

### EmfPlusSerializableObject {#EmfPlusSerializableObject}
```
public static final short EmfPlusSerializableObject
```


Эта запись определяет блок параметров эффектов изображения, который был сериализован в буфер данных.

### EmfPlusSetTSGraphics {#EmfPlusSetTSGraphics}
```
public static final short EmfPlusSetTSGraphics
```


Эта запись задает состояние контекста графического устройства для терминального сервера.

### EmfPlusSetTSClip {#EmfPlusSetTSClip}
```
public static final short EmfPlusSetTSClip
```


Эта запись задает области отсечения в контексте графического устройства для терминального сервера.

