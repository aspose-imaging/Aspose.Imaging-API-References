---
title: Aspose.Imaging.FileFormats.Wmf.Objects
second_title: Справочник по Aspose.Imaging for .NET API
description: namespace содержит типы MS-WMF Windows Формат метафайла 2.2 WMF Objects
type: docs
weight: 710
url: /ru/net/aspose.imaging.fileformats.wmf.objects/
---
`namespace` содержит типы [MS-WMF]: Windows Формат метафайла 2.2 WMF Objects

## Классы

| Учебный класс | Описание |
| --- | --- |
| [WmfAnimatePalette](./wmfanimatepalette) | Запись META_ANIMATEPALETTE переопределяет записи в логической палитре , которая определена в контексте устройства воспроизведения с указанным объектом палитры (раздел 2.2.1.3). |
| [WmfArc](./wmfarc) | Запись META_ARC рисует эллиптическую дугу. |
| [WmfBitBlt](./wmfbitblt) | Запись META_BITBLT определяет передачу блока пикселей в соответствии с растровой операцией. Местом назначения передачи является текущая область вывода в контексте устройства воспроизведения. |
| [WmfBitmap16](./wmfbitmap16) | Объект Bitmap16 указывает информацию о размерах и формате color растрового изображения. |
| [WmfBitmapBaseHeader](./wmfbitmapbaseheader) | Базовый класс заголовка растрового изображения. |
| [WmfBitmapCoreHeader](./wmfbitmapcoreheader) | Объект BitmapCoreHeader содержит информацию о размерах и цветовом формате аппаратно-независимого растрового изображения (DIB). |
| [WmfBitmapInfoHeader](./wmfbitmapinfoheader) | Объект BitmapInfoHeader содержит информацию о размерах и цветовом формате аппаратно-независимого растрового изображения (DIB). |
| [WmfChord](./wmfchord) | Запись META_CHORD рисует хорду, которая определяется областью , ограниченной пересечением эллипса с отрезком линии. Аккорд обводится пером и заполняется кистью, которые определены в контексте устройства воспроизведения. |
| [WmfCieXyzTriple](./wmfciexyztriple) | Объект CIEXYZTriple определяет информацию об объекте CIEXYZTriple color . |
| [WmfCreateBrushInDirect](./wmfcreatebrushindirect) | Кисть Create в direct |
| [WmfCreateFontInDirect](./wmfcreatefontindirect) | Создать шрифт |
| [WmfCreatePalette](./wmfcreatepalette) | Запись META_CREATEPALETTE создает объект палитры (раздел 2.2.1.3). |
| [WmfCreatePatternBrush](./wmfcreatepatternbrush) | Запись META_CREATEPATTERNBRUSH создает объект кисти с рисунком , заданным растровым изображением. |
| [WmfCreatePenInDirect](./wmfcreatepenindirect) | Перо создания в direct |
| [WmfCreateRegion](./wmfcreateregion) | Запись META_CREATEREGION создает объект региона (раздел 2.2.1.5). |
| [WmfDeleteObject](./wmfdeleteobject) | Удалить объект |
| [WmfDeviceIndependentBitmap](./wmfdeviceindependentbitmap) | Объект DeviceIndependentBitmap определяет изображение в формате аппаратно-независимого растрового изображения (DIB) |
| [WmfDibBitBlt](./wmfdibbitblt) | Запись META_DIBBITBLT определяет передачу блока пикселей в аппаратно-независимом формате в соответствии с растровой операцией. |
| [WmfDibCreatePatternBrush](./wmfdibcreatepatternbrush) | Запись META_DIBCREATEPATTERNBRUSH создает объект Brush (section 2.2.1.1) с шаблоном, заданным объектом DeviceIndependentBitmap (DIB) (раздел 2.2.2.9). |
| [WmfDibStrechBlt](./wmfdibstrechblt) | Запись META_DIBSTRETCHBLT определяет передачу блока пикселей в аппаратно-независимый формат в соответствии с растровой операцией, с возможным расширением или сжатием. |
| [WmfEllipse](./wmfellipse) | Запись META_ELLIPSE рисует эллипс. Центр эллипса — это центр указанного ограничивающего прямоугольника. Эллипс обведен с помощью пера и заполнен с помощью кисти; они определены в контексте устройства воспроизведения. |
| [WmfEof](./wmfeof) | Объект Eof. |
| [WmfEscape](./wmfescape) | Экранирующий объект wmf. |
| [WmfExcludeClipRect](./wmfexcludecliprect) | Запись META_EXCLUDECLIPRECT устанавливает область отсечения в контексте устройства Play на существующую область отсечения за вычетом указанного прямоугольника . |
| [WmfExtFloodFill](./wmfextfloodfill) | Запись META_EXTFLOODFILL заполняет область кистью, которая определена в контексте устройства воспроизведения. |
| [WmfExtTextOut](./wmfexttextout) | Расширенный текст WMF out |
| [WmfFillRegion](./wmffillregion) | Запись META_FILLREGION заполняет область с помощью указанной кисти. |
| [WmfFloodFill](./wmffloodfill) | Запись META_FLOODFILL заполняет область выходной поверхности кистью , определенной в контексте устройства воспроизведения. |
| [WmfFrameRegion](./wmfframeregion) | Объект области фрейма wmf. |
| [WmfGraphicObject](./wmfgraphicobject) | Графические объекты WMF задают параметры для вывода графики. |
| [WmfIntersectClipRect](./wmfintersectcliprect) | Запись META_INTERSECTCLIPRECT устанавливает область отсечения в контексте устройства воспроизведения на пересечение существующей области отсечения и указанного прямоугольника. |
| [WmfInvertRegion](./wmfinvertregion) | Запись META_INVERTREGION рисует область, в которой цвета инвертированы. |
| [WmfLineTo](./wmflineto) | Запись META_LINETO рисует линию от позиции рисования, которая определена в контексте устройства воспроизведения, до, но не включая, указанную точку . |
| [WmfLogColorSpace](./wmflogcolorspace) | Объект LogColorSpace определяет логическое цветовое пространство для контекста устройства воспроизведения, которое может быть именем цветового профиля в символах ASCII. |
| [WmfLogColorSpaceW](./wmflogcolorspacew) | Объект LogColorSpaceW задает логическое цветовое пространство, которое может быть определено файлом цветового профиля с именем, состоящим из 16-битных символов Unicode . |
| [WmfMoveTo](./wmfmoveto) | Запись META_MOVETO устанавливает позицию вывода в контексте устройства воспроизведения в указанную точку. |
| [WmfObject](./wmfobject) | Базовый объект wmf. |
| [WmfOffsetClipRgn](./wmfoffsetcliprgn) | Запись META_OFFSETCLIPRGN перемещает область отсечения в контексте устройстваplay на указанные смещения. |
| [WmfOffsetViewPortOrg](./wmfoffsetviewportorg) | Запись META_OFFSETVIEWPORTORG перемещает исходную точку окна просмотра в контексте устройства воспроизведения на указанные смещения по горизонтали и вертикали. |
| [WmfOffsetWindowOrg](./wmfoffsetwindoworg) | Запись META_OFFSETWINDOWORG перемещает исходную точку выходного окна в контексте устройства воспроизведения на указанные смещения по горизонтали и вертикали. |
| [WmfPaintRegion](./wmfpaintregion) | Запись META_PAINTREGION закрашивает указанную область с помощью кисти , определенной в контексте устройства воспроизведения. |
| [WmfPatBlt](./wmfpatblt) | Запись META_PATBLT закрашивает указанный прямоугольник с помощью кисти, которая определена в контексте устройства воспроизведения. Цвет кисти и цвет или цвета поверхности объединяются с помощью указанной операции raster . |
| [WmfPie](./wmfpie) | Запись META_PIE рисует клин в форме пирога, ограниченный пересечением эллипса и двух радиалов. Круговая диаграмма очерчена с помощью пера и заполнена с помощью кисти, которые определены в контексте устройства воспроизведения. |
| [WmfPointObject](./wmfpointobject) | Объект Point. |
| [WmfPolygon](./wmfpolygon) | Полигональный объект |
| [WmfPolyLine](./wmfpolyline) | Объект полилинии. |
| [WmfPolyPolygon](./wmfpolypolygon) | Объект PolyPolygon определяет серию замкнутых полигонов. |
| [WmfRealizePalette](./wmfrealizepalette) | Запись META_REALIZEPALETTE отображает записи из логической палитры , определенной в контексте устройства воспроизведения, в системную палитру. |
| [WmfRecord](./wmfrecord) | Запись WMF |
| [WmfRectangle](./wmfrectangle) | Запись META_RECTANGLE рисует прямоугольник. Прямоугольник обводится с помощью пера и заполняется с помощью кисти, которые определены в контексте устройства воспроизведения. |
| [WmfRegion](./wmfregion) | Объект Region определяет потенциально непрямолинейную форму, определяемую массивом строк развертки. |
| [WmfResizePalette](./wmfresizepalette) | Запись META_RESIZEPALETTE переопределяет размер логической палитры , определенной в контексте устройства воспроизведения. |
| [WmfRestoreDc](./wmfrestoredc) | Объект DC восстановления |
| [WmfRoundRect](./wmfroundrect) | Прямоугольный объект. |
| [WmfSaveDc](./wmfsavedc) | Запись META_SAVEDC сохраняет контекст устройства воспроизведения для последующего извлечения. |
| [WmfScaleViewportExt](./wmfscaleviewportext) | Запись META_SCALEVIEWPORTEXT масштабирует горизонтальную и вертикальную экстентов области просмотра, которая определена в контексте устройства воспроизведения , используя отношения, образованные указанными множителями и делителями. |
| [WmfScaleWindowExt](./wmfscalewindowext) | Запись META_SCALEWINDOWEXT масштабирует горизонтальную и вертикальную экстентов выходного окна, которое определено в контексте устройства воспроизведения , используя отношения, образованные указанными множителями и делителями. |
| [WmfScanObject](./wmfscanobject) | Объект сканирования определяет набор строк сканирования. |
| [WmfSelectClipRegion](./wmfselectclipregion) | Запись META_SELECTCLIPREGION определяет объект региона (раздел 2.2.1.5) как текущую область отсечения. |
| [WmfSelectObject](./wmfselectobject) | Выбранный объект. |
| [WmfSelectPalette](./wmfselectpalette) | Запись META_SELECTPALETTE определяет текущую логическую палитру с указанным a объектом палитры. |
| [WmfSetBkColor](./wmfsetbkcolor) | Запись META_SETBKCOLOR устанавливает цвет фона в контексте устройстваplay на указанный цвет или на ближайший физический цвет, если устройство не может отображать указанный цвет. |
| [WmfSetBkMode](./wmfsetbkmode) | Установленный режим bk. |
| [WmfSetDibToDev](./wmfsetdibtodev) | Запись META_SETDIBTODEV устанавливает блок пикселей в контексте устройстваplay , используя независимые от устройства данные о цвете. Источником данных цвета является DIB. |
| [WmfSetLayout](./wmfsetlayout) | Запись META_SETLAYOUT определяет ориентацию макета в контексте устройстваplay . Ориентация макета определяет направление, в котором отрисовываются текст и графика |
| [WmfSetMapMode](./wmfsetmapmode) | Установленный режим карты. |
| [WmfSetMapperFlags](./wmfsetmapperflags) | Запись META_SETMAPPERFLAGS определяет алгоритм, который использует средство отображения font при сопоставлении логических шрифтов с физическими шрифтами. |
| [WmfSetPalentries](./wmfsetpalentries) | Запись META_SETPALENTRIES определяет значения цвета RGB в диапазоне записей в логической палитре, которая определена в контексте устройства воспроизведения . |
| [WmfSetPixel](./wmfsetpixel) | Запись META_SETPIXEL устанавливает для пикселя с указанными координатами указанный цвет. |
| [WmfSetPolyFillMode](./wmfsetpolyfillmode) | Установленный режим полифонической заливки. |
| [WmfSetRelabs](./wmfsetrelabs) | Запись META_SETRELABS зарезервирована и не поддерживается. |
| [WmfSetRop2](./wmfsetrop2) | Набор rop2 |
| [WmfSetStretchbltMode](./wmfsetstretchbltmode) | Запись META_SETSTRETCHBLTMODE определяет режим растяжения растрового изображения в контексте устройства воспроизведения. |
| [WmfSetTextAlign](./wmfsettextalign) | Текст набора align |
| [WmfSetTextCharExtra](./wmfsettextcharextra) | Запись META_SETTEXTCHAREXTRA определяет межсимвольный интервал для выравнивания текста в контексте устройства воспроизведения. Пробел добавляется к пробелу между каждым символом, включая `break` символов, когда строка выравниваемого текста is output. |
| [WmfSetTextColor](./wmfsettextcolor) | Установить цвет текста. |
| [WmfSetTextJustification](./wmfsettextjustification) | Запись META_SETTEXTJUSTIFICATION определяет количество места, которое нужно добавить в`break` символы в строке выравниваемого текста. |
| [WmfSetViewportExt](./wmfsetviewportext) | Запись META_SETVIEWPORTEXT устанавливает горизонтальную и вертикальную протяженность окна просмотра в контексте устройства воспроизведения. |
| [WmfSetViewportOrg](./wmfsetviewportorg) | Запись META_SETVIEWPORTORG определяет исходную точку окна просмотра в контексте устройства воспроизведения. |
| [WmfSetWindowExt](./wmfsetwindowext) | Установленный объект окна. |
| [WmfSetWindowOrg](./wmfsetwindoworg) | Установленный объект окна org |
| [WmfStretchBlt](./wmfstretchblt) | Запись META_STRETCHBLT определяет передачу блока пикселей в соответствии с растровой операцией с возможным расширением или сжатием. |
| [WmfStretchDib](./wmfstretchdib) | Объект WMF Stretch DIB c. |
| [WmfTextOut](./wmftextout) | Запись META_EXTTEXTOUT выводит текст с использованием шрифта, цвета background и цвета текста, которые определены в контексте устройства воспроизведения. |
| [WmfUntyped](./wmfuntyped) | Нетипизированный объект WMF |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
