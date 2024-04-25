---
title: WmfMetafileEscapes
second_title: Aspose.Imaging för .NET API-referens
description: MetafileEscapes Enumeration anger skrivardrivrutinsfunktioner som kanske inte är direkt åtkomliga via WMF-poster som definieras i RecordType Enumeration avsnitt 2.1.1.1.
type: docs
weight: 8230
url: /sv/aspose.imaging.fileformats.wmf.consts/wmfmetafileescapes/
---
## WmfMetafileEscapes enumeration

MetafileEscapes Enumeration anger skrivardrivrutinsfunktioner som kanske inte är direkt åtkomliga via WMF-poster som definieras i RecordType Enumeration (avsnitt 2.1.1.1).

```csharp
public enum WmfMetafileEscapes
```

### Värderingar

| namn | Värde | Beskrivning |
| --- | --- | --- |
| Newframe | `1` | Meddelar skrivardrivrutinen att programmet har skrivit klart till en sida. |
| Abortdoc | `2` | Slutar bearbeta det aktuella dokumentet. |
| Nextband | `3` | Meddelar skrivardrivrutinen att programmet har skrivit klart till ett band. |
| Setcolortable | `4` | Ställer in färgtabellsvärden. |
| Getcolortable | `5` | Får färgtabellvärden. |
| Flushout | `6` | Gör att alla väntande utdata spolas till utenheten. |
| Draftmode | `7` | Indikerar att skrivardrivrutinen endast SKA skriva ut text och ingen grafik. |
| Queryescsupport | `8` | Frågar en skrivardrivrutin för att avgöra om en specifik escape-funktion stöds på den utenhet som den driver. |
| Setabortproc | `9` | Ställer in den programdefinierade funktionen som gör att ett utskriftsjobb kan avbrytas under utskrift. |
| Startdoc | `10` | Meddelar skrivardrivrutinen att ett nytt utskriftsjobb startar. |
| Enddoc | `11` | Meddelar skrivardrivrutinen att det aktuella utskriftsjobbet avslutas. |
| Getphyspagesize | `12` | Hämtar den fysiska sidstorleken som för närvarande är vald på en utdataenhet. |
| Getprintingoffset | `13` | Hämtar offset från det övre vänstra hörnet av den fysiska sidan där själva utskriften eller ritningen börjar. |
| Getscalingfactor | `14` | Hämtar skalningsfaktorerna för x-axeln och y-axeln för en skrivare. |
| MetaEscapeEnhancedMetafile | `15` | Används för att bädda in ett förbättrat metafilformat (EMF) metafil i en WMF-metafil. |
| Setpenwidth | `16` | Ställer in bredden på en penna i pixlar. |
| Setcopycount | `17` | Ställer in antalet kopior. |
| Setpapersource | `18` | Ställer in källan, till exempel ett visst pappersfack eller fack på en skrivare, för utmatningsformulär. |
| Passthrough | `19` | Denna post passerar genom godtyckliga data. |
| Gettechnology | `20` | Får information om grafikteknik som stöds på en enhet. |
| Setlinecap | `21` | Anger linjeritningsläget som ska användas vid utmatning till en enhet. |
| Setlinejoin | `22` | Anger linjekopplingsläget som ska användas vid utmatning till en enhet. |
| Setmiterlimit | `23` | Anger gränsen för längden på geringsfogar som ska användas i utdata till en enhet. |
| Bandinfo | `24` | Hämtar eller anger inställningar för banding på en enhet, såsom antal band. |
| Drawpatternrect | `25` | Ritar en rektangel med ett definierat mönster. |
| Getvectorpensize | `26` | Hämtar den fysiska pennstorleken som för närvarande är definierad på en enhet. |
| Getvectorbrushsize | `27` | Hämtar den fysiska borststorleken som för närvarande är definierad på en enhet. |
| Enableduplex | `28` | Aktiverar eller inaktiverar dubbelsidig (duplex) utskrift på en enhet. |
| Getsetpaperbins | `29` | Hämtar eller anger källan för utdataformulär på en enhet. |
| Getsetprintorient | `30` | Hämtar eller anger pappersorientering på en enhet. |
| Enumpaperbins | `31` | Hämtar information om källorna till olika formulär på en utenhet. |
| Setdibscaling | `32` | Anger skalningen av enhetsoberoende bitmappar (DIB). |
| Epsprinting | `33` | Indikerar början och slutet av en inkapslad PostScript-sektion (EPS). |
| Enumpapermetrics | `34` | Frågar en skrivardrivrutin för pappersdimensioner och andra formulärdata. |
| Getsetpapermetrics | `35` | Hämtar eller anger pappersmått och andra formulärdata på en utenhet. |
| PostscriptData | `37` | Skickar godtycklig PostScript-data till en utenhet. |
| PostscriptIgnore | `38` | Meddelar en utenhet att ignorera PostScript-data. |
| Getdeviceunits | `42` | Hämtar enhetsenheterna som för närvarande är konfigurerade på en utenhet. |
| Getextendedtextmetrics | `256` | Får utökade textstatistik som för närvarande är konfigurerade på en output -enhet. |
| Getpairkerntable | `258` | Hämtar teckensnittskärntabellen som för närvarande är definierad på en utenhet. |
| Exttextout | `512` | Ritar text med det valda teckensnittet, bakgrundsfärgen och textfärgen. |
| Getfacename | `513` | Hämtar teckensnittsnamnet som för närvarande är konfigurerat på en enhet. |
| Downloadface | `514` | Ställer in teckensnittsnamnet på en enhet. |
| MetafileDriver | `2049` | Frågar en skrivardrivrutin om stöd för metafiler på en output enhet. |
| Querydibsupport | `3073` | Frågar skrivardrivrutinen om dess stöd för DIB:er på en utenhet. |
| BeginPath | `4096` | Öppnar en sökväg. |
| ClipToPath | `4097` | Definierar ett klippområde som begränsas av en bana. Ingången MÅSTE vara en 16-bitars kvantitet som definierar åtgärden som ska vidtas. |
| EndPath | `4098` | Avslutar en sökväg. |
| OpenChannel | `4110` | Samma som STARTDOC specificerat med ett NULL-dokument och output filnamn, data i råläge och en typ av noll. |
| Downloadheader | `4111` | Instruerar skrivardrivrutinen att ladda ned uppsättningar av PostScript-procedurer. |
| CloseChannel | `4112` | Samma som ENDDOC. Se OPEN_CHANNEL. |
| PostscriptPassthrough | `4115` | Skickar godtyckliga data direkt till en skrivardrivrutin, som förväntas bearbeta dessa data endast i PostScript-läge.PostscriptIdentify . |
| EncapsulatedPostscript | `4116` | Skickar godtyckliga data direkt till skrivardrivrutinen. |
| PostscriptIdentify | `4117` | Ställer in skrivardrivrutinen på antingen PostScript- eller GDI-läge. |
| PostscriptInjection | `4118` | Infogar ett block med rådata i en PostScript-ström. Ingången MÅSTE vara en 32-bitars kvantitet som anger antalet byte som ska injiceras, en 16-bitars kvantitet som anger injektionspunkten och en 16-bitars kvantitet som anger sidnumret, följt av de bytes som ska injiceras. |
| Checkjpegformat | `4119` | Kontrollerar om skrivaren stöder en JPEG-bild. |
| Checkpngformat | `4120` | Kontrollerar om skrivaren stöder en PNG-bild. |
| GetPsFeaturesetting | `4121` | Får information om en specificerad funktionsinställning för en PostScript skrivardrivrutin. |
| MxdcEscape | `4122` | Gör det möjligt för program att skriva dokument till en fil eller till en skrivare i formatet XML Paper Specification (XPS). |
| Spclpassthrough2 | `4568` | Gör det möjligt för applikationer att inkludera privata procedurer och andra godtyckliga data i dokument. |

### Se även

* namnutrymme [Aspose.Imaging.FileFormats.Wmf.Consts](../../aspose.imaging.fileformats.wmf.consts)
* hopsättning [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
