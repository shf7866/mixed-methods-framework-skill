# 学术研究方法教程集

本仓库收录了面向学术研究（特别是管理学、心理学、教育学领域）的完整研究方法教程，涵盖混合研究方法与潜在类别分析两大范式。

## 📚 教程列表

### 1. 混合研究方法教程（SEM + NCA + QCA）

**文件**: `tutorials/混合研究方法教程_SEM_NCA_QCA.md` / `.html`

**方法范式**: 变量中心（Variable-Centered）

**核心内容**:
- SEM（结构方程模型）：检验变量间的平均效应
- NCA（必要条件分析）：识别必要条件瓶颈
- QCA（定性比较分析）：揭示因果组态路径
- 三种方法的整合策略与结果解释框架
- R / Stata / Mplus 完整代码模板

**适用场景**: 检验变量间复杂关系、探索多重因果关系、顶刊发表（AMJ、JAP等）

---

### 2. 潜在类别分析教程（LCA / LPA / LTA）

**文件**: `tutorials/潜在类别分析LCA_LPA_LTA完整教程.md` / `.html`

**方法范式**: 人中心（Person-Centered）

**核心内容**:
- LCA（潜在类别分析）：识别类别变量构成的异质子群体
- LPA（潜在剖面分析）：识别连续变量构成的异质子群体
- LTA（潜在转变分析）：捕捉类别成员身份的纵向转换
- 前沿扩展：多组LCA、多层LTA、贝叶斯模型、时变协变量
- 模型拟合指标、类别数确定、结果可视化
- R / Mplus 完整代码模板

**适用场景**: 识别异质子群体、捕捉发展轨迹、顶刊发表（Journal of Applied Psychology、Personnel Psychology等）

---

## 🎯 方法选择指南

| 研究问题 | 推荐方法 | 教程 |
|---------|---------|------|
| "X对Y的平均效应是多少？" | SEM | 教程1 |
| "X是Y的必要条件吗？" | NCA | 教程1 |
| "哪些条件组合导致Y？" | QCA | 教程1 |
| "存在哪些异质子群体？" | LCA / LPA | 教程2 |
| "子群体如何随时间变化？" | LTA | 教程2 |

**组合使用**: 两份教程的方法可以互补。例如，先用LCA识别子群体，再用SEM检验群体内差异；或用QCA识别组态路径，再用LCA检验路径的异质性。

---

## 🚀 快速开始

### 阅读 HTML 版本（推荐）

HTML 版本使用交互式模板，带折叠目录和导航，适合长文档阅读。

1. 下载仓库
   ```bash
   git clone https://github.com/shf7866/mixed-methods-framework-skill.git
   ```

2. 在浏览器中打开 HTML 文件
   - `tutorials/混合研究方法教程_SEM_NCA_QCA.html`
   - `tutorials/潜在类别分析LCA_LPA_LTA完整教程.html`

### 使用 Markdown 版本

Markdown 版本便于编辑和版本控制，可直接在 GitHub 查看或下载后用 Markdown 编辑器打开。

---

## 📋 教程特色

- ✅ **系统全面**：从理论到实践的完整流程（每份教程约2.5万字）
- ✅ **实战导向**：包含完整的 R / Mplus / Stata 代码模板
- ✅ **顶刊标准**：符合 AMJ、JAP、Personnel Psychology 等顶刊报告规范
- ✅ **前沿覆盖**：介绍多组分析、贝叶斯模型、时变协变量等前沿方法
- ✅ **可视化丰富**：提供结果可视化方案和 R 代码
- ✅ **交互式阅读**：HTML 版本带导航目录，阅读体验佳

---

## 🛠️ 软件与工具

| 方法 | 推荐软件 | 教程中提供的代码 |
|------|---------|-----------------|
| SEM | Mplus（推荐）/ lavaan（R） | R + Mplus |
| NCA | R（NCA package） | R |
| QCA | R（QCA package）/ fsQCA | R |
| LCA / LPA | Mplus（推荐）/ poLCA（R）/ tidyLPA（R） | R + Mplus |
| LTA | Mplus（推荐）/ LTA（R） | R + Mplus |

---

## 📖 参考文献

教程中引用的关键文献：

**混合研究方法**:
- Mayerl (2024) - NCA + SEM 整合
- Mokhtarian et al. (2022) - SEM + NCA + QCA 三元整合
- Dul (2020) - NCA 必要条件分析
- Ragin (2008) - QCA 定性比较分析

**潜在类别分析**:
- Collins & Lanza (2010) - LCA/LTA 权威指南
- Morin et al. (2016) - LPA 在应用研究中的报告规范
- Nylund-Gibson & Choi (2018) - LTA 前沿发展

---

## 🤝 贡献与反馈

如果你发现教程中有任何错误、需要补充的内容，或想分享使用这些方法的经验，欢迎：

1. 提交 Issue
2. 提交 Pull Request
3. 联系作者

---

## 📄 许可证

本教程采用 MIT 许可证。你可以自由使用、修改和分发，但请注明出处。

---

## ✍️ 关于作者

本教程由学术研究方法爱好者编写，旨在为国内学者提供系统、实用、前沿的研究方法指南。

如有任何问题或建议，欢迎通过 GitHub Issue 联系。

---

**最后更新**: 2026年6月
