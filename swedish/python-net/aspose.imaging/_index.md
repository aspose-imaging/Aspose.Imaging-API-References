---
title: "aspose.imaging"
type: docs
weight: 10
url: /sv/python-net/aspose.imaging/
---


Modulen är kärnan för nästlade moduler och de mest grundläggande objekten som används för Aspose.Imaging‑behandling.

## **Classes**
| **Klass** | **Description** |
| :- | :- |
| [Blend](/imaging/python-net/aspose.imaging/blend/) | Definierar ett blandningsmönster. Denna klass kan inte ärvas. |
| [Brush](/imaging/python-net/aspose.imaging/brush/) | Baspenselklassen. |
| [BuildVersionInfo](/imaging/python-net/aspose.imaging/buildversioninfo/) | Innehåller information om den aktuella byggversionen. |
| [Cache](/imaging/python-net/aspose.imaging/cache/) | Innehåller cache‑inställningar. |
| [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) | CMYK‑färgen för pixeln. |
| [CmykColorHelper](/imaging/python-net/aspose.imaging/cmykcolorhelper/) | Hjälpmetoder för att arbeta med CMYK‑färg presenterad som ett signerat 32‑bitars heltalsvärde.<br/>            Tillhandahåller ett liknande API som strukturen [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/).<br/>            Den är mer lättviktig eftersom CMYK‑färgen bara presenteras som Int32 snarare än som en struktur med interna fält.<br/>            Använd gärna de statiska metoderna i denna klass när det är möjligt istället för den föråldrade<br/>            [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) strukturen. |
| [Color](/imaging/python-net/aspose.imaging/color/) | Färgen på pixeln. |
| [ColorBlend](/imaging/python-net/aspose.imaging/colorblend/) | Definierar arrayer av färger och positioner som används för interpolering av färgblandning i en flerfärgsgradient. Denna klass kan inte ärvas. |
| [ColorMap](/imaging/python-net/aspose.imaging/colormap/) | Definierar en karta för färgkonvertering. Flera metoder i klassen [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) justerar bildfärger genom att använda en färg-omkartningstabell, som är en array av [ColorMap](/imaging/python-net/aspose.imaging/colormap/) strukturer. Inte ärvbar. |
| [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) | Definierar en 5 x 5-matris som innehåller koordinaterna för RGBA-rymden. Flera metoder i klassen [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) justerar bildfärger genom att använda en färgmatris. Denna klass kan inte ärvas. |
| [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) | Definierar en array av färger som utgör en färgpalett. Färgerna är 32-bitars ARGB-färger. Inte ärvbar. |
| [ColorPaletteHelper](/imaging/python-net/aspose.imaging/colorpalettehelper/) | Hjälparklass för manipulation av färgpaletter. |
| [ColorTranslator](/imaging/python-net/aspose.imaging/colortranslator/) | Översätter färger till och från GDI+ Color-strukturer. Denna klass kan inte ärvas. |
| [CustomLineCap](/imaging/python-net/aspose.imaging/customlinecap/) | Inkapslar en anpassad användardefinierad linjekap. |
| [DataStreamSupporter](/imaging/python-net/aspose.imaging/datastreamsupporter/) | Behållaren för datastreamen. |
| [DisposableObject](/imaging/python-net/aspose.imaging/disposableobject/) | Representerar ett engångsobjekt. |
| [EmbeddedImage](/imaging/python-net/aspose.imaging/embeddedimage/) | Den inbäddade bildklassen |
| [Figure](/imaging/python-net/aspose.imaging/figure/) | Figuren. En behållare för former. |
| [FileStreamContainer](/imaging/python-net/aspose.imaging/filestreamcontainer/) | Hjälp för filströmshantering. |
| [Font](/imaging/python-net/aspose.imaging/font/) | Definierar ett specifikt format för text, inklusive teckensnitt, storlek och stilattribut. Denna klass kan inte ärvas. |
| [FontSettings](/imaging/python-net/aspose.imaging/fontsettings/) | Allmänna teckensnittsinställningar för vektorgrafikformatrenderare. |
| [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Representerar grafiken enligt den grafikmotor som används i den aktuella sammansättningen. |
| [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Representerar en serie av sammanhängande linjer och kurvor. Denna klass kan inte ärvas. |
| [IAdvancedBufferProcessor](/imaging/python-net/aspose.imaging/iadvancedbufferprocessor/) | Den avancerade buffertprocessorn. |
| [IAnimationFrame](/imaging/python-net/aspose.imaging/ianimationframe/) | Animationsramen |
| [IBufferProcessor](/imaging/python-net/aspose.imaging/ibufferprocessor/) | Buffertprocessorn. |
| [IColorConverter](/imaging/python-net/aspose.imaging/icolorconverter/) | Färgkonverteraren. |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | Färgpalettgränssnittet. |
| [IHasMetadata](/imaging/python-net/aspose.imaging/ihasmetadata/) | Bildmetadata-gränssnittet. |
| [IImageCreator](/imaging/python-net/aspose.imaging/iimagecreator/) | Bildskaparen. |
| [IImageCreatorDescriptor](/imaging/python-net/aspose.imaging/iimagecreatordescriptor/) | Bildskapardeskriptorn som specificerar skaparegenskaperna. Skapardeskriptorn används för att övervinna<br/>            behovet av att hålla varje bildskaparinstans i minnet och problem med flertrådad körning. |
| [IImageDescriptor](/imaging/python-net/aspose.imaging/iimagedescriptor/) | Bildbeskrivaren. Innehåller grundegenskaper och metoder för alla andra bildbeskrivartyper. |
| [IImageExporter](/imaging/python-net/aspose.imaging/iimageexporter/) | Bildexportören. Kan exportera data från internt `aspose.imaging`-format till ett specificerat dataformat. |
| [IImageExporterDescriptor](/imaging/python-net/aspose.imaging/iimageexporterdescriptor/) | Representerar bildexportörens beskrivning. Exportörens beskrivning används för att övervinna behovet av att hålla varje exportörsinstans i minnet och problem med multitrådad körning.<br/>             |
| [IImageLoader](/imaging/python-net/aspose.imaging/iimageloader/) | Bildläsaren. |
| [IImageLoaderDescriptor](/imaging/python-net/aspose.imaging/iimageloaderdescriptor/) | Bildläsarens beskrivning som specificerar laddarens egenskaper. Laddarens beskrivning används för att övervinna<br/>            behovet av att hålla varje bildläsarinstans i minnet och problem med multitrådad körning. |
| [IIndexedColorConverter](/imaging/python-net/aspose.imaging/iindexedcolorconverter/) | Färgkonverteraren för indexerade bildformat. |
| [IMetadataContainer](/imaging/python-net/aspose.imaging/imetadatacontainer/) | Gränssnitt för bildmetadata-behållare. |
| [IMultipageImage](/imaging/python-net/aspose.imaging/imultipageimage/) | Gränssnittet för flersidiga bilder |
| [IMultipageImageExt](/imaging/python-net/aspose.imaging/imultipageimageext/) | Det utökade gränssnittet för flersidiga bilder |
| [IObjectWithBounds](/imaging/python-net/aspose.imaging/iobjectwithbounds/) | Representerar ett objekt med gränser. |
| [IOrderedShape](/imaging/python-net/aspose.imaging/iorderedshape/) | Representerar en ordnad form. En ordnad form är en kontinuerlig uppsättning punkter med en startpunkt och en slutpunkt.<br/>            Den kontinuerliga uppsättningen av punkter som är sammankopplade med en specifik regel. |
| [IPartialArgb32PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb32pixelloader/) | Följer de delvis laddade 32-bitars ARGB-pixlarna. |
| [IPartialArgb64PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb64pixelloader/) | 64-bitars ARGB-pixel-laddaren. |
| [IPartialPixelLoader](/imaging/python-net/aspose.imaging/ipartialpixelloader/) | Följer de delvis laddade pixlarna. |
| [IPartialRawDataLoader](/imaging/python-net/aspose.imaging/ipartialrawdataloader/) | Den partiella dataladdaren. |
| [IRasterImageArgb32PixelLoader](/imaging/python-net/aspose.imaging/irasterimageargb32pixelloader/) | Rasterbildens 32-bitars ARGB-pixel-laddare. |
| [IRasterImageArgb64PixelLoader](/imaging/python-net/aspose.imaging/irasterimageargb64pixelloader/) | Rasterbildens 64-bitars ARGB-pixel-laddare. |
| [IRasterImagePixelLoader](/imaging/python-net/aspose.imaging/irasterimagepixelloader/) | Rasterbildens pixel-laddare. |
| [IRasterImageRawDataLoader](/imaging/python-net/aspose.imaging/irasterimagerawdataloader/) | Rasterbildens rådata-laddare. |
| [Image](/imaging/python-net/aspose.imaging/image/) | Bilden är basklassen för alla typer av bilder. |
| [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | Ett [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/)‑objekt innehåller information om hur bitmap‑ och metafilfärger manipuleras under rendering. Ett [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/)‑objekt upprätthåller flera färgjusteringsinställningar, inklusive färgjusteringsmatriser, gråskalejusteringsmatriser, gamma‑korrektionsvärden, färgkartutabeller och färgtröskelvärden. Under rendering kan färger korrigeras, mörkras, ljusas upp och tas bort. För att tillämpa sådana manipulationer, initiera ett [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/)‑objekt och skicka sökvägen till det [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/)‑objektet (tillsammans med sökvägen till en [Image](/imaging/python-net/aspose.imaging/image/)) till metoden DrawImage. |
| [ImageCreatorsRegistry](/imaging/python-net/aspose.imaging/imagecreatorsregistry/) | Representerar registret för bildskapare. |
| [ImageExportersRegistry](/imaging/python-net/aspose.imaging/imageexportersregistry/) | Representerar registret för bildexportörer. |
| [ImageLoadersRegistry](/imaging/python-net/aspose.imaging/imageloadersregistry/) | Representerar registret för bildläsare. |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Bildens grundalternativ. |
| [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Klass för bildstorleksändringsinställningar |
| [IntRange](/imaging/python-net/aspose.imaging/intrange/) | Klass för att representera en sekvens av element |
| [License](/imaging/python-net/aspose.imaging/license/) | Tillhandahåller metoder för att licensiera komponenten. |
| [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | Representerar laddningsalternativen. |
| [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Ersätter GDI+ Matrix. |
| [Metered](/imaging/python-net/aspose.imaging/metered/) | Tillhandahåller mätade metoder för integration |
| [NonGenericDictionary](/imaging/python-net/aspose.imaging/nongenericdictionary/) | Representerar en icke-generisk ordbok. |
| [NonGenericList](/imaging/python-net/aspose.imaging/nongenericlist/) | Icke-generisk lista med objekt |
| [ObjectWithBounds](/imaging/python-net/aspose.imaging/objectwithbounds/) | Objektet med gränser. |
| [OpenTypeFontsCache](/imaging/python-net/aspose.imaging/opentypefontscache/) | Cache för OpenType-teckensnitt som är installerade i systemet. |
| [Pen](/imaging/python-net/aspose.imaging/pen/) | Definierar ett objekt som används för att rita linjer, kurvor och figurer. |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | Pixeldataformatet. Detta är ett oföränderligt objekt. |
| [Point](/imaging/python-net/aspose.imaging/point/) | Representerar ett ordnat par av heltals x- och y-koordinater som definierar en punkt i ett tvådimensionellt plan. |
| [PointF](/imaging/python-net/aspose.imaging/pointf/) | Representerar ett ordnat par av flyttals x- och y-koordinater som definierar en punkt i ett tvådimensionellt plan. |
| [RasterCachedImage](/imaging/python-net/aspose.imaging/rastercachedimage/) | Representerar en rasterbild som stöder rastergrafikoperationer. Denna bild cachar pixeldata vid behov. |
| [RasterCachedMultipageImage](/imaging/python-net/aspose.imaging/rastercachedmultipageimage/) | Rasterflersidig bild |
| [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Representerar en rasterbild som stöder rastergrafikoperationer. |
| [RawDataSettings](/imaging/python-net/aspose.imaging/rawdatasettings/) | Inställningarna för rådata |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Lagrar en uppsättning av fyra heltal som representerar platsen och storleken på en rektangel. |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Lagrar en uppsättning av fyra flyttal som representerar platsen och storleken på en rektangel. |
| [Region](/imaging/python-net/aspose.imaging/region/) | Beskriver insidan av en grafisk form bestående av rektanglar och banor. Denna klass kan inte ärvas. |
| [RemoveBackgroundSettings](/imaging/python-net/aspose.imaging/removebackgroundsettings/) | Inställningarna för att ta bort bakgrund |
| [ResolutionSetting](/imaging/python-net/aspose.imaging/resolutionsetting/) | Upplösningsinställningen för bildsparalternativ. |
| [Shape](/imaging/python-net/aspose.imaging/shape/) | Formen. En kontinuerlig uppsättning punkter som är sammankopplade med en specifik regel. |
| [ShapeSegment](/imaging/python-net/aspose.imaging/shapesegment/) | Representerar ett formsegment. Ett segment är en linje eller kurva som förbinder två punkter. |
| [Size](/imaging/python-net/aspose.imaging/size/) | Representerar storlek. |
| [SizeF](/imaging/python-net/aspose.imaging/sizef/) | Lagrar ett ordnat par flyttal, vanligtvis bredden och höjden på en rektangel. |
| [Source](/imaging/python-net/aspose.imaging/source/) | Källan används för att innehålla all relevant information för ett objektpipe. |
| [SplitStreamContainer](/imaging/python-net/aspose.imaging/splitstreamcontainer/) | Representerar en delad strömkontainer som innehåller strömmen och tillhandahåller strömbehandlingsrutiner. |
| [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | Representerar en strömkontainer som innehåller strömmen och tillhandahåller strömbehandlingsrutiner. |
| [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | Inkapslar information om textlayout (såsom justering, orientering och tabbstopp), displaymanipulationer (såsom insättning av ellips och nationell siffrersubstitution) och OpenType-funktioner. Denna klass kan inte ärvas. |
| [TransparencySupporter](/imaging/python-net/aspose.imaging/transparencysupporter/) | Objektet som stödjer transparens. |
| [VectorImage](/imaging/python-net/aspose.imaging/vectorimage/) | Vektorbilden är basklassen för alla typer av vektorbilder. |
| [VectorMultipageImage](/imaging/python-net/aspose.imaging/vectormultipageimage/) | Vektor‑multipagesbilden. |
## **Enumerations**
| **Enumeration** | **Description** |
| :- | :- |
| [AnimationDisposalMethods](/imaging/python-net/aspose.imaging/animationdisposalmethods/) | Anger hur grafiken ska behandlas efter att den har visats. |
| [CacheType](/imaging/python-net/aspose.imaging/cachetype/) | Anger vilken cache‑typ som ska användas. |
| [CharacterSet](/imaging/python-net/aspose.imaging/characterset/) | Representerar den använda teckenuppsättningen. |
| [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | Anger vilka objekt som använder färgjusteringsinformation. |
| [ColorChannelFlag](/imaging/python-net/aspose.imaging/colorchannelflag/) | Anger enskilda kanaler i CMYK‑färgrymden (cyan, magenta, gult, svart). Denna uppräkning används av metoderna SetOutputChannel. |
| [ColorCompareMethod](/imaging/python-net/aspose.imaging/colorcomparemethod/) | Färgjämförelsesmetod för att justera till närmaste granne. |
| [ColorMatrixFlag](/imaging/python-net/aspose.imaging/colormatrixflag/) | Anger vilka typer av bilder och färger som kommer att påverkas av färg‑ och gråskalajusteringsinställningarna för ett [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/). |
| [ColorQuantizationMethod](/imaging/python-net/aspose.imaging/colorquantizationmethod/) | Metoder för färgkvantisering. |
| [CompositingQuality](/imaging/python-net/aspose.imaging/compositingquality/) | Anger kvalitetsnivån som ska användas under sammanslagning. |
| [DashCap](/imaging/python-net/aspose.imaging/dashcap/) | Anger vilken typ av grafisk form som ska användas i båda ändarna av varje streck i en streckad linje. |
| [DashStyle](/imaging/python-net/aspose.imaging/dashstyle/) | Anger stilen på streckade linjer som ritas med ett [Pen](/imaging/python-net/aspose.imaging/pen/)‑objekt. |
| [DataRecoveryMode](/imaging/python-net/aspose.imaging/datarecoverymode/) | Datåterställningsläget. |
| [DitheringMethod](/imaging/python-net/aspose.imaging/ditheringmethod/) | Dithermetod. |
| [DitheringMethods](/imaging/python-net/aspose.imaging/ditheringmethods/) | Dithermetoderna som används för att kontrollera färgkonvertering. |
| [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | Ett av de stödjade bildfilformaten. |
| [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | Anger hur insidan av en sluten bana fylls. |
| [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) | Anger stilinformation som tillämpas på text. |
| [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Anger måttenheten för de givna data. |
| [HatchStyle](/imaging/python-net/aspose.imaging/hatchstyle/) | Anger de olika mönstren som är tillgängliga för [HatchBrush](/imaging/python-net/aspose.imaging.brushes/hatchbrush/) objekt. |
| [HotkeyPrefix](/imaging/python-net/aspose.imaging/hotkeyprefix/) | Anger vilken typ av visning som används för snabbtangentprefix som relaterar till text. |
| [ImageFilterType](/imaging/python-net/aspose.imaging/imagefiltertype/) | Bildfilter att använda |
| [InterpolationMode](/imaging/python-net/aspose.imaging/interpolationmode/) | Enumen [InterpolationMode](/imaging/python-net/aspose.imaging/interpolationmode/) anger den algoritm som används när bilder skalas eller roteras. |
| [KnownColor](/imaging/python-net/aspose.imaging/knowncolor/) | Anger de kända systemfärgerna. |
| [LineCap](/imaging/python-net/aspose.imaging/linecap/) | Anger de tillgängliga spetsstilarna som ett [Pen](/imaging/python-net/aspose.imaging/pen/) objekt kan avsluta en linje med. |
| [LineJoin](/imaging/python-net/aspose.imaging/linejoin/) | Anger hur man förenar på varandra följande linje- eller kurvsegment i en figur (delväg) som finns i ett [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) objekt. |
| [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Anger ordningen för matristransformationsoperationer. |
| [PaletteMiningMethod](/imaging/python-net/aspose.imaging/paletteminingmethod/) | Metoden för bildpalettutvinning |
| [PdfComplianceVersion](/imaging/python-net/aspose.imaging/pdfcomplianceversion/) | Anger PDF-kompatibilitetsnivån för utdatafilen. |
| [PenAlignment](/imaging/python-net/aspose.imaging/penalignment/) | Anger justeringen av ett [Pen](/imaging/python-net/aspose.imaging/pen/) objekt i förhållande till den teoretiska linjen med noll bredd. |
| [PenType](/imaging/python-net/aspose.imaging/pentype/) | Anger vilken fyllningstyp ett [Pen](/imaging/python-net/aspose.imaging/pen/) objekt använder för att fylla linjer. |
| [PixelFormat](/imaging/python-net/aspose.imaging/pixelformat/) | Den faktiska betydelsen av pixeldataformatet. |
| [ProcessingType](/imaging/python-net/aspose.imaging/processingtype/) | Typen av bearbetning. |
| [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | Anger typ av storleksändring. |
| [ResolutionUnit](/imaging/python-net/aspose.imaging/resolutionunit/) | Enum för upplösningsenhet. |
| [RotateFlipType](/imaging/python-net/aspose.imaging/rotatefliptype/) | Anger hur mycket en bild roteras och vilken axel som används för att vända bilden. |
| [SeekOrigin](/imaging/python-net/aspose.imaging/seekorigin/) | Tillhandahåller fälten som representerar referenspunkter i [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) för sökning. |
| [SmoothingMode](/imaging/python-net/aspose.imaging/smoothingmode/) | Anger om jämning (kantutjämning) tillämpas på linjer och kurvor samt kanterna på fyllda områden. |
| [StringAlignment](/imaging/python-net/aspose.imaging/stringalignment/) | Anger justeringen av en textsträng i förhållande till dess layoutrektangel. |
| [StringDigitSubstitute](/imaging/python-net/aspose.imaging/stringdigitsubstitute/) | Enumen anger hur man ersätter siffror i en sträng enligt en användares landsinställning eller språk. |
| [StringFormatFlags](/imaging/python-net/aspose.imaging/stringformatflags/) | Anger visnings- och layoutinformation för textsträngar. |
| [StringTrimming](/imaging/python-net/aspose.imaging/stringtrimming/) | Anger hur man trimmar tecken från en sträng som inte helt får plats i en layoutform. |
| [TextRenderingHint](/imaging/python-net/aspose.imaging/textrenderinghint/) | Anger kvaliteten på textåtergivning. |
| [WarpMode](/imaging/python-net/aspose.imaging/warpmode/) | Anger typen av warp‑transformation som tillämpas. |
| [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | Anger hur en textur eller gradient tileas när den är mindre än det område som fylls. |
