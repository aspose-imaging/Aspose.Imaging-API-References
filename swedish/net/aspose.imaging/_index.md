---
title: Aspose.Imaging
second_title: Aspose.Imaging för .NET API-referens
description: Namnutrymmet är kärnan för kapslade namnutrymmen och de mest grundläggande objekten som används för Aspose.Imaging-behandling.
type: docs
weight: 10
url: /sv/net/aspose.imaging/
---
Namnutrymmet är kärnan för kapslade namnutrymmen och de mest grundläggande objekten som används för Aspose.Imaging-behandling.

## Klasser

| Klass | Beskrivning |
| --- | --- |
| [AggregateException](./aggregateexception) | Samlar flera undantag. |
| [Blend](./blend) | Definierar ett blandningsmönster. Denna klass kan inte ärvas. |
| [Brush](./brush) | Klassen för basborst. |
| [BuildVersionInfo](./buildversioninfo) | Innehåller den aktuella versionsinformationen. |
| [Cache](./cache) | Innehåller cacheinställningar. |
| [CmykColorHelper](./cmykcolorhelper) | Hjälpmetoder för att arbeta med CMYK-färg presenteras som ett signerat 32-bitars heltalsvärde. Tillhandahåller liknande API som[`CmykColor`](../aspose.imaging/cmykcolor) struct. Den är mer lättviktig eftersom CMYK-färg presenteras precis som Int32 snarare än struktur med interna fält. Föredrar att använda statiska metoder av denna klass när det är möjligt istället för deprecated [`CmykColor`](../aspose.imaging/cmykcolor) struct. |
| [ColorBlend](./colorblend) | Definierar arrayer av färger och positioner som används för att interpolera färgblandning i en flerfärgsgradient. Denna klass kan inte ärvas. |
| [ColorMap](./colormap) | Definierar en karta för att konvertera färger. Flera metoder för[`ImageAttributes`](../aspose.imaging/imageattributes) klass justera bildfärger med hjälp av en färgombildningstabell, som är en uppsättning av[`ColorMap`](../aspose.imaging/colormap) strukturer. Inte ärftlig. |
| [ColorMatrix](./colormatrix) | Definierar en 5 x 5 matris som innehåller koordinaterna för RGBA-utrymmet. Flera metoder för[`ImageAttributes`](../aspose.imaging/imageattributes) klass justera bildfärger med hjälp av en färgmatris. Denna klass kan inte ärvas. |
| [ColorPalette](./colorpalette) | Definierar en uppsättning färger som utgör en färgpalett. Färgerna är 32-bitars ARGB-färger. Inte ärftligt. |
| [ColorPaletteHelper](./colorpalettehelper) | Hjälparklass för manipulering av färgpaletter. |
| [ColorTranslator](./colortranslator) | Översätter färger till och från GDI+ färgstrukturer. Denna klass kan inte ärvas. |
| [CompositeException](./compositeexception) | Det sammansatta undantaget |
| [CustomFontSource](./customfontsource) | Anpassad teckensnittskälla funktion |
| [CustomLineCap](./customlinecap) | Kapslar in ett anpassat användardefinierat linjetak. |
| [DataStreamSupporter](./datastreamsupporter) | Dataströmsbehållaren. |
| [DisposableObject](./disposableobject) | Representerar engångsobjekt. |
| [EmbeddedImage](./embeddedimage) | Den inbäddade bilden class |
| [Figure](./figure) | Figuren. En behållare för former. |
| [FileStreamContainer](./filestreamcontainer) | Hjälpare för bearbetning av filström. |
| [Font](./font) | Definierar ett visst format för text, inklusive teckensnitt, storlek och stilattribut. Denna klass kan inte ärvas. |
| [FontSettings](./fontsettings) | Allmänna teckensnittsinställningar för bildframställning vektorformat för renderare. |
| [Graphics](./graphics) | Representerar grafiken enligt den grafikmotor som används i den aktuella sammansättningen. |
| [GraphicsPath](./graphicspath) | Representerar en serie sammankopplade linjer och kurvor. Denna klass kan inte ärvas. |
| [Image](./image) | Bilden är basklassen för alla typer av bilder. |
| [ImageAttributes](./imageattributes) | An[`ImageAttributes`](../aspose.imaging/imageattributes) objektet innehåller information om hur bitmapps- och metafilfärger manipuleras under rendering. En[`ImageAttributes`](../aspose.imaging/imageattributes)objektet har flera färgjusteringsinställningar, inklusive färgjusteringsmatriser, gråskalejusteringsmatriser, gammakorrigeringsvärden, färgkartatabeller och färgtröskelvärden. Under renderingen kan färger korrigeras, mörkas, ljusnas och tas bort. För att tillämpa sådana manipulationer, initiera en[`ImageAttributes`](../aspose.imaging/imageattributes) objekt och passera vägen för det[`ImageAttributes`](../aspose.imaging/imageattributes) objekt (tillsammans med sökvägen för en[`Image`](../aspose.imaging/image) ) till DrawImage-metoden. |
| [ImageCreatorsRegistry](./imagecreatorsregistry) | Representerar registret för bildskapare. |
| [ImageExportersRegistry](./imageexportersregistry) | Representerar bildexportörernas register. |
| [ImageLoadersRegistry](./imageloadersregistry) | Representerar bildladdarens register. |
| [ImageOptionsBase](./imageoptionsbase) | Bildbasalternativen. |
| [ImageResizeSettings](./imageresizesettings) | Inställningar för bildstorleksändring class |
| [IntRange](./intrange) | Klass för att representera sekvens av element |
| [License](./license) | Tillhandahåller metoder för att licensiera komponenten. |
| [LoadOptions](./loadoptions) | Representerar laddningsalternativen. |
| [Matrix](./matrix) | Ersätter GDI+-matrisen. |
| [Metered](./metered) | Tillhandahåller metoder för att ställa in mätnyckel. |
| [NonGenericDictionary](./nongenericdictionary) | Representerar en icke-generisk ordbok. |
| [NonGenericList](./nongenericlist) | Icke generisk lista över objekt |
| [ObjectWithBounds](./objectwithbounds) | Objektet som har gränser. |
| [OpenTypeFontsCache](./opentypefontscache) | Cache för OpenType-teckensnitt som är installerade i systemet. |
| [PageExportingAction](./pageexportingaction) | Delegat för avfyrning innan sidan exporteras |
| [Pen](./pen) | Definierar ett objekt som används för att rita linjer, kurvor och figurer. |
| [PixelDataFormat](./pixeldataformat) | Pixeldataformatet. Detta är ett oföränderligt objekt. |
| [ProgressEventHandler](./progresseventhandler) | Progress händelsehanterare funktion reference |
| [RasterCachedImage](./rastercachedimage) | Representerar en rasterbild som stöder rastergrafikoperationer. Den här bilden cachar pixeldata vid behov. |
| [RasterCachedMultipageImage](./rastercachedmultipageimage) | Rasterbilden med flera sidor |
| [RasterImage](./rasterimage) | Representerar en rasterbild som stöder rastergrafikoperationer. |
| [RawDataSettings](./rawdatasettings) | Inställningarna för rådata |
| [Region](./region) | Beskriver det inre av en grafisk form som består av rektanglar och banor. Denna klass kan inte ärvas. |
| [ResolutionSetting](./resolutionsetting) | Upplösningsinställningen för bildsparalternativ. |
| [Shape](./shape) | Formen. En kontinuerlig uppsättning punkter kopplade med en specifik regel. |
| [ShapeSegment](./shapesegment) | Representerar ett formsegment. Ett segment är en linje eller kurva som förbinder två punkter. |
| [Source](./source) | Källan används för att innehålla all relevant information för ett objektrör. |
| [SplitStreamContainer](./splitstreamcontainer) | Representerar delad strömbehållare som innehåller strömmen och tillhandahåller strömbehandlingsrutiner. |
| [StreamContainer](./streamcontainer) | Representerar strömbehållare som innehåller strömmen och tillhandahåller strömbehandlingsrutiner. |
| [StringFormat](./stringformat) | Kapslar in textlayoutinformation (som justering, orientering och tabbstopp), visningsmanipulationer (som ellipsinsättning och nationell siffrorsättning) och OpenType-funktioner. Denna klass kan inte ärvas. |
| [TransparencySupporter](./transparencysupporter) | Objektet som stöder transparens. |
| [VectorImage](./vectorimage) | Vektorbilden är basklassen för alla typer av vektorbilder. |
| [VectorMultipageImage](./vectormultipageimage) | Vector flersidig bild |
## Gränssnitt

