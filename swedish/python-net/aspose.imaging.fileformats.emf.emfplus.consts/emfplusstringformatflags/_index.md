---
title: "EmfPlusStringFormatFlags uppräkning"
type: docs
weight: 410
url: /sv/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusstringformatflags/
---

StringFormat‑flaggorna specificerar alternativ för grafisk textlayout, inklusive riktning, beskärning och teckensnittshantering. Dessa flaggor kan kombineras för att ange flera alternativ.

**Module:** [aspose.imaging.fileformats.emf.emfplus.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.consts.EmfPlusStringFormatFlags

## **Members**
| **Member name** | **Description** |
| :- | :- |
| STRING_FORMAT_BYPASS_GDI | Denna flagga MAY användas för att specificera en implementationsspecifik process för rendering av text. |
| STRING_FORMAT_DIRECTION_RIGHT_TO_LEFT | Om angivet, ska läsriktningen för strängen SHOULD vara från höger till vänster. För horisontell text innebär detta att tecken läses från höger till vänster. För vertikal text innebär detta att kolumner läses från höger till vänster.<br/>            Om rensad, ska horisontell eller vertikal text läsas från vänster till höger. |
| STRING_FORMAT_DIRECTION_VERTICAL | Om angivet, ska enskilda textrader SHOULD ritas vertikalt på displayen.<br/>            Om rensad, ska enskilda textrader SHOULD ritas horisontellt, med varje ny rad under den föregående. |
| STRING_FORMAT_DISPLAY_FORMAT_CONTROL | Om angivet, ska kontrolltecken SHOULD visas i utdata som representativa Unicode-glyfer. |
| STRING_FORMAT_LINE_LIMIT | Om angivet, ska hela textrader SHOULD skrivas ut och SHOULD NOT klippas av strängens layoutrektangel.<br/>            Om rensad, ska textlayouten SHOULD fortsätta tills alla rader har skrivits ut, eller tills ytterligare rader inte skulle vara synliga som ett resultat av klippning.<br/>            Denna flagga kan användas för att antingen förbjuda eller tillåta att en textrad delvis döljs av en layoutrektangel som inte är en multipel av radens höjd. För att all text ska vara synlig krävs en layoutrektangel minst lika hög som höjden på en rad. |
| STRING_FORMAT_MEASURE_TRAILING_SPACES | Om inställd, MÅSTE mellanslaget i slutet av varje rad inkluderas i mätningarna av stränglängd.<br/>            Om avaktiverad, MÅSTE mellanslaget i slutet av varje rad exkluderas från mätningarna av stränglängd. |
| STRING_FORMAT_NO_CLIP | Om inställd, bör text som sträcker sig utanför rektangeln för stränglayout visas.<br/>            Om avaktiverad, bör all text som sträcker sig utanför layoutrektangeln klippas. |
| STRING_FORMAT_NO_FIT_BLACK_BOX | Om inställd, MÅSTE delar av tecken tillåtas hänga utanför rektangeln för textlayout.<br/>            Om avaktiverad, MÅSTE tecken som hänger utanför gränserna för textlayoutrektangeln omplaceras för att undvika överskjutning.<br/>            En kursiv, \"f\" är ett exempel på ett tecken som kan ha hängande delar. |
| STRING_FORMAT_NO_FONT_FALLBACK | Om inställd, bör ett alternativt teckensnitt användas för tecken som inte stöds i det begärda teckensnittet.<br/>            Om avaktiverad, bör ett tecken som saknas i det begärda teckensnittet visas som ett \"font missing\"-tecken, vilket KAN vara en öppen ruta. |
| STRING_FORMAT_NO_WRAP | Om inställd, MÅSTE en sträng som sträcker sig förbi slutet av textlayoutrektangeln INTE radbrytas till nästa rad.<br/>            Om avaktiverad, MÅSTE en sträng som sträcker sig förbi slutet av textlayoutrektangeln brytas vid den sista ordgränsen inom den avgränsande rektangeln, och återstoden av strängen MÅSTE radbrytas till nästa rad. |
