---
title: "Перечисление WmfBinaryRasterOperation"
type: docs
weight: 20
url: /ru/python-net/aspose.imaging.fileformats.wmf.consts/wmfbinaryrasteroperation/
---

Раздел перечисления BinaryRasterOperation перечисляет коды бинарных растровых операций. Коды растровых операций<br/>                определяют, как обработка метафайла объединяет биты выбранного пера с<br/>                битами в целевом растровом изображении.

**Module:** [aspose.imaging.fileformats.wmf.consts](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/)

**Full Name:** aspose.imaging.fileformats.wmf.consts.WmfBinaryRasterOperation

## **Members**
| **Имя члена** | **Description** |
| :- | :- |
| BLACK | 0, Пиксель всегда 0. |
| COPYPEN | P, Пиксель — цвет пера. |
| MASKNOTPEN | DPna, Пиксель — комбинация цвета экрана и инверсии цвета пера. |
| MASKPEN | DPa, Pixel — комбинация цветов, общих как для пера, так и для экрана. |
| MASKPENNOT | PDna, Pixel — комбинация цветов, общих для пера и <br/>                обратного экрана. |
| MERGENOTPEN | DPno, Pixel — комбинация цветов, общих для экрана и <br/>                обратного пера. |
| MERGEPEN | DPo, Pixel — комбинация цвета пера и цвета экрана. |
| MERGEPENNOT | PDno, Pixel — комбинация цвета пера и <br/>                обратного цвета экрана. |
| NOP | D, Pixel остаётся неизменным. |
| NOT | Dn, Pixel — обратный цвет экрана. |
| NOTCOPYPEN | Pn, Pixel — обратный цвет пера. |
| NOTMASKPEN | DPan, Pixel — обратный цвет MASKPEN. |
| NOTMERGEPEN | DPon, Pixel — обратный цвет MERGEPEN |
| NOTXORPEN | DPxn, Pixel — обратный цвет XORPEN. |
| WHITE | 1, Pixel всегда равен 1 |
| XORPEN | DPx, Pixel — это комбинация цветов в перо или на экране, но не в обоих. |
