---
title: "ExifProperties"
second_title: "Aspose.Imaging för Java API-referens"
description: "Lista över Exif-taggar"
type: docs
weight: 11
url: /sv/java/com.aspose.imaging.exif/exifproperties/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ExifProperties extends System.Enum
```

Lista över Exif-taggar
## Fält

| Fält | Beskrivning |
| --- | --- |
| [ImageWidth](#ImageWidth) | Antalet kolumner i bilddata, lika med antalet pixlar per rad. |
| [ImageLength](#ImageLength) | Antalet rader i bilddata. |
| [BitsPerSample](#BitsPerSample) | Antalet bitar per bildkomponent. |
| [Compression](#Compression) | Komprimeringsschemat som används för bilddata. |
| [PhotometricInterpretation](#PhotometricInterpretation) | Pixelns sammansättning. |
| [ImageDescription](#ImageDescription) | En teckensträng som ger bildens titel. |
| [Make](#Make) | Tillverkaren av inspelningsutrustningen. |
| [Model](#Model) | Modellnamnet eller modellnumret på utrustningen. |
| [Orientation](#Orientation) | Bildens orientering betraktad i termer av rader och kolumner. |
| [SamplesPerPixel](#SamplesPerPixel) | Antalet komponenter per pixel. |
| [XResolution](#XResolution) | Antalet pixlar per upplösningsenhet i ImageWidth-riktningen. |
| [YResolution](#YResolution) | Antalet pixlar per upplösningsenhet i ImageLength-riktningen. |
| [PlanarConfiguration](#PlanarConfiguration) | Anger om pixelkomponenter registreras i ett chunky- eller planarformat. |
| [ResolutionUnit](#ResolutionUnit) | Enheten för att mäta XResolution och YResolution. |
| [TransferFunction](#TransferFunction) | En överföringsfunktion för bilden, beskriven i tabellformat. |
| [Software](#Software) | Denna tagg registrerar namn och version av mjukvaran eller firmware för kameran eller bildinmatningsenheten som användes för att skapa bilden. |
| [DateTime](#DateTime) | Datum och tid för bildskapandet. |
| [Artist](#Artist) | Denna tagg registrerar namnet på kamerans ägare, fotograf eller bildskapare. |
| [WhitePoint](#WhitePoint) | Kromaticiteten för bildens vitpunkt. |
| [PrimaryChromaticities](#PrimaryChromaticities) | Kromaticiteten för de tre primära färgerna i bilden. |
| [YCbCrCoefficients](#YCbCrCoefficients) | Matriskoefficienterna för transformation från RGB till YCbCr bilddata. |
| [YCbCrSubSampling](#YCbCrSubSampling) | Samplingsförhållandet för krominanskomponenter i förhållande till luminanskomponenten. |
| [YCbCrPositioning](#YCbCrPositioning) | Positionen för krominanskomponenter i förhållande till luminanskomponenten. |
| [ReferenceBlackWhite](#ReferenceBlackWhite) | Referensvärdet för svartpunkt och referensvärdet för vitpunkt. |
| [Copyright](#Copyright) | Upphovsrättsinformation. |
| [ExposureTime](#ExposureTime) | Exponeringstid, angiven i sekunder. |
| [FNumber](#FNumber) | F-talet. |
| [ExposureProgram](#ExposureProgram) | Klassen för programmet som kameran använder för att ställa in exponeringen när bilden tas. |
| [SpectralSensitivity](#SpectralSensitivity) | Anger den spektrala känsligheten för varje kanal i den använda kameran. |
| [PhotographicSensitivity](#PhotographicSensitivity) | Anger ISO-hastigheten och ISO-latituden för kameran eller inmatningsenheten enligt ISO 12232. |
| [OECF](#OECF) | Anger den optoelektriska konverteringsfunktionen (OECF) som specificeras i ISO 14524. |
| [ExifVersion](#ExifVersion) | Exif-versionen. |
| [DateTimeOriginal](#DateTimeOriginal) | Datum och tid då den ursprungliga bilddatan genererades. |
| [DateTimeDigitized](#DateTimeDigitized) | Datum och tid för digitalisering. |
| [ComponentsConfiguration](#ComponentsConfiguration) | Komponenternas konfiguration. |
| [CompressedBitsPerPixel](#CompressedBitsPerPixel) | Specifikt för komprimerad data; anger komprimerade bitar per pixel. |
| [ShutterSpeedValue](#ShutterSpeedValue) | Värdet för slutartiden. |
| [ApertureValue](#ApertureValue) | Värdet för objektivets bländare. |
| [BrightnessValue](#BrightnessValue) | Ljusstyrkevärdet. |
| [ExposureBiasValue](#ExposureBiasValue) | Exponeringskompensationsvärdet. |
| [MaxApertureValue](#MaxApertureValue) | Det maximala bländarvärdet. |
| [SubjectDistance](#SubjectDistance) | Avståndet till motivet, angivet i meter. |
| [MeteringMode](#MeteringMode) | Mätningsläget. |
| [LightSource](#LightSource) | Typ av ljuskälla. |
| [Flash](#Flash) | Anger blixtens status när bilden togs. |
| [FocalLength](#FocalLength) | Den faktiska brännvidden på linsen, i mm. |
| [SubjectArea](#SubjectArea) | Denna tagg anger platsen och området för huvudmotivet i hela scenen. |
| [MakerNote](#MakerNote) | En tagg för tillverkare av Exif‑skrivare att lagra önskad information. |
| [UserComment](#UserComment) | En tagg för Exif‑användare att skriva nyckelord eller kommentarer på bilden utöver de i ImageDescription, och utan teckenkodningsbegränsningarna i ImageDescription‑taggen. |
| [SubsecTime](#SubsecTime) | En tagg som används för att lagra bråkdelar av sekunder för DateTime‑taggen. |
| [SubsecTimeOriginal](#SubsecTimeOriginal) | En tagg som används för att lagra bråkdelar av sekunder för DateTimeOriginal‑taggen. |
| [SubsecTimeDigitized](#SubsecTimeDigitized) | En tagg som används för att lagra bråkdelar av sekunder för DateTimeDigitized‑taggen. |
| [FlashpixVersion](#FlashpixVersion) | Flashpix‑formatversionen som stöds av en FPXR‑fil. |
| [ColorSpace](#ColorSpace) | Färgrymdsinformations‑taggen (ColorSpace) registreras alltid som färgrymdsspecifikator. |
| [RelatedSoundFile](#RelatedSoundFile) | Den relaterade ljudfilen. |
| [FlashEnergy](#FlashEnergy) | Anger strobenenergin när bilden tas, mätt i Beam Candle Power Seconds (BCPS). |
| [SpatialFrequencyResponse](#SpatialFrequencyResponse) | Denna tagg registrerar kamerans eller inmatningsenhetens spatialfrekvenstabell och SFR‑värden i bildens bredd-, höjd- och diagonalriktning, enligt ISO 12233. |
| [FocalPlaneXResolution](#FocalPlaneXResolution) | Anger antalet pixlar i bildens bredd (X) per FocalPlaneResolutionUnit på kamerans fokalplan. |
| [FocalPlaneYResolution](#FocalPlaneYResolution) | Anger antalet pixlar i bildens höjd (Y) per FocalPlaneResolutionUnit på kamerans fokalplan. |
| [FocalPlaneResolutionUnit](#FocalPlaneResolutionUnit) | Anger enheten för mätning av FocalPlaneXResolution och FocalPlaneYResolution. |
| [SubjectLocation](#SubjectLocation) | Anger huvudmotivet placering i scenen. |
| [ExposureIndex](#ExposureIndex) | Anger exponeringsindexet som valdes på kameran eller inmatningsenheten när bilden togs. |
| [SensingMethod](#SensingMethod) | Anger bildsensortypen på kameran eller inmatningsenheten. |
| [FileSource](#FileSource) | Filkällan. |
| [SceneType](#SceneType) | Anger scenens typ. |
| [CFAPattern](#CFAPattern) | Anger den geometriska mönstret för färgfilterarrayen (CFA) på bildsensorn när en enkelskikts färgområdessensor används. |
| [CustomRendered](#CustomRendered) | Denna tagg anger användning av speciell bearbetning av bilddata, såsom rendering anpassad för utdata. |
| [ExposureMode](#ExposureMode) | Denna tagg anger exponeringsläget som sattes när bilden togs. |
| [WhiteBalance](#WhiteBalance) | Denna tagg anger vitbalansläget som sattes när bilden togs. |
| [DigitalZoomRatio](#DigitalZoomRatio) | Denna tagg anger det digitala zoomförhållandet när bilden togs. |
| [FocalLengthIn35MmFilm](#FocalLengthIn35MmFilm) | Denna tagg anger den ekvivalenta brännvidden förutsatt en 35 mm filmkamera, i mm. |
| [SceneCaptureType](#SceneCaptureType) | Denna tagg anger vilken typ av scen som fotograferades. |
| [GainControl](#GainControl) | Denna tagg anger graden av total bildförstärkningsjustering. |
| [Contrast](#Contrast) | Denna tagg anger riktningen för kontrastbehandling som kameran använde när bilden togs. |
| [Saturation](#Saturation) | Denna tagg anger riktningen för mättnadsbehandling som kameran använde när bilden togs. |
| [Sharpness](#Sharpness) | Denna tagg anger riktningen för skärpebehandling som kameran använde när bilden togs |
| [DeviceSettingDescription](#DeviceSettingDescription) | Denna tagg anger information om bildtagningsförhållandena för en viss kameramodell. |
| [SubjectDistanceRange](#SubjectDistanceRange) | Denna tagg anger avståndet till motivet. |
| [ImageUniqueID](#ImageUniqueID) | Bildens unika ID. |
| [GPSVersionID](#GPSVersionID) | Anger versionen av GPSInfoIFD. |
| [GPSLatitudeRef](#GPSLatitudeRef) | Anger om latituden är nordlig eller sydlig latitud. |
| [GPSLatitude](#GPSLatitude) | Anger latituden. |
| [GPSLongitudeRef](#GPSLongitudeRef) | Anger om longituden är östlig eller västlig longitud. |
| [GPSLongitude](#GPSLongitude) | Anger longituden. |
| [GPSAltitudeRef](#GPSAltitudeRef) | Anger den höjd som används som referenshöjd. |
| [GPSAltitude](#GPSAltitude) | Anger höjden baserat på referensen i GPSAltitudeRef. |
| [GPSTimestamp](#GPSTimestamp) | Anger tiden som UTC (Coordinated Universal Time). |
| [GPSSatellites](#GPSSatellites) | Anger GPS-satelliterna som används för mätningarna. |
| [GPSStatus](#GPSStatus) | Anger GPS-mottagarens status när bilden spelas in. |
| [GPSMeasureMode](#GPSMeasureMode) | Anger GPS-mätningsläget. |
| [GPSDOP](#GPSDOP) | Anger GPS DOP (data degree of precision). |
| [GPSSpeedRef](#GPSSpeedRef) | Anger enheten som används för att uttrycka GPS-mottagarens rörelsehastighet. |
| [GPSSpeed](#GPSSpeed) | Anger hastigheten för GPS-mottagarens rörelse. |
| [GPSTrackRef](#GPSTrackRef) | Anger referensen för att ange riktningen för GPS-mottagarens rörelse. |
| [GPSTrack](#GPSTrack) | Anger riktningen för GPS-mottagarens rörelse. |
| [GPSImgDirectionRef](#GPSImgDirectionRef) | Anger referensen för att ange bildens riktning när den tas. |
| [GPSImgDirection](#GPSImgDirection) | Anger bildens riktning när den togs. |
| [GPSMapDatum](#GPSMapDatum) | Anger de geodetiska undersökningsdata som GPS-mottagaren använder. |
| [GPSDestLatitudeRef](#GPSDestLatitudeRef) | Anger om latituden för destinationspunkten är nordlig eller sydlig latitud. |
| [GPSDestLatitude](#GPSDestLatitude) | Anger latituden för destinationspunkten. |
| [GPSDestLongitudeRef](#GPSDestLongitudeRef) | Anger om longituden för destinationspunkten är östlig eller västlig longitud. |
| [GPSDestLongitude](#GPSDestLongitude) | Anger longituden för destinationspunkten. |
| [GPSDestBearingRef](#GPSDestBearingRef) | Anger referensen som används för att ange kursen till destinationspunkten. |
| [GPSDestBearing](#GPSDestBearing) | Anger kursen till destinationspunkten. |
| [GPSDestDistanceRef](#GPSDestDistanceRef) | Anger enheten som används för att uttrycka avståndet till destinationspunkten. |
| [GPSDestDistance](#GPSDestDistance) | Anger avståndet till destinationspunkten. |
| [GPSProcessingMethod](#GPSProcessingMethod) | En teckensträng som registrerar namnet på metoden som används för positionsbestämning. |
| [GPSAreaInformation](#GPSAreaInformation) | En teckensträng som registrerar namnet på GPS-området. |
| [GPSDateStamp](#GPSDateStamp) | En teckensträng som registrerar datum- och tidsinformation i förhållande till UTC (Coordinated Universal Time). |
| [GPSDifferential](#GPSDifferential) | Anger om differentialkorrigering tillämpas på GPS-mottagaren. |
| [StripOffsets](#StripOffsets) | För varje remsa, byteoffseten för den remsan. |
| [JPEGInterchangeFormat](#JPEGInterchangeFormat) | Offseten till startbyten (SOI) för JPEG-komprimerad miniatyrdata. |
| [JPEGInterchangeFormatLength](#JPEGInterchangeFormatLength) | Antalet byte i JPEG-komprimerad miniatyrdata. |
| [ExifIfdPointer](#ExifIfdPointer) | En pekare till Exif IFD. |
| [GPSIfdPointer](#GPSIfdPointer) | GPS IFD-pekaren. |
| [RowsPerStrip](#RowsPerStrip) | Antalet rader per remsa. |
| [StripByteCounts](#StripByteCounts) | Det totala antalet byte i varje remsa. |
| [PixelXDimension](#PixelXDimension) | Information specifik för komprimerad data. |
| [PixelYDimension](#PixelYDimension) | Information specifik för komprimerad data. |
| [Gamma](#Gamma) | Gammavärde |
| [SensitivityType](#SensitivityType) | Typ av fotografisk känslighet |
| [StandardOutputSensitivity](#StandardOutputSensitivity) | Anger standardutgångskänsligheten för kameran |
| [RecommendedExposureIndex](#RecommendedExposureIndex) | Anger rekommenderat exponeringsindex |
| [ISOSpeed](#ISOSpeed) | Information om ISO-hastighetsvärde enligt ISO 12232 |
| [ISOSpeedLatitudeYYY](#ISOSpeedLatitudeYYY) | Denna tagg anger ISO-hastighetslatitud yyy-värde enligt ISO 12232 |
| [ISOSpeedLatitudeZZZ](#ISOSpeedLatitudeZZZ) | Denna tagg anger ISO-hastighetslatitud zzz-värde enligt ISO 12232 |
| [CameraOwnerName](#CameraOwnerName) | Innehåller kamerans ägarnamn |
| [BodySerialNumber](#BodySerialNumber) | Innehåller kamerahusets serienummer |
| [LensMake](#LensMake) | Denna tagg registrerar linsens tillverkare |
| [LensModel](#LensModel) | Denna tagg registrerar lins\`s modellnamn och modellnummer |
| [LensSerialNumber](#LensSerialNumber) | Denna tagg registrerar serienumret för utbytbar lins |
| [LensSpecification](#LensSpecification) | Denna tagg noterar minsta brännvidd, största brännvidd, minsta F-nummer vid minsta brännvidd och minsta F-nummer vid största brännvidd |
### ImageWidth {#ImageWidth}
```
public static final int ImageWidth
```


Antalet kolumner i bilddata, lika med antalet pixlar per rad.

### ImageLength {#ImageLength}
```
public static final int ImageLength
```


Antalet rader i bilddata.

### BitsPerSample {#BitsPerSample}
```
public static final int BitsPerSample
```


Antalet bitar per bildkomponent. I denna standard är varje komponent i bilden 8 bitar, så värdet för denna tagg är 8.

### Compression {#Compression}
```
public static final int Compression
```


Komprimeringsschemat som används för bilddata. När en primär bild är JPEG-komprimerad är denna beteckning onödig och utelämnas.

### PhotometricInterpretation {#PhotometricInterpretation}
```
public static final int PhotometricInterpretation
```


Pixelns sammansättning.

### ImageDescription {#ImageDescription}
```
public static final int ImageDescription
```


En teckensträng som ger bildens titel. Det kan vara en kommentar såsom "1988 company picnic" eller liknande.

### Make {#Make}
```
public static final int Make
```


Tillverkaren av inspelningsutrustningen. Detta är tillverkaren av DSC, skanner, videodigitaliserare eller annan utrustning som skapade bilden. När fältet lämnas tomt behandlas det som okänt.

### Model {#Model}
```
public static final int Model
```


Modellnamnet eller modellnumret på utrustningen. Detta är modellnamnet eller -numret på DSC, skanner, videodigitaliserare eller annan utrustning som skapade bilden. När fältet lämnas tomt behandlas det som okänt.

### Orientation {#Orientation}
```
public static final int Orientation
```


Bildens orientering betraktad i termer av rader och kolumner.

### SamplesPerPixel {#SamplesPerPixel}
```
public static final int SamplesPerPixel
```


Antalet komponenter per pixel. Eftersom denna standard gäller RGB- och YCbCr-bilder är värdet för denna tagg 3.

### XResolution {#XResolution}
```
public static final int XResolution
```


Antalet pixlar per ResolutionUnit i ImageWidth-riktningen. När bildens upplösning är okänd anges 72 [dpi].

### YResolution {#YResolution}
```
public static final int YResolution
```


Antalet pixlar per ResolutionUnit i ImageLength-riktningen. Samma värde som XResolution anges.

### PlanarConfiguration {#PlanarConfiguration}
```
public static final int PlanarConfiguration
```


Anger om pixelkomponenter registreras i chunky- eller planarformat. Om detta fält saknas antas TIFF-standardvärdet 1 (chunky).

### ResolutionUnit {#ResolutionUnit}
```
public static final int ResolutionUnit
```


Enheten för att mäta XResolution och YResolution. Samma enhet används för både XResolution och YResolution. Om bildens upplösning är okänd anges 2 (tum).

### TransferFunction {#TransferFunction}
```
public static final int TransferFunction
```


En överföringsfunktion för bilden, beskriven i tabellformat. Normalt är denna tagg onödig, eftersom färgrymden specificeras i färgrymdsinformationen i ColorSpace-taggen.

### Software {#Software}
```
public static final int Software
```


Denna tagg registrerar namn och version på programvaran eller firmware för kameran eller bildinmatningsenheten som användes för att skapa bilden. Det detaljerade formatet är inte specificerat, men det rekommenderas att följa exemplet nedan. När fältet lämnas tomt behandlas det som okänt.

### DateTime {#DateTime}
```
public static final int DateTime
```


Datum och tid för bildskapande. I Exif-standarden är det datum och tid då filen ändrades.

### Artist {#Artist}
```
public static final int Artist
```


Denna tagg registrerar namn på kamerans ägare, fotograf eller bildskapare. Det detaljerade formatet är inte specificerat, men det rekommenderas att informationen skrivas enligt exemplet nedan för enkel interoperabilitet. När fältet lämnas tomt behandlas det som okänt. (Ex. "Camera owner, John Smith; Photographer, Michael Brown; Image creator, Ken James")

### WhitePoint {#WhitePoint}
```
public static final int WhitePoint
```


Kromaticiteten för bildens vitpunkt. Normalt är denna tagg inte nödvändig, eftersom färgrymden specificeras i färgrymdsinformationen ColorSpace-taggen.

### PrimaryChromaticities {#PrimaryChromaticities}
```
public static final int PrimaryChromaticities
```


Kromaticiteten för bildens tre primära färger. Normalt är denna tagg inte nödvändig, eftersom färgrymden specificeras i färgrymdsinformationen ColorSpace-taggen.

### YCbCrCoefficients {#YCbCrCoefficients}
```
public static final int YCbCrCoefficients
```


Matriskoefficienterna för transformation från RGB till YCbCr bilddata.

### YCbCrSubSampling {#YCbCrSubSampling}
```
public static final int YCbCrSubSampling
```


Samplingsförhållandet för krominanskomponenter i förhållande till luminanskomponenten.

### YCbCrPositioning {#YCbCrPositioning}
```
public static final int YCbCrPositioning
```


Positionen för krominanskomponenterna i förhållande till luminanskomponenten. Detta fält är endast avsett för JPEG-komprimerad data eller okomprimerad YCbCr-data. TIFF‑standardvärdet är 1 (centrerat); men när Y:Cb:Cr = 4:2:2 rekommenderas i denna standard att 2 (sido‑placerad) används för att lagra data, för att förbättra bildkvaliteten när den visas på TV‑system. När detta fält saknas ska läsaren anta TIFF‑standardvärdet. Vid Y:Cb:Cr = 4:2:0 rekommenderas TIFF‑standardvärdet (centrerat). Om läsaren inte har möjlighet att stödja båda typerna av YCbCrPositioning ska den följa TIFF‑standardvärdet oavsett värdet i detta fält. Det är önskvärt att läsare ska kunna stödja både centrerad och sido‑placerad positionering.

### ReferenceBlackWhite {#ReferenceBlackWhite}
```
public static final int ReferenceBlackWhite
```


Referensvärdet för svartpunkt och referensvärdet för vitpunkt. Inga standardvärden anges i TIFF, men värdena nedan ges som standardvärden här. Färgrymden deklareras i en färgrymdsinformations‑tagg, där standardvärdet är det som ger de optimala bildegenskaperna för interoperabilitet under dessa förhållanden.

### Copyright {#Copyright}
```
public static final int Copyright
```


Upphovsrättsinformation. I denna standard används taggen för att ange både fotografens och redaktörens upphovsrätt. Det är upphovsrättsmeddelandet från den person eller organisation som gör anspråk på bilden. Upphovsrättsmeddelandet för interoperabilitet inklusive datum och rättigheter ska skrivas i detta fält; t.ex. "Copyright, John Smith, 19xx. All rights reserved." I denna standard registreras både fotografens och redaktörens upphovsrätt, där varje registreras i en separat del av meddelandet. När det finns en tydlig åtskillnad mellan fotografens och redaktörens upphovsrätt ska de skrivas i ordning fotograf följt av redaktör, separerade av NULL (i detta fall eftersom meddelandet också avslutas med en NULL, finns två NULL‑koder). När endast fotografens upphovsrätt anges, avslutas den med en NULL‑kod. När endast redaktörens upphovsrätt anges, består fotografens del av ett mellanslag följt av en avslutande NULL‑kod, sedan anges redaktörens upphovsrätt. När fältet lämnas tomt behandlas det som okänt.

### ExposureTime {#ExposureTime}
```
public static final int ExposureTime
```


Exponeringstid, angiven i sekunder.

### FNumber {#FNumber}
```
public static final int FNumber
```


F-talet.

### ExposureProgram {#ExposureProgram}
```
public static final int ExposureProgram
```


Klassen för programmet som kameran använder för att ställa in exponeringen när bilden tas.

### SpectralSensitivity {#SpectralSensitivity}
```
public static final int SpectralSensitivity
```


Anger den spektrala känsligheten för varje kanal i den använda kameran.

### PhotographicSensitivity {#PhotographicSensitivity}
```
public static final int PhotographicSensitivity
```


Anger ISO-hastigheten och ISO-latituden för kameran eller inmatningsenheten enligt ISO 12232.

### OECF {#OECF}
```
public static final int OECF
```


Anger den optoelektriska konverteringsfunktionen (OECF) som specificeras i ISO 14524.

### ExifVersion {#ExifVersion}
```
public static final int ExifVersion
```


Exif-versionen.

### DateTimeOriginal {#DateTimeOriginal}
```
public static final int DateTimeOriginal
```


Datum och tid då den ursprungliga bilddatan genererades.

### DateTimeDigitized {#DateTimeDigitized}
```
public static final int DateTimeDigitized
```


Datum och tid för digitalisering.

### ComponentsConfiguration {#ComponentsConfiguration}
```
public static final int ComponentsConfiguration
```


Komponenternas konfiguration.

### CompressedBitsPerPixel {#CompressedBitsPerPixel}
```
public static final int CompressedBitsPerPixel
```


Specifikt för komprimerad data; anger komprimerade bitar per pixel.

### ShutterSpeedValue {#ShutterSpeedValue}
```
public static final int ShutterSpeedValue
```


Värdet för slutartiden.

### ApertureValue {#ApertureValue}
```
public static final int ApertureValue
```


Värdet för objektivets bländare.

### BrightnessValue {#BrightnessValue}
```
public static final int BrightnessValue
```


Ljusstyrkevärdet.

### ExposureBiasValue {#ExposureBiasValue}
```
public static final int ExposureBiasValue
```


Exponeringskompensationsvärdet.

### MaxApertureValue {#MaxApertureValue}
```
public static final int MaxApertureValue
```


Det maximala bländarvärdet.

### SubjectDistance {#SubjectDistance}
```
public static final int SubjectDistance
```


Avståndet till motivet, angivet i meter.

### MeteringMode {#MeteringMode}
```
public static final int MeteringMode
```


Mätningsläget.

### LightSource {#LightSource}
```
public static final int LightSource
```


Typ av ljuskälla.

### Flash {#Flash}
```
public static final int Flash
```


Anger blixtens status när bilden togs.

### FocalLength {#FocalLength}
```
public static final int FocalLength
```


Den faktiska brännvidden på linsen, i mm.

### SubjectArea {#SubjectArea}
```
public static final int SubjectArea
```


Denna tagg anger platsen och området för huvudmotivet i hela scenen.

### MakerNote {#MakerNote}
```
public static final int MakerNote
```


En tagg för tillverkare av Exif‑skrivare att lagra önskad information. Innehållet bestäms av tillverkaren, men denna tagg bör inte användas för annat än sitt avsedda ändamål.

### UserComment {#UserComment}
```
public static final int UserComment
```


En tagg för Exif‑användare att skriva nyckelord eller kommentarer på bilden utöver de i ImageDescription, och utan teckenkodningsbegränsningarna i ImageDescription‑taggen.

### SubsecTime {#SubsecTime}
```
public static final int SubsecTime
```


En tagg som används för att lagra bråkdelar av sekunder för DateTime‑taggen.

### SubsecTimeOriginal {#SubsecTimeOriginal}
```
public static final int SubsecTimeOriginal
```


En tagg som används för att lagra bråkdelar av sekunder för DateTimeOriginal‑taggen.

### SubsecTimeDigitized {#SubsecTimeDigitized}
```
public static final int SubsecTimeDigitized
```


En tagg som används för att lagra bråkdelar av sekunder för DateTimeDigitized‑taggen.

### FlashpixVersion {#FlashpixVersion}
```
public static final int FlashpixVersion
```


Flashpix‑formatversionen som stöds av en FPXR‑fil.

### ColorSpace {#ColorSpace}
```
public static final int ColorSpace
```


Färgrymdsinformations‑taggen (ColorSpace) registreras alltid som färgrymdsspecifikator.

### RelatedSoundFile {#RelatedSoundFile}
```
public static final int RelatedSoundFile
```


Den relaterade ljudfilen.

### FlashEnergy {#FlashEnergy}
```
public static final int FlashEnergy
```


Anger strobenenergin när bilden tas, mätt i Beam Candle Power Seconds (BCPS).

### SpatialFrequencyResponse {#SpatialFrequencyResponse}
```
public static final int SpatialFrequencyResponse
```


Denna tagg registrerar kamerans eller inmatningsenhetens spatialfrekvenstabell och SFR‑värden i bildens bredd-, höjd- och diagonalriktning, enligt ISO 12233.

### FocalPlaneXResolution {#FocalPlaneXResolution}
```
public static final int FocalPlaneXResolution
```


Anger antalet pixlar i bildens bredd (X) per FocalPlaneResolutionUnit på kamerans fokalplan.

### FocalPlaneYResolution {#FocalPlaneYResolution}
```
public static final int FocalPlaneYResolution
```


Anger antalet pixlar i bildens höjd (Y) per FocalPlaneResolutionUnit på kamerans fokalplan.

### FocalPlaneResolutionUnit {#FocalPlaneResolutionUnit}
```
public static final int FocalPlaneResolutionUnit
```


Anger enheten för mätning av FocalPlaneXResolution och FocalPlaneYResolution. Detta värde är detsamma som ResolutionUnit.

### SubjectLocation {#SubjectLocation}
```
public static final int SubjectLocation
```


Anger huvudobjektets position i scenen. Värdet för denna tagg representerar pixeln i centrum av huvudobjektet i förhållande till vänster kant, före rotationsbehandling enligt Rotation‑taggen.

### ExposureIndex {#ExposureIndex}
```
public static final int ExposureIndex
```


Anger exponeringsindexet som valdes på kameran eller inmatningsenheten när bilden togs.

### SensingMethod {#SensingMethod}
```
public static final int SensingMethod
```


Anger bildsensortypen på kameran eller inmatningsenheten.

### FileSource {#FileSource}
```
public static final int FileSource
```


Filkällan.

### SceneType {#SceneType}
```
public static final int SceneType
```


Anger scenens typ. Om en DSC har spelat in bilden ska detta taggvärde alltid vara 1, vilket indikerar att bilden fotograferades direkt.

### CFAPattern {#CFAPattern}
```
public static final int CFAPattern
```


Anger färgfilterarrayens (CFA) geometriska mönster för bildsensorn när en enkelskikts färgområdessensor används. Det gäller inte alla sensormetoder.

### CustomRendered {#CustomRendered}
```
public static final int CustomRendered
```


Denna tagg indikerar användning av specialbehandling på bilddata, såsom rendering anpassad för utdata. När specialbehandling utförs förväntas läsaren inaktivera eller minimera ytterligare bearbetning.

### ExposureMode {#ExposureMode}
```
public static final int ExposureMode
```


Denna tagg indikerar det exponeringsläge som var inställt när bilden togs. I auto‑bracketing‑läge tar kameran en serie bildrutor av samma scen med olika exponeringar.

### WhiteBalance {#WhiteBalance}
```
public static final int WhiteBalance
```


Denna tagg anger vitbalansläget som sattes när bilden togs.

### DigitalZoomRatio {#DigitalZoomRatio}
```
public static final int DigitalZoomRatio
```


Denna tagg indikerar den digitala zoomfaktorn när bilden togs. Om täljaren i det registrerade värdet är 0 betyder det att digital zoom inte användes.

### FocalLengthIn35MmFilm {#FocalLengthIn35MmFilm}
```
public static final int FocalLengthIn35MmFilm
```


Denna tagg indikerar den ekvivalenta brännvidden för en 35 mm filmkamera, i mm. Ett värde på 0 betyder att brännvidden är okänd. Observera att denna tagg skiljer sig från FocalLength‑taggen.

### SceneCaptureType {#SceneCaptureType}
```
public static final int SceneCaptureType
```


Denna tagg indikerar vilken typ av scen som fotograferades. Den kan också användas för att registrera vilket läge bilden togs i.

### GainControl {#GainControl}
```
public static final int GainControl
```


Denna tagg anger graden av total bildförstärkningsjustering.

### Contrast {#Contrast}
```
public static final int Contrast
```


Denna tagg anger riktningen för kontrastbehandling som kameran använde när bilden togs.

### Saturation {#Saturation}
```
public static final int Saturation
```


Denna tagg anger riktningen för mättnadsbehandling som kameran använde när bilden togs.

### Sharpness {#Sharpness}
```
public static final int Sharpness
```


Denna tagg anger riktningen för skärpebehandling som kameran använde när bilden togs

### DeviceSettingDescription {#DeviceSettingDescription}
```
public static final int DeviceSettingDescription
```


Denna tagg anger information om fotograferingsförhållandena för en specifik kameramodell. Taggen används endast för att indikera fotograferingsförhållandena i läsaren.

### SubjectDistanceRange {#SubjectDistanceRange}
```
public static final int SubjectDistanceRange
```


Denna tagg anger avståndet till motivet.

### ImageUniqueID {#ImageUniqueID}
```
public static final int ImageUniqueID
```


Bildens unika ID.

### GPSVersionID {#GPSVersionID}
```
public static final int GPSVersionID
```


Anger versionen av GPSInfoIFD.

### GPSLatitudeRef {#GPSLatitudeRef}
```
public static final int GPSLatitudeRef
```


Anger om latituden är nordlig eller sydlig latitud.

### GPSLatitude {#GPSLatitude}
```
public static final int GPSLatitude
```


Anger latituden. Latituden uttrycks som tre RATIONAL‑värden som ger grader, minuter och sekunder, i den ordningen. Om latituden uttrycks i grader, minuter och sekunder är ett typiskt format dd/1,mm/1,ss/1. När grader och minuter används och exempelvis bråkdelar av minuter anges med två decimaler, blir formatet dd/1,mmmm/100,0/1.

### GPSLongitudeRef {#GPSLongitudeRef}
```
public static final int GPSLongitudeRef
```


Anger om longituden är östlig eller västlig longitud.

### GPSLongitude {#GPSLongitude}
```
public static final int GPSLongitude
```


Anger longituden. Longituden uttrycks som tre RATIONAL‑värden som ger grader, minuter och sekunder, i den ordningen. Om longituden uttrycks i grader, minuter och sekunder är ett typiskt format ddd/1,mm/1,ss/1. När grader och minuter används och exempelvis bråkdelar av minuter anges med två decimaler, blir formatet ddd/1,mmmm/100,0/1.

### GPSAltitudeRef {#GPSAltitudeRef}
```
public static final int GPSAltitudeRef
```


Anger den referenshöjd som används för höjden. Om referensen är havsnivå och höjden är över havsnivå anges 0. Om höjden är under havsnivå anges 1 och höjden anges som ett absolut värde i GPSAltitude‑taggen.

### GPSAltitude {#GPSAltitude}
```
public static final int GPSAltitude
```


Anger höjden baserat på referensen i GPSAltitudeRef. Höjden uttrycks som ett RATIONAL‑värde. Referensenheten är meter.

### GPSTimestamp {#GPSTimestamp}
```
public static final int GPSTimestamp
```


Anger tiden som UTC (Coordinated Universal Time). TimeStamp uttrycks som tre RATIONAL‑värden som ger timme, minut och sekund.

### GPSSatellites {#GPSSatellites}
```
public static final int GPSSatellites
```


Anger de GPS‑satelliter som används för mätningarna. Denna tagg kan användas för att beskriva antalet satelliter, deras ID‑nummer, höjdvinkel, azimut, SNR och annan information i ASCII‑notation. Formatet är inte specificerat. Om GPS‑mottagaren inte kan göra mätningar ska taggens värde sättas till NULL.

### GPSStatus {#GPSStatus}
```
public static final int GPSStatus
```


Anger GPS-mottagarens status när bilden spelas in.

### GPSMeasureMode {#GPSMeasureMode}
```
public static final int GPSMeasureMode
```


Anger GPS‑mätningsläget. – 2‑ eller 3‑dimensionellt.

### GPSDOP {#GPSDOP}
```
public static final int GPSDOP
```


Anger GPS‑DOP (data degree of precision). Ett HDOP‑värde skrivs vid tvådimensionell mätning, och PDOP vid tredimensionell mätning.

### GPSSpeedRef {#GPSSpeedRef}
```
public static final int GPSSpeedRef
```


Anger enheten som används för att uttrycka GPS‑mottagarens rörelsehastighet. 'K', 'M' och 'N' står för kilometer per timme, miles per timme och knop.

### GPSSpeed {#GPSSpeed}
```
public static final int GPSSpeed
```


Anger hastigheten för GPS-mottagarens rörelse.

### GPSTrackRef {#GPSTrackRef}
```
public static final int GPSTrackRef
```


Anger referensen för att ange riktningen för GPS-mottagarens rörelse. 'T' betecknar sann riktning och 'M' är magnetisk riktning.

### GPSTrack {#GPSTrack}
```
public static final int GPSTrack
```


Anger riktningen för GPS-mottagarens rörelse. Värdeintervallet är från 0.00 till 359.99.

### GPSImgDirectionRef {#GPSImgDirectionRef}
```
public static final int GPSImgDirectionRef
```


Anger referensen för att ange bildens riktning när den tas. 'T' betecknar sann riktning och 'M' är magnetisk riktning.

### GPSImgDirection {#GPSImgDirection}
```
public static final int GPSImgDirection
```


Anger bildens riktning när den togs. Värdeintervallet är från 0.00 till 359.99.

### GPSMapDatum {#GPSMapDatum}
```
public static final int GPSMapDatum
```


Anger de geodetiska undersökningsdata som GPS-mottagaren använder.

### GPSDestLatitudeRef {#GPSDestLatitudeRef}
```
public static final int GPSDestLatitudeRef
```


Anger om latituden för destinationspunkten är norra eller södra latitud. ASCII‑värdet 'N' indikerar norra latitud, och 'S' är södra latitud.

### GPSDestLatitude {#GPSDestLatitude}
```
public static final int GPSDestLatitude
```


Anger latituden för destinationspunkten. Latituden uttrycks som tre RATIONAL‑värden som ger grader, minuter och sekunder, i den ordningen. Om latituden uttrycks i grader, minuter och sekunder är ett typiskt format dd/1,mm/1,ss/1. När grader och minuter används och exempelvis minuterna anges med två decimaler blir formatet dd/1,mmmm/100,0/1.

### GPSDestLongitudeRef {#GPSDestLongitudeRef}
```
public static final int GPSDestLongitudeRef
```


Anger om longituden för destinationspunkten är östlig eller västlig longitud. ASCII‑värdet 'E' indikerar östlig longitud, och 'W' är västlig longitud.

### GPSDestLongitude {#GPSDestLongitude}
```
public static final int GPSDestLongitude
```


Anger longituden för destinationspunkten. Longituden uttrycks som tre RATIONAL‑värden som ger grader, minuter och sekunder, i den ordningen. Om longituden uttrycks i grader, minuter och sekunder är ett typiskt format ddd/1,mm/1,ss/1. När grader och minuter används och exempelvis minuterna anges med två decimaler blir formatet ddd/1,mmmm/100,0/1.

### GPSDestBearingRef {#GPSDestBearingRef}
```
public static final int GPSDestBearingRef
```


Anger referensen som används för att ange kursen till destinationspunkten. 'T' betecknar sann riktning och 'M' är magnetisk riktning.

### GPSDestBearing {#GPSDestBearing}
```
public static final int GPSDestBearing
```


Anger kursen till destinationspunkten. Värdeintervallet är från 0.00 till 359.99.

### GPSDestDistanceRef {#GPSDestDistanceRef}
```
public static final int GPSDestDistanceRef
```


Anger enheten som används för att uttrycka avståndet till destinationspunkten. 'K', 'M' och 'N' representerar kilometer, miles och knop.

### GPSDestDistance {#GPSDestDistance}
```
public static final int GPSDestDistance
```


Anger avståndet till destinationspunkten.

### GPSProcessingMethod {#GPSProcessingMethod}
```
public static final int GPSProcessingMethod
```


En teckensträng som registrerar namnet på den metod som används för positionsbestämning. Den första byten anger den teckenkod som används, och därefter följer metodens namn.

### GPSAreaInformation {#GPSAreaInformation}
```
public static final int GPSAreaInformation
```


En teckensträng som registrerar namnet på GPS‑området. Den första byten anger den teckenkod som används, och därefter följer GPS‑områdets namn.

### GPSDateStamp {#GPSDateStamp}
```
public static final int GPSDateStamp
```


En teckensträng som registrerar datum- och tidsinformation i förhållande till UTC (Coordinated Universal Time). Formatet är ÅÅÅÅ:MM:DD.

### GPSDifferential {#GPSDifferential}
```
public static final int GPSDifferential
```


Anger om differentialkorrigering tillämpas på GPS-mottagaren.

### StripOffsets {#StripOffsets}
```
public static final int StripOffsets
```


För varje remsa, byte‑offseten för den remsan. Det rekommenderas att detta väljs så att antalet byte per remsa inte överstiger 64 KB. Aux‑tagg.

### JPEGInterchangeFormat {#JPEGInterchangeFormat}
```
public static final int JPEGInterchangeFormat
```


Offseten till startbyten (SOI) för JPEG‑komprimerad miniatyrbildsdata. Detta används inte för primär bilds JPEG‑data.

### JPEGInterchangeFormatLength {#JPEGInterchangeFormatLength}
```
public static final int JPEGInterchangeFormatLength
```


Antalet byte för JPEG‑komprimerad miniatyrbildsdata. Detta används inte för primär bilds JPEG‑data. JPEG‑miniatyrbilder delas inte utan registreras som en kontinuerlig JPEG‑bitström från SOI till EOI. Appn‑ och COM‑markörer bör inte registreras. Komprimerade miniatyrbilder får inte registreras i mer än 64 KB, inklusive all annan data som ska registreras i APP1.

### ExifIfdPointer {#ExifIfdPointer}
```
public static final int ExifIfdPointer
```


En pekare till Exif‑IFD. Interoperabilitet, Exif‑IFD har samma struktur som den IFD som specificeras i TIFF. Vanligtvis innehåller den dock inte bilddata som i TIFF‑fallet.

### GPSIfdPointer {#GPSIfdPointer}
```
public static final int GPSIfdPointer
```


GPS IFD-pekaren.

### RowsPerStrip {#RowsPerStrip}
```
public static final int RowsPerStrip
```


Antalet rader per remsa. Detta är antalet rader i bilden för en remsa när en bild delas upp i remsor.

### StripByteCounts {#StripByteCounts}
```
public static final int StripByteCounts
```


Det totala antalet byte i varje remsa.

### PixelXDimension {#PixelXDimension}
```
public static final int PixelXDimension
```


Information specifik för komprimerad data. När en komprimerad fil registreras ska den giltiga bredden på den meningsfulla bilden registreras i denna tagg, oavsett om det finns utfyllnadsdata eller en omstartsmarkör.

### PixelYDimension {#PixelYDimension}
```
public static final int PixelYDimension
```


Information specifik för komprimerad data. När en komprimerad fil registreras ska den giltiga höjden på den meningsfulla bilden registreras i denna tagg.

### Gamma {#Gamma}
```
public static final int Gamma
```


Gammavärde

### SensitivityType {#SensitivityType}
```
public static final int SensitivityType
```


Typ av fotografisk känslighet

### StandardOutputSensitivity {#StandardOutputSensitivity}
```
public static final int StandardOutputSensitivity
```


Anger standardutgångskänsligheten för kameran

### RecommendedExposureIndex {#RecommendedExposureIndex}
```
public static final int RecommendedExposureIndex
```


Anger rekommenderat exponeringsindex

### ISOSpeed {#ISOSpeed}
```
public static final int ISOSpeed
```


Information om ISO-hastighetsvärde enligt ISO 12232

### ISOSpeedLatitudeYYY {#ISOSpeedLatitudeYYY}
```
public static final int ISOSpeedLatitudeYYY
```


Denna tagg anger ISO-hastighetslatitud yyy-värde enligt ISO 12232

### ISOSpeedLatitudeZZZ {#ISOSpeedLatitudeZZZ}
```
public static final int ISOSpeedLatitudeZZZ
```


Denna tagg anger ISO-hastighetslatitud zzz-värde enligt ISO 12232

### CameraOwnerName {#CameraOwnerName}
```
public static final int CameraOwnerName
```


Innehåller kamerans ägarnamn

### BodySerialNumber {#BodySerialNumber}
```
public static final int BodySerialNumber
```


Innehåller kamerahusets serienummer

### LensMake {#LensMake}
```
public static final int LensMake
```


Denna tagg registrerar linsens tillverkare

### LensModel {#LensModel}
```
public static final int LensModel
```


Denna tagg registrerar lins\`s modellnamn och modellnummer

### LensSerialNumber {#LensSerialNumber}
```
public static final int LensSerialNumber
```


Denna tagg registrerar serienumret för utbytbar lins

### LensSpecification {#LensSpecification}
```
public static final int LensSpecification
```


Denna tagg noterar minsta brännvidd, största brännvidd, minsta F-nummer vid minsta brännvidd och minsta F-nummer vid största brännvidd

