---
title: "EmfPlusPathPointFlags Enumeration"
type: docs
weight: 290
url: /tr/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluspathpointflags/
---

Bu nesne tarafından tanımlanan noktaları ve ilişkili nokta türlerini yorumlamayı belirten 32-bit işaretsiz tamsayı.<br/>            C  (1 bit): Ayarlanmışsa, PathPoints dizisi koordinat uzayında 16-bit tamsayı koordinatlarıyla mutlak konumları belirtir.<br/>             Temizlenmişse, PathPoints dizisi koordinat uzayında 32-bit kayan nokta koordinatlarıyla mutlak konumları belirtir.<br/>             Not: Eğer aşağıdaki P bayrağı ayarlanmışsa, bu bayrak KAPALI olabilir ve YOK SAYILMALIDIR.<br/>            R (1 bit): Ayarlanmışsa, PathPointTypes dizisindeki nokta türleri EmfPlusPathPointTypeRle nesneleri (bölüm 2.2.2.32), <br/>             ki run-length encoding (RLE) sıkıştırması ve/veya EmfPlusPathPointType nesneleri (bölüm 2.2.2.31) kullanır. RLE sıkıştırması hakkında daha fazla bilgi için [MS-WMF] bölüm 3.1.6'ya bakın.<br/>             Temizlenmişse, PathPointTypes dizisindeki nokta türleri EmfPlusPathPointType nesneleri tarafından belirtilir.<br/>            P (1 bit): Ayarlanmışsa, PathPoints dizisindeki her öğe, koordinat uzayında önceki öğe tarafından belirtilen konuma göre bir konum belirtir,<br/>             dizideki önceki öğe tarafından belirtilen konum. PathPoints'taki ilk öğe durumunda, (0,0) koordinatlarında bir önceki konum varsayılır.<br/>             Temizlenmişse, PathPoints dizisindeki her öğe mutlak bir konum belirtir.

**Module:** [aspose.imaging.fileformats.emf.emfplus.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.consts.EmfPlusPathPointFlags

## **Members**
| **Üye adı** | **Açıklama** |
| :- | :- |
| C | c bayrağı |
| P | p bayrağı |
| R | r bayrağı |
