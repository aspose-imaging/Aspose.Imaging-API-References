---
title: "WmfMetafileEscapes Enumeration"
type: docs
weight: 150
url: /sv/python-net/aspose.imaging.fileformats.wmf.consts/wmfmetafileescapes/
---

MetafileEscapes‑enumerationen specificerar skrivardrivrutinens funktionalitet som kanske inte är<br/>                direkt åtkomlig via WMF‑poster definierade i RecordType‑enumerationen (avsnitt 2.1.1.1).

**Module:** [aspose.imaging.fileformats.wmf.consts](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/)

**Full Name:** aspose.imaging.fileformats.wmf.consts.WmfMetafileEscapes

## **Members**
| **Member name** | **Description** |
| :- | :- |
| ABORTDOC | Stoppar bearbetning av det aktuella dokumentet. |
| BANDINFO | Hämtar eller anger inställningar som rör bandning på en enhet, såsom<br/>                antalet band. |
| BEGIN_PATH | Öppnar en sökväg. |
| CHECKJPEGFORMAT | Kontrollerar om skrivaren stöder en JPEG-bild. |
| CHECKPNGFORMAT | Kontrollerar om skrivaren stöder en PNG-bild. |
| CLIP_TO_PATH | Definierar ett klippområde som begränsas av en sökväg. Indatan MÅSTE vara en 16-bitars<br/>                kvantitet som definierar den åtgärd som ska vidtas. |
| CLOSE_CHANNEL | Samma som ENDDOC. Se OPEN_CHANNEL. |
| DOWNLOADFACE | Ställer in teckensnittets namn på en enhet. |
| DOWNLOADHEADER | Instruerar skrivardrivrutinen att ladda ner uppsättningar av PostScript-procedurer. |
| DRAFTMODE | Indikerar att skrivardrivrutinen SHOULD skriva ut endast text och ingen grafik. |
| DRAWPATTERNRECT | Ritar en rektangel med ett definierat mönster. |
| ENABLEDUPLEX | Aktiverar eller inaktiverar dubbelsidig (duplex) utskrift på en enhet. |
| ENCAPSULATED_POSTSCRIPT | Skickar godtycklig data direkt till skrivardrivrutinen. |
| ENDDOC | Informerar skrivardrivrutinen om att det aktuella utskriftsjobbet avslutas. |
| END_PATH | Avslutar en bana. |
| ENUMPAPERBINS | Hämtar information om källorna till olika formulär på en<br/>                utskriftsenhet. |
| ENUMPAPERMETRICS | Begär information från skrivardrivrutinen om papperdimensioner och annan formulärdata. |
| EPSPRINTING | Indikerar början och slutet på ett kapslat PostScript (EPS)-avsnitt. |
| EXTTEXTOUT | Ritar text med det för närvarande valda teckensnittet, bakgrundsfärgen och textfärgen. |
| FLUSHOUT | Orsakar att all väntande utdata spolas till utmatningsenheten. |
| GETCOLORTABLE | Hämtar färgtabellvärden. |
| GETDEVICEUNITS | Hämtar enhetens enheter som för närvarande är konfigurerade på en utskriftsenhet. |
| GETEXTENDEDTEXTMETRICS | Hämtar utökade textmått som för närvarande är konfigurerade på en utskrift<br/>                enhet. |
| GETFACENAME | Hämtar teckensnittets namn som för närvarande är konfigurerat på en enhet. |
| GETPAIRKERNTABLE | Hämtar teckensnittets kerningtabell som för närvarande är definierad på en utskriftsenhet. |
| GETPHYSPAGESIZE | Hämtar den fysiska sidstorleken som för närvarande är vald på en utskriftsenhet. |
| GETPRINTINGOFFSET | Hämtar förskjutningen från det övre vänstra hörnet av den fysiska sidan<br/>                där den faktiska utskriften eller ritningen börjar. |
| GETSCALINGFACTOR | Hämtar skalningsfaktorerna för x-axeln och y-axeln på en skrivare. |
| GETSETPAPERBINS | Hämtar eller anger källan för utskriftsformulär på en enhet. |
| GETSETPAPERMETRICS | Hämtar eller anger pappersdimensioner och annan formulärdata på en<br/>                utskriftsenhet. |
| GETSETPRINTORIENT | Hämtar eller anger papperets orientering på en enhet. |
| GETTECHNOLOGY | Hämtar information om grafikteknik som stöds på en<br/>                enhet. |
| GETVECTORBRUSHSIZE | Hämtar den fysiska penselstorleken som för närvarande är definierad på en enhet. |
| GETVECTORPENSIZE | Hämtar den fysiska pennstorleken som för närvarande är definierad på en enhet. |
| GET_PS_FEATURESETTING | Hämtar information om en specificerad funktionsinställning för en PostScript<br/>                skrivardrivrutin. |
| METAFILE_DRIVER | Frågar en skrivardrivrutin om stöd för metafiler på en utskrifts<br/>                enhet. |
| META_ESCAPE_ENHANCED_METAFILE | Används för att bädda in ett förbättrat metafilformat (EMF)<br/>                metafil i en WMF-metafil. |
| MXDC_ESCAPE | Gör det möjligt för program att skriva dokument till en fil eller till en skrivare i XML Paper<br/>                Specification (XPS)-format. |
| NEWFRAME | Meddelar skrivardrivrutinen att programmet har slutfört skrivning till en sida. |
| NEXTBAND | Meddelar skrivardrivrutinen att programmet har slutfört skrivning till ett band. |
| OPEN_CHANNEL | Samma som STARTDOC specificerad med ett NULL-dokument och utskrifts<br/>                filnamn, data i råläge och en typ av noll. |
| PASSTHROUGH | Denna post passerar godtycklig data. |
| POSTSCRIPT_DATA | Skickar godtycklig PostScript-data till en utskriftsenhet. |
| POSTSCRIPT_IDENTIFY | Ställer in skrivardrivrutinen till antingen PostScript- eller GDI-läge. |
| POSTSCRIPT_IGNORE | Meddelar en utskriftsenhet att ignorera PostScript-data. |
| POSTSCRIPT_INJECTION | Infogar ett block med rådata i en PostScript-ström. Inmatningen<br/>                MÅSTE vara en 32-bitars kvantitet som specificerar antalet byte att injicera, en 16-bitars kvantitet<br/>                som specificerar injektionspunkten, och en 16-bitars kvantitet som specificerar sidnumret, följt av<br/>                de byte som ska injiceras. |
| POSTSCRIPT_PASSTHROUGH | Skickar godtycklig data direkt till en skrivardrivrutin, som<br/>                förväntas bearbeta denna data endast när den är i PostScript-läge. [WmfMetafileEscapes.POSTSCRIPT_IDENTIFY](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfmetafileescapes/). |
| QUERYDIBSUPPORT | Frågar skrivardrivrutinen om dess stöd för DIB:er på en utskriftsenhet. |
| QUERYESCSUPPORT | Frågar en skrivardrivrutin för att avgöra om en specifik escape-funktion<br/>                stöds på den utskriftsenhet den driver. |
| SETABORTPROC | Ställer in den applikationsdefinierade funktionen som möjliggör att ett utskriftsjobb kan avbrytas<br/>                under utskrift. |
| SETCOLORTABLE | Ställer in färgtabellvärden. |
| SETCOPYCOUNT | Ställer in antalet kopior. |
| SETDIBSCALING | Specificerar skalning av enhetsoberoende bitmaps (DIB:er). |
| SETLINECAP | Specificerar linjeteckningsläget som ska användas vid utskrift till en enhet. |
| SETLINEJOIN | Specificerar linjesammanfogningsläget som ska användas vid utskrift till en enhet. |
| SETMITERLIMIT | Ställer in gränsen för längden på snedställda fogar som ska användas vid utskrift till en enhet. |
| SETPAPERSOURCE | Ställer in källan, till exempel en specifik pappersfack eller behållare på en skrivare, för<br/>                utskriftsformulär. |
| SETPENWIDTH | Ställer in bredden på en penna i pixlar. |
| SPCLPASSTHROUGH2 | Gör det möjligt för applikationer att inkludera privata procedurer och annan godtycklig<br/>                data i dokument. |
| STARTDOC | Meddelar skrivardrivrutinen att ett nytt utskriftsjobb startar. |
