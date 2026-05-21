---
title: "EmfCommentPublicRecordType"
second_title: "Aspose.Imaging för Java API-referens"
description: "EMR_COMMENT_PUBLIC‑posttyper specificerar utökningar av EMF‑behandlingen."
type: docs
weight: 31
url: /sv/java/com.aspose.imaging.fileformats.emf.emf.records/emfcommentpublicrecordtype/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfCommentRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype)
```
public abstract class EmfCommentPublicRecordType extends EmfCommentRecordType
```

De EMR\_COMMENT\_PUBLIC-posttyperna anger tillägg till EMF-bearbetning.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getCommentIdentifier()](#getCommentIdentifier--) | Hämtar eller anger ett 32‑bitars osignerat heltal som identifierar denna kommentarspost som specificerar offentliga data. |
| [setCommentIdentifier(int value)](#setCommentIdentifier-int-) | Hämtar eller anger ett 32‑bitars osignerat heltal som identifierar denna kommentarspost som specificerar offentliga data. |
| [getPublicCommentIdentifier()](#getPublicCommentIdentifier--) | Hämtar eller anger ett 32‑bitars osignerat heltal som identifierar typen av offentlig kommentarspost. |
| [setPublicCommentIdentifier(long value)](#setPublicCommentIdentifier-long-) | Hämtar eller anger ett 32‑bitars osignerat heltal som identifierar typen av offentlig kommentarspost. |
### getCommentIdentifier() {#getCommentIdentifier--}
```
public int getCommentIdentifier()
```


Hämtar eller anger ett 32‑bitars osignerat heltal som identifierar denna kommentarspost som specificerar offentliga data. Värdet 0x43494447, som är ASCII‑strängen "CIDG", identifierar detta som en EMR\_COMMENT\_PUBLIC‑post.

**Returns:**
int
### setCommentIdentifier(int value) {#setCommentIdentifier-int-}
```
public void setCommentIdentifier(int value)
```


Hämtar eller anger ett 32‑bitars osignerat heltal som identifierar denna kommentarspost som specificerar offentliga data. Värdet 0x43494447, som är ASCII‑strängen "CIDG", identifierar detta som en EMR\_COMMENT\_PUBLIC‑post.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getPublicCommentIdentifier() {#getPublicCommentIdentifier--}
```
public long getPublicCommentIdentifier()
```


Hämtar eller anger ett 32‑bitars osignerat heltal som identifierar typen av offentlig kommentarspost. Detta SKA vara ett av värdena i den föregående tabellen, som specificeras i uppräkningen EmrComment (avsnitt 2.1.10), såvida inte ytterligare offentliga kommentarsposttyper har implementerats på utskriftsservern.

**Returns:**
long
### setPublicCommentIdentifier(long value) {#setPublicCommentIdentifier-long-}
```
public void setPublicCommentIdentifier(long value)
```


Hämtar eller anger ett 32‑bitars osignerat heltal som identifierar typen av offentlig kommentarspost. Detta SKA vara ett av värdena i den föregående tabellen, som specificeras i uppräkningen EmrComment (avsnitt 2.1.10), såvida inte ytterligare offentliga kommentarsposttyper har implementerats på utskriftsservern.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | long |  |

