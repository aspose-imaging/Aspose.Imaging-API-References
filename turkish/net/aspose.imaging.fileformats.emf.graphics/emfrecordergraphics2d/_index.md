---
title: EmfRecorderGraphics2D
second_title: Aspose.Imaging for .NET API Referansı
description: Emf kaydedici grafikleri
type: docs
weight: 6490
url: /tr/net/aspose.imaging.fileformats.emf.graphics/emfrecordergraphics2d/
---
## EmfRecorderGraphics2D class

Emf kaydedici grafikleri

```csharp
public sealed class EmfRecorderGraphics2D : MetafileRecorderGraphics2D
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [EmfRecorderGraphics2D](emfrecordergraphics2d)(Rectangle, Size, Size) | Yeni bir örneğini başlatır[`EmfRecorderGraphics2D`](../emfrecordergraphics2d) sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [BackgroundColor](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/backgroundcolor) { get; set; } | Arka planın rengini alır veya ayarlar. |
| [BackgroundMode](../../aspose.imaging.fileformats.emf.graphics/emfrecordergraphics2d/backgroundmode) { get; set; } | Arka plan modunu alır veya ayarlar. |
| [Clip](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/clip) { get; set; } | Bu Graphics çizim bölgesini sınırlayan bir Bölge alır veya ayarlar |
| [ClipBounds](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/clipbounds) { get; } | Klip sınırlarını alır. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| static [FromEmfImage](../../aspose.imaging.fileformats.emf.graphics/emfrecordergraphics2d/fromemfimage)(EmfImage) | Şunun bir örneğini alır:[`EmfRecorderGraphics2D`](../emfrecordergraphics2d) Emf görüntüsündeki tüm kayıtları içerir. |
| [Clear](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/clear)() | grafik nesnesinin durumunu temizler |
| [DrawArc](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawarc)(Pen, Rectangle, float, float) | Bir Dikdörtgen yapısı tarafından belirtilen bir elipsin bir bölümünü temsil eden bir yay çizer. |
| [DrawCubicBezier](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawcubicbezier)(Pen, Point, Point, Point, Point) | Kübik bezier'i çizer. |
| [DrawEllipse](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawellipse)(Pen, Rectangle) | Elipsi çizer. |
| [DrawImage](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawimage)(RasterImage, Point) | Belirtilen Resmi orijinal fiziksel boyutunu kullanarak belirtilen konumda çizer. |
| [DrawImage](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawimage)(byte[], Rectangle, GraphicsUnit) | Resmi çizer. |
| [DrawImage](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawimage)(Stream, Rectangle, GraphicsUnit) | Resmi çizer. |
| [DrawImage](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawimage)(RasterImage, Rectangle, Rectangle, GraphicsUnit) | Belirtilen Görüntünün belirtilen bölümünü belirtilen konumda ve belirtilen boyutta çizer. |
| [DrawLine](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawline)(Pen, Point, Point) | Çizgiyi çizer. |
| [DrawLine](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawline)(Pen, int, int, int, int) | Çizgiyi çizer. |
| [DrawPath](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawpath)(Pen, GraphicsPath) | Yolu çizer. |
| [DrawPie](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawpie)(Pen, Rectangle, float, float) | Pastayı çizer. |
| [DrawPolyCubicBezier](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawpolycubicbezier)(Pen, Point[]) | Poli kübik bezier'i çizer. |
| [DrawPolygon](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawpolygon)(Pen, Point[]) | Çokgeni çizer. |
| [DrawPolyline](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawpolyline)(Pen, Point[]) | Çoklu çizgiyi çizer. |
| [DrawRectangle](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawrectangle)(Pen, Rectangle) | Dikdörtgeni çizer. |
| [DrawRectangle](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawrectangle)(Pen, int, int, int, int) | Dikdörtgeni çizer. |
| [DrawString](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawstring)(string, Font, Color, int, int) | Dizeyi çizer. |
| [DrawString](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawstring)(string, Font, Color, int, int, float) | Dizeyi çizer. |
| [EndRecording](../../aspose.imaging.fileformats.emf.graphics/emfrecordergraphics2d/endrecording)() | Kaydı sonlandırır. |
| [ExcludeClip](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/excludeclip)(Rectangle) | Bir Dikdörtgen yapısı tarafından belirtilen alanı hariç tutmak için bu Grafiğin klip bölgesini günceller. |
| [ExcludeClip](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/excludeclip)(Region) | Bir Bölge tarafından belirtilen alanı hariç tutmak için bu Grafiğin klip bölgesini günceller. |
| [FillEllipse](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/fillellipse)(Brush, Rectangle) | Elipsi doldurur. |
| [FillPath](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/fillpath)(Pen, Brush, GraphicsPath) | Yolu doldurur. |
| [FillPie](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/fillpie)(Brush, Rectangle, float, float) | Pastayı doldurur. |
| [FillPolygon](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/fillpolygon)(Brush, Point[]) | Çokgeni doldurur. |
| [FillPolygon](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/fillpolygon)(Brush, Point[], FillMode) | Çokgeni doldurur. |
| [FillRectangle](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/fillrectangle)(Brush, Rectangle) | Dikdörtgeni doldurur. |
| [GetTransform](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/gettransform)() | Dünyanın dönüşümünü sağlar. |
| [IntersectClip](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/intersectclip)(RectangleF) | Bu Grafiğin klip bölgesini, mevcut klip bölgesi ile belirtilen Dikdörtgen yapısının kesişimine göre günceller. |
| [IntersectClip](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/intersectclip)(Region) | Bu Grafiğin klip bölgesini, geçerli klip bölgesi ile belirtilen Bölgenin kesişimine göre günceller. |
| [MultiplyTransform](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/multiplytransform)(Matrix) | Bu Grafiğin dünya dönüşümünü çarpar ve Matrix'i belirtir. |
| [MultiplyTransform](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/multiplytransform)(Matrix, MatrixOrder) | Bu Grafiğin dünya dönüşümünü çarpar ve Matrix'i belirtilen sırada belirtir. |
| [ResetClip](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/resetclip)() | Klibi sıfırlar. |
| [RotateTransform](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/rotatetransform)(float) | Belirtilen döndürmeyi bu Grafiğin dönüştürme matrisine uygular. |
| [RotateTransform](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/rotatetransform)(float, PointF, MatrixOrder) | Belirtilen döndürmeyi bu Grafiğin dönüştürme matrisine belirtilen sırada uygular. |
| [ScaleTransform](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/scaletransform)(float, float) | Belirtilen ölçekleme işlemini, nesnenin dönüştürme matrisinin başına ekleyerek bu Grafiklerin dönüştürme matrisine uygular. |
| [ScaleTransform](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/scaletransform)(float, float, MatrixOrder) | Belirtilen ölçekleme işlemini bu Grafiğin dönüştürme matrisine belirtilen sırada uygular. |
| [SetTransform](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/settransform)(Matrix) | Dönüşümü ayarlar. |
| [TranslateTransform](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/translatetransform)(float, float) | Belirtilen çeviriyi bu Grafiğin dönüştürme matrisine ekleyerek koordinat sisteminin orijinini değiştirir. |
| [TranslateTransform](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/translatetransform)(float, float, MatrixOrder) | Belirtilen çeviriyi bu Grafiğin dönüşüm matrisine belirtilen sırayla uygulayarak koordinat sisteminin orijinini değiştirir. |

### Ayrıca bakınız

* class [MetafileRecorderGraphics2D](../metafilerecordergraphics2d)
* ad alanı [Aspose.Imaging.FileFormats.Emf.Graphics](../../aspose.imaging.fileformats.emf.graphics)
* toplantı [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
