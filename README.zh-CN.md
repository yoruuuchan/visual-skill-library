# Visual Skill Library

[English](README.md) | 中文

这是一个个人视觉 Skill 收藏库，用来收集我可能真正会使用的、具有明确审美特征的 AI Skills、工作流和设计系统。

这个仓库会刻意保持轻量：先收集，再整理；先记录，再测试。当前内容主要集中在图像生成与照片转译，后续也会逐步加入数据可视化、流程图 / Diagram、编辑设计以及其他具有明确视觉语言的工作流。

## 这个仓库怎么用

- **先收集。** 刷到有意思的 Skill，可以先丢进 `inbox.md`，不用当场做完整分析。
- **后整理。** 周期性检查重复项目、同源项目和相近方法，再统一归类。
- **优先实测。** 真正用于实际任务并验证过的 Skill，才会获得更高优先级。
- **读取当前版本。** 实际使用某个 Skill 时，优先读取其 GitHub 仓库最新的 `SKILL.md`，不要只依赖旧摘要或记忆。
- **尊重许可证。** 每个项目仍遵循其原始许可证和使用限制；本仓库以索引、分类、测试记录和个人评价为主，不直接重新发布受限制的代码或资产。

## 当前已整理 Skills

> 预览图直接引用各上游仓库已有示例，不复制图片文件到本仓库；版权与许可证仍归各上游项目及原作者所有。许可证明确限制再发布的项目只提供示例入口，不直接嵌图。

| 分类 | Skill | 效果预览 | GitHub | 简介 |
|---|---|---|---|---|
| 照片转译 · 保留原图 | `photo-abstract-editorial` | <img src="https://raw.githubusercontent.com/ZzzLc0405/photo-abstract-editorial/main/assets/examples/case-1.jpg" width="180" alt="photo-abstract-editorial preview"> | [ZzzLc0405/photo-abstract-editorial](https://github.com/ZzzLc0405/photo-abstract-editorial) | 保留原照片，并从其空间、色彩与构图关系中生成克制的抽象编辑面板。 |
| 照片转译 · 保留原图 | `travel-photo-abstraction` | [查看上游 Showcase](https://github.com/Evianis/travel-photo-abstraction#showcase) · *许可证限制再发布* | [Evianis/travel-photo-abstraction](https://github.com/Evianis/travel-photo-abstraction) | 工程化程度更高的“照片 + 抽象面板”工作流，带参考库、确定性合成与输出校验。 |
| 照片转译 · 保留原图 | `scenes-gathered-zine-v1-3` | <img src="https://raw.githubusercontent.com/Zeejay0/gathered-scenes-zine-skill/main/examples/real-scene-collage/01-where-stone-meets-sky/result.jpg" width="180" alt="scenes-gathered-zine preview"> | [Zeejay0/gathered-scenes-zine-skill](https://github.com/Zeejay0/gathered-scenes-zine-skill) | 以真实照片为锚点，通过抽象插画、结构性色彩与撕纸边界扩展画面。 |
| 照片转译 · 重构 | `scene-distillation-zine-v1-3` | <img src="https://raw.githubusercontent.com/Zeejay0/gathered-scenes-zine-skill/main/examples/image-distillation/01-time-waves-back/result.jpg" width="180" alt="scene-distillation-zine preview"> | [Zeejay0/gathered-scenes-zine-skill](https://github.com/Zeejay0/gathered-scenes-zine-skill) | 原照片不进入最终画面，只提炼语义核心、张力与视觉隐喻后重新创作。 |
| 编辑设计 / 海报 | `gc-minimal-zine-poster` | <img src="https://raw.githubusercontent.com/LiamGvchi/gc-minimal-zine-poster/main/examples/night-door.jpeg" width="180" alt="gc-minimal-zine-poster preview"> | [LiamGvchi/gc-minimal-zine-poster](https://github.com/LiamGvchi/gc-minimal-zine-poster) | 极简 Zine / 编辑海报系统，强调大留白、小视觉簇、纸张质感与受控高饱和色锚。 |
| 实验界面 | `tait-crt-interface-skill` | <img src="https://raw.githubusercontent.com/TaiT-tt/tait-crt-interface-skill/main/%E7%94%9F%E6%88%90%E7%A4%BA%E4%BE%8B/%E7%BB%8F%E5%85%B8a.png" width="180" alt="tait-crt-interface-skill preview"> | [TaiT-tt/tait-crt-interface-skill](https://github.com/TaiT-tt/tait-crt-interface-skill) | 将人物、物体或场景重构为早期计算机 / CRT 像素界面，带主体锚定和确定性后处理。 |
| 数据可视化 | `lieflat-charts` | <img src="https://raw.githubusercontent.com/larashero3-dotcom/lieflat-charts/main/docs/assets/preview-lupi-01.png" width="220" alt="lieflat-charts preview"> | [larashero3-dotcom/lieflat-charts](https://github.com/larashero3-dotcom/lieflat-charts) | 模板驱动的编辑型数据可视化系统，包含 Lupi、Basics、Glance 与 Interactive，主要输出可编辑 HTML。 |

## 当前分类

- **图像生成 / 照片转译** — 保留、抽象、重构或强风格化已有照片与图像。
- **编辑设计 / 海报系统** — Zine、海报、杂志式排版等可复用视觉语言。
- **实验界面** — CRT、复古计算机、像素界面等具有强烈视觉特征的重构系统。
- **数据可视化** — 拥有明确图表语法、模板和数据叙事方法的可视化系统。

更详细的状态、许可证备注和照片转译保真度关系见 [`catalog.md`](catalog.md)；等待整理的内容见 [`inbox.md`](inbox.md)。
