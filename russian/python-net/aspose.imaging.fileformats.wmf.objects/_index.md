---
title: "aspose.imaging.fileformats.wmf.objects"
type: docs
weight: 790
url: /ru/python-net/aspose.imaging.fileformats.wmf.objects/
---


Модуль содержит типы [MS-WMF]: Объекты Windows Metafile Format 2.2 WMF

## **Classes**
| **Class** | **Description** |
| :- | :- |
| [WmfAnimatePalette](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfanimatepalette/) | Запись META_ANIMATEPALETTE переопределяет элементы в логической палитре<br/>                которая определена в контексте устройства воспроизведения с указанным<br/>                объектом Palette (раздел 2.2.1.3). |
| [WmfArc](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfarc/) | Запись META_ARC рисует эллиптическую дугу. |
| [WmfBitBlt](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfbitblt/) | Запись META_BITBLT указывает передачу блока пикселей<br/>                согласно растровой операции. Назначение передачи — текущий выходной регион в контексте устройства воспроизведения. |
| [WmfBitmap16](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfbitmap16/) | Объект Bitmap16 определяет информацию о размерах и цветовом<br/>                формате битмапа. |
| [WmfBitmapBaseHeader](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfbitmapbaseheader/) | Базовый класс заголовка битмапа. |
| [WmfBitmapCoreHeader](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfbitmapcoreheader/) | Объект BitmapCoreHeader содержит информацию о размерах<br/>                и цветовом формате независимого от устройства битмапа (DIB). |
| [WmfBitmapInfoHeader](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/) | Объект BitmapInfoHeader содержит информацию о размерах и цветовом формате независимого от устройства<br/>                битмапа (DIB). |
| [WmfChord](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfchord/) | Запись META_CHORD рисует хорду, определяемую областью<br/>                ограниченной пересечением эллипса с отрезком линии. Хорда<br/>                обводится с помощью пера и заполняется кистью, определёнными в<br/>                контексте устройства воспроизведения. |
| [WmfCieXyz](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfciexyz/) | Объект CIEXYZ определяет информацию об объекте хроматичности CIEXYZ. |
| [WmfCieXyzTriple](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfciexyztriple/) | Объект CIEXYZTriple определяет информацию о цветовом объекте CIEXYZTriple<br/>                . |
| [WmfCreateBrushInDirect](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfcreatebrushindirect/) | Создание кисти в прямом режиме |
| [WmfCreateFontInDirect](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfcreatefontindirect/) | Создание шрифта |
| [WmfCreatePalette](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfcreatepalette/) | Запись META_CREATEPALETTE создает объект Palette (раздел 2.2.1.3). |
| [WmfCreatePatternBrush](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfcreatepatternbrush/) | Запись META_CREATEPATTERNBRUSH создает объект кисти с узором,<br/>                заданным битмапом. |
| [WmfCreatePenInDirect](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfcreatepenindirect/) | Создание пера в прямом режиме |
| [WmfCreateRegion](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfcreateregion/) | Запись META_CREATEREGION создает объект Region (раздел 2.2.1.5). |
| [WmfDeleteObject](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfdeleteobject/) | Удаление объекта |
| [WmfDeviceIndependentBitmap](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap/) | Объект DeviceIndependentBitmap определяет изображение в<br/>                формате независимого от устройства битмапа (DIB). |
| [WmfDibBitBlt](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfdibbitblt/) | Запись META_DIBBITBLT указывает передачу блока пикселей в<br/>                независимом от устройства формате согласно растровой операции. |
| [WmfDibCreatePatternBrush](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfdibcreatepatternbrush/) | Запись META_DIBCREATEPATTERNBRUSH создает объект Brush (раздел<br/>                2.2.1.1) с узором, заданным объектом DeviceIndependentBitmap (DIB)<br/>                (раздел 2.2.2.9). |
| [WmfDibStrechBlt](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfdibstrechblt/) | The META_DIBSTRETCHBLT record specifies the transfer of a block of<br/>                pixels in device-independent format according to a raster operation,<br/>                with possible expansion or contraction. |
| [WmfEllipse](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfellipse/) | The META_ELLIPSE record draws an ellipse. The center of the ellipse is<br/>                the center of the specified bounding rectangle. The ellipse is outlined<br/>                by using the pen and is filled by using the brush; these are defined in<br/>                the playback device context. |
| [WmfEof](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfeof/) | The Eof object. |
| [WmfEscape](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfescape/) | The wmf escape object. |
| [WmfExcludeClipRect](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfexcludecliprect/) | The META_EXCLUDECLIPRECT record sets the clipping region in the playback<br/>                device context to the existing clipping region minus the specified<br/>                rectangle. |
| [WmfExtFloodFill](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfextfloodfill/) | The META_EXTFLOODFILL record fills an area with the brush that is<br/>                defined in the playback device context. |
| [WmfExtTextOut](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfexttextout/) | Wmf ext text out |
| [WmfFillRegion](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmffillregion/) | The META_FILLREGION record fills a region using a specified brush. |
| [WmfFloodFill](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmffloodfill/) | The META_FLOODFILL record fills an area of the output surface with the<br/>                brush that is defined in the playback device context. |
| [WmfFrameRegion](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfframeregion/) | The wmf frame region object. |
| [WmfGraphicObject](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfgraphicobject/) | The WMF Graphics Objects specify parameters for graphics output. |
| [WmfIntersectClipRect](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfintersectcliprect/) | The META_INTERSECTCLIPRECT record sets the clipping region in the<br/>                playback device context to the intersection of the existing clipping<br/>                region and the specified rectangle. |
| [WmfInvertRegion](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfinvertregion/) | The META_INVERTREGION record draws a region in which the colors are<br/>                inverted. |
| [WmfLineTo](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflineto/) | The META_LINETO record draws a line from the drawing position that is<br/>                defined in the playback device context up to, but not including, the<br/>                specified point. |
| [WmfLogColorSpace](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/) | The LogColorSpace object specifies a logical color space for the<br/>                playback device context, which can be the name of a color profile in<br/>                ASCII characters. |
| [WmfLogColorSpaceW](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew/) | The LogColorSpaceW object specifies a logical color space, which can be<br/>                defined by a color profile file with a name consisting of Unicode 16-bit<br/>                characters. |
| [WmfMoveTo](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfmoveto/) | The META_MOVETO record sets the output position in the playback device<br/>                context to a specified point. |
| [WmfObject](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfobject/) | The base wmf object. |
| [WmfOffsetClipRgn](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfoffsetcliprgn/) | The META_OFFSETCLIPRGN record moves the clipping region in the playback<br/>                device context by the specified offsets. |
| [WmfOffsetViewPortOrg](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfoffsetviewportorg/) | The META_OFFSETVIEWPORTORG record moves the viewport origin in the<br/>                playback device context by specified horizontal and vertical offsets. |
| [WmfOffsetWindowOrg](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfoffsetwindoworg/) | The META_OFFSETWINDOWORG record moves the output window origin in the<br/>                playback device context by specified horizontal and vertical offsets. |
| [WmfPaintRegion](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfpaintregion/) | The META_PAINTREGION record paints the specified region by using the<br/>                brush that is defined in the playback device context. |
| [WmfPatBlt](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfpatblt/) | The META_PATBLT record paints a specified rectangle using the brush that<br/>                is defined in the playback device context. The brush color and the<br/>                surface color or colors are combined using the specified raster<br/>                operation. |
| [WmfPie](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfpie/) | The META_PIE record draws a pie-shaped wedge bounded by the intersection<br/>                of an ellipse and two radials. The pie is outlined by using the pen and<br/>                filled by using the brush that are defined in the playback device<br/>                context. |
| [WmfPitchAndFamily](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfpitchandfamily/) | The PitchAndFamily object specifies the pitch and family properties of a<br/>                Font object (section 2.2.1.2). Pitch refers to the width of the<br/>                characters, and family refers to the general appearance of a font. |
| [WmfPointObject](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfpointobject/) | Объект Point. |
| [WmfPolyLine](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfpolyline/) | Объект poly line. |
| [WmfPolyPolygon](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfpolypolygon/) | Объект PolyPolygon определяет серию замкнутых полигонов. |
| [WmfPolygon](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfpolygon/) | Объект polygon |
| [WmfRealizePalette](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfrealizepalette/) | Запись META_REALIZEPALETTE отображает элементы из логической палитры<br/>                определенной в контексте устройства воспроизведения, в системную палитру. |
| [WmfRecord](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfrecord/) | Запись Wmf |
| [WmfRectangle](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfrectangle/) | Запись META_RECTANGLE рисует прямоугольник. Прямоугольник обводится<br/>                с помощью пера и заполняется кистью, определёнными в<br/>                контексте устройства воспроизведения. |
| [WmfRegion](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfregion/) | Объект Region определяет потенциально неректильную форму, задаваемую<br/>                массивом строк сканирования. |
| [WmfResizePalette](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfresizepalette/) | Запись META_RESIZEPALETTE переопределяет размер логической палитры<br/>                определённой в контексте устройства воспроизведения. |
| [WmfRestoreDc](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfrestoredc/) | Объект restore DC |
| [WmfRoundRect](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfroundrect/) | Объект rectangle. |
| [WmfSaveDc](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfsavedc/) | Запись META_SAVEDC сохраняет контекст устройства воспроизведения для последующего<br/>                извлечения. |
| [WmfScaleViewportExt](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfscaleviewportext/) | Запись META_SCALEVIEWPORTEXT масштабирует горизонтальные и вертикальные<br/>                размеры области просмотра, определённой в контексте устройства воспроизведения,<br/>                используя отношения, образованные указанными множителями и делителями. |
| [WmfScaleWindowExt](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfscalewindowext/) | Запись META_SCALEWINDOWEXT масштабирует горизонтальные и вертикальные<br/>                размеры выходного окна, определённого в контексте устройства воспроизведения,<br/>                используя отношения, образованные указанными множителями и<br/>                делителями. |
| [WmfScanObject](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfscanobject/) | Объект Scan указывает коллекцию строк сканирования. |
| [WmfSelectClipRegion](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfselectclipregion/) | Запись META_SELECTCLIPREGION указывает объект Region (раздел 2.2.1.5) в качестве текущего области отсечения. |
| [WmfSelectObject](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfselectobject/) | Объект select. |
| [WmfSelectPalette](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfselectpalette/) | Запись META_SELECTPALETTE определяет текущую логическую палитру с помощью<br/>                указанного объекта Palette. |
| [WmfSetBkColor](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfsetbkcolor/) | Запись META_SETBKCOLOR устанавливает цвет фона в контексте устройства воспроизведения<br/>                в указанный цвет или в ближайший физический цвет, если<br/>                устройство не может представить указанный цвет. |
| [WmfSetBkMode](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfsetbkmode/) | Установка режима bk. |
| [WmfSetDibToDev](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfsetdibtodev/) | Запись META_SETDIBTODEV устанавливает блок пикселей в контексте устройства воспроизведения<br/>                с использованием независимых от устройства цветовых данных. Источник<br/>                цветовых данных — DIB. |
| [WmfSetLayout](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfsetlayout/) | Запись META_SETLAYOUT определяет ориентацию макета в контексте устройства воспроизведения.<br/>                Ориентация макета определяет направление, в котором<br/>                рисуются текст и графика. |
| [WmfSetMapMode](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfsetmapmode/) | Установка режима карты. |
| [WmfSetMapperFlags](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfsetmapperflags/) | Запись META_SETMAPPERFLAGS определяет алгоритм, который использует сопоставитель шрифтов при преобразовании логических шрифтов в физические. |
| [WmfSetPalentries](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfsetpalentries/) | Запись META_SETPALENTRIES определяет значения цветов RGB в диапазоне<br/>                элементов логической палитры, определённой в контексте устройства воспроизведения. |
| [WmfSetPixel](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfsetpixel/) | Запись META_SETPIXEL устанавливает пиксель в указанных координатах в<br/>                указанный цвет. |
| [WmfSetPolyFillMode](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfsetpolyfillmode/) | Устанавливает режим заливки полигонов. |
| [WmfSetRelabs](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfsetrelabs/) | Запись META_SETRELABS зарезервирована и не поддерживается. |
| [WmfSetRop2](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfsetrop2/) | Устанавливает rop2 |
| [WmfSetStretchbltMode](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfsetstretchbltmode/) | Запись META_SETSTRETCHBLTMODE определяет режим растягивания битмапа в<br/>                контексте воспроизведения устройства. |
| [WmfSetTextAlign](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfsettextalign/) | Устанавливает выравнивание текста |
| [WmfSetTextCharExtra](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfsettextcharextra/) | Запись META_SETTEXTCHAREXTRA определяет межсимвольный интервал для<br/>                выравнивания текста в контексте воспроизведения устройства. Интервал добавляется к<br/>                пробельному пространству между каждым символом, включая<br/>                **break** символы, когда строка выровненного текста<br/>                выводится. |
| [WmfSetTextColor](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfsettextcolor/) | Устанавливает цвет текста. |
| [WmfSetTextJustification](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfsettextjustification/) | Запись META_SETTEXTJUSTIFICATION определяет количество пространства, которое добавляется<br/>                к **break** символам в строке выровненного текста. |
| [WmfSetViewportExt](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfsetviewportext/) | Запись META_SETVIEWPORTEXT устанавливает горизонтальные и вертикальные размеры<br/>                области просмотра в контексте воспроизведения устройства. |
| [WmfSetViewportOrg](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfsetviewportorg/) | Запись META_SETVIEWPORTORG определяет начало области просмотра в<br/>                контексте воспроизведения устройства. |
| [WmfSetWindowExt](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfsetwindowext/) | Устанавливает объект окна. |
| [WmfSetWindowOrg](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfsetwindoworg/) | Устанавливает объект org окна |
| [WmfStretchBlt](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfstretchblt/) | Запись META_STRETCHBLT указывает передачу блока пикселей<br/>                согласно растровой операции, с возможным расширением или сжатием. |
| [WmfStretchDib](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfstretchdib/) | Объект wmf Stretch DIB. |
| [WmfTextOut](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmftextout/) | Запись META_EXTTEXTOUT выводит текст, используя шрифт, цвет фона<br/>                и цвет текста, определённые в контексте воспроизведения устройства.<br/>                При необходимости можно указать размеры для обрезки, затемнения или обоих. |
| [WmfUntyped](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfuntyped/) | Объект wmf без типа |
