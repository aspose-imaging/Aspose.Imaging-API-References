---
title: "WmfCompression Enumeration"
type: docs
weight: 70
url: /sv/python-net/aspose.imaging.fileformats.wmf.consts/wmfcompression/
---

Compression‑enumerationen specificerar kompressionstypen för en bitmap‑bild.

**Module:** [aspose.imaging.fileformats.wmf.consts](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/)

**Full Name:** aspose.imaging.fileformats.wmf.consts.WmfCompression

## **Members**
| **Member name** | **Description** |
| :- | :- |
| BI_BITFIELDS | Bitmapen är inte komprimerad och färgtabellen består av tre DWORD-färgmasker som<br/>                specificerar de röda, gröna och blåa komponenterna för varje pixel.<br/>                Detta är giltigt när den används med 16- och 32-bitars per pixel-bitmapar. |
| BI_CMYK | Bilden är i ett okomprimerat CMYK-format. |
| BI_CMYKRLE4 | Ett CMYK-format som använder RLE-komprimering för bitmapar med 4 bitar per pixel.<br/>                Komprimeringen använder ett 2-byte format bestående av en räknebyte följt av två ordlånga färgindex. |
| BI_CMYKRLE8 | Ett CMYK-format som använder RLE-komprimering för bitmapar med 8 bitar per pixel.<br/>                Komprimeringen använder ett 2-byte format bestående av en räknebyte följt av en byte som innehåller ett färgindex. |
| BI_JPEG | Bilden är en JPEG-bild, enligt specifikationen i [JFIF]. Detta värde BÖR endast användas i vissa bitmap-<br/>                operationer, såsom JPEG-genomströmning. Applikationen MÅSTE fråga efter stöd för genomströmning,<br/>                eftersom inte alla enheter stödjer JPEG-genomströmning. Användning av icke-RGB-bitmapar KAN begränsa metafilens portabilitet<br/>                till andra enheter. Till exempel stödjer displayenhetssammanhang generellt sett inte denna genomströmning. |
| BI_PNG | Bilden är en PNG-bild, enligt specifikationen i [RFC2083]. Detta värde BÖR endast användas i vissa bitmap-<br/>                operationer, såsom JPEG/PNG-genomströmning. Applikationen MÅSTE fråga efter stöd för genomströmning, eftersom inte alla enheter<br/>                stödjer JPEG/PNG-genomströmning. Användning av icke-RGB-bitmapar KAN begränsa metafilens portabilitet till andra enheter.<br/>                Till exempel stödjer displayenhetssammanhang generellt sett inte denna genomströmning. |
| BI_RGB | Bitmappen är i ett okomprimerat röd‑grön‑blå (RGB)-format som inte är komprimerat och inte använder färgmasker. |
| BI_RLE4 | Ett RGB-format som använder RLE-kompression för bitmaps med 4 bitar per pixel.<br/>                Kompressionen använder ett 2‑byteformat bestående av en räknebyte följt av två ordlängds färgindex. |
| BI_RLE8 | Ett RGB-format som använder run‑length‑encoding (RLE)-kompression för bitmaps med 8 bitar per pixel.<br/>                Kompressionen använder ett 2‑byteformat bestående av en räknebyte följt av en byte som innehåller ett färgindex. |