| Gränssnitt | Beskrivning |
| --- | --- |
| [IAdvancedBufferProcessor](./iadvancedbufferprocessor) | Den avancerade buffertprocessorn. |
| [IAnimationFrame](./ianimationframe) | Animationsramen |
| [IBufferProcessor](./ibufferprocessor) | Buffertprocessorn. |
| [IColorConverter](./icolorconverter) | Färgomvandlaren. |
| [IColorPalette](./icolorpalette) | Gränssnittet för färgpaletten. |
| [IImageCreator](./iimagecreator) | Bildskaparen. |
| [IImageCreatorDescriptor](./iimagecreatordescriptor) | Bildskaparens beskrivning som specificerar skaparens egenskaper. Skaparbeskrivningen används för att övervinna nödvändigheten av att innehålla varje bildskaparinstans i minnes- och flertrådsproblem. |
| [IImageDescriptor](./iimagedescriptor) | Bildbeskrivningen. Innehåller basegenskaper och metoder för alla andra bildbeskrivningstyper. |
| [IImageExporter](./iimageexporter) | Bildexportören. Kan exportera data från internt Aspose.Imaging-format till ett specificerat dataformat. |
| [IImageExporterDescriptor](./iimageexporterdescriptor) | Representerar bildexportörens beskrivning. Exportörbeskrivningen används för att övervinna behovet av att innehålla varje exportörinstans i minnet och problem med flera trådar. |
| [IImageLoader](./iimageloader) | Bildladdaren. |
| [IImageLoaderDescriptor](./iimageloaderdescriptor) | Bildladdningsbeskrivningen som anger laddningsegenskaperna. Lastarbeskrivningen används för att övervinna nödvändigheten att innehålla varje bildladdningsinstans i minnes- och flertrådsproblem. |
| [IIndexedColorConverter](./iindexedcolorconverter) | Färgkonverteraren för indexerade bildformat. |
| [IKeyedObject](./ikeyedobject) | Representerar gränssnitt för objekt med nycklar. |
| [IMultipageImage](./imultipageimage) | Flersidig bildgränssnitt |
| [IMultipageImageExt](./imultipageimageext) | Det utökade flersidiga bildgränssnittet |
| [IObjectWithBounds](./iobjectwithbounds) | Representerar ett objekt med gränser. |
| [IOrderedShape](./iorderedshape) | Representerar en ordnad form. En ordnad form är en kontinuerlig uppsättning punkter som har en startpunkt och en slutpunkt. Den kontinuerliga uppsättningen av punkter kopplade med en specifik regel. |
| [IPartialArgb32PixelLoader](./ipartialargb32pixelloader) | Överensstämmer med 32-bitars ARGB-pixlar som laddas delvis. |
| [IPartialArgb64PixelLoader](./ipartialargb64pixelloader) | 64-bitars ARGB-pixelladdaren. |
| [IPartialPixelLoader](./ipartialpixelloader) | Överensstämmer med pixlarna som laddas delvis. |
| [IPartialRawDataLoader](./ipartialrawdataloader) | Den partiella dataladdaren. |
| [IRasterImageArgb32PixelLoader](./irasterimageargb32pixelloader) | Rasterbilden 32-bitars ARGB pixel loader. |
| [IRasterImagePixelLoader](./irasterimagepixelloader) | Rasterbildpixelladdaren. |
| [IRasterImageRawDataLoader](./irasterimagerawdataloader) | Rasterbildens rådataladdare. |
## Uppräkning

