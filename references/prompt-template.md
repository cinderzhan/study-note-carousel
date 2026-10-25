# 提示词模板与落盘记录

将以下变量替换成真实文案与布局；只传本页需要的少量参考，并说明每张参考的用途。不要复制参考正文、署名或编辑选框。

```text
Generate ONE finished 3:4 portrait Chinese learning notebook page.
Physical style: neutral nearly-white ivory paper, three silver binder rings on left,
dark olive grass visible outside paper, soft natural daylight. Paper has no green tint.
Typography: simplified Chinese; clean modern printed Songti title LEFT ALIGNED,
light printed book Songti body, dark and readable; short diagram labels handwritten.
Series: {configured series or omit}. Source/author only as specified below.
Use visible translucent pale sage MARKER BLOCKS behind {exact existing phrases},
letter-height with rough ends, no mere thin underline, no obscured letters.
Layout: {page-specific arrangement and area budget}; reserve body safe area and
separate page-number zone. Keep prose at least about two lines away from page number
and 6–8% page height above paper bottom. Keep text within paper right boundary.
If dense: reduce illustration and title first, never omit or rewrite approved copy.
Diagram: {conceptual relation, minimal necessary objects, exact short labels and arrows}.
Simple slightly wobbly BLACK contours, few green accents, no realistic sketch,
crosshatching, 3D, irrelevant objects or repeated decorative icons.
Exact title: {title}
Exact FULL body, all paragraphs verbatim: {body}
Exact footer: {page / total, or cover-specific footer}
Only specified text; no extra prose. Do not copy reference wording.
```

封面换成主标题、副标题、来源和作者的明确层级，减少概念图比重；正文页明确每段与图的顺序，长页缩图。不要将单页示例里的总页数、期数、作者或题目写成全局常量。

将每次真正提交的完整提示词（含返修）保存到项目 `生成提示词.txt` 或 JSON；同时记录参考图片文件与用途、输出文件路径。不要只保存尚未展开的模板。

`制作进度.md` 可使用一张表：页序｜标题｜图片相对路径｜提示词记录位置｜状态｜具体问题。生成后立即记待核对，文字和布局均检查后才记完成。只记录实际完成的检查，不把“文件已存在”当成“已核对”。

最终交付目录只放按数字命名的最终图片、`发布文案.md`、`发布顺序.txt`、`生成提示词.txt`（或 JSON）、`制作进度.md`；参考与预览放项目其他目录保留。需要 ZIP 时按最终清单打包，并核对图片数量与页序。
