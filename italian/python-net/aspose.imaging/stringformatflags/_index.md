---
title: "StringFormatFlags Enumerazione"
type: docs
weight: 11220
url: /it/python-net/aspose.imaging/stringformatflags/
---

Specifica le informazioni di visualizzazione e layout per le stringhe di testo.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.StringFormatFlags

## **Members**
| **Member name** | **Descrizione** |
| :- | :- |
| DIRECTION_RIGHT_TO_LEFT | Il testo è visualizzato da destra a sinistra. |
| DIRECTION_VERTICAL | Il testo è allineato verticalmente. |
| DISPLAY_FORMAT_CONTROL | I caratteri di controllo, come il segno da sinistra a destra, sono mostrati nell'output con un glifo rappresentativo. |
| EXACT_ALIGNMENT | L'allineamento esatto, padding corretto GDI+ |
| FIT_BLACK_BOX | È consentito che parti dei caratteri sporgono dal rettangolo di layout della stringa. Per impostazione predefinita, i caratteri vengono riposizionati per evitare qualsiasi sporgenza. |
| LINE_LIMIT | Solo le righe intere vengono disposte nel rettangolo di formattazione. Per impostazione predefinita la disposizione continua fino alla fine del testo, o finché non ci sono più righe visibili a causa del ritaglio, a seconda di quale evento si verifichi per primo.<br/>            Si noti che le impostazioni predefinite consentono all'ultima riga di essere parzialmente oscurata da un rettangolo di formattazione che non è un multiplo intero dell'altezza della riga. Per garantire che vengano visualizzate solo righe intere,<br/>            specificare questo valore e fare attenzione a fornire un rettangolo di formattazione alto almeno quanto l'altezza di una riga. |
| MEASURE_TRAILING_SPACES | Include lo spazio finale alla fine di ogni riga. Per impostazione predefinita il rettangolo di delimitazione restituito dal metodo MeasureString esclude lo spazio alla fine di ogni riga. Impostare questa opzione per includere quello spazio nella misurazione. |
| NO_CLIP | Le parti sporgenti dei glifi e il testo non avvolto che si estende al di fuori del rettangolo di formattazione sono consentiti a visualizzarsi. Per impostazione predefinita tutti i testi e le parti dei glifi che si estendono al di fuori del rettangolo di formattazione vengono ritagliati. |
| NO_FONT_FALLBACK | Il ricorso a caratteri alternativi per i caratteri non supportati nel font richiesto è disabilitato. Qualsiasi carattere mancante viene visualizzato con il glifo mancante del font, solitamente un quadrato vuoto. |
| NO_WRAP | L'avvolgimento del testo tra le righe durante la formattazione all'interno di un rettangolo è disabilitato. Questa opzione è implicita quando viene passato un punto anziché un rettangolo, o quando il rettangolo specificato ha una lunghezza di riga pari a zero. |
