# 团队六边形战力演算器 (Team Hexagon Power Calculator)

一个基于 Bauhaus 设计风格的团队能力评估工具，支持四维对比分析。

## 🎯 在线体验

🔗 [https://isalicema.github.io/radar-calculator/](https://isalicema.github.io/radar-calculator/)

## ✨ 功能特性

### 四维评估体系

| 维度 | 说明 | 获胜条件 |
|------|------|----------|
| **Weighted Score** (加权总分) | 根据权重计算加权平均分 | 分数最高 |
| **Radar Area** (雷达面积) | 使用鞋带公式计算雷达图多边形面积 | 面积最大 |
| **Average Score** (平均分) | 六个维度的简单算术平均 | 分数最高 |
| **Balance** (均衡度) | 标准差转换为 0-100% 的均衡度分数 | 分数最高 |

### 权重配置

- **S级 (2.0x)**: 技术实力、创新性
- **A级 (1.5x)**: 团队匹配度、野心愿景
- **B级 (1.0x)**: 市场空间、商业化现状

### 支持功能

- ✅ 多团队对比（最多9个团队）
- ✅ 实时雷达图可视化
- ✅ 中英文双语切换
- ✅ 数据本地缓存
- ✅ 响应式设计

## 📊 均衡度计算

将标准差转换为直观的百分比：

```
Balance = (1 - σ/σₘₐₓ) × 100%

其中:
σ = √[Σ(xᵢ - μ)² / n]  (标准差)
σₘₐₓ = 50  (理论最大标准差)
```

- 100% = 完美均衡（所有维度相同）
- 0% = 极度不均衡

## 🎨 设计特色

- **Bauhaus 包豪斯风格**：红黄蓝黑配色，几何构图
- **对比鲜明**：高对比度黑白灰，突出重点
- **信息密度**：单屏展示所有关键信息

## 📁 文件结构

```
radar-evaluator/
├── index.html          # 原版（加权总分 vs 雷达面积）
├── index-v2.html       # 新版（四维评估）⭐ 推荐
├── radar_comparison.png
└── radar_comparison_merged.png
```

## 🚀 本地运行

```bash
# 克隆仓库
git clone https://github.com/isalicema/radar-calculator.git

# 进入目录
cd radar-calculator

# 打开页面
open index-v2.html
```

## 📝 更新日志

### v2.0 (2026-03-13)
- 新增 Average Score 和 Balance 两个评估维度
- 优化对比表格，统一显示格式
- 添加完整的中英文支持
- 改进均衡度计算，显示为百分比

### v1.0 (2026-03-11)
- 初始版本发布
- 支持加权总分和雷达面积对比
- Bauhaus 风格设计

## 📄 许可证

MIT License

---

Made with 🌱 by Machiwhale Studio