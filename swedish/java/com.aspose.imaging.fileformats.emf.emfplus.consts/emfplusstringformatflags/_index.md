---
title: "EmfPlusStringFormatFlags"
second_title: "Aspose.Imaging för Java API-referens"
description: "StringFormat-flaggorna specificerar alternativ för grafiktextlayout inklusive riktning, beskärning och teckensnittshantering."
type: docs
weight: 50
url: /sv/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfplusstringformatflags/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusStringFormatFlags extends System.Enum
```

StringFormat-flaggorna specificerar alternativ för grafiktextlayout, inklusive riktning, beskärning och teckensnittshantering. Dessa flaggor kan kombineras för att specificera flera alternativ.
## Fält

| Fält | Beskrivning |
| --- | --- |
| [StringFormatDirectionRightToLeft](#StringFormatDirectionRightToLeft) | Om den är inställd ska läsriktningen för strängen vara från höger till vänster. |
| [StringFormatDirectionVertical](#StringFormatDirectionVertical) | Om den är inställd ska enskilda textrader ritas vertikalt på displayen. |
| [StringFormatNoFitBlackBox](#StringFormatNoFitBlackBox) | Om den är inställd måste delar av tecken tillåtas att sticka utanför textlayoutens rektangel. |
| [StringFormatDisplayFormatControl](#StringFormatDisplayFormatControl) | Om den är inställd ska kontrolltecken visas i utdata som representativa Unicode-glyfer. |
| [StringFormatNoFontFallback](#StringFormatNoFontFallback) | Om den är inställd ska ett alternativt teckensnitt användas för tecken som inte stöds av det begärda teckensnittet. |
| [StringFormatMeasureTrailingSpaces](#StringFormatMeasureTrailingSpaces) | Om den är inställd måste mellanslaget i slutet av varje rad inkluderas i mätningarna av stränglängden. |
| [StringFormatNoWrap](#StringFormatNoWrap) | Om den är inställd får en sträng som sträcker sig förbi slutet av textlayoutens rektangel INTE radbrytas till nästa rad. |
| [StringFormatLineLimit](#StringFormatLineLimit) | Om den är inställd ska hela textrader skrivas ut och får INTE klippas av strängens layoutrektangel. |
| [StringFormatNoClip](#StringFormatNoClip) | Om den är inställd ska text som sträcker sig utanför strängens layoutrektangel tillåtas att visas. |
| [StringFormatBypassGdi](#StringFormatBypassGdi) | Denna flagga kan användas för att specificera en implementation-specifik process för rendering av text. |
### StringFormatDirectionRightToLeft {#StringFormatDirectionRightToLeft}
```
public static final long StringFormatDirectionRightToLeft
```


Om den är inställd ska läsriktningen för strängen vara från höger till vänster. För horisontell text betyder det att tecken läses från höger till vänster. För vertikal text betyder det att kolumner läses från höger till vänster. Om den är avaktiverad ska horisontell eller vertikal text läsas från vänster till höger.

--------------------

Grafiktextlayout specificeras av [EmfPlusStringFormat](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat)-objekt

### StringFormatDirectionVertical {#StringFormatDirectionVertical}
```
public static final long StringFormatDirectionVertical
```


Om den är inställd ska enskilda textrader ritas vertikalt på displayen. Om den är avaktiverad ska enskilda textrader ritas horisontellt, med varje ny rad under den föregående.

### StringFormatNoFitBlackBox {#StringFormatNoFitBlackBox}
```
public static final long StringFormatNoFitBlackBox
```


Om den är inställd måste delar av tecken tillåtas att sticka utanför textlayoutens rektangel. Om den är avaktiverad måste tecken som sticker utanför textlayoutens gränser omplaceras för att undvika utskjutning. En kursiv "f" är ett exempel på ett tecken som kan ha utskjutande delar.

### StringFormatDisplayFormatControl {#StringFormatDisplayFormatControl}
```
public static final long StringFormatDisplayFormatControl
```


Om den är inställd ska kontrolltecken visas i utdata som representativa Unicode-glyfer.

### StringFormatNoFontFallback {#StringFormatNoFontFallback}
```
public static final long StringFormatNoFontFallback
```


Om den är inställd ska ett alternativt teckensnitt användas för tecken som inte stöds av det begärda teckensnittet. Om den är avaktiverad ska ett tecken som saknas i det begärda teckensnittet visas som ett "font missing"-tecken, vilket kan vara en öppen ruta.

### StringFormatMeasureTrailingSpaces {#StringFormatMeasureTrailingSpaces}
```
public static final long StringFormatMeasureTrailingSpaces
```


Om den är inställd måste mellanslaget i slutet av varje rad inkluderas i mätningarna av stränglängden. Om den är avaktiverad måste mellanslaget i slutet av varje rad exkluderas från mätningarna av stränglängden.

### StringFormatNoWrap {#StringFormatNoWrap}
```
public static final long StringFormatNoWrap
```


Om den är inställd får en sträng som sträcker sig förbi slutet av textlayoutens rektangel INTE radbrytas till nästa rad. Om den är avaktiverad måste en sträng som sträcker sig förbi slutet av textlayoutens rektangel brytas vid den sista ordgränsen inom den begränsande rektangeln, och återstoden av strängen måste radbrytas till nästa rad.

### StringFormatLineLimit {#StringFormatLineLimit}
```
public static final long StringFormatLineLimit
```


Om den är inställd ska hela textrader skrivas ut och får INTE klippas av strängens layoutrektangel. Om den är avaktiverad ska textlayouten fortsätta tills alla rader har skrivits ut, eller tills ytterligare rader inte skulle vara synliga på grund av beskärning. Denna flagga kan användas för att antingen förbjuda eller tillåta att en textrad delvis döljs av en layoutrektangel som inte är en multipel av radens höjd. För att all text ska vara synlig krävs en layoutrektangel som är minst lika hög som en rad.

### StringFormatNoClip {#StringFormatNoClip}
```
public static final long StringFormatNoClip
```


Om den är inställd ska text som sträcker sig utanför strängens layoutrektangel tillåtas att visas. Om den är avaktiverad ska all text som sträcker sig utanför layoutrektangeln klippas.

### StringFormatBypassGdi {#StringFormatBypassGdi}
```
public static final long StringFormatBypassGdi
```


Denna flagga kan användas för att specificera en implementation-specifik process för rendering av text.

