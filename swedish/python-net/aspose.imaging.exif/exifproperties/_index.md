---
title: "ExifProperties-uppräkning"
type: docs
weight: 190
url: /sv/python-net/aspose.imaging.exif/exifproperties/
---

Exif‑tagglista

**Module:** [aspose.imaging.exif](/imaging/python-net/aspose.imaging.exif/)

**Full Name:** aspose.imaging.exif.ExifProperties

## **Members**
| **Member name** | **Description** |
| :- | :- |
| APERTURE_VALUE | Bländarvärdet för linsen. |
| ARTIST | Denna tagg registrerar namnet på kamerans ägare, fotograf eller bildskapare. Det detaljerade formatet är inte specificerat, men det rekommenderas att informationen skrivs enligt exemplet nedan för att underlätta interoperabilitet. När fältet lämnas tomt behandlas det som okänt. Ex.) "Camera owner, John Smith; Photographer, Michael Brown; Image creator, Ken James" |
| BITS_PER_SAMPLE | Antalet bitar per bildkomponent. I denna standard är varje komponent i bilden 8 bitar, så värdet för denna tagg är 8. |
| BODY_SERIAL_NUMBER | Innehåller kamerahusets serienummer |
| BRIGHTNESS_VALUE | Ljusstyrkevärdet. |
| CAMERA_OWNER_NAME | Innehåller kamerans ägarnamn |
| CFA_PATTERN | Anger färgfilterarrayens (CFA) geometriska mönster för bildsensorn när en enkelskikts färgområdessensor används. Det gäller inte alla avkänningsmetoder. |
| COLOR_SPACE | Färgrymdsinformations-taggen (ColorSpace) registreras alltid som färgrymdsspecifikator. |
| COMPONENTS_CONFIGURATION | Komponenternas konfiguration. |
| COMPRESSED_BITS_PER_PIXEL | Specifikt för komprimerad data; anger de komprimerade bitarna per pixel. |
| KOMPRESSION | Komprimeringsschemat som används för bilddata. När en primär bild är JPEG-komprimerad är denna beteckning inte nödvändig och utelämnas. |
| KONTRAST | Denna tagg anger riktningen för kontrastbehandling som kameran tillämpade när bilden togs. |
| UPPHOVSRÄTT | Upphovsrättsinformation. I denna standard används taggen för<br/>                ange både fotografens och redaktörens upphovsrätt. Det är<br/>                upphovsrättsmeddelandet från den person eller organisation som gör<br/>                anspråk på bilden. Interoperabilitetens upphovsrätts<br/>                uttalande inklusive datum och rättigheter bör skrivas i detta<br/>                fält; t.ex. "Copyright, John Smith, 19xx. All rights
                reserved.". I denna standard registrerar fältet både<br/>                fotografens och redaktörens upphovsrätt, där varje registreras i en<br/>                separat del av uttalandet. När det finns en tydlig skillnad<br/>                mellan fotografens och redaktörens upphovsrätt ska dessa<br/>                skrivas i ordning fotograf följt av redaktörens upphovsrätt,<br/>                separerade med NULL (i detta fall, eftersom uttalandet också avslutas med<br/>                en NULL, finns två NULL-koder). När endast fotografens<br/>                upphovsrätt anges, avslutas den med en NULL-kod. När endast<br/>                redaktörens upphovsrätt anges, består fotografens upphovsrättsdel<br/>                av ett mellanslag följt av en avslutande NULL-kod, sedan
                anges redaktörens upphovsrätt. När fältet lämnas tomt, behandlas det
                som okänt. |
