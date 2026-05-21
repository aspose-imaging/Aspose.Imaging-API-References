---
title: "StringFormatFlags"
second_title: "Aspose.Imaging för Java API-referens"
description: "Anger display- och layoutinformation för textsträngar."
type: docs
weight: 113
url: /sv/java/com.aspose.imaging/stringformatflags/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class StringFormatFlags extends System.Enum
```

Anger display- och layoutinformation för textsträngar.
## Fält

| Fält | Beskrivning |
| --- | --- |
| [DirectionRightToLeft](#DirectionRightToLeft) | Text visas från höger till vänster. |
| [DirectionVertical](#DirectionVertical) | Text är vertikalt justerad. |
| [FitBlackBox](#FitBlackBox) | Delar av tecken får hänga över strängens layoutrektangel. |
| [DisplayFormatControl](#DisplayFormatControl) | Kontrolltecken såsom vänster-till-höger-märket visas i utdata med ett representativt tecken. |
| [NoFontFallback](#NoFontFallback) | Reserv till alternativa teckensnitt för tecken som inte stöds i det begärda teckensnittet är inaktiverad. |
| [MeasureTrailingSpaces](#MeasureTrailingSpaces) | Inkluderar efterföljande blanksteg i slutet av varje rad. |
| [NoWrap](#NoWrap) | Radbrytning mellan rader vid formatering inom en rektangel är inaktiverad. |
| [LineLimit](#LineLimit) | Endast hela rader läggs ut i formateringsrektangeln. |
| [NoClip](#NoClip) | Hängande delar av teckenformer och oinsvept text som når utanför formateringsrektangeln får visas. |
| [ExactAlignment](#ExactAlignment) | Den exakta justeringen, korrekt utfyllnad GDI+ |
### DirectionRightToLeft {#DirectionRightToLeft}
```
public static final int DirectionRightToLeft
```


Text visas från höger till vänster.

### DirectionVertical {#DirectionVertical}
```
public static final int DirectionVertical
```


Text är vertikalt justerad.

### FitBlackBox {#FitBlackBox}
```
public static final int FitBlackBox
```


Delar av tecken får hänga över strängens layoutrektangel. Som standard omplaceras tecken för att undvika någon överhängning.

### DisplayFormatControl {#DisplayFormatControl}
```
public static final int DisplayFormatControl
```


Kontrolltecken såsom vänster-till-höger-märket visas i utdata med ett representativt tecken.

### NoFontFallback {#NoFontFallback}
```
public static final int NoFontFallback
```


Reserv till alternativa teckensnitt för tecken som inte stöds i det begärda teckensnittet är inaktiverad. Eventuella saknade tecken visas med teckensnittets saknade tecken, vanligtvis en öppen ruta.

### MeasureTrailingSpaces {#MeasureTrailingSpaces}
```
public static final int MeasureTrailingSpaces
```


Inkluderar efterföljande blanksteg i slutet av varje rad. Som standard exkluderar rektangeln som returneras av MeasureString‑metoden blanksteget i slutet av varje rad. Ställ in detta flagg för att inkludera det blanksteget i mätningen.

### NoWrap {#NoWrap}
```
public static final int NoWrap
```


Radbrytning mellan rader vid formatering inom en rektangel är inaktiverad. Detta flagg antas när en punkt skickas istället för en rektangel, eller när den angivna rektangeln har en linjelängd på noll.

### LineLimit {#LineLimit}
```
public static final int LineLimit
```


Endast hela rader läggs ut i formateringsrektangeln. Som standard fortsätter layouten tills slutet av texten, eller tills inga fler rader är synliga på grund av beskärning, vilket som kommer först. Observera att standardinställningarna tillåter den sista raden att delvis döljas av en formateringsrektangel som inte är ett helt multipel av radhöjden. För att säkerställa att endast hela rader syns, ange detta värde och var noga med att tillhandahålla en formateringsrektangel som är minst lika hög som höjden på en rad.

### NoClip {#NoClip}
```
public static final int NoClip
```


Hängande delar av teckenformer och oinsvept text som når utanför formateringsrektangeln får visas. Som standard klipps all text och teckenformdelar som når utanför formateringsrektangeln.

### ExactAlignment {#ExactAlignment}
```
public static final int ExactAlignment
```


Den exakta justeringen, korrekt utfyllnad GDI+

