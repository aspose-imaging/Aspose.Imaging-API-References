---
title: "EmfPlusPathPointFlags Enumeration"
type: docs
weight: 290
url: /it/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluspathpointflags/
---

Un intero senza segno a 32 bit che specifica come interpretare i punti e i tipi di punto associati definiti da questo oggetto.<br/>            C  (1 bit): Se impostato, l'array PathPoints specifica posizioni assolute nello spazio delle coordinate con coordinate intere a 16 bit.<br/>             Se non impostato, l'array PathPoints specifica posizioni assolute nello spazio delle coordinate con coordinate a virgola mobile a 32 bit.<br/>             Nota: se il flag P (sotto) è impostato, questo flag PUÒ essere non impostato e DEVE essere ignorato.<br/>            R (1 bit): Se impostato, i tipi di punto nell'array PathPointTypes sono specificati da oggetti EmfPlusPathPointTypeRle (sezione 2.2.2.32), <br/>             che utilizzano la compressione run-length encoding (RLE), e/o da oggetti EmfPlusPathPointType (sezione 2.2.2.31). Vedere la sezione 3.1.6 di [MS-WMF] per ulteriori informazioni sulla compressione RLE.<br/>             Se non impostato, i tipi di punto nell'array PathPointTypes sono specificati da oggetti EmfPlusPathPointType.<br/>            P (1 bit): Se impostato, ogni elemento dell'array PathPoints specifica una posizione nello spazio delle coordinate relativa alla<br/>             posizione specificata dall'elemento precedente nell'array. Nel caso del primo elemento di PathPoints, si assume una posizione precedente alle coordinate (0,0).<br/>             Se non impostato, ogni elemento dell'array PathPoints specifica una posizione assoluta.

**Module:** [aspose.imaging.fileformats.emf.emfplus.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.consts.EmfPlusPathPointFlags

## **Members**
| **Member name** | **Descrizione** |
| :- | :- |
| C | Il flag c |
| P | Il flag p |
| R | Il flag r |