| ANPASSAD_RENDERAD | Denna tagg indikerar användning av speciell bearbetning av bilddata, såsom rendering anpassad för utskrift. När speciell bearbetning utförs förväntas läsaren inaktivera eller minimera ytterligare bearbetning. |
| DATUM_TID | Datum och tid för bildens skapande. I Exif-standarden är det datum och tid då filen ändrades. |
| DATUM_TID_DIGITALISERAD | Datum och tid för digitalisering. |
| DATUM_TID_ORIGINAL | Datum och tid då den ursprungliga bilddata skapades. |
| ENHET_INSTÄLLNING_BESKRIVNING | Denna tagg anger information om bildtagningsförhållandena för en specifik kameramodell. Taggen används endast för att indikera bildtagningsförhållandena i läsaren. |
| DIGITAL_ZOOM_FÖRHÅLLANDE | Denna tagg anger det digitala zoomförhållandet när bilden togs. Om täljaren för det registrerade värdet är 0 indikerar det att digital zoom inte användes. |
| EXIF_IFD_PEKARE | En pekare till Exif IFD. Interoperabilitet, Exif IFD har samma struktur som IFD som specificeras i TIFF. Vanligtvis innehåller den dock inte bilddata som i fallet med TIFF. |
| EXIF_VERSION | Exif-versionen. |
| EXPOSURE_BIAS_VÄRDE | Exponeringsbiasvärdet. |
| EXPOSURE_INDEX | Anger exponeringsindexet som valdes på kameran eller inmatningsenheten när bilden fångas. |
| EXPOSURE_MODE | Denna tagg anger exponeringsläget som ställdes in när bilden togs. I auto‑bracketing‑läge tar kameran en serie bildrutor av samma scen med olika exponeringsinställningar. |
| EXPOSURE_PROGRAM | Klassen för programmet som kameran använder för att ställa in exponering när bilden tas. |
| EXPOSURE_TIME | Exponeringstid, angiven i sekunder. |
| FILE_SOURCE | Filkällan. |
| FLASH | Anger blixtens status när bilden togs. |
| FLASHPIX_VERSION | Flashpix-formatversionen som stöds av en FPXR‑fil. |
| FLASH_ENERGY | Anger stroberenergin vid tiden då bilden fångas, mätt i Beam Candle Power Seconds (BCPS). |
| FOCAL_LENGTH | Den faktiska brännvidden på linsen, i mm. |
| FOCAL_LENGTH_IN_35_MM_FILM | Denna tagg anger den ekvivalenta brännvidden förutsatt en 35 mm filmkamera, i mm. Ett värde på 0 betyder att brännvidden är okänd. Observera att denna tagg skiljer sig från FocalLength‑taggen. |
| FOCAL_PLANE_RESOLUTION_UNIT | Anger enheten för att mäta FocalPlaneXResolution och FocalPlaneYResolution. Detta värde är detsamma som ResolutionUnit. |
| FOCAL_PLANE_X_RESOLUTION | Anger antalet pixlar i bildens bredd (X)-riktning per FocalPlaneResolutionUnit på kamerans fokalplan. |
| FOCAL_PLANE_Y_RESOLUTION | Anger antalet pixlar i bildens höjd (Y)-riktning per FocalPlaneResolutionUnit på kamerans fokalplan. |
| F_NUMBER | F-numret. |
| GAIN_CONTROL | Denna tagg anger graden av total bildförstärkningsjustering. |
| GAMMA | Gamma-värde |
| GPSDOP | Anger GPS DOP (dataprecisionsgrad). Ett HDOP-värde skrivs under tvådimensionell mätning,<br/>                och PDOP under tredimensionell mätning. |
| GPS_ALTITUDE | Anger höjden baserat på referensen i GPSAltitudeRef. Höjden uttrycks som ett RATIONAL-värde.<br/>                Referensenheten är meter. |
| GPS_ALTITUDE_REF | Anger den höjd som används som referenshöjd. Om referensen är havsnivå och höjden är över havsnivå,<br/>                anges 0. Om höjden är under havsnivå, anges värdet 1 och höjden indikeras som ett absolut värde i<br/>                GPSAltitude-taggen. |
| GPS_AREA_INFORMATION | En teckensträng som registrerar namnet på GPS-området. Den första byten indikerar<br/>                den använda teckenkoden, och detta följs av namnet på GPS-området. |
| GPS_DATE_STAMP | En teckensträng som registrerar datum- och tidsinformation relativt UTC<br/>                (Coordinated Universal Time). Formatet är YYYY:MM:DD. |
| GPS_DEST_BEARING | Anger riktningen till destinationspunkten. Värdeintervallet är från 0.00 till 359.99. |
| GPS_DEST_BEARING_REF | Anger referensen som används för att ange riktningen till destinationspunkten. 'T' betyder sann riktning och 'M' är<br/>                magnetisk riktning. |
| GPS_DEST_DISTANCE | Anger avståndet till destinationspunkten. |
| GPS_DEST_DISTANCE_REF | Anger enheten som används för att uttrycka avståndet till destinationspunkten. 'K', 'M' och 'N' representerar kilometer, miles<br/>                och knop. |
| GPS_DEST_LATITUDE | Anger latituden för destinationspunkten. Latituden uttrycks som tre RATIONAL‑värden som ger<br/>                grader, minuter och sekunder, i den ordningen. Om latituden uttrycks i grader, minuter och sekunder, är ett typiskt<br/>                format dd/1,mm/1,ss/1. När grader och minuter används och exempelvis bråkdelar av minuter anges med upp till två decimaler,<br/>                blir formatet dd/1,mmmm/100,0/1. |
| GPS_DEST_LATITUDE_REF | Anger om latituden för destinationspunkten är nordlig eller sydlig latitud. ASCII‑värdet 'N' indikerar nordlig<br/>                latitud, och 'S' är sydlig latitud. |
| GPS_DEST_LONGITUDE | Anger longituden för destinationspunkten. Longituden uttrycks som tre RATIONAL‑värden som ger<br/>                grader, minuter och sekunder, i den ordningen. Om longituden uttrycks i grader, minuter och sekunder, är ett typiskt<br/>                format ddd/1,mm/1,ss/1. När grader och minuter används och exempelvis bråkdelar av minuter anges med upp till två decimaler,<br/>                blir formatet ddd/1,mmmm/100,0/1. |
| GPS_DEST_LONGITUDE_REF | Anger om longituden för destinationspunkten är östlig eller västlig longitud. ASCII 'E' indikerar östlig longitud,<br/>                och 'W' är västlig longitud. |
| GPS_DIFFERENTIAL | Anger om differentialkorrigering tillämpas på GPS‑mottagaren. |
| GPS_IFD_POINTER | GPS‑IFD‑pekaren. |
| GPS_IMG_DIRECTION | Anger bildens riktning när den togs. Värdeintervallet är från 0,00 till 359,99. |
| GPS_IMG_DIRECTION_REF | Anger referensen för att ange bildens riktning när den tas. 'T' betyder sann riktning och 'M' är<br/>                magnetisk riktning. |
| GPS_LATITUDE | Anger latituden. Latituden uttrycks som tre RATIONAL‑värden som ger grader, minuter och<br/>                sekunder, i den ordningen. Om latituden uttrycks i grader, minuter och sekunder, är ett typiskt format<br/>                dd/1,mm/1,ss/1. När grader och minuter används och exempelvis bråkdelar av minuter anges med upp till två<br/>                decimaler, blir formatet dd/1,mmmm/100,0/1. |
| GPS_LATITUDE_REF | Anger om latituden är nordlig eller sydlig. |
| GPS_LONGITUDE | Anger longituden. Longituden uttrycks som tre RATIONAL‑värden som ger grader, minuter och<br/>                sekunder, i den ordningen. Om longituden uttrycks i grader, minuter och sekunder, är ett typiskt format<br/>                ddd/1,mm/1,ss/1. När grader och minuter används och exempelvis bråkdelar av minuter anges med upp till två<br/>                decimaler, blir formatet ddd/1,mmmm/100,0/1. |
| GPS_LONGITUDE_REF | Anger om longituden är östlig eller västlig. |
| GPS_MAP_DATUM | Anger de geodetiska kartdata som används av GPS‑mottagaren. |
| GPS_MEASURE_MODE | Anger GPS-mätningsläget. - 2- eller 3-dimensionellt. |
| GPS_PROCESSING_METHOD | En teckensträng som registrerar namnet på den metod som används för positionsbestämning.<br/>                Den första byten indikerar den använda teckenkoden, och detta följs av metodens namn<br/>                . |
| GPS_SATELLITES | Anger de GPS-satelliter som används för mätningar. Denna tagg kan användas för att beskriva antalet satelliter,<br/>                deras ID-nummer, höjdvinkel, azimut, SNR och annan information i ASCII‑notation. Formatet är inte<br/>                specificerat. Om GPS-mottagaren inte kan utföra mätningar ska taggens värde sättas till NULL. |
| GPS_SPEED | Anger hastigheten för GPS-mottagarens rörelse. |
| GPS_SPEED_REF | Anger enheten som används för att uttrycka GPS-mottagarens rörelsehastighet. 'K', 'M' och 'N' representerar kilometer per<br/>                timme, miles per timme och knop. |
| GPS_STATUS | Anger GPS-mottagarens status när bilden spelas in. |
| GPS_TIMESTAMP | Anger tiden som UTC (Coordinated Universal Time). Tidsstämpeln uttrycks som tre RATIONAL‑värden<br/>                som ger timme, minut och sekund. |
| GPS_TRACK | Anger riktningen för GPS-mottagarens rörelse. Värdeintervallet är från 0,00 till 359,99. |
| GPS_TRACK_REF | Anger referensen för att ange riktningen för GPS-mottagarens rörelse. 'T' betecknar sann riktning och 'M' är<br/>                magnetisk riktning. |
| GPS_VERSION_ID | Anger versionen av GPSInfoIFD. |
| IMAGE_DESCRIPTION | En teckensträng som ger bildens titel. Det kan vara en kommentar som "1988 företagsutflykt" eller liknande. |
| IMAGE_LENGTH | Antalet rader av bilddata. |
| IMAGE_UNIQUE_ID | Bildens unika ID. |
| IMAGE_WIDTH | Antalet kolumner i bilddata, lika med antalet pixlar per rad. |
| ISO_SPEED | Information om ISO-hastighetsvärdet enligt ISO 12232. |
| ISO_SPEED_LATITUDE_YYY | Denna tagg anger ISO-hastighetslatitud yyy-värdet enligt ISO 12232. |
| ISO_SPEED_LATITUDE_ZZZ | Denna tagg anger ISO-hastighetslatitud zzz-värdet enligt ISO 12232. |
| JPEG_INTERCHANGE_FORMAT | Förskjutningen till startbyten (SOI) för JPEG-komprimerad miniatyrbildsdata. Detta används inte för primär JPEG-bilddata. |
| JPEG_INTERCHANGE_FORMAT_LENGTH | Antalet byte av JPEG-komprimerad miniatyrbildsdata. Detta används inte för primär JPEG-bilddata. JPEG-miniatyrbilder är inte delade utan registreras som ett kontinuerligt JPEG-bitflöde från SOI till EOI. Appn- och COM-markörer bör inte registreras. Komprimerade miniatyrbilder får inte registreras i mer än 64 Kbyte, inklusive all annan data som ska registreras i APP1. |
| LENS_MAKE | Denna tagg registrerar objektivets tillverkare. |
| LENS_MODEL | Denna tagg registrerar objektivets modellnamn och modellnummer. |
| LENS_SERIAL_NUMBER | Denna tagg registrerar serienumret för utbytbart objektiv. |
| LENS_SPECIFICATION | Denna tagg noterar minsta brännvidd, största brännvidd, lägsta bländartal vid minsta brännvidd och lägsta bländartal vid största brännvidd. |
| LIGHT_SOURCE | Typ av ljuskälla. |
| MAKE | Tillverkaren av inspelningsutrustningen. Detta är tillverkaren av DSC, skanner, videodigitaliserare eller annan utrustning som skapade bilden. När fältet lämnas tomt behandlas det som okänt. |
| MAKER_NOTE | En tagg för tillverkare av Exif‑skrivare för att registrera önskad information. Innehållet bestäms av tillverkaren, men denna tagg bör inte användas för något annat än dess avsedda syfte. |
| MAX_APERTURE_VALUE | Det maximala bländarvärdet. |
| METERING_MODE | Mätningsläget. |
| MODEL | Modellnamnet eller modellnumret på utrustningen. Detta är modellnamnet eller -numret för DSC, skanner, videodigitaliserare eller annan utrustning som skapade bilden. När fältet är tomt behandlas det som okänt. |
| OECF | Anger den opto‑elektriska konverteringsfunktionen (OECF) som specificeras i ISO 14524. |
| ORIENTATION | Bildens orientering visas i rader och kolumner. |
| PHOTOGRAPHIC_SENSITIVITY | Anger ISO‑hastigheten och ISO‑latituden för kameran eller inmatningsenheten enligt ISO 12232. |
| PHOTOMETRIC_INTERPRETATION | Pixelns sammansättning. |
| PIXEL_X_DIMENSION | Information specifik för komprimerad data. När en komprimerad fil registreras ska den giltiga bredden på den meningsfulla bilden registreras i denna tagg, oavsett om det finns utfyllnadsdata eller en omstartsmarkör. |
| PIXEL_Y_DIMENSION | Information specifik för komprimerad data. När en komprimerad fil registreras ska den giltiga höjden på den meningsfulla bilden registreras i denna tagg |
| PLANAR_CONFIGURATION | Anger om pixelkomponenter registreras i ett chunky‑ eller planarformat. Om detta fält inte finns antas TIFF‑standardvärdet 1 (chunky). |
| PRIMARY_CHROMATICITIES | Färgens kromaticitet för bildens tre primära färger. Normalt är denna tagg onödig, eftersom färgrymden specificeras i färgrymdsinformationen i ColorSpace‑taggen. |
| RECOMMENDED_EXPOSURE_INDEX | Anger rekommenderat exponeringindex |
| REFERENCE_BLACK_WHITE | Referensvärdet för svartpunkt och referensvärdet för vitpunkt<br/>                värde. Inga standardvärden ges i TIFF, men värdena nedan anges som standardvärden här.<br/>                Färgrymden deklareras<br/>                i en färgrymdsinformations‑tagg, med standardvärdet<br/>                som är det värde som ger de optimala bildegenskaperna<br/>                Interoperabilitet under dessa förhållanden |
| RELATED_SOUND_FILE | Den relaterade ljudfilen. |
| RESOLUTION_UNIT | Enheten för att mäta XResolution och YResolution. Samma enhet används för både XResolution och YResolution. Om bildens upplösning är okänd, anges 2 (tum). |
| ROWS_PER_STRIP | Antalet rader per remsa. Detta är antalet rader i bilden för en remsa när en bild delas upp i remsor. |
| SAMPLES_PER_PIXEL | Antalet komponenter per pixel. Eftersom denna standard gäller för RGB- och YCbCr-bilder, är värdet som sätts för denna tagg 3. |
| SATURATION | Denna tagg anger riktningen för mättnadsbehandling som kameran tillämpade när bilden togs. |
| SCENE_CAPTURE_TYPE | Denna tagg anger vilken typ av scen som fotograferades. Den kan också användas för att registrera vilket läge bilden togs i. |
| SCENE_TYPE | Anger scenens typ. Om en DSC har spelat in bilden ska detta taggvärde alltid vara 1, vilket indikerar att bilden fotograferades direkt. |
| SENSING_METHOD | Anger bildsensortypen på kameran eller inmatningsenheten. |
| SENSITIVITY_TYPE | Typ av fotografisk känslighet |
| SHARPNESS | Denna tagg anger riktningen för skärpebehandling som kameran tillämpade när bilden togs |
| SHUTTER_SPEED_VALUE | Värdet för slutartiden. |
| PROGRAMVARA | Detta tag registrerar namn och version av programvaran eller firmware för kameran eller bildinmatningsenheten som användes för att generera bilden. Det detaljerade formatet är inte specificerat, men det rekommenderas att följa exemplet nedan. När fältet lämnas tomt behandlas det som okänt. |
| SPATIAL_FREQUENCY_RESPONSE | Detta tag registrerar kamerans eller inmatningsenhetens spatialfrekvenstabell och SFR-värden i bildens bredd, höjd och diagonalriktning, enligt ISO 12233. |
| SPECTRAL_SENSITIVITY | Anger det spektrala känsligheten för varje kanal i den använda kameran. |
| STANDARD_OUTPUT_SENSITIVITY | Anger standardutgångskänsligheten för kameran. |
| STRIP_BYTE_COUNTS | Det totala antalet byte i varje remsa. |
| STRIP_OFFSETS | För varje remsa, byteoffseten för den remsan. Det rekommenderas att detta väljs så att antalet byte per remsa inte överstiger 64 Kbyte.<br/>                Aux tag. |
| SUBJECT_AREA | Detta tag anger platsen och området för huvudmotivet i den övergripande scenen. |
| SUBJECT_DISTANCE | Avståndet till motivet, angivet i meter. |
| SUBJECT_DISTANCE_RANGE | Detta tag anger avståndet till motivet. |
| SUBJECT_LOCATION | Anger platsen för huvudmotivet i scenen. Värdet för detta tag representerar pixeln i centrum av huvudmotivet relativt till vänster kant, före rotationsbearbetning enligt Rotation tag. |
| SUBSEC_TIME | Ett tag som används för att registrera bråkdelar av sekunder för DateTime‑taggen. |
| SUBSEC_TIME_DIGITIZED | Ett tag som används för att registrera bråkdelar av sekunder för DateTimeDigitized‑taggen. |
| SUBSEC_TIME_ORIGINAL | En tagg som används för att registrera bråkdelar av sekunder för DateTimeOriginal-taggen. |
| TRANSFER_FUNCTION | En överföringsfunktion för bilden, beskriven i tabellformat. Normalt är denna tagg inte nödvändig, eftersom färgrymden specificeras i färgrymdsinformationen i ColorSpace-taggen. |
| USER_COMMENT | En tagg för Exif-användare att skriva nyckelord eller kommentarer på bilden förutom de i ImageDescription, och utan teckenkodningsbegränsningarna i ImageDescription-taggen. |
| WHITE_BALANCE | Denna tagg indikerar vitbalansläget som sattes när bilden togs. |
| WHITE_POINT | Kromaticiteten för bildens vitpunkt. Normalt är denna tagg inte nödvändig, eftersom färgrymden specificeras i färgrymdsinformationen i ColorSpace-taggen. |
| X_RESOLUTION | Antalet pixlar per ResolutionUnit i ImageWidth-riktningen. När bildens upplösning är okänd anges 72 [dpi]. |
| Y_CB_CR_COEFFICIENTS | Matriskoefficienterna för transformation från RGB till YCbCr-bilddata. |
| Y_CB_CR_POSITIONING | Positionen för krominanskomponenterna i förhållande till<br/>                luminanskomponenten. Detta fält är avsett endast för<br/>                JPEG-komprimerad data eller okomprimerad YCbCr-data. TIFF‑standardens<br/>                standardvärde är 1 (centrerad); men när Y:Cb:Cr = 4:2:2 rekommenderas i detta standard att 2 (sido‑placerad) används för att<br/>                registrera data, för att förbättra bildkvaliteten när den visas<br/>                på TV-system. När detta fält saknas ska läsaren<br/>                anta TIFF‑standardvärdet. I fallet Y:Cb:Cr = 4:2:0 är<br/>                TIFF‑standardvärdet (centrerat) rekommenderat. Om läsaren<br/>                inte har möjlighet att stödja båda typerna av<br/>                YCbCrPositioning, ska den följa TIFF‑standardvärdet oavsett<br/>                värdet i detta fält. Det är önskvärt att läsare "<br/>                kan stödja både centrerad och sido‑placerad positionering. |
| Y_CB_CR_SUB_SAMPLING | Samplingsförhållandet för krominanskomponenterna i förhållande till luminanskomponenten. |
| Y_RESOLUTION | Antalet pixlar per ResolutionUnit i ImageLength-riktningen. Samma värde som XResolution anges. |
