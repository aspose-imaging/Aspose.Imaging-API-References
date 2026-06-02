---
title: "EmfModifyWorldTransformMode‑enumeration"
type: docs
weight: 240
url: /sv/python-net/aspose.imaging.fileformats.emf.emf.consts/emfmodifyworldtransformmode/
---

ModifyWorldTransformMode‑enumerationen definierar lägen för att använda specificerade transformdata<br/>            för att ändra världsrummets till sidrummets transform som för närvarande är definierad i uppspelningsenhetens kontext.

**Module:** [aspose.imaging.fileformats.emf.emf.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emf.consts.EmfModifyWorldTransformMode

## **Members**
| **Member name** | **Description** |
| :- | :- |
| MWT_IDENTITY | Återställ den aktuella transformen med identitetsmatrisen. I detta läge ignoreras den specificerade transformdata. |
| MWT_LEFTMULTIPLY | Multiplicera den aktuella transformen. I detta läge är den specificerade transformdata den vänstra multiplikanden, och <br/>            den transform som för närvarande är definierad i uppspelningsenhetens kontext är den högra multiplikanden. |
| MWT_RIGHTMULTIPLY | Multiplicera den aktuella transformen. I detta läge är de specificerade transformdata den högra multiplikanden, <br/>            och transformen som för närvarande är definierad i uppspelningsenhetens kontext den vänstra multiplikanden |
| MWT_SET | Utför funktionen för en EMR_SETWORLDTRANSFORM-post (avsnitt 2.3.12.2). |
