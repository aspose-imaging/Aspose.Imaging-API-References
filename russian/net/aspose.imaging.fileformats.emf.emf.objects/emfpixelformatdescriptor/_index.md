---
title: EmfPixelFormatDescriptor
second_title: Справочник по Aspose.Imaging for .NET API
description: Объект PixelFormatDescriptor можно использовать в записях EMR_HEADER раздел 2.3.4.2 для указания формата пикселей выходной поверхности для контекста устройства воспроизведения.
type: docs
weight: 3120
url: /ru/net/aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/
---
## EmfPixelFormatDescriptor class

Объект PixelFormatDescriptor можно использовать в записях EMR_HEADER (раздел 2.3.4.2) для указания формата пикселей выходной поверхности для контекста устройства воспроизведения.

```csharp
public sealed class EmfPixelFormatDescriptor : EmfObject
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [EmfPixelFormatDescriptor](emfpixelformatdescriptor)() | Конструктор по умолчанию. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [BReserved](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/breserved) { get; set; } | Получает или задает количество плоскостей наложения и подложки. Биты с 0 по 3 определяют до 15 плоскостей наложения, а биты с 4 по 7 определяют до 15 плоскостей подложки |
| [CAccumAlphaBits](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/caccumalphabits) { get; set; } | Получает или задает количество альфа-битовых плоскостей в накопительном буфере |
| [CAccumBits](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/caccumbits) { get; set; } | Получает или устанавливает общее количество битовых плоскостей в буфере накопления. |
| [CAccumBlueBits](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/caccumbluebits) { get; set; } | Получает или задает количество синих битовых плоскостей в буфере накопления. |
| [CAccumGreenBits](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/caccumgreenbits) { get; set; } | Получает или задает количество зеленых битовых плоскостей в наборе. |
| [CAccumRedBits](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/caccumredbits) { get; set; } | Получает или задает количество красных битовых плоскостей в накопительном буфере |
| [CAlphaBits](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/calphabits) { get; set; } | Получает или устанавливает количество альфа-битовых плоскостей в каждом цветовом буфере RGBA |
| [CAlphaShift](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/calphashift) { get; set; } | Получает или устанавливает количество смещений для альфа-битовых плоскостей в каждом цветовом буфере RGBA |
| [CAuxBuffers](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/cauxbuffers) { get; set; } | Получает или устанавливает количество вспомогательных буферов. Вспомогательные буферы не поддерживаются |
| [CBlueBits](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/cbluebits) { get; set; } | Получает или задает количество синих битовых плоскостей в каждом цветовом буфере RGBA. |
| [CBlueShift](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/cblueshift) { get; set; } | Получает или задает количество сдвигов для синих битовых плоскостей в каждом цветовом буфере RGBA. |
| [CColorBits](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/ccolorbits) { get; set; } | Получает или задает количество битов на пиксель для типов пикселей RGBA, исключая альфа-битовые плоскости. Для пикселей таблицы цветов это размер каждой таблицы цветов index |
| [CDepthBits](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/cdepthbits) { get; set; } | Получает или задает глубину буфера глубины (по оси Z). |
| [CGreenBits](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/cgreenbits) { get; set; } | Получает или задает количество зеленых битовых плоскостей в каждом цветовом буфере RGBA |
| [CGreenShift](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/cgreenshift) { get; set; } | Получает или задает количество сдвигов для зеленых битовых плоскостей в каждом цветовом буфере RGBA. |
| [CRedBits](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/credbits) { get; set; } | Получает или задает количество красных битовых плоскостей в каждом цветовом буфере RGBA |
| [CRedShift](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/credshift) { get; set; } | Получает или устанавливает количество смещений в битах для красных битовых плоскостей в каждом цветовом буфере RGBA. |
| [CStencilBits](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/cstencilbits) { get; set; } | Получает или задает глубину буфера трафарета. |
| [DwDamageMask](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/dwdamagemask) { get; set; } | Получает или устанавливает Это поле МОЖЕТ быть проигнорировано |
| [DwFlags](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/dwflags) { get; set; } | Получает или задает битовые флаги, определяющие свойства буфера пикселей, который используется для вывода на поверхность рисования. Эти свойства не все исключают друг друга; комбинации флагов разрешены, если не указано иное. |
| [DwLayerMask](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/dwlayermask) { get; set; } | Получает или устанавливает Это поле МОЖЕТ быть проигнорировано. |
| [DwVisibleMask](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/dwvisiblemask) { get; set; } | Получает или задает прозрачный цвет или индекс плоскости подложки. Когда тип пикселя — RGBA, dwVisibleMask — это прозрачное значение цвета RGB. Когда тип пикселя является индексом цвета, это значение индекса прозрачности. |
| [ILayerType](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/ilayertype) { get; set; } | Получает или устанавливает Это поле МОЖЕТ быть проигнорировано |
| [IPixelType](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/ipixeltype) { get; set; } | Получает или устанавливает тип пикселя data PFD_TYPE_RGBA 0x00 Формат пикселя — RGBA. PFD_TYPE_COLORINDEX 0x01 Каждый пиксель является индексом в таблице цветов. |
| [NSize](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/nsize) { get; set; } | Получает или задает 16-разрядное целое число, указывающее размер в байтах этой структуры данных. |
| [NVersion](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/nversion) { get; set; } | Получает или устанавливает 16-битное целое число, которое ДОЛЖНО быть установлено равным 0x0001. |

### Смотрите также

* class [EmfObject](../emfobject)
* пространство имен [Aspose.Imaging.FileFormats.Emf.Emf.Objects](../../aspose.imaging.fileformats.emf.emf.objects)
* сборка [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
