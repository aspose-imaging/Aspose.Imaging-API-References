---
title: "WmfMetafileEscapes"
second_title: "Aspose.Imaging för Java API-referens"
description: "MetafileEscapes‑enumerationen specificerar skrivardrivrutinens funktionalitet som kanske inte är direkt åtkomlig via WMF‑poster definierade i RecordType‑enumerationen avsnitt 2.1.1.1."
type: docs
weight: 24
url: /sv/java/com.aspose.imaging.fileformats.wmf.consts/wmfmetafileescapes/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class WmfMetafileEscapes extends System.Enum
```

MetafileEscapes‑enumerationen specificerar skrivardrivrutinens funktionalitet som kanske inte är direkt tillgänglig via WMF‑poster definierade i RecordType‑enumerationen (avsnitt 2.1.1.1).
## Fält

| Fält | Beskrivning |
| --- | --- |
| [Newframe](#Newframe) | Meddelar skrivardrivrutinen att programmet har avslutat skrivning till en sida. |
| [Abortdoc](#Abortdoc) | Stoppar bearbetning av det aktuella dokumentet. |
| [Nextband](#Nextband) | Meddelar skrivardrivrutinen att programmet har avslutat skrivning till ett band. |
| [Setcolortable](#Setcolortable) | Ställer in färgtabellvärden. |
| [Getcolortable](#Getcolortable) | Hämtar färgtabellvärden. |
| [Flushout](#Flushout) | Gör så att all väntande utskrift spolas till utskriftsenheten. |
| [Draftmode](#Draftmode) | Indikerar att skrivardrivrutinen BÖR skriva endast text och ingen grafik. |
| [Queryescsupport](#Queryescsupport) | Frågar en skrivardrivrutin för att avgöra om en specifik escape‑funktion stöds på den utskriftsenhet den styr. |
| [Setabortproc](#Setabortproc) | Ställer in den programdefinierade funktionen som möjliggör att ett utskriftsjobb kan avbrytas under utskrift. |
| [Startdoc](#Startdoc) | Meddelar skrivardrivrutinen att ett nytt utskriftsjobb startas. |
| [Enddoc](#Enddoc) | Meddelar skrivardrivrutinen att det aktuella utskriftsjobbet avslutas. |
| [Getphyspagesize](#Getphyspagesize) | Hämtar den fysiska sidstorleken som för närvarande är vald på en utskriftsenhet. |
| [Getprintingoffset](#Getprintingoffset) | Hämtar förskjutningen från det övre vänstra hörnet på den fysiska sidan där den faktiska utskriften eller ritningen börjar. |
| [Getscalingfactor](#Getscalingfactor) | Hämtar skalningsfaktorerna för x‑axeln och y‑axeln på en skrivare. |
| [MetaEscapeEnhancedMetafile](#MetaEscapeEnhancedMetafile) | Används för att bädda in en metafil i förbättrat format (EMF) i en WMF‑metafil. |
| [Setpenwidth](#Setpenwidth) | Ställer in bredden på en penna i pixlar. |
| [Setcopycount](#Setcopycount) | Ställer in antalet kopior. |
| [Setpapersource](#Setpapersource) | Ställer in källan, till exempel en specifik pappersfack eller behållare på en skrivare, för utskriftsformulär. |
| [Passthrough](#Passthrough) | Denna post vidarebefordrar godtyckliga data. |
| [Gettechnology](#Gettechnology) | Hämtar information om grafikteknik som stöds på en enhet. |
| [Setlinecap](#Setlinecap) | Specificerar linjeteckningsläget som ska användas vid utskrift till en enhet. |
| [Setlinejoin](#Setlinejoin) | Specificerar linjesammanslagningsläget som ska användas vid utskrift till en enhet. |
| [Setmiterlimit](#Setmiterlimit) | Ställer in gränsen för längden på snedställda fogar som ska användas vid utskrift till en enhet. |
| [Bandinfo](#Bandinfo) | Hämtar eller anger inställningar som rör bandning på en enhet, såsom antalet band. |
| [Drawpatternrect](#Drawpatternrect) | Ritar en rektangel med ett definierat mönster. |
| [Getvectorpensize](#Getvectorpensize) | Hämtar den fysiska pennstorleken som för närvarande är definierad på en enhet. |
| [Getvectorbrushsize](#Getvectorbrushsize) | Hämtar den fysiska penselstorleken som för närvarande är definierad på en enhet. |
| [Enableduplex](#Enableduplex) | Aktiverar eller inaktiverar dubbelsidig (duplex) utskrift på en enhet. |
| [Getsetpaperbins](#Getsetpaperbins) | Hämtar eller anger källan till utskriftsformulär på en enhet. |
| [Getsetprintorient](#Getsetprintorient) | Hämtar eller anger papperets orientering på en enhet. |
| [Enumpaperbins](#Enumpaperbins) | Hämtar information om källorna till olika formulär på en utskriftsenhet. |
| [Setdibscaling](#Setdibscaling) | Anger skalning av enhetsoberoende bitmappar (DIBs). |
| [Epsprinting](#Epsprinting) | Anger början och slutet på ett inkapslat PostScript (EPS)-avsnitt. |
| [Enumpapermetrics](#Enumpapermetrics) | Frågar en skrivardrivrutin om papperdimensioner och annan formulärdata. |
| [Getsetpapermetrics](#Getsetpapermetrics) | Hämtar eller anger papperdimensioner och annan formulärdata på en utskriftsenhet. |
| [PostscriptData](#PostscriptData) | Skickar godtycklig PostScript-data till en utskriftsenhet. |
| [PostscriptIgnore](#PostscriptIgnore) | Meddelar en utskriftsenhet att ignorera PostScript-data. |
| [Getdeviceunits](#Getdeviceunits) | Hämtar enhetens enheter som för närvarande är konfigurerade på en utskriftsenhet. |
| [Getextendedtextmetrics](#Getextendedtextmetrics) | Hämtar utökade textmått som för närvarande är konfigurerade på en utskriftsenhet. |
| [Getpairkerntable](#Getpairkerntable) | Hämtar teckensnittets kerningtabell som för närvarande är definierad på en utskriftsenhet. |
| [Exttextout](#Exttextout) | Ritar text med det för närvarande valda teckensnittet, bakgrundsfärgen och textfärgen. |
| [Getfacename](#Getfacename) | Hämtar teckensnittets namn som för närvarande är konfigurerat på en enhet. |
| [Downloadface](#Downloadface) | Ställer in teckensnittets namn på en enhet. |
| [MetafileDriver](#MetafileDriver) | Frågar en skrivardrivrutin om stöd för metafiler på en utskriftsenhet. |
| [Querydibsupport](#Querydibsupport) | Frågar skrivardrivrutinen om dess stöd för DIBs på en utskriftsenhet. |
| [BeginPath](#BeginPath) | Öppnar en bana. |
| [ClipToPath](#ClipToPath) | Definierar ett urklippsområde som begränsas av en bana. |
| [EndPath](#EndPath) | Avslutar en bana. |
| [OpenChannel](#OpenChannel) | Samma som STARTDOC specificerad med ett NULL-dokument och utdatafilnamn, data i rått läge och en typ på noll. |
| [Downloadheader](#Downloadheader) | Instruerar skrivardrivrutinen att ladda ner uppsättningar av PostScript‑procedurer. |
| [CloseChannel](#CloseChannel) | Samma som ENDDOC. |
| [PostscriptPassthrough](#PostscriptPassthrough) | Skickar godtycklig data direkt till en skrivardrivrutin, som förväntas bearbeta denna data endast när den är i PostScript‑läge. |
| [EncapsulatedPostscript](#EncapsulatedPostscript) | Skickar godtycklig data direkt till skrivardrivrutinen. |
| [PostscriptIdentify](#PostscriptIdentify) | Ställer in skrivardrivrutinen till antingen PostScript‑ eller GDI‑läge. |
| [PostscriptInjection](#PostscriptInjection) | Infogar ett block med rådata i en PostScript‑ström. |
| [Checkjpegformat](#Checkjpegformat) | Kontrollerar om skrivaren stöder en JPEG‑bild. |
| [Checkpngformat](#Checkpngformat) | Kontrollerar om skrivaren stöder en PNG‑bild. |
| [GetPsFeaturesetting](#GetPsFeaturesetting) | Hämtar information om en specificerad funktionsinställning för en PostScript‑skrivardrivrutin. |
| [MxdcEscape](#MxdcEscape) | Gör det möjligt för applikationer att skriva dokument till en fil eller till en skrivare i XML Paper Specification (XPS)-format. |
| [Spclpassthrough2](#Spclpassthrough2) | Gör det möjligt för applikationer att inkludera privata procedurer och annan godtycklig data i dokument. |
### Newframe {#Newframe}
```
public static final int Newframe
```


Meddelar skrivardrivrutinen att programmet har avslutat skrivning till en sida.

### Abortdoc {#Abortdoc}
```
public static final int Abortdoc
```


Stoppar bearbetning av det aktuella dokumentet.

### Nextband {#Nextband}
```
public static final int Nextband
```


Meddelar skrivardrivrutinen att programmet har avslutat skrivning till ett band.

### Setcolortable {#Setcolortable}
```
public static final int Setcolortable
```


Ställer in färgtabellvärden.

### Getcolortable {#Getcolortable}
```
public static final int Getcolortable
```


Hämtar färgtabellvärden.

### Flushout {#Flushout}
```
public static final int Flushout
```


Gör så att all väntande utskrift spolas till utskriftsenheten.

### Draftmode {#Draftmode}
```
public static final int Draftmode
```


Indikerar att skrivardrivrutinen BÖR skriva endast text och ingen grafik.

### Queryescsupport {#Queryescsupport}
```
public static final int Queryescsupport
```


Frågar en skrivardrivrutin för att avgöra om en specifik escape‑funktion stöds på den utskriftsenhet den styr.

### Setabortproc {#Setabortproc}
```
public static final int Setabortproc
```


Ställer in den programdefinierade funktionen som möjliggör att ett utskriftsjobb kan avbrytas under utskrift.

### Startdoc {#Startdoc}
```
public static final int Startdoc
```


Meddelar skrivardrivrutinen att ett nytt utskriftsjobb startas.

### Enddoc {#Enddoc}
```
public static final int Enddoc
```


Meddelar skrivardrivrutinen att det aktuella utskriftsjobbet avslutas.

### Getphyspagesize {#Getphyspagesize}
```
public static final int Getphyspagesize
```


Hämtar den fysiska sidstorleken som för närvarande är vald på en utskriftsenhet.

### Getprintingoffset {#Getprintingoffset}
```
public static final int Getprintingoffset
```


Hämtar förskjutningen från det övre vänstra hörnet på den fysiska sidan där den faktiska utskriften eller ritningen börjar.

### Getscalingfactor {#Getscalingfactor}
```
public static final int Getscalingfactor
```


Hämtar skalningsfaktorerna för x‑axeln och y‑axeln på en skrivare.

### MetaEscapeEnhancedMetafile {#MetaEscapeEnhancedMetafile}
```
public static final int MetaEscapeEnhancedMetafile
```


Används för att bädda in en metafil i förbättrat format (EMF) i en WMF‑metafil.

### Setpenwidth {#Setpenwidth}
```
public static final int Setpenwidth
```


Ställer in bredden på en penna i pixlar.

### Setcopycount {#Setcopycount}
```
public static final int Setcopycount
```


Ställer in antalet kopior.

### Setpapersource {#Setpapersource}
```
public static final int Setpapersource
```


Ställer in källan, till exempel en specifik pappersfack eller behållare på en skrivare, för utskriftsformulär.

### Passthrough {#Passthrough}
```
public static final int Passthrough
```


Denna post vidarebefordrar godtyckliga data.

### Gettechnology {#Gettechnology}
```
public static final int Gettechnology
```


Hämtar information om grafikteknik som stöds på en enhet.

### Setlinecap {#Setlinecap}
```
public static final int Setlinecap
```


Specificerar linjeteckningsläget som ska användas vid utskrift till en enhet.

### Setlinejoin {#Setlinejoin}
```
public static final int Setlinejoin
```


Specificerar linjesammanslagningsläget som ska användas vid utskrift till en enhet.

### Setmiterlimit {#Setmiterlimit}
```
public static final int Setmiterlimit
```


Ställer in gränsen för längden på snedställda fogar som ska användas vid utskrift till en enhet.

### Bandinfo {#Bandinfo}
```
public static final int Bandinfo
```


Hämtar eller anger inställningar som rör bandning på en enhet, såsom antalet band.

### Drawpatternrect {#Drawpatternrect}
```
public static final int Drawpatternrect
```


Ritar en rektangel med ett definierat mönster.

### Getvectorpensize {#Getvectorpensize}
```
public static final int Getvectorpensize
```


Hämtar den fysiska pennstorleken som för närvarande är definierad på en enhet.

### Getvectorbrushsize {#Getvectorbrushsize}
```
public static final int Getvectorbrushsize
```


Hämtar den fysiska penselstorleken som för närvarande är definierad på en enhet.

### Enableduplex {#Enableduplex}
```
public static final int Enableduplex
```


Aktiverar eller inaktiverar dubbelsidig (duplex) utskrift på en enhet.

### Getsetpaperbins {#Getsetpaperbins}
```
public static final int Getsetpaperbins
```


Hämtar eller anger källan till utskriftsformulär på en enhet.

### Getsetprintorient {#Getsetprintorient}
```
public static final int Getsetprintorient
```


Hämtar eller anger papperets orientering på en enhet.

### Enumpaperbins {#Enumpaperbins}
```
public static final int Enumpaperbins
```


Hämtar information om källorna till olika formulär på en utskriftsenhet.

### Setdibscaling {#Setdibscaling}
```
public static final int Setdibscaling
```


Anger skalning av enhetsoberoende bitmappar (DIBs).

### Epsprinting {#Epsprinting}
```
public static final int Epsprinting
```


Anger början och slutet på ett inkapslat PostScript (EPS)-avsnitt.

### Enumpapermetrics {#Enumpapermetrics}
```
public static final int Enumpapermetrics
```


Frågar en skrivardrivrutin om papperdimensioner och annan formulärdata.

### Getsetpapermetrics {#Getsetpapermetrics}
```
public static final int Getsetpapermetrics
```


Hämtar eller anger papperdimensioner och annan formulärdata på en utskriftsenhet.

### PostscriptData {#PostscriptData}
```
public static final int PostscriptData
```


Skickar godtycklig PostScript-data till en utskriftsenhet.

### PostscriptIgnore {#PostscriptIgnore}
```
public static final int PostscriptIgnore
```


Meddelar en utskriftsenhet att ignorera PostScript-data.

### Getdeviceunits {#Getdeviceunits}
```
public static final int Getdeviceunits
```


Hämtar enhetens enheter som för närvarande är konfigurerade på en utskriftsenhet.

### Getextendedtextmetrics {#Getextendedtextmetrics}
```
public static final int Getextendedtextmetrics
```


Hämtar utökade textmått som för närvarande är konfigurerade på en utskriftsenhet.

### Getpairkerntable {#Getpairkerntable}
```
public static final int Getpairkerntable
```


Hämtar teckensnittets kerningtabell som för närvarande är definierad på en utskriftsenhet.

### Exttextout {#Exttextout}
```
public static final int Exttextout
```


Ritar text med det för närvarande valda teckensnittet, bakgrundsfärgen och textfärgen.

### Getfacename {#Getfacename}
```
public static final int Getfacename
```


Hämtar teckensnittets namn som för närvarande är konfigurerat på en enhet.

### Downloadface {#Downloadface}
```
public static final int Downloadface
```


Ställer in teckensnittets namn på en enhet.

### MetafileDriver {#MetafileDriver}
```
public static final int MetafileDriver
```


Frågar en skrivardrivrutin om stöd för metafiler på en utskriftsenhet.

### Querydibsupport {#Querydibsupport}
```
public static final int Querydibsupport
```


Frågar skrivardrivrutinen om dess stöd för DIBs på en utskriftsenhet.

### BeginPath {#BeginPath}
```
public static final int BeginPath
```


Öppnar en bana.

### ClipToPath {#ClipToPath}
```
public static final int ClipToPath
```


Definierar ett urklippsområde som begränsas av en bana. Indatan MÅSTE vara en 16‑bit kvantitet som definierar åtgärden som ska utföras.

### EndPath {#EndPath}
```
public static final int EndPath
```


Avslutar en bana.

### OpenChannel {#OpenChannel}
```
public static final int OpenChannel
```


Samma som STARTDOC specificerad med ett NULL-dokument och utdatafilnamn, data i rått läge och en typ på noll.

### Downloadheader {#Downloadheader}
```
public static final int Downloadheader
```


Instruerar skrivardrivrutinen att ladda ner uppsättningar av PostScript‑procedurer.

### CloseChannel {#CloseChannel}
```
public static final int CloseChannel
```


Samma som ENDDOC. Se OPEN\_CHANNEL.

### PostscriptPassthrough {#PostscriptPassthrough}
```
public static final int PostscriptPassthrough
```


Skickar godtycklig data direkt till en skrivardrivrutin, som förväntas bearbeta denna data endast när den är i PostScript‑läge. [PostscriptIdentify](../../com.aspose.imaging.fileformats.wmf.consts/wmfmetafileescapes\#PostscriptIdentify).

### EncapsulatedPostscript {#EncapsulatedPostscript}
```
public static final int EncapsulatedPostscript
```


Skickar godtycklig data direkt till skrivardrivrutinen.

### PostscriptIdentify {#PostscriptIdentify}
```
public static final int PostscriptIdentify
```


Ställer in skrivardrivrutinen till antingen PostScript‑ eller GDI‑läge.

### PostscriptInjection {#PostscriptInjection}
```
public static final int PostscriptInjection
```


Infogar ett block med rådata i en PostScript‑ström. Indatan MÅSTE vara en 32‑bit kvantitet som anger antalet byte att injicera, en 16‑bit kvantitet som anger injektionspunkten och en 16‑bit kvantitet som anger sidnumret, följt av de byte som ska injiceras.

### Checkjpegformat {#Checkjpegformat}
```
public static final int Checkjpegformat
```


Kontrollerar om skrivaren stöder en JPEG‑bild.

### Checkpngformat {#Checkpngformat}
```
public static final int Checkpngformat
```


Kontrollerar om skrivaren stöder en PNG‑bild.

### GetPsFeaturesetting {#GetPsFeaturesetting}
```
public static final int GetPsFeaturesetting
```


Hämtar information om en specificerad funktionsinställning för en PostScript‑skrivardrivrutin.

### MxdcEscape {#MxdcEscape}
```
public static final int MxdcEscape
```


Gör det möjligt för applikationer att skriva dokument till en fil eller till en skrivare i XML Paper Specification (XPS)-format.

### Spclpassthrough2 {#Spclpassthrough2}
```
public static final int Spclpassthrough2
```


Gör det möjligt för applikationer att inkludera privata procedurer och annan godtycklig data i dokument.

