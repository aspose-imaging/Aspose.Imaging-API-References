---
title: "CompressionMethod-enumeration"
type: docs
weight: 20
url: /sv/python-net/aspose.imaging.fileformats.psd/compressionmethod/
---

Definierar komprimeringsmetoden som används för bilddata.

**Module:** [aspose.imaging.fileformats.psd](/imaging/python-net/aspose.imaging.fileformats.psd/)

**Full Name:** aspose.imaging.fileformats.psd.CompressionMethod

## **Members**
| **Member name** | **Description** |
| :- | :- |
| RAW | Ingen komprimering. Bilddata lagras som råa byte i RGBA-planarordning.<br/>            Det betyder att först all R-data skrivs, sedan all G-data, sedan all B-data och slutligen all A-data skrivs. |
| RLE | RLE-komprimerad bilddata börjar med byteantalet för alla bildrader (rader * kanaler), där varje<br/>            antal lagras som ett tvåbytevärde. De RLE-komprimerade data följer, där varje bildrad komprimeras separat.<br/>            RLE-komprimeringen är samma komprimeringsalgoritm som används av Macintosh ROM‑rutinen PackBits och TIFF‑standarden. |
| ZIP_WITHOUT_PREDICTION | ZIP utan prediktion. |
| ZIP_WITH_PREDICTION | ZIP med prediktion. |
