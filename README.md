# 高性能计算与人工智能应用

**Math on AI · 2026 年秋季 · 清华大学求真书院**

从数学走近生成式人工智能。本课程围绕大基础模型，介绍概率建模、训练算法、生成过程及其计算实现，并讨论世界模型、强化学习、推理、智能体和科学应用。

[课程导论 PDF](lectures/source/compiled_pdfs/lecture0_introduction.pdf) · [全部课件](lectures/source/compiled_pdfs/) · [课程讲义](book/compiled_pdfs/book.pdf)

## 课程信息

| 项目 | 内容 |
| --- | --- |
| 课程名称 | 高性能计算与人工智能应用 |
| 授课教师 | 胡丕丕 |
| 开课单位 | 清华大学求真书院 |
| 学期 | 2026 年秋季 |
| 上课时间 | 第1–16周，星期四第2节 |
| 上课地点 | 清华大学六教6B404 |

## 学习目标

课程以概率、动力学与计算为主线，结合推导、代码和实验，帮助同学们：

- 理解生成模型学习的分布、目标函数和采样过程。
- 比较自回归、VAE、GAN、归一化流、扩散、流匹配和离散扩散的数学构造。
- 从头实现小模型，分析模型表达、训练优化与数值采样带来的误差。
- 评估训练和生成的效率，关注网络调用次数、耗时、显存与并行计算。
- 理解生成建模与世界模型、强化学习、推理、智能体和科学问题的联系。

导论从双峰分布出发，介绍点预测与分布学习的区别，再通过流匹配说明训练目标、生成动力学与数值误差的关系。课件还收录了 Rich Sutton 的《苦涩的教训》，用于讨论搜索、学习和计算规模之间的关系。

## 考核方式

| 考核部分 | 占比 | 内容 |
| --- | --- | --- |
| 平时成绩 | 50% | 几次课后作业、两次课堂小作业 |
| 课程大作业 | 50% | 课程大作业 |

**两次课堂小作业不能使用大模型。** 题目比较简单，主要考查对课程概念与基本原理的理解。

日常学习中鼓励使用 AI 辅助解释概念、编写代码和设计测试。提交的推导与代码需要自己理解并核验，同时记录关键帮助、修改过程和验证方法。

## 课程内容与课件

以下按资料编号列出课程主题，具体教学进度结合课堂与实践安排。

| 编号 | 主题 | 主要内容 |
| --- | --- | --- |
| [第0讲](lectures/source/compiled_pdfs/lecture0_introduction.pdf) | 课程导论 | 学习目标、生成模型概览、计算与实验、考核方式 |
| [第1讲](lectures/source/compiled_pdfs/lecture1_diffusion_model.pdf) | 扩散模型 | 加噪、去噪、score 与反向生成 |
| [第2讲](lectures/source/compiled_pdfs/lecture2_Flow_matching.pdf) | 流匹配 | 概率路径、速度场、ODE 与采样 |
| [第3讲](lectures/source/compiled_pdfs/lecture3_vae.pdf) | 变分自编码器 | 隐变量、变分推断与训练方法 |
| [第4讲](lectures/source/compiled_pdfs/lecture4_normalizing_flow.pdf) | 归一化流 | 可逆变换、变量代换与条件生成 |
| [第5讲](lectures/source/compiled_pdfs/lecture5_GANs.pdf) | 生成对抗网络 | 对抗训练、生成质量与分布覆盖 |
| [第6讲](lectures/source/compiled_pdfs/lecture6_autoregressive.pdf) | 自回归模型 | 条件概率分解、Transformer 与序列生成 |
| [第7讲](lectures/source/compiled_pdfs/lecture7_discrete_diffusion.pdf) | 离散扩散 | 离散状态转移与生成建模 |
| [第8讲](lectures/source/compiled_pdfs/lecture8_world_model.pdf) | 世界模型 | 状态表示、动力学预测与规划 |
| [第9讲](lectures/source/compiled_pdfs/lecture9_reinforcementlearning.pdf) | 强化学习 | 策略、价值、交互反馈与长期回报 |
| [第10讲](lectures/source/compiled_pdfs/lecture10_reasoning.pdf) | 推理 | 大模型的推理方法与能力 |
| [第11讲](lectures/source/compiled_pdfs/lecture11_agent.pdf) | 智能体 | 模型、工具、记忆与环境交互 |
| [第12讲](lectures/source/compiled_pdfs/lecture12_ai4science.pdf) | 科学智能 | 生成模型在科学计算与研究中的应用 |

## 学习准备

- **数学基础**：微积分、线性代数与基本概率，熟悉条件概率、期望、梯度和矩阵运算。
- **编程基础**：能够阅读和修改 Python，逐步熟悉 PyTorch 张量、自动微分、训练循环与调试。
- **学习方法**：核对定义与假设，将公式转为代码，通过反例和对照实验检查结论。

学习过程中可以结合具体问题补充背景知识。课堂欢迎有依据的不同意见，鼓励同学们独立解释、实现和判断。

## 资料与使用方式

- **课件源码**：[lectures/source/](lectures/source/)，包含各讲 LaTeX 文件。
- **课件 PDF**：[lectures/source/compiled_pdfs/](lectures/source/compiled_pdfs/)。
- **课程图片**：[lectures/figures/](lectures/figures/)。
- **课程讲义**：[book.pdf](book/compiled_pdfs/book.pdf)，持续整理中；章节源码见 [book/chapters/](book/chapters/)。
- **作业资料**：[生成模型作业](lectures/source/compiled_pdfs/homework1_generative_models.pdf)，涉及扩散、流匹配、VAE、归一化流与 GAN。
- **代码示例**：[examples/](examples/)，包含扩散模型 Notebook 和训练脚本，持续完善中。

### 下载仓库

```bash
git clone https://github.com/cam1681/CS25_Large_Foundation_model.git
cd CS25_Large_Foundation_model
```

### 编译课程导论

导论使用 XeLaTeX，需安装包含中文支持的 TeX Live 或同类 LaTeX 环境，以及 `latexmk`。

```bash
cd lectures/source
latexmk -xelatex -interaction=nonstopmode -halt-on-error \
  -outdir=compiled_pdfs lecture0_introduction.tex
```

## 目录结构

```text
CS25_Large_Foundation_model/
├── lectures/
│   ├── source/             # 课件与作业的 LaTeX 源码
│   │   └── compiled_pdfs/  # 编译后的 PDF
│   └── figures/            # 课件图片
├── book/
│   ├── book.tex            # 讲义主文件
│   ├── chapters/           # 章节源码
│   └── compiled_pdfs/      # 讲义 PDF
└── examples/
    ├── notebooks/          # 交互式示例
    ├── scripts/            # 训练脚本
    ├── datasets/           # 数据说明
    └── requirements.txt    # Python 依赖
```

## 参与完善与致谢

欢迎通过 Issue 或 Pull Request 反馈公式与代码问题、改进讲解、补充示例。

课程资料制作过程中使用了 Cursor 和大模型辅助整理文献、生成插图、搭建讲义与代码框架、调整排版和校对文字。内容与结果仍需人工检查和验证。

## 引用与使用

课程资料用于教学与学习。使用其中内容时，请注明来源，并尊重引用文献和第三方图片的权利。

引用当前课程资料可使用：

```bibtex
@misc{hu2026_math_on_ai,
  title={高性能计算与人工智能应用},
  author={胡丕丕},
  year={2026},
  institution={清华大学求真书院},
  url={https://github.com/cam1681/CS25_Large_Foundation_model},
  note={Math on AI，2026年秋季课程资料}
}
```
