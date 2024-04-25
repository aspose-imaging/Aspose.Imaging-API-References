---
title: Aspose.Imaging.FileFormats.Emf.EmfPlus.Records
second_title: Справочник по Aspose.Imaging for .NET API
description: Пространство имен содержит типы MS-EMFPLUS Enhanced Metafile Format Plus Extensions 2.3 EMF Records
type: docs
weight: 390
url: /ru/aspose.imaging.fileformats.emf.emfplus.records/
---
Пространство имен содержит типы [MS-EMFPLUS]: Enhanced Metafile Format Plus Extensions 2.3 EMF+ Records

## Классы

| Учебный класс | Описание |
| --- | --- |
| [EmfPlusBeginContainer](./emfplusbegincontainer) | Запись EmfPlusBeginContainer открывает новый контейнер состояния графики и задает для него преобразование. |
| [EmfPlusBeginContainerNoParams](./emfplusbegincontainernoparams) | Запись EmfPlusBeginContainerNoParams открывает новый контейнер состояния графики. |
| [EmfPlusClear](./emfplusclear) | Запись EmfPlusClear очищает выходное координатное пространство и инициализирует его цветом фона и прозрачностью |
| [EmfPlusClippingRecordType](./emfplusclippingrecordtype) | Типы записей отсечения определяют области и операции отсечения. |
| [EmfPlusComment](./emfpluscomment) | Запись EmfPlusComment указывает произвольные частные данные. |
| [EmfPlusControlRecordType](./emfpluscontrolrecordtype) | Типы контрольных записей определяют глобальные параметры для обработки метафайлов EMF+. |
| [EmfPlusDrawArc](./emfplusdrawarc) | Запись EmfPlusDrawArc определяет рисование дуги эллипса. |
| [EmfPlusDrawBeziers](./emfplusdrawbeziers) | Запись EmfPlusDrawBeziers определяет рисование последовательности соединенных кривых Безье. Порядок точек данных Безье следующий: начальная точка, контрольная точка 1, контрольная точка 2 и конечная точка. Дополнительные сведения см. в [MSDN-DrawBeziers]. |
| [EmfPlusDrawClosedCurve](./emfplusdrawclosedcurve) | Запись EmfPlusDrawClosedCurve определяет рисование замкнутого кардинального сплайна |
| [EmfPlusDrawCurve](./emfplusdrawcurve) | Запись EmfPlusDrawCurve определяет рисование кардинального сплайна ПРИМЕЧАНИЕ: ObjectID (1 байт): индекс объекта EmfPlusPen (раздел 2.2.1.7) в таблице объектов EMF+ для рисования кривой. Значение ДОЛЖНО быть от нуля до 63 включительно. |
| [EmfPlusDrawDriverString](./emfplusdrawdriverstring) | Запись EmfPlusDrawDriverString определяет вывод текста с позициями символов. |
| [EmfPlusDrawEllipse](./emfplusdrawellipse) | Запись EmfPlusDrawEllipse определяет рисование эллипса. |
| [EmfPlusDrawImage](./emfplusdrawimage) | Запись EmfPlusDrawImage определяет рисование масштабированного изображения. |
| [EmfPlusDrawImagePoints](./emfplusdrawimagepoints) | Запись EmfPlusDrawImagePoints определяет рисование масштабированного изображения внутри параллелограмма. |
| [EmfPlusDrawingRecordType](./emfplusdrawingrecordtype) | Типы записей чертежей определяют вывод графики. |
| [EmfPlusDrawLines](./emfplusdrawlines) | Запись EmfPlusDrawlLines определяет рисование ряда соединенных линий |
| [EmfPlusDrawPath](./emfplusdrawpath) | Запись EmfPlusDrawPath указывает путь рисования графики. |
| [EmfPlusDrawPie](./emfplusdrawpie) | Запись EmfPlusDrawPie определяет рисование внутренней части эллипса. |
| [EmfPlusDrawRects](./emfplusdrawrects) | Запись EmfPlusDrawRects определяет рисование серии прямоугольников |
| [EmfPlusDrawString](./emfplusdrawstring) | Запись EmfPlusDrawString определяет вывод текста с форматированием строки |
| [EmfPlusEndContainer](./emfplusendcontainer) | Запись EmfPlusEndContainer закрывает контейнер состояния графики, который ранее был открыт операцией запуска контейнера. |
| [EmfPlusEndOfFile](./emfplusendoffile) | Запись EmfPlusEndOfFile указывает конец данных EMF+ в метафайле. |
| [EmfPlusFillClosedCurve](./emfplusfillclosedcurve) | Запись EmfPlusFillClosedCurve определяет заполнение внутренней части замкнутого кардинального сплайна |
| [EmfPlusFillEllipse](./emfplusfillellipse) | Запись EmfPlusFillEllipse определяет заполнение внутренней части эллипса |
| [EmfPlusFillPath](./emfplusfillpath) | Запись пути заполнения ФЛАГИ: 16-битное целое число без знака, которое предоставляет информацию о том, как должна выполняться операция, и о структуре записи. 0 1 2 3 4 5 6 7 8 9 1 0 1 2 3 4 5 6 7 8 9 2 0 1 2 3 4 5 6 7 8 9 3 0 1 SXXXXXXX &#x7C; ObjectId &#x7C; S (1 бит): этот бит указывает тип данных в поле BrushId. Если установлено, BrushId определяет цвет как объект EmfPlusARGB (раздел 2.2.2.1). Если флажок не установлен, BrushId содержит индекс объекта EmfPlusBrush (раздел 2.2.1.1) в таблице объектов EMF+. X (1 бит): зарезервировано и ДОЛЖНО игнорироваться. ObjectId (1 байт): индекс объекта EmfPlusPath ( раздел 2.2.1.6) для заполнения в таблице объектов EMF+. Значение ДОЛЖНО быть от нуля до 63 включительно. |
| [EmfPlusFillPie](./emfplusfillpie) | Запись EmfPlusFillPie определяет заполнение внутренней части эллипса |
| [EmfPlusFillPolygon](./emfplusfillpolygon) | Запись EmfPlusFillPolygon определяет заполнение внутренней части многоугольника. |
| [EmfPlusFillRects](./emfplusfillrects) | Запись EmfPlusFillRects определяет заполнение внутренней части ряда прямоугольников |
| [EmfPlusFillRegion](./emfplusfillregion) | Запись EmfPlusFillRegion определяет заполнение внутренней части графического региона |
| [EmfPlusGetDc](./emfplusgetdc) | Запись EmfPlusGetDC указывает, что последующие записи EMF, обнаруженные в метафайле, ДОЛЖНЫ быть обработаны. |
| [EmfPlusHeader](./emfplusheader) | Запись EmfPlusHeader указывает начало данных EMF+ в метафайле. Запись EmfPlusHeader ДОЛЖНА быть встроена в запись EMF EMR_COMMENT_EMFPLUS, , которая ДОЛЖНА быть записью, следующей за заголовком EMF в метафайле. Запись EMR_COMMENT_EMFPLUS указана в разделе [MS-EMF] 2.3.3.2. |
| [EmfPlusMultiplyWorldTransform](./emfplusmultiplyworldtransform) | Запись EmfPlusMultiplyWorldTransform умножает текущее преобразование мирового пространства на указанную матрицу преобразования a . |
| [EmfPlusObject](./emfplusobject) | Запись EmfPlusObject определяет объект для использования в графических операциях. Определение объекта может охватывать несколько записей, на что указывает значение поля Флаги. |
| [EmfPlusObjectRecordType](./emfplusobjectrecordtype) | Типы записей объектов определяют многократно используемые графические объекты. |
| [EmfPlusOffsetClip](./emfplusoffsetclip) | Запись EmfPlusOffsetClip применяет преобразование перевода к текущей области отсечения для мирового пространства. Новая текущая область отсечения устанавливается на результат преобразования преобразования. |
| [EmfPlusPropertyRecordType](./emfpluspropertyrecordtype) | Типы записей свойств определяют свойства контекста устройства воспроизведения. |
| [EmfPlusRecord](./emfplusrecord) | Базовый тип записи Emf+. |
| [EmfPlusResetClip](./emfplusresetclip) | Запись EmfPlusResetClip сбрасывает текущую область отсечения для мирового пространства до бесконечности. |
| [EmfPlusResetWorldTransform](./emfplusresetworldtransform) | Запись EmfPlusResetWorldTransform сбрасывает текущее преобразование мирового пространства в идентификационную матрицу. |
| [EmfPlusRestore](./emfplusrestore) | Запись EmfPlusRestore восстанавливает состояние графики, идентифицированное указанным индексом, из стека сохраненных состояний графики. |
| [EmfPlusRotateWorldTransform](./emfplusrotateworldtransform) | Запись EmfPlusRotateWorldTransform выполняет поворот текущего преобразования мирового пространства. |
| [EmfPlusSave](./emfplussave) | Запись EmfPlusSave сохраняет состояние графики, идентифицированное указанным индексом, в стеке сохраненных состояний графики. |
| [EmfPlusScaleWorldTransform](./emfplusscaleworldtransform) | Запись EmfPlusScaleWorldTransform выполняет масштабирование текущего преобразования мирового пространства. |
| [EmfPlusSerializableObject](./emfplusserializableobject) | Запись EmfPlusSerializableObject определяет блок параметров эффектов изображения, который был сериализован в буфер данных. |
| [EmfPlusSetAntiAliasMode](./emfplussetantialiasmode) | Запись EmfPlusSetAntiAliasMode указывает режим сглаживания для вывода текста. |
| [EmfPlusSetClipPath](./emfplussetclippath) | Запись EmfPlusSetClipPath объединяет текущую область отсечения с графическим контуром. Новая текущая область отсечения устанавливается в результате операции CombineMode. |
| [EmfPlusSetClipRect](./emfplussetcliprect) | Запись EmfPlusSetClipRect объединяет текущую область отсечения с прямоугольником. |
| [EmfPlusSetClipRegion](./emfplussetclipregion) | Запись EmfPlusSetClipRegion объединяет текущую область отсечения с другой графической областью. Новая текущая область отсечения устанавливается в результате выполнения операции CombineMode над предыдущей текущей областью отсечения и указанным объектом EmfPlusRegion. |
| [EmfPlusSetCompositingMode](./emfplussetcompositingmode) | Запись EmfPlusSetCompositingMode указывает, как исходные цвета сочетаются с цветами фона. |
| [EmfPlusSetCompositingQuality](./emfplussetcompositingquality) | Запись EmfPlusSetCompositingQuality определяет желаемый уровень качества для создания составных изображений из нескольких объектов. |
| [EmfPlusSetInterpolationMode](./emfplussetinterpolationmode) | Запись EmfPlusSetInterpolationMode указывает, как выполняется масштабирование изображения, включая растяжение и сжатие. |
| [EmfPlusSetPageTransform](./emfplussetpagetransform) | Запись EmfPlusSetPageTransform указывает коэффициенты и единицы масштабирования для преобразования координат пространства страницы в координаты пространства устройства. |
| [EmfPlusSetPixelOffsetMode](./emfplussetpixeloffsetmode) | Запись EmfPlusSetPixelOffsetMode указывает, как центрируются пиксели относительно координат поверхности рисования. |
| [EmfPlusSetRenderingOrigin](./emfplussetrenderingorigin) | Запись EmfPlusSetRenderingOrigin указывает источник рендеринга для вывода графики. |
| [EmfPlusSetTextContrast](./emfplussettextcontrast) | Запись EmfPlusSetTextContrast определяет контрастность текста в соответствии со значением гамма-коррекции. |
| [EmfPlusSetTextRenderingHint](./emfplussettextrenderinghint) | Запись EmfPlusSetTextRenderingHint определяет качество рендеринга текста, включая тип сглаживания. |
| [EmfPlusSetTsClip](./emfplussettsclip) | Запись EmfPlusSetTSClip определяет области отсечения в контексте графического устройства для терминального сервера. |
| [EmfPlusSetTsGraphics](./emfplussettsgraphics) | Запись EmfPlusSetTSGraphics определяет состояние контекста графического устройства для терминального сервера. |
| [EmfPlusSetWorldTransform](./emfplussetworldtransform) | Запись EmfPlusSetWorldTransform задает преобразование мира в соответствии со значениями в указанной матрице преобразования a . |
| [EmfPlusStateRecordType](./emfplusstaterecordtype) | Типы записей состояния определяют операции над состоянием контекста устройства воспроизведения. |
| [EmfPlusTerminalServerRecordType](./emfplusterminalserverrecordtype) | Типы записей сервера терминалов определяют обработку графики на сервере терминалов. Следующие являются типами записей терминального сервера EMF+. |
| [EmfPlusTransformRecordType](./emfplustransformrecordtype) | Типы записей преобразования определяют свойства и преобразования в координатных пространствах. |
| [EmfPlusTranslateWorldTransform](./emfplustranslateworldtransform) | Запись EmfPlusTranslateWorldTransform выполняет преобразование текущего мирового пространства. |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
