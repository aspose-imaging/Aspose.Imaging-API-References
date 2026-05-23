---
title: "StringFormatFlags uppräkning"
type: docs
weight: 11220
url: /sv/python-net/aspose.imaging/stringformatflags/
---

Anger visnings- och layoutinformation för textsträngar.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.StringFormatFlags

## **Members**
| **Member name** | **Description** |
| :- | :- |
| DIRECTION_RIGHT_TO_LEFT | Text visas från höger till vänster. |
| DIRECTION_VERTICAL | Texten är vertikalt justerad. |
| DISPLAY_FORMAT_CONTROL | Kontrolltecken såsom vänster-till-höger-märket visas i utdata med en representativ glyf. |
| EXACT_ALIGNMENT | Den exakta justeringen, korrekt utfyllnad GDI+ |
| FIT_BLACK_BOX | Delar av tecken får hänga över strängens layoutrektangel. Som standard omplaceras tecken för att undvika någon överhäng. |
| LINE_LIMIT | Endast hela rader läggs ut i formateringsrektangeln. Som standard fortsätter layouten tills slutet av texten, eller tills inga fler rader är synliga som ett resultat av beskärning, beroende på vad som inträffar först.<br/>            Observera att standardinställningarna tillåter den sista raden att delvis döljas av en formateringsrektangel som inte är ett helt multipel av radhöjden. För att säkerställa att endast hela rader visas,<br/>            ange detta värde och var noga med att tillhandahålla en formateringsrektangel som är minst lika hög som höjden på en rad. |
| MEASURE_TRAILING_SPACES | Inkluderar efterföljande blanksteg i slutet av varje rad. Som standard exkluderar rektangeln som returneras av MeasureString‑metoden blanksteget i slutet av varje rad. Ställ in detta flagga för att inkludera det blanksteget i mätningen. |
| NO_CLIP | Överhängande delar av glyfer och oinsvept text som når utanför formateringsrektangeln får visas. Som standard klipps all text och glyfd delar som når utanför formateringsrektangeln. |
| NO_FONT_FALLBACK | Reserv till alternativa teckensnitt för tecken som inte stöds i det begärda teckensnittet är inaktiverad. Eventuella saknade tecken visas med teckensnittets saknade glyf, vanligtvis en öppen ruta. |
| NO_WRAP | Textbrytning mellan rader när formatering sker inom en rektangel är inaktiverad. Detta flagga antas när en punkt skickas istället för en rektangel, eller när den angivna rektangeln har en radlängd på noll. |
