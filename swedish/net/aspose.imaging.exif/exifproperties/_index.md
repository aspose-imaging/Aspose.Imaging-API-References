---
title: ExifProperties
second_title: Aspose.Imaging för .NET API-referens
description: Exif-taggar lista
type: docs
weight: 1080
url: /sv/net/aspose.imaging.exif/exifproperties/
---
## ExifProperties enumeration

Exif-taggar lista

```csharp
public enum ExifProperties : ushort
```

### Värderingar

| namn | Värde | Beskrivning |
| --- | --- | --- |
| ImageWidth | `256` | Antalet kolumner med bilddata, lika med antalet pixlar per rad. |
| ImageLength | `257` | Antalet rader med bilddata. |
| BitsPerSample | `258` | Antalet bitar per bildkomponent. I denna standard är varje komponent i bilden 8 bitar, så värdet för denna tagg är 8. |
| Compression | `259` | Kompressionsschemat som används för bilddata. När en primär bild är JPEG-komprimerad är denna beteckning inte nödvändig och den utelämnas. |
| PhotometricInterpretation | `262` | Pixelkompositionen. |
| ImageDescription | `270` | En teckensträng som ger bildens titel. Det kan vara en kommentar som "1988 företagspicknick" eller liknande. |
| Make | `271` | Tillverkaren av färdskrivaren. Detta är tillverkaren av DSC, skannern, videodigitalisatorn eller annan utrustning som genererade bilden. När fältet lämnas tomt behandlas det som okänt. |
| Model | `272` | Utrustningens modellnamn eller modellnummer. Detta är modellnamnet eller numret på DSC, skanner, videodigitalisator eller annan utrustning som genererade bilden. När fältet lämnas tomt behandlas det som okänt. |
| Orientation | `274` | Bildorienteringen sett i termer av rader och kolumner. |
| SamplesPerPixel | `277` | Antalet komponenter per pixel. Eftersom den här standarden gäller för RGB- och YCbCr-bilder är värdet för denna tagg 3. |
| XResolution | `282` | Antalet pixlar per ResolutionUnit i ImageWidth-riktningen. När bildupplösningen är okänd anges 72 [dpi]. |
| YResolution | `283` | Antalet pixlar per ResolutionUnit i ImageLength-riktningen. Samma värde som XResolution anges. |
| PlanarConfiguration | `284` | Indikerar om pixelkomponenter är inspelade i ett chunky eller plant format. Om det här fältet inte finns, antas TIFF-standarden 1 (chunky). |
| ResolutionUnit | `296` | Enheten för att mäta XResolution och YResolution. Samma enhet används för både XResolution och YResolution. Om bildupplösningen är okänd anges 2 (tum). |
| TransferFunction | `301` | En överföringsfunktion för bilden, beskriven i tabellformat. Normalt är denna tagg inte nödvändig, eftersom färgrymd anges i färgrymdsinformationen ColorSpace-taggen. |
| Software | `305` | Den här taggen registrerar namnet och versionen av programvaran eller firmware för kameran eller bildinmatningsenheten som används för att skapa bilden. Det detaljerade formatet anges inte, men det rekommenderas att exemplet nedan följs. När fältet lämnas tomt behandlas det som okänt. |
| DateTime | `306` | Datum och tid för bildskapande. I Exif-standarden är det datum och tid då filen ändrades. |
| Artist | `315` | Den här taggen registrerar namnet på kameraägaren, fotografen eller bildskaparen. Det detaljerade formatet är inte specificerat, men det rekommenderas att informationen skrivs som i exemplet nedan för att underlätta interoperabilitet. När fältet lämnas tomt, behandlas det som okänt. Ex.) "Kameraägare, John Smith; Fotograf, Michael Brown; Bildskapare, Ken James" |
| WhitePoint | `318` | Kromaticiteten hos bildens vita punkt. Normalt är denna tagg inte nödvändig, eftersom färgrymd anges i färgrymdsinformationen ColorSpace-taggen. |
| PrimaryChromaticities | `319` | Kromaticiteten hos bildens tre primära färger. Normalt är denna tagg inte nödvändig, eftersom färgrymd anges i färgrymdsinformationen ColorSpace-taggen. |
| YCbCrCoefficients | `529` | Matriskoefficienterna för transformation från RGB till YCbCr bilddata. |
| YCbCrSubSampling | `530` | Samplingsförhållandet för krominanskomponenter i förhållande till luminanskomponenten. |
| YCbCrPositioning | `531` | Placeringen av krominanskomponenter i förhållande till luminanskomponenten. Detta fält är endast avsett för JPEG-komprimerade data eller okomprimerade YCbCr-data. TIFF standard är 1 (centrerad); men när Y:Cb:Cr = 4:2:2 rekommenderas i denna standard att 2 (samplats) används för att spela in data, för att förbättra bildkvaliteten när den visas på TV-system. När detta fält inte finns, ska läsaren anta TIFF-standarden. I fallet med Y:Cb:Cr = 4:2:0, rekommenderas TIFF-standarden (centrerad). Om reader inte har förmågan att stödja båda typerna av YCbCrPositioning, ska den följa TIFF-standarden oavsett av värdet i detta fält. Det är att föredra att läsare " kan stödja både centrerad och samplacerad positionering. |
| ReferenceBlackWhite | `532` | Referenssvartpunktsvärdet och referensvitpunktsvärdet . Inga standardvärden anges i TIFF, men värdena nedan anges som standard här. Färgrymden deklareras i en informationstagg för färgrymd, där default är det värde som ger de optimala bildegenskaperna Interoperabilitet dessa villkor |
| Copyright | `33432` | Upphovsrättsinformation. I denna standard används taggen för att indikera både fotografens och redaktörens upphovsrätt. Det är copyrightmeddelandet för den person eller organisation som hävdar rättigheterna till bilden. Interoperability copyright uttalandet inklusive datum och rättigheter ska skrivas i detta fält; t.ex. "Copyright, John Smith, 19xx. Alla rättigheter reserverade.". I denna standard registrerar fältet både fotografens och redaktörens upphovsrätt, med var och en inspelad i en separat del av uttalandet. När det finns en tydlig skillnad mellan fotografens och redaktörens upphovsrätt, ska dessa skrivas i fotografens ordning följt av redaktörens copyright, separerade med NULL (i detta fall eftersom uttalandet också slutar med ett NULL, finns det två NULL-koder ). När endast upphovsrätten till photographer ges, avslutas den med en NULL-kod . När endast ges redaktörens copyright, består fotografens copyright part av ett mellanslag följt av en avslutande NULL-kod, sedan ges redaktörens copyright. När fältet lämnas tomt behandlas det som okänt. |
| ExposureTime | `33434` | Exponeringstid, angiven i sekunder. |
| FNumber | `33437` | F-numret. |
| ExposureProgram | `34850` | Klassen för programmet som används av kameran för att ställa in exponeringen när bilden tas. |
| SpectralSensitivity | `34852` | Indikerar den spektrala känsligheten för varje kanal i kameran som används. |
| PhotographicSensitivity | `34855` | Indikerar ISO-hastighet och ISO-latitud för kameran eller inmatningsenheten enligt ISO 12232. |
| OECF | `34856` | Indikerar den optoelektriska konverteringsfunktionen (OECF) specificerad i ISO 14524. |
| ExifVersion | `36864` | Exif-versionen. |
| DateTimeOriginal | `36867` | Datum och tid då den ursprungliga bilddatan genererades. |
| DateTimeDigitized | `36868` | Datum och tid digitaliserad. |
| ComponentsConfiguration | `37121` | Komponentens konfiguration. |
| CompressedBitsPerPixel | `37122` | Specifik för komprimerad data; anger de komprimerade bitarna per pixel. |
| ShutterSpeedValue | `37377` | Slutarhastighetsvärdet. |
| ApertureValue | `37378` | Objektivets bländarvärde. |
| BrightnessValue | `37379` | Ljusstyrkan. |
| ExposureBiasValue | `37380` | Exponeringsbiasvärdet. |
| MaxApertureValue | `37381` | Det maximala bländarvärdet. |
| SubjectDistance | `37382` | Avståndet till motivet, angivet i meter. |
| MeteringMode | `37383` | Mätläget. |
| LightSource | `37384` | Den snälla ljuskällan. |
| Flash | `37385` | Indikerar blixtens status när bilden togs. |
| FocalLength | `37386` | Objektivets faktiska brännvidd, i mm. |
| SubjectArea | `37396` | Den här taggen anger platsen och området för huvudmotivet i den övergripande scenen. |
| MakerNote | `37500` | En tagg för tillverkare av Exif-skrivare för att registrera all önskad information. Innehållet är upp till tillverkaren, men denna tagg bör inte användas för något annat än det avsedda syftet. |
| UserComment | `37510` | En tagg för Exif-användare att skriva nyckelord eller kommentarer på bilden förutom de i ImageDescription, och utan teckenkodsbegränsningarna för ImageDescription-taggen. |
| SubsecTime | `37520` | En tagg som används för att registrera bråkdelar av sekunder för DateTime-taggen. |
| SubsecTimeOriginal | `37521` | En tagg som används för att registrera bråkdelar av sekunder för DateTimeOriginal-taggen. |
| SubsecTimeDigitized | `37522` | En tagg som används för att registrera bråkdelar av sekunder för DateTime Digitalized-taggen. |
| FlashpixVersion | `40960` | Flashpix-formatversionen som stöds av en FPXR-fil. |
| ColorSpace | `40961` | Färgrymdsinformationstaggen (ColorSpace) registreras alltid som färgrymdsspecifikator. |
| RelatedSoundFile | `40964` | Den relaterade ljudfilen. |
| FlashEnergy | `41483` | Indikerar strobeenergin vid den tidpunkt då bilden tas, mätt i Beam Candle Power Seconds (BCPS). |
| SpatialFrequencyResponse | `41484` | Denna tagg registrerar kameran eller inmatningsenhetens rumsliga frekvenstabell och SFR-värden i riktning mot bildbredd, bildhöjd och diagonalriktning, enligt ISO 12233. |
| FocalPlaneXResolution | `41486` | Indikerar antalet pixlar i bildens bredd (X) riktning per FocalPlaneResolutionUnit på kamerans fokalplan. |
| FocalPlaneYResolution | `41487` | Indikerar antalet pixlar i bildhöjdsriktningen (Y) per FocalPlaneResolutionUnit på kamerans fokalplan. |
| FocalPlaneResolutionUnit | `41488` | Indikerar enheten för att mäta FocalPlaneXResolution och FocalPlaneYResolution. Detta värde är detsamma som ResolutionUnit. |
| SubjectLocation | `41492` | Indikerar platsen för huvudmotivet i scenen. Värdet på denna tagg representerar pixeln i mitten av huvudmotivet i förhållande till den vänstra kanten, före rotationsbearbetning enligt rotationstaggen. |
| ExposureIndex | `41493` | Indikerar exponeringsindexet som valts på kameran eller inmatningsenheten vid den tidpunkt då bilden togs. |
| SensingMethod | `41495` | Indikerar bildsensortypen på kameran eller inmatningsenheten. |
| FileSource | `41728` | Filkällan. |
| SceneType | `41729` | Indikerar typen av scen. Om en DSC spelade in bilden ska detta taggvärde alltid sättas till 1, vilket indikerar att bilden är direkt fotograferad. |
| CFAPattern | `41730` | Indikerar det geometriska mönstret för färgfiltermatrisen (CFA) för bildsensorn när en färgområdessensor med ett chip används. Det gäller inte alla avkänningsmetoder. |
| CustomRendered | `41985` | Den här taggen indikerar användningen av speciell bearbetning av bilddata, såsom rendering anpassad till utdata. När speciell bearbetning utförs förväntas läsaren inaktivera eller minimera all ytterligare bearbetning. |
| ExposureMode | `41986` | Denna tagg indikerar exponeringsläget som ställdes in när bilden togs. I autogafflingläge tar kameran en serie bilder av samma scen med olika exponeringsinställningar. |
| WhiteBalance | `41987` | Den här taggen anger vilket vitbalansläge som ställdes in när bilden togs. |
| DigitalZoomRatio | `41988` | Den här taggen anger det digitala zoomförhållandet när bilden togs. Om täljaren för det registrerade värdet är 0, indikerar detta att digital zoom inte användes. |
| FocalLengthIn35MmFilm | `41989` | Den här taggen indikerar motsvarande brännvidd om man antar en 35 mm filmkamera, i mm. Ett värde på 0 betyder att brännvidden är okänd. Observera att denna tagg skiljer sig från FocalLength-taggen. |
| SceneCaptureType | `41990` | Den här taggen anger vilken typ av scen som spelades in. Den kan också användas för att spela in i vilket läge bilden togs. |
| GainControl | `41991` | Denna tagg indikerar graden av total bildförstärkningsjustering. |
| Contrast | `41992` | Den här taggen indikerar riktningen för kontrastbehandling som användes av kameran när bilden togs. |
| Saturation | `41993` | Den här taggen indikerar riktningen för mättnadsbearbetning som användes av kameran när bilden togs. |
| Sharpness | `41994` | Den här taggen indikerar riktningen för skärpebearbetningen som användes av kameran när bilden togs |
| DeviceSettingDescription | `41995` | Den här taggen indikerar information om fotograferingsförhållandena för en viss kameramodell. Taggen används endast för att indikera bildtagningsförhållandena i läsaren. |
| SubjectDistanceRange | `41996` | Den här taggen anger avståndet till motivet. |
| ImageUniqueID | `42016` | Bildens unika id. |
| GPSVersionID | `0` | Indikerar versionen av GPSInfoIFD. |
| GPSLatitudeRef | `1` | Indikerar om latituden är nordlig eller sydlig latitud. |
| GPSLatitude | `2` | Indikerar latitud. Latituden uttrycks som tre RATIONELLA värden som ger grader, minuter respektive sekunder. Om latitud uttrycks som grader, minuter och sekunder skulle ett typiskt format vara dd/1,mm/1,ss/1. När grader och minuter används och till exempel bråkdelar av minuter ges upp till två decimaler, skulle formatet vara dd/1,mmmm/100,0/1. |
| GPSLongitudeRef | `3` | Indikerar om longituden är östlig eller västlig longitud. |
| GPSLongitude | `4` | Indikerar longituden. Longituden uttrycks som tre RATIONELLA värden som ger grader, minuter respektive sekunder. Om longitud uttrycks som grader, minuter och sekunder skulle ett typiskt format vara ddd/1,mm/1,ss/1. När grader och minuter används och till exempel bråkdelar av minuter ges upp till två decimaler, skulle formatet vara ddd/1,mmmm/100,0/1. |
| GPSAltitudeRef | `5` | Indikerar höjden som används som referenshöjd. Om referensen är havsnivån och höjden är över havet ges 0. Om höjden är under havsytan ges ett värde på 1 och höjden anges som ett absolut värde i GPSAltitude-taggen. |
| GPSAltitude | `6` | Indikerar höjden baserat på referensen i GPSAltitudeRef. Höjd uttrycks som ett RATIONELLT värde. Referensenheten är meter. |
| GPSTimestamp | `7` | Indikerar tiden som UTC (Coordinated Universal Time). Tidsstämpel uttrycks som tre RATIONELLA värden som ger timme, minut och sekund. |
| GPSSatellites | `8` | Indikerar GPS-satelliterna som används för mätningar. Denna tagg kan användas för att beskriva antalet satelliter, deras ID-nummer, höjdvinkel, azimut, SNR och annan information i ASCII-notation. Formatet är inte specificerat. Om GPS-mottagaren inte kan göra mätningar ska värdet på taggen sättas till NULL. |
| GPSStatus | `9` | Indikerar GPS-mottagarens status när bilden spelas in. |
| GPSMeasureMode | `10` | Indikerar GPS-mätläget. - 2- eller 3-dimensionell. |
| GPSDOP | `11` | Indikerar GPS DOP (datagrad av precision). Ett HDOP-värde skrivs under tvådimensionell mätning, och PDOP under tredimensionell mätning. |
| GPSSpeedRef | `12` | Indikerar enheten som används för att uttrycka GPS-mottagarens rörelsehastighet. 'K' 'M' och 'N' representerar kilometer per timme, miles per timme och knop. |
| GPSSpeed | `13` | Indikerar hastigheten för GPS-mottagarens rörelse. |
| GPSTrackRef | `14` | Indikerar referensen för att ge GPS-mottagarens rörelseriktning. 'T' betecknar sann riktning och 'M' är magnetisk riktning. |
| GPSTrack | `15` | Indikerar riktningen för GPS-mottagarens rörelse. Värdeintervallet är från 0,00 till 359,99. |
| GPSImgDirectionRef | `16` | Indikerar referensen för att ge bildens riktning när den tas. 'T' betecknar sann riktning och 'M' är magnetisk riktning. |
| GPSImgDirection | `17` | Indikerar bildens riktning när den togs. Värdeintervallet är från 0,00 till 359,99. |
| GPSMapDatum | `18` | Indikerar de geodetiska mätdata som används av GPS-mottagaren. |
| GPSDestLatitudeRef | `19` | Indikerar om latituden för destinationspunkten är nordlig eller sydlig latitud. ASCII-värdet 'N' indikerar north latitud och 'S' är sydlig latitud. |
| GPSDestLatitude | `20` | Indikerar latitud för destinationspunkten. Latituden uttrycks som tre RATIONELLA värden som ger grader, minuter respektive sekunder. Om latitud uttrycks som grader, minuter och sekunder, skulle ett typiskt -format vara dd/1,mm/1,ss/1. När grader och minuter används och till exempel bråkdelar av minuter är ges upp till två decimaler, skulle formatet vara dd/1,mmmm/100,0/1. |
| GPSDestLongitudeRef | `21` | Indikerar om longituden för destinationspunkten är östlig eller västlig longitud. ASCII 'E' indikerar östlig longitud, och 'W' är västlig longitud. |
| GPSDestLongitude | `22` | Indikerar longituden för destinationspunkten. Longituden uttrycks som tre RATIONELLA värden som ger grader, minuter respektive sekunder. Om longitud uttrycks som grader, minuter och sekunder, skulle ett typiskt -format vara ddd/1,mm/1,ss/1. När grader och minuter används och till exempel bråkdelar av minuter är ges upp till två decimaler, skulle formatet vara ddd/1,mmmm/100,0/1. |
| GPSDestBearingRef | `23` | Indikerar referensen som används för att ge bäringen till destinationspunkten. 'T' betecknar sann riktning och 'M' är magnetisk riktning. |
| GPSDestBearing | `24` | Indikerar bäringen till destinationspunkten. Värdeintervallet är från 0,00 till 359,99. |
| GPSDestDistanceRef | `25` | Indikerar enheten som används för att uttrycka avståndet till destinationspunkten. 'K', 'M' och 'N' representerar kilometer, miles och knop. |
| GPSDestDistance | `26` | Indikerar avståndet till destinationspunkten. |
| GPSProcessingMethod | `27` | En teckensträng som registrerar namnet på metoden som används för att hitta plats. Den första byten indikerar teckenkoden som används, och denna följs av metodens name . |
| GPSAreaInformation | `28` | En teckensträng som registrerar namnet på GPS-området. Den första byten indikerar teckenkoden som används, och denna följs av namnet på GPS-området. |
| GPSDateStamp | `29` | En teckensträng som registrerar datum- och tidsinformation i förhållande till UTC (Coordinated Universal Time). Formatet är ÅÅÅÅ:MM:DD. |
| GPSDifferential | `30` | Indikerar om differentiell korrigering tillämpas på GPS-mottagaren. |
| StripOffsets | `273` | För varje remsa, byteoffset för den remsan. Det rekommenderas att detta väljs så att antalet stripbyte inte överstiger 64 Kbytes. Aux tag. |
| JPEGInterchangeFormat | `513` | Förskjutningen till startbyten (SOI) för JPEG-komprimerade miniatyrbildsdata. Detta används inte för primär bild JPEG-data. |
| JPEGInterchangeFormatLength | `514` | Antalet byte av JPEG-komprimerade miniatyrdata. Detta används inte för primärbild JPEG-data. JPEG-miniatyrbilder är inte uppdelade utan spelas in som en kontinuerlig JPEG-bitström från SOI till EOI. Appn- och COM-markörer ska inte registreras. Komprimerade miniatyrer måste spelas in i högst 64 Kbyte, inklusive all annan data som ska spelas in i APP1. |
| ExifIfdPointer | `34665` | En pekare till Exif IFD. Interoperabilitet, Exif IFD har samma struktur som den för IFD som anges i TIFF. vanligtvis innehåller den dock inte bilddata som i fallet med TIFF. |
| GPSIfdPointer | `34853` | GPS-ifd-pekaren. |
| RowsPerStrip | `278` | Antalet rader per remsa. Detta är antalet rader i bilden av en remsa när en bild är uppdelad i remsor. |
| StripByteCounts | `279` | Det totala antalet byte i varje remsa. |
| PixelXDimension | `40962` | Information som är specifik för komprimerad data. När en komprimerad fil spelas in, ska den giltiga bredden på den meningsfulla bilden registreras i denna tagg, oavsett om det finns utfyllnadsdata eller en omstartsmarkör. |
| PixelYDimension | `40963` | Information som är specifik för komprimerad data. När en komprimerad fil spelas in, ska den giltiga höjden på den meningsfulla bilden registreras i denna tag |
| Gamma | `42240` | Gammavärde |
| SensitivityType | `34864` | Typ av fotografisk känslighet |
| StandardOutputSensitivity | `34865` | Indikerar standardutgångskänslighet för camera |
| RecommendedExposureIndex | `34866` | Indikerar rekommenderat exponeringsindex |
| ISOSpeed | `34867` | Information om isohastighetsvärde enligt definition i ISO 12232 |
| ISOSpeedLatitudeYYY | `34868` | Den här taggen indikerar ISO-hastighet latitud yyy värde enligt definition i ISO 12232 |
| ISOSpeedLatitudeZZZ | `34869` | Denna tagg indikerar ISO-hastighets latitud zzz-värde enligt definition i ISO 12232 |
| CameraOwnerName | `42032` | Innehåller kameraägarens namn |
| BodySerialNumber | `42033` | Innehåller kamerahusets serienummer |
| LensMake | `42035` | Denna tagg registrerar linstillverkare |
| LensModel | `42036` | Denna tagg registrerar objektivets modellnamn och modellnummer |
| LensSerialNumber | `42037` | Den här taggen registrerar serienumret för utbytbara lins |
| LensSpecification | `42034` | Den här taggen noterar minsta brännvidd, maximal brännvidd, minsta F-nummer i minsta brännvidd och minsta F-nummer i maximal brännvidd |

### Se även

* namnutrymme [Aspose.Imaging.Exif](../../aspose.imaging.exif)
* hopsättning [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