| Uppräkning | Beskrivning |
| --- | --- |
| [AnimationDisposalMethods](./animationdisposalmethods) | Indikerar hur grafiken ska behandlas efter att den har visats. |
| [CacheType](./cachetype) | Anger vilken typ av cache som ska användas. |
| [CharacterSet](./characterset) | Representerar teckenuppsättningen som används. |
| [ColorAdjustType](./coloradjusttype) | Anger vilka objekt som använder färgjusteringsinformation. |
| [ColorChannelFlag](./colorchannelflag) | Anger enskilda kanaler i CMYK-färgrymden (cyan, magenta, gul, svart). Denna uppräkning används av SetOutputChannel-metoderna. |
| [ColorCompareMethod](./colorcomparemethod) | Färgjämförelsesmetod för att justera till närmaste granne |
| [ColorMatrixFlag](./colormatrixflag) | Anger vilka typer av bilder och färger som kommer att påverkas av färg- och gråskalejusteringsinställningarna för en[`ImageAttributes`](../aspose.imaging/imageattributes) . |
| [ColorQuantizationMethod](./colorquantizationmethod) | Färgkvantiseringsmetoder |
| [CompositingQuality](./compositingquality) | Anger den kvalitetsnivå som ska användas under sammansättningen. |
| [DashCap](./dashcap) | Anger vilken typ av grafisk form som ska användas på båda ändarna av varje streck i en streckad linje. |
| [DashStyle](./dashstyle) | Anger stilen för streckade linjer som ritas med a[`Pen`](../aspose.imaging/pen) objekt. |
| [DataRecoveryMode](./datarecoverymode) | Dataåterställningsläget. |
| [DitheringMethod](./ditheringmethod) | Rastreringsmetod. |
| [DitheringMethods](./ditheringmethods) | Vibreringsmetoderna som används för att kontrollera färgkonvertering. |
| [FileFormat](./fileformat) | Ett av de bildformat som stöds. |
| [FillMode](./fillmode) | Anger hur det inre av en stängd bana fylls. |
| [FontStyle](./fontstyle) | Anger stilinformation som tillämpas på text. |
| [GraphicsUnit](./graphicsunit) | Anger måttenheten för givna data. |
| [HatchStyle](./hatchstyle) | Anger de olika mönster som är tillgängliga för[`HatchBrush`](../aspose.imaging.brushes/hatchbrush) objekt. |
| [HotkeyPrefix](./hotkeyprefix) | Anger typen av visning för snabbtangentsprefix som relaterar till text. |
| [ImageFilterType](./imagefiltertype) | Bildfilter att använda |
| [InterpolationMode](./interpolationmode) | Den[`InterpolationMode`](../aspose.imaging/interpolationmode) uppräkning anger algoritmen som används när bilder skalas eller roteras. |
| [KnownColor](./knowncolor) | Anger de kända systemfärgerna. |
| [LineCap](./linecap) | Anger tillgängliga cap-stilar med vilka en[`Pen`](../aspose.imaging/pen) objekt kan avsluta en rad. |
| [LineJoin](./linejoin) | Anger hur man sammanfogar på varandra följande linje- eller kurvsegment i en figur (undersökväg) som finns i en[`GraphicsPath`](../aspose.imaging/graphicspath) objekt. |
| [MatrixOrder](./matrixorder) | Anger ordningen för matristransformeringsoperationer. |
| [PaletteMiningMethod](./paletteminingmethod) | Bildpalettbrytningsmetoden |
| [PdfComplianceVersion](./pdfcomplianceversion) | Anger PDF-kompatibilitetsnivån för utdatafilen. |
| [PenAlignment](./penalignment) | Anger justeringen av en[`Pen`](../aspose.imaging/pen)objekt i förhållande till den teoretiska nollbreddslinjen. |
| [PenType](./pentype) | Anger typen av fyllning a[`Pen`](../aspose.imaging/pen) objekt använder för att fylla linjer. |
| [PixelFormat](./pixelformat) | Pixeldataformatets faktiska betydelse. |
| [ResizeType](./resizetype) | Anger storleksändringstypen. |
| [ResolutionUnit](./resolutionunit) | Upplösningsenhet enum. |
| [RotateFlipType](./rotatefliptype) | Anger hur mycket en bild roteras och axeln som används för att vända bilden. |
| [SeekOrigin](./seekorigin) | Tillhandahåller fälten som representerar referenspunkter i[`StreamContainer`](../aspose.imaging/streamcontainer) för att söka. |
| [SmoothingMode](./smoothingmode) | Anger om utjämning (kantutjämning) tillämpas på linjer och kurvor och kanterna på fyllda områden. |
| [StringAlignment](./stringalignment) | Anger justeringen av en textsträng i förhållande till dess layoutrektangel. |
| [StringDigitSubstitute](./stringdigitsubstitute) | Uppräkningen anger hur man byter ut siffror i en sträng enligt en användares språk eller språk. |
| [StringFormatFlags](./stringformatflags) | Anger visnings- och layoutinformation för textsträngar. |
| [StringTrimming](./stringtrimming) | Anger hur tecken ska trimmas från en sträng som inte passar helt in i en layoutform. |
| [TextRenderingHint](./textrenderinghint) | Anger kvaliteten på textåtergivningen. |
| [WarpMode](./warpmode) | Anger vilken typ av varptransformation som tillämpas. |
| [WrapMode](./wrapmode) | Anger hur en struktur eller övertoning är sida vid sida när den är mindre än området som fylls. |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
