---
name: midjourney-douyin-detail
description: 为抖音女装电商生成可上架的商品详情图，Midjourney用于背景/视觉元素，中文文案采用可编辑矢量排版保证准确性。
---
# 女装电商 Midjourney 详情图 Skill

## 输入
- 商品类型、材质、颜色、图片、用途、尺寸、已有洗标要求。
- 参考图只学习排版风格，不照搬其他店铺品牌文案。
- 默认比例 3:4，建议导出 1200×1600 或更高像素，手机端大字优先。

## 标准工作流
1. 提取商品事实与用户特别需要强调的信息。
2. 拟写简短准确的中文详情文案，不虚构功能、检验结果或售后限制。
3. 用 Midjourney 生成**无文字背景**；不得让 Midjourney 直接生成中文，避免错字。
4. 用 SVG/Canvas 等工具叠加准确的标题、正文、角标与图标。
5. 校对内容、阅读层级、手机浏览效果，导出清晰 PNG，保存可编辑 SVG。

## Midjourney 提示词（用于背景，无中文字）
```text
premium Chinese womenswear e-commerce product detail page background, light ice-blue to white gradient, airy soft bokeh, elegant clean editorial design, large rounded white content card taking 78% of the frame, very subtle ambient drop shadow, refined calm minimal aesthetic, mobile-friendly vertical composition, blank spacious areas deliberately reserved for Chinese typography, sophisticated commercial UI style, no garments, no human, no logos, no writing, no text, no letters, no watermark --ar 3:4 --stylize 75
```

## 黑色衣物单独洗示范
标题：**洗护须知**

主提醒：**黑色衣物请单独洗涤** / **不要与其他黑色衣服混洗！**

步骤：
1. 单件单洗：其他黑色、深色、浅色衣物均不要混洗。
2. 冷水轻柔：建议反面轻柔清洗，避免大力揉搓。
3. 避免久泡：勿长时间浸泡，避免高温洗涤。
4. 及时晾干：洗后及时取出晾晒，避免衣物互相接触。

底部提示：洗涤方式请以实物洗标为准。如遇明显异常掉色、串色，请及时联系客服处理。

**合规提醒：**未确认面料和洗标前，不要擅自声称明显掉色、串色一律属于正常现象，也不要虚构售后政策。

## 成品
- 本仓库示范矢量设计：`designs/douyin-wash-care/black-clothing-single-wash.svg`
- 对外 PNG：可在 SVG 设计基础上导出，Midjourney 并不能由 GitHub 文件直接运行。
