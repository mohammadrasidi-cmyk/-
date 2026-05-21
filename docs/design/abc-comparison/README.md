# 日目标 - 产品ABC对标 设计资源

本目录包含该需求的完整设计资源。

## 文件清单

| 文件 | 用途 | 打开方式 |
|---|---|---|
| `01-prototype.html` | 5 个页面的高保真可交互 HTML 原型 | 浏览器直接打开 |
| `02-figma-spec.md` | Figma 设计规范文档（Color Token / Typography / Component） | 在 Figma 中按规格搭建 |
| `03-prd-supplement.md` | 待并入主 PRD 的需求详细内容 | Markdown 阅读器 |
| `README.md` | 本文件 | — |

## 5 个核心页面

1. **PAD - 日目标主表（默认态）** — 评级列从单值升级为双值
2. **PAD - 评级详情抽屉** — 点击单元格触发，展示多组 ABC 对标
3. **PAD - 列设置抽屉** — 解决列吃紧，可自定义显示列
4. **PC 后台 - 默认对标组配置** — 后台管理员配置入口
5. **设计规格表** — 颜色与组件参数

## 决策已确认

| Q | 问题 | 结论 |
|---|---|---|
| Q1 | 默认对标组配置位置 | 后台管理员（已有"分析组管理"中扩展）|
| Q2 | 列吃紧解决方案 | 序号合并到物料列 + 销量合并 + 营销折叠 + 列设置 + 计划试吃/退货/上架默认隐藏 |
| Q3 | 组内 ABC 是否剔除本店 | 不剔除 |
| Q4 | 切换对标组生效范围 | 仅本次会话 |
| Q5 | 是否做"建议加货"CTA | V1.0 不做，仅显示提示文案 |

## 在 Figma 中使用

1. 浏览器打开 `01-prototype.html`，截图作为 Figma 参考底稿
2. 在 Figma 中按 `02-figma-spec.md` 的规范搭建：
   - 录入 Color Tokens
   - 创建 Typography Style
   - 组装 Component（GradeCell、Drawer 等）
   - 按 Frame 结构搭建 5 个页面
   - 用 Prototype 连接交互

## 推送到 GitHub 后查看

推送后可通过以下方式预览：
- HTML 原型：`https://raw.githack.com/<owner>/<repo>/<branch>/docs/design/abc-comparison/01-prototype.html`
- Markdown：直接在 GitHub 上查看
