# Monetization Guide — 商业化负责人方案产出指南

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Version](https://img.shields.io/badge/version-1.0.0-green.svg)](SKILL.md)

一个面向 AI 编程助手的 **商业化负责人 Skill**，将商业变现方法论转化为可执行工作流。自动识别 5 类场景（0→1 商业化体系搭建 / 中大型商业化项目 / 小优化定价调整 / 商业化模式转型 / 商业化探索），按对应清单产出商业模式、定价策略、销售漏斗、客户成功体系等完整交付物。

## 适用场景

| 场景 | 示例 | 产出量 |
|------|------|:---:|
| 0→1 商业化体系搭建 | 新产品从0搭建付费/销售体系 | 10-12类 |
| 中大型商业化项目 | 新付费线、新市场拓展、定价重组 | 6-8类 |
| 小优化/定价调整 | 单SKU调价、促销活动 | 2-3类 |
| 商业化模式转型 | 免费→付费、一次性→订阅制 | 8-10类 |
| 商业化探索 | 新变现模式可行性、竞品商业模式分析 | 3-4类 |

## 触发热词

商业化、变现、定价、订阅、付费、SaaS、SKU、销售、MRR、ARR、LTV、商业模式

---

## 安装

本 Skill 遵循 **Open Agent Skills 标准**（SKILL.md 格式），兼容以下工具：

### WorkBuddy / CodeBuddy

**方式一：克隆到 skills 目录**
```bash
git clone https://github.com/genapohub/monetization-guide.git ~/.workbuddy/skills/monetization-guide
```

### Trae

**ZIP 导入**
```bash
git clone https://github.com/genapohub/monetization-guide.git
zip -r monetization-guide.zip monetization-guide/
```
然后在 Trae → **设置** → **Rules & Skills** → **创建** → 上传 `monetization-guide.zip`。

### Codex

```bash
# 克隆到 skills 目录
git clone https://github.com/genapohub/monetization-guide.git ~/.codex/skills/monetization-guide

# 或使用 cc switch (推荐)
git clone https://github.com/genapohub/monetization-guide.git ~/.cc-switch/skills/monetization-guide
```

若选 CC Switch 克隆后需在cc switch客户端-技能中心里导入技能，选中Codex等工具，重启Codex客户端后在对话中输入 $monetization-guide 手动调用。

### Cursor
```bash
# 克隆到 skills 目录
git clone https://github.com/genapohub/monetization-guide.git ~/.cursor/skills-cursor/monetization-guide
```

重启 Cursor客户端 后自动发现。也可以在对话中输入 `$monetization-guide` 手动调用。

---

## 使用

```
帮我设计SaaS产品的定价策略
从免费转向付费，怎么过渡
销售漏斗怎么搭建
竞品是怎么变现的，帮我拆解
```

## 许可

[MIT](LICENSE) © zhangmengbo
