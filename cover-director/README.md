# 📷 Cover Director (文章封面总监 4.0)

[![Language](https://img.shields.io/badge/Language-English-blue.svg)](README_EN.md)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

> **Visual Metaphor & Real Optics Driven Cover Art Agent Skill**  
> 兼具“编剧、视觉隐喻大师、广告创意总监、真实摄影指导”四重灵魂的顶级文章封面图与视觉概念设计 Agent 技能。

---

## 🌟 核心理念：从“拍文章”升维至“拍隐喻与认知冲突”

传统的 AI 提示词生成工具往往陷入“直白叙事”或“镜头参数堆砌”的误区。**Cover Director 4.0** 引入广告级 **Key Visual (KV)** 概念，拒绝直白记录文本，而是将抽象商业概念/情绪转化为高冲击力的**视觉隐喻（Visual Metaphor）**，并配合单反红圈镜头的极致真实光学质感，打造 0.5 秒停顿的封面冲击力。

> [!TIP]
> **💡 最佳生图效果推荐**：本技能生成的提示词，使用 **ChatGPT 图像 2.0（基于底层模型 gpt-image-2）** 生成图片效果最佳！

---

## 🧠 4 重顶层灵魂与 5 层创意架构

本技能由以下五层决策架构升维推演：

```text
[L1: 编剧解构] ──> [L2: 视觉隐喻与 KV] ──> [L3: 12 Triggers 模型] ──> [L4: 真实光学与文字融入] ──> [L5: 跨平台策略与 Prompt]
```

1. 📖 **编剧 (The Screenwriter)**：精读文本，提炼核心戏剧反差与一句话 Logline。
2. 💡 **视觉隐喻与创意总监 (Creative Director & Metaphor Master)**：超越直白叙事，寻找抽象概念的视觉降维表现（Visual Metaphor）与 0.5 秒认知秒停概念。
3. 🧠 **传播心理学家 (Visual Marketer)**：调用 **12 大结构化传播 Trigger 模型**，精准计算受众注意力停留机制与社交传播动力。
4. 📷 **智能相机器材指导 (Camera Optics DOP)**：默认统一推荐使用**佳能 EOS 红圈单反系统**（凭借温润发色与红圈虚化最易激发 AI 生图模型画质），并能根据奢华物证/电影切片情境动态匹配哈苏中画幅或莱卡电影机，配合**文字有机融入协议 (Organic Typography)** 彻底消除 AI 塑料感。

---

## ⚡ 12 大结构化传播触发器 (Visual Triggers)

技能内置 12 种社交媒体传播心理学模型：
1. 🪞 **`Identity Alignment` (身份认同)**：特定人群的集体记忆与工具符号。
2. 👁️ **`Voyeuristic Gaze` (窥探感/偷窥)**：破壁视角，窥探幕后决定性密谈或崩溃时刻。
3. ⚠️ **`Peril & Chaos` (危险/失控边缘)**：悬崖边缘、倒计时最后一秒、崩塌前夜。
4. 👑 **`Power & Hierarchy` (权力位阶/压迫)**：俯仰视线带来的巨头压迫与个人渺小感。
5. 💰 **`Capital & Wealth` (财富/资本流向)**：高耸玻璃幕墙、冷酷算力与巨额资本隐喻。
6. 🌌 **`Absolute Isolation` (绝对孤独)**：浩瀚冷酷背景下极度微小的个体。
7. 📏 **`Scale Contrast` (体量极差)**：极度悬殊的比例对比。
8. ❓ **`The Unknown & Mystery` (未知/悬念)**：黑箱打开瞬间、未见全貌的光影悬念。
9. 📉 **`Failure & Glitch` (崩溃/挫败)**：千百次尝试后的系统崩溃或清零。
10. 🔄 **`Reversal & Irony` (命运反转/讽刺)**：荒诞对立与戏剧性讽刺。
11. ⏱️ **`Ticking Clock & Pressure` (高压时刻/倒计时)**：终极截止日期前的窒息压迫感。
12. 💡 **`The Genesis Moment` (破局/质变瞬间)**：黑暗中第一缕曙光刺破重围的顿悟时刻。

---

## 📦 安装与配置 (Installation & Setup)

### 🤖 方式 A：让 AI Agent 为你自主一键安装 (AI Autonomous Installation)

你无需手动敲命令，只需将以下指令直接复制给你的 AI 助手（如 Antigravity, OpenClaw, Claude Code 等）：

> **发送给 AI 的指令：**  
> *"请帮我将 `https://github.com/lwgscau2024/leiskill` 仓库中的 `cover-director` 技能自动下载并安装到全局 skills 目录下。"*

---

### 💻 方式 B：终端一键命令行安装 (One-Liner CLI Installation)

#### 🪟 Windows (PowerShell 一键安装)：
```powershell
$target="$HOME\.gemini\antigravity-cli\skills"; if (-not (Test-Path $target)) { New-Item -ItemType Directory -Path $target -Force }; git clone --depth 1 https://github.com/lwgscau2024/leiskill.git "$env:TEMP\leiskill_temp"; Copy-Item -Path "$env:TEMP\leiskill_temp\cover-director" -Destination "$target\cover-director" -Recurse -Force; Remove-Item "$env:TEMP\leiskill_temp" -Recurse -Force; Write-Host "✅ cover-director 技能已成功安装至: $target\cover-director" -ForegroundColor Green
```

#### 🐧 macOS / Linux (Bash 一键安装)：
```bash
TARGET_DIR="$HOME/.gemini/antigravity-cli/skills" && mkdir -p "$TARGET_DIR" && git clone --depth 1 https://github.com/lwgscau2024/leiskill.git /tmp/leiskill_temp && cp -r /tmp/leiskill_temp/cover-director "$TARGET_DIR/" && rm -rf /tmp/leiskill_temp && echo "✅ cover-director installed successfully to $TARGET_DIR/cover-director"
```

---

### 🛠️ 方式 C：常规分步克隆与手动配置

```bash
# 克隆仓库
git clone https://github.com/lwgscau2024/leiskill.git

# 复制 cover-director 目录至你的 Agent skills 文件夹
cp -r leiskill/cover-director ~/.gemini/antigravity-cli/skills/
```

---

## 🚀 触发与使用

在支持 Agent/Skill 机制的对话框架（如 Antigravity, OpenClaw, Claude Code 等）中，使用以下任意关键词或直接输入文章内容即可唤醒：

- **自然语言触发词**：
  - `cover-director` / `文章封面总监`
  - `封面总监` / `文章封面`
  - `爆款封面` / `封面图提示词`
  - `文章封面设计` / `封面配图`

---

## 💡 视觉生成真实效果与输出示例 (Showcase Gallery)

技能将自动输出 3 个不同切角的真实单反方案，包含中文/英文 Prompt 与参数设定（默认使用微信公众号 `--ar 2.35:1` 画幅）：

### 🖼️ 真实生成效果画廊 (Visual Metaphor Showcase)

| 案例 1：【广告 KV 极简概念流】思想止痛药 | 案例 2：【戏剧冲突/传播 Trigger】认知反差 |
| :---: | :---: |
| ![Concept 1](assets/example_cover_1.webp) | ![Concept 2](assets/example_cover_2.webp) |

| 案例 3：【真实红圈光学质感】物理字融入 | 案例 4：【资本/权力位阶隐喻】巨头视角 |
| :---: | :---: |
| ![Concept 3](assets/example_cover_3.webp) | ![Concept 4](assets/example_cover_4.webp) |

| 案例 5：【破局/顿悟时刻】破晓红光 |
| :---: |
| ![Concept 5](assets/example_cover_5.webp) |

---

### 📝 Prompt 交付标准结构

```text
### 方案 1：【广告 KV 极简概念流】思想止痛药

【中文 Prompt】
佳能 EOS R3 拍摄，85mm f/1.2L USM DS 镜头，广告级 Key Visual 视觉概念。在极简黑色大理石台面上，静止平放着一颗高透光玻璃材质的透明医药胶囊。胶囊内部封存着一颗微型金属大脑，大脑内部的精密齿轮被一个红色的物理休止符按钮（⏸️）卡住。大理石表面以雕刻工艺深度嵌入着中文“思想止痛药”。单侧柔光箱勾勒出玻璃的高光轮廓，焦外极其柔美。极简、冷酷、真实摄影质感，--ar 2.35:1

【英文 Prompt】
Shot on Canon EOS R3 with Canon RF 85mm f/1.2L USM DS lens, minimalist advertising Key Visual concept. On a dark minimalist black marble surface, a crystal-clear glass medicine capsule rests in sharp focus. Encapsulated inside is a microscopic metallic human brain, its intricate gears jammed by a prominent red physical pause button symbol (⏸️). Deeply engraved into the marble surface is organic physical typography reading "PAIN RELIEVER". Lit with Canon's signature high-end studio lighting, single softbox casting crisp highlights. Ultra-shallow depth of field. Pure photographic realism, --ar 2.35:1
```

---

## 🤝 参与贡献

非常欢迎提交 Pull Request 来完善镜头库或新增 Visual Trigger！请参阅 [CONTRIBUTING.md](CONTRIBUTING.md) 了解详细指南。

---

## 📄 开源许可证

本项目基于 [MIT License](LICENSE) 协议开源，欢迎自由使用、修改与传播。
