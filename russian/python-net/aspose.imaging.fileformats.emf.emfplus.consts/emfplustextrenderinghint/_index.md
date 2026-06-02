---
title: "Перечисление EmfPlusTextRenderingHint"
type: docs
weight: 430
url: /ru/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplustextrenderinghint/
---

Перечисление TextRenderingHint определяет типы подсказок текста и сглаживания, которые влияют на качество отображения текста.

**Module:** [aspose.imaging.fileformats.emf.emfplus.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.consts.EmfPlusTextRenderingHint

## **Members**
| **Имя члена** | **Description** |
| :- | :- |
| TEXT_RENDERING_HINT_ANTIALIAS | Указывает, что каждый символ текста отрисовывается с помощью его антиалиасного битмапа глифа без хинтинга. Лучшее качество достигается за счёт антиалиасинга, но различия в ширине штрихов МОГУТ быть заметны, поскольку хинтинг отключён. |
| TEXT_RENDERING_HINT_ANTIALIAS_GRID_FIT | Указывает, что каждый символ текста ДОЛЖЕН отрисовываться с помощью его антиалиасного битмапа глифа со сглаживанием. Рендеринг имеет высокое качество благодаря антиалиасингу, но требует больших затрат производительности. |
| TEXT_RENDERING_HINT_CLEAR_TYPE_GRID_FIT | Указывает, что каждый символ текста ДОЛЖЕН отрисовываться с помощью его ClearType битмапа глифа со сглаживанием. Это настройка хинтинга самого высокого качества, используемая для использования возможностей шрифтов ClearType. |
| TEXT_RENDERING_HINT_SINGLE_BIT_PER_PIXEL | Указывает, что каждый символ текста ДОЛЖЕН отрисовываться с помощью его битмапа глифа. Сглаживание не используется. |
| TEXT_RENDERING_HINT_SINGLE_BIT_PER_PIXEL_GRID_FIT | Указывает, что каждый символ текста ДОЛЖЕН отображаться с использованием его растрового глифа. Сглаживание МОЖЕТ использоваться для улучшения внешнего вида стволов глифов и их кривизны. |
| TEXT_RENDERING_HINT_SYSTEM_DEFAULT | Указывает, что каждый символ текста ДОЛЖЕН отображаться с использованием любых настроек сглаживания шрифтов, сконфигурированных в операционной системе. |
