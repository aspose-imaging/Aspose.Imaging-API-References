---
title: "aspose.imaging"
type: docs
weight: 10
url: /de/python-net/aspose.imaging/
---


Das Modul ist das Kernstück für verschachtelte Module und die grundlegendsten Objekte, die für die Verarbeitung von Aspose.Imaging verwendet werden.

## **Classes**
| **Klasse** | **Beschreibung** |
| :- | :- |
| [Blend](/imaging/python-net/aspose.imaging/blend/) | Definiert ein Mischmuster. Diese Klasse kann nicht abgeleitet werden. |
| [Brush](/imaging/python-net/aspose.imaging/brush/) | Die Basispinsel‑Klasse. |
| [BuildVersionInfo](/imaging/python-net/aspose.imaging/buildversioninfo/) | Enthält die aktuelle Build‑Versionsinformation. |
| [Cache](/imaging/python-net/aspose.imaging/cache/) | Enthält Cache‑Einstellungen. |
| [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) | Die CMYK‑Farbe des Pixels. |
| [CmykColorHelper](/imaging/python-net/aspose.imaging/cmykcolorhelper/) | Hilfsmethoden zur Arbeit mit CMYK‑Farbe, dargestellt als vorzeichenbehafteter 32‑Bit‑Integer‑Wert.<br/> Bietet eine ähnliche API wie die [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/)‑Struktur.<br/> Sie ist leichter, weil die CMYK‑Farbe nur als Int32 und nicht als Struktur mit internen Feldern dargestellt wird.<br/> Bitte bevorzugen Sie nach Möglichkeit die statischen Methoden dieser Klasse anstelle der veralteten<br/> [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/)‑Struktur. |
| [Color](/imaging/python-net/aspose.imaging/color/) | Die Farbe des Pixels. |
| [ColorBlend](/imaging/python-net/aspose.imaging/colorblend/) | Definiert Arrays von Farben und Positionen, die für die Interpolation von Farbmischungen in einem mehrfarbigen Verlauf verwendet werden. Diese Klasse kann nicht geerbt werden. |
| [ColorMap](/imaging/python-net/aspose.imaging/colormap/) | Definiert eine Zuordnung zum Konvertieren von Farben. Mehrere Methoden der Klasse [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) passen Bildfarben mithilfe einer Farb-Remap-Tabelle an, die ein Array von Strukturen des Typs [ColorMap](/imaging/python-net/aspose.imaging/colormap/) ist. Nicht vererbbar. |
| [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) | Definiert eine 5 × 5‑Matrix, die die Koordinaten für den RGBA‑Raum enthält. Mehrere Methoden der Klasse [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) passen Bildfarben mithilfe einer Farbmatrix an. Diese Klasse kann nicht geerbt werden. |
| [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) | Definiert ein Array von Farben, das eine Farbpalette bildet. Die Farben sind 32‑Bit‑ARGB‑Farben. Nicht vererbbar. |
| [ColorPaletteHelper](/imaging/python-net/aspose.imaging/colorpalettehelper/) | Hilfsklasse zur Manipulation von Farbpaletten. |
| [ColorTranslator](/imaging/python-net/aspose.imaging/colortranslator/) | Übersetzt Farben zu und von GDI+‑Color‑Strukturen. Diese Klasse kann nicht geerbt werden. |
| [CustomLineCap](/imaging/python-net/aspose.imaging/customlinecap/) | Kapselt eine benutzerdefinierte, vom Nutzer definierte Linienendkappe. |
| [DataStreamSupporter](/imaging/python-net/aspose.imaging/datastreamsupporter/) | Der Datenstrom‑Container. |
| [DisposableObject](/imaging/python-net/aspose.imaging/disposableobject/) | Stellt ein verwerfbares Objekt dar. |
| [EmbeddedImage](/imaging/python-net/aspose.imaging/embeddedimage/) | Die eingebettete Bildklasse |
| [Figure](/imaging/python-net/aspose.imaging/figure/) | Die Figur. Ein Container für Formen. |
| [FileStreamContainer](/imaging/python-net/aspose.imaging/filestreamcontainer/) | Hilfsmittel für die Verarbeitung von Dateistreams. |
| [Font](/imaging/python-net/aspose.imaging/font/) | Definiert ein bestimmtes Format für Text, einschließlich Schriftart, Größe und Stil‑Attribute. Diese Klasse kann nicht geerbt werden. |
| [FontSettings](/imaging/python-net/aspose.imaging/fontsettings/) | Allgemeine Schriftarteinstellungen für den Renderer von Bildvektorformaten. |
| [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Stellt die Grafik gemäß der im aktuellen Assembly verwendeten Grafik-Engine dar. |
| [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Stellt eine Reihe verbundener Linien und Kurven dar. Diese Klasse kann nicht geerbt werden. |
| [IAdvancedBufferProcessor](/imaging/python-net/aspose.imaging/iadvancedbufferprocessor/) | Der erweiterte Pufferprozessor. |
| [IAnimationFrame](/imaging/python-net/aspose.imaging/ianimationframe/) | Der Animationsrahmen |
| [IBufferProcessor](/imaging/python-net/aspose.imaging/ibufferprocessor/) | Der Pufferprozessor. |
| [IColorConverter](/imaging/python-net/aspose.imaging/icolorconverter/) | Der Farbkonverter. |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | Die Farbpaletten‑Schnittstelle. |
| [IHasMetadata](/imaging/python-net/aspose.imaging/ihasmetadata/) | Bild‑Metadaten‑Schnittstelle. |
| [IImageCreator](/imaging/python-net/aspose.imaging/iimagecreator/) | Der Bildersteller. |
| [IImageCreatorDescriptor](/imaging/python-net/aspose.imaging/iimagecreatordescriptor/) | Der Bildersteller‑Deskriptor, der die Ersteller‑Eigenschaften angibt. Der Deskriptor wird verwendet, um<br/>            die Notwendigkeit zu überwinden, jede Bildersteller‑Instanz im Speicher zu halten und Probleme bei der Mehrfachthread‑Verarbeitung zu vermeiden. |
| [IImageDescriptor](/imaging/python-net/aspose.imaging/iimagedescriptor/) | Der Bild-Deskriptor. Enthält Basiseigenschaften und -methoden für alle anderen Bild-Deskriptor-Typen. |
| [IImageExporter](/imaging/python-net/aspose.imaging/iimageexporter/) | Der Bild-Exporter. Kann Daten vom internen `aspose.imaging`-Format in ein angegebenes Datenformat exportieren. |
| [IImageExporterDescriptor](/imaging/python-net/aspose.imaging/iimageexporterdescriptor/) | Stellt den Bild-Exporter-Deskriptor dar. Der Exporter-Deskriptor wird verwendet, um die Notwendigkeit zu umgehen, jede Exporter-Instanz<br/>            im Speicher zu halten und Probleme mit Multithreading zu vermeiden. |
| [IImageLoader](/imaging/python-net/aspose.imaging/iimageloader/) | Der Bild-Loader. |
| [IImageLoaderDescriptor](/imaging/python-net/aspose.imaging/iimageloaderdescriptor/) | Der Bild-Loader-Deskriptor, der die Loader-Eigenschaften spezifiziert. Der Loader-Deskriptor wird verwendet, um die Notwendigkeit zu umgehen<br/>            jede Bild-Loader-Instanz im Speicher zu halten und Multithreading-Probleme zu vermeiden. |
| [IIndexedColorConverter](/imaging/python-net/aspose.imaging/iindexedcolorconverter/) | Der Farbkonverter für indizierte Bildformate. |
| [IMetadataContainer](/imaging/python-net/aspose.imaging/imetadatacontainer/) | Schnittstelle für Bild-Metadaten-Container. |
| [IMultipageImage](/imaging/python-net/aspose.imaging/imultipageimage/) | Die Mehrseiten-Bild-Schnittstelle |
| [IMultipageImageExt](/imaging/python-net/aspose.imaging/imultipageimageext/) | Die erweiterte Mehrseiten-Bild-Schnittstelle |
| [IObjectWithBounds](/imaging/python-net/aspose.imaging/iobjectwithbounds/) | Stellt ein Objekt mit Grenzen dar. |
| [IOrderedShape](/imaging/python-net/aspose.imaging/iorderedshape/) | Stellt eine geordnete Form dar. Eine geordnete Form ist eine kontinuierliche Menge von Punkten mit einem Start- und Endpunkt.<br/>            Die kontinuierliche Punktmenge, die mittels einer spezifischen Regel verbunden ist. |
| [IPartialArgb32PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb32pixelloader/) | Entspricht den teilweise geladenen 32‑Bit‑ARGB‑Pixeln. |
| [IPartialArgb64PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb64pixelloader/) | Der 64‑Bit‑ARGB‑Pixel‑Loader. |
| [IPartialPixelLoader](/imaging/python-net/aspose.imaging/ipartialpixelloader/) | Entspricht den teilweise geladenen Pixeln. |
| [IPartialRawDataLoader](/imaging/python-net/aspose.imaging/ipartialrawdataloader/) | Der Teil-Daten‑Loader. |
| [IRasterImageArgb32PixelLoader](/imaging/python-net/aspose.imaging/irasterimageargb32pixelloader/) | Der Raster‑Bild‑32‑Bit‑ARGB‑Pixel‑Loader. |
| [IRasterImageArgb64PixelLoader](/imaging/python-net/aspose.imaging/irasterimageargb64pixelloader/) | Der Raster‑Bild‑64‑Bit‑ARGB‑Pixel‑Loader. |
| [IRasterImagePixelLoader](/imaging/python-net/aspose.imaging/irasterimagepixelloader/) | Der Raster‑Bild‑Pixel‑Loader. |
| [IRasterImageRawDataLoader](/imaging/python-net/aspose.imaging/irasterimagerawdataloader/) | Der Raster‑Bild‑Rohdaten‑Loader. |
| [Image](/imaging/python-net/aspose.imaging/image/) | Das Bild ist die Basisklasse für alle Bildtypen. |
| [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | Ein [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/)‑Objekt enthält Informationen darüber, wie Bitmap‑ und Metafile‑Farben während des Renderns manipuliert werden. Ein [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/)‑Objekt verwaltet mehrere Farbe‑Anpassungseinstellungen, einschließlich Farb‑Anpassungsmatrizen, Graustufen‑Anpassungsmatrizen, Gamma‑Korrekturwerte, Farb‑Zuordnungstabellen und Farb‑Schwellenwerte. Beim Rendern können Farben korrigiert, abgedunkelt, aufgehellt und entfernt werden. Um solche Manipulationen anzuwenden, initialisieren Sie ein [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/)‑Objekt und übergeben Sie den Pfad dieses [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/)‑Objekts (zusammen mit dem Pfad eines [Image](/imaging/python-net/aspose.imaging/image/)) an die DrawImage‑Methode. |
| [ImageCreatorsRegistry](/imaging/python-net/aspose.imaging/imagecreatorsregistry/) | Stellt das Bild‑Ersteller‑Register dar. |
| [ImageExportersRegistry](/imaging/python-net/aspose.imaging/imageexportersregistry/) | Stellt das Bild‑Exporter‑Register dar. |
| [ImageLoadersRegistry](/imaging/python-net/aspose.imaging/imageloadersregistry/) | Stellt das Bild‑Loader‑Register dar. |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Die Bild‑Basisoptionen. |
| [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Klasse für Bildgrößenänderungs-Einstellungen |
| [IntRange](/imaging/python-net/aspose.imaging/intrange/) | Klasse zur Darstellung einer Sequenz von Elementen |
| [License](/imaging/python-net/aspose.imaging/license/) | Stellt Methoden zur Lizenzierung der Komponente bereit. |
| [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | Stellt die Ladeoptionen dar. |
| [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Ersetzt die GDI+-Matrix. |
| [Metered](/imaging/python-net/aspose.imaging/metered/) | Stellt messbare Methoden für die Integration bereit. |
| [NonGenericDictionary](/imaging/python-net/aspose.imaging/nongenericdictionary/) | Stellt ein nicht generisches Wörterbuch dar. |
| [NonGenericList](/imaging/python-net/aspose.imaging/nongenericlist/) | Nicht generische Liste von Objekten |
| [ObjectWithBounds](/imaging/python-net/aspose.imaging/objectwithbounds/) | Das Objekt mit Begrenzungen. |
| [OpenTypeFontsCache](/imaging/python-net/aspose.imaging/opentypefontscache/) | Cache für OpenType-Schriften, die im System installiert sind. |
| [Pen](/imaging/python-net/aspose.imaging/pen/) | Definiert ein Objekt zum Zeichnen von Linien, Kurven und Figuren. |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | Das Pixeldatenformat. Dies ist ein unveränderliches Objekt. |
| [Point](/imaging/python-net/aspose.imaging/point/) | Stellt ein geordnetes Paar von ganzzahligen x- und y-Koordinaten dar, das einen Punkt in einer zweidimensionalen Ebene definiert. |
| [PointF](/imaging/python-net/aspose.imaging/pointf/) | Stellt ein geordnetes Paar von Gleitkomma-x- und y-Koordinaten dar, das einen Punkt in einer zweidimensionalen Ebene definiert. |
| [RasterCachedImage](/imaging/python-net/aspose.imaging/rastercachedimage/) | Stellt ein Rasterbild dar, das Rastergrafik-Operationen unterstützt. Dieses Bild cached Pixeldaten bei Bedarf. |
| [RasterCachedMultipageImage](/imaging/python-net/aspose.imaging/rastercachedmultipageimage/) | Das rasterbasierte Mehrseitenbild |
| [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Stellt ein Rasterbild dar, das Rastergrafik-Operationen unterstützt. |
| [RawDataSettings](/imaging/python-net/aspose.imaging/rawdatasettings/) | Die Rohdaten-Einstellungen |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Speichert ein Set von vier Ganzzahlen, die die Position und Größe eines Rechtecks darstellen. |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Speichert ein Set von vier Gleitkommazahlen, die die Position und Größe eines Rechtecks darstellen. |
| [Region](/imaging/python-net/aspose.imaging/region/) | Beschreibt das Innere einer Grafikform, die aus Rechtecken und Pfaden besteht. Diese Klasse kann nicht vererbt werden. |
| [RemoveBackgroundSettings](/imaging/python-net/aspose.imaging/removebackgroundsettings/) | Die Hintergrund-Entfernungseinstellungen |
| [ResolutionSetting](/imaging/python-net/aspose.imaging/resolutionsetting/) | Die Auflösungseinstellung für Bildspeicheroptionen. |
| [Shape](/imaging/python-net/aspose.imaging/shape/) | Die Form. Eine kontinuierliche Menge von Punkten, die nach einer bestimmten Regel verbunden sind. |
| [ShapeSegment](/imaging/python-net/aspose.imaging/shapesegment/) | Stellt ein Formsegment dar. Ein Segment ist eine Linie oder Kurve, die zwei Punkte verbindet. |
| [Size](/imaging/python-net/aspose.imaging/size/) | Stellt die Größe dar. |
| [SizeF](/imaging/python-net/aspose.imaging/sizef/) | Speichert ein geordnetes Paar von Fließkommazahlen, typischerweise die Breite und Höhe eines Rechtecks. |
| [Source](/imaging/python-net/aspose.imaging/source/) | Die Quelle wird verwendet, um alle relevanten Informationen für ein Objekt‑Pipe zu enthalten. |
| [SplitStreamContainer](/imaging/python-net/aspose.imaging/splitstreamcontainer/) | Stellt einen geteilten Stream‑Container dar, der den Stream enthält und Routinen zur Stream‑Verarbeitung bereitstellt. |
| [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | Stellt einen Stream‑Container dar, der den Stream enthält und Routinen zur Stream‑Verarbeitung bereitstellt. |
| [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | Kapselt Textlayout‑Informationen (wie Ausrichtung, Orientierung und Tabulatoren), Anzeige‑Manipulationen (wie Ellipsen‑Einfügung und nationale Ziffern‑Ersetzung) und OpenType‑Funktionen. Diese Klasse kann nicht abgeleitet werden. |
| [TransparencySupporter](/imaging/python-net/aspose.imaging/transparencysupporter/) | Das Objekt, das Transparenz unterstützt. |
| [VectorImage](/imaging/python-net/aspose.imaging/vectorimage/) | Das Vektor‑Bild ist die Basisklasse für alle Arten von Vektor‑Bildern. |
| [VectorMultipageImage](/imaging/python-net/aspose.imaging/vectormultipageimage/) | Das Vektor‑Mehrseiten‑Bild |
## **Enumerations**
| **Aufzählung** | **Beschreibung** |
| :- | :- |
| [AnimationDisposalMethods](/imaging/python-net/aspose.imaging/animationdisposalmethods/) | Gibt an, wie die Grafik nach der Anzeige behandelt werden soll. |
| [CacheType](/imaging/python-net/aspose.imaging/cachetype/) | Gibt den zu verwendenden Cache‑Typ an. |
| [CharacterSet](/imaging/python-net/aspose.imaging/characterset/) | Stellt den verwendeten Zeichensatz dar. |
| [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | Gibt an, welche Objekte Farbanpassungsinformationen verwenden. |
| [ColorChannelFlag](/imaging/python-net/aspose.imaging/colorchannelflag/) | Gibt einzelne Kanäle im CMYK (Cyan, Magenta, Gelb, Schwarz) Farbraum an. Diese Aufzählung wird von den SetOutputChannel‑Methoden verwendet. |
| [ColorCompareMethod](/imaging/python-net/aspose.imaging/colorcomparemethod/) | Farbvergleichsmethode zur Anpassung an den nächsten Nachbarn |
| [ColorMatrixFlag](/imaging/python-net/aspose.imaging/colormatrixflag/) | Gibt die Arten von Bildern und Farben an, die von den Farb‑ und Graustufen‑Anpassungseinstellungen eines [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) betroffen sind. |
| [ColorQuantizationMethod](/imaging/python-net/aspose.imaging/colorquantizationmethod/) | Methoden zur Farbkodierung |
| [CompositingQuality](/imaging/python-net/aspose.imaging/compositingquality/) | Gibt die während der Komposition zu verwendende Qualitätsstufe an. |
| [DashCap](/imaging/python-net/aspose.imaging/dashcap/) | Gibt den Typ der grafischen Form an, die an beiden Enden jedes Strichs in einer gestrichelten Linie verwendet wird. |
| [DashStyle](/imaging/python-net/aspose.imaging/dashstyle/) | Gibt den Stil der mit einem [Pen](/imaging/python-net/aspose.imaging/pen/) Objekt gezeichneten gestrichelten Linien an. |
| [DataRecoveryMode](/imaging/python-net/aspose.imaging/datarecoverymode/) | Der Datenwiederherstellungsmodus. |
| [DitheringMethod](/imaging/python-net/aspose.imaging/ditheringmethod/) | Dithering‑Methode. |
| [DitheringMethods](/imaging/python-net/aspose.imaging/ditheringmethods/) | Die Dithering‑Methoden, die zur Steuerung der Farbkonvertierung verwendet werden. |
| [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | Eines der unterstützten Bilddateiformate. |
| [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | Gibt an, wie das Innere eines geschlossenen Pfades gefüllt wird. |
| [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) | Gibt die Stilinformationen an, die auf Text angewendet werden. |
| [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Gibt die Maßeinheit für die angegebenen Daten an. |
| [HatchStyle](/imaging/python-net/aspose.imaging/hatchstyle/) | Gibt die verschiedenen Muster an, die für [HatchBrush](/imaging/python-net/aspose.imaging.brushes/hatchbrush/) Objekte verfügbar sind. |
| [HotkeyPrefix](/imaging/python-net/aspose.imaging/hotkeyprefix/) | Gibt den Anzeigetyp für Tastenkombinationspräfixe an, die sich auf Text beziehen. |
| [ImageFilterType](/imaging/python-net/aspose.imaging/imagefiltertype/) | Zu verwendende Bildfilter |
| [InterpolationMode](/imaging/python-net/aspose.imaging/interpolationmode/) | Die Aufzählung [InterpolationMode](/imaging/python-net/aspose.imaging/interpolationmode/) gibt den Algorithmus an, der verwendet wird, wenn Bilder skaliert oder rotiert werden. |
| [KnownColor](/imaging/python-net/aspose.imaging/knowncolor/) | Gibt die bekannten Systemfarben an. |
| [LineCap](/imaging/python-net/aspose.imaging/linecap/) | Gibt die verfügbaren Endstilarten an, mit denen ein [Pen](/imaging/python-net/aspose.imaging/pen/) Objekt eine Linie beenden kann. |
| [LineJoin](/imaging/python-net/aspose.imaging/linejoin/) | Gibt an, wie aufeinanderfolgende Linien- oder Kurvensegmente in einer Figur (Unterpfad), die in einem [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) Objekt enthalten ist, verbunden werden. |
| [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Gibt die Reihenfolge für Matrix-Transformationsoperationen an. |
| [PaletteMiningMethod](/imaging/python-net/aspose.imaging/paletteminingmethod/) | Die Bildpaletten‑Extraktionsmethode |
| [PdfComplianceVersion](/imaging/python-net/aspose.imaging/pdfcomplianceversion/) | Gibt das PDF‑Konformitätsniveau für die Ausgabedatei an. |
| [PenAlignment](/imaging/python-net/aspose.imaging/penalignment/) | Gibt die Ausrichtung eines [Pen](/imaging/python-net/aspose.imaging/pen/) Objekts in Bezug auf die theoretische, nullbreite Linie an. |
| [PenType](/imaging/python-net/aspose.imaging/pentype/) | Gibt den Fülltyp an, den ein [Pen](/imaging/python-net/aspose.imaging/pen/) Objekt zum Füllen von Linien verwendet. |
| [PixelFormat](/imaging/python-net/aspose.imaging/pixelformat/) | Die tatsächliche Bedeutung des Pixel-Datenformats. |
| [ProcessingType](/imaging/python-net/aspose.imaging/processingtype/) | Die Art der Verarbeitung. |
| [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | Gibt den Skalierungstyp an. |
| [ResolutionUnit](/imaging/python-net/aspose.imaging/resolutionunit/) | Auflösungseinheit‑Aufzählung. |
| [RotateFlipType](/imaging/python-net/aspose.imaging/rotatefliptype/) | Gibt an, um wie viel ein Bild rotiert wird und welche Achse zum Spiegeln des Bildes verwendet wird. |
| [SeekOrigin](/imaging/python-net/aspose.imaging/seekorigin/) | Stellt die Felder bereit, die Referenzpunkte in [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) für das Suchen darstellen. |
| [SmoothingMode](/imaging/python-net/aspose.imaging/smoothingmode/) | Gibt an, ob Glättung (Antialiasing) auf Linien und Kurven sowie die Kanten von gefüllten Bereichen angewendet wird. |
| [StringAlignment](/imaging/python-net/aspose.imaging/stringalignment/) | Gibt die Ausrichtung einer Textzeichenfolge relativ zu ihrem Layout‑Rechteck an. |
| [StringDigitSubstitute](/imaging/python-net/aspose.imaging/stringdigitsubstitute/) | Die Aufzählung gibt an, wie Ziffern in einer Zeichenfolge gemäß der Gebietsschema‑ oder Spracheinstellung eines Benutzers ersetzt werden. |
| [StringFormatFlags](/imaging/python-net/aspose.imaging/stringformatflags/) | Gibt die Anzeige‑ und Layoutinformationen für Textzeichenfolgen an. |
| [StringTrimming](/imaging/python-net/aspose.imaging/stringtrimming/) | Gibt an, wie Zeichen aus einer Zeichenfolge entfernt werden, die nicht vollständig in eine Layout‑Form passt. |
| [TextRenderingHint](/imaging/python-net/aspose.imaging/textrenderinghint/) | Gibt die Qualität der Textdarstellung an. |
| [WarpMode](/imaging/python-net/aspose.imaging/warpmode/) | Gibt den Typ der angewendeten Verzerrungstransformation an. |
| [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | Gibt an, wie eine Textur oder ein Farbverlauf gekachelt wird, wenn sie kleiner ist als der zu füllende Bereich. |
