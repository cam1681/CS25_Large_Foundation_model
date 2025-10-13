# Large Foundation Models: Mathematics, Algorithms, and Applications

<div align="center">

**CS25 Course - Autumn 2025**  
*Beijing Institute of Mathematical Sciences and Applications (BIMSA)*

[![Course Status](https://img.shields.io/badge/Status-Course_Info-brightgreen)](https://bimsa.net/activity/LarFouModMatAlgandApp/)
[![Instructor](https://img.shields.io/badge/Instructor-Pipi%20Hu-blue)](https://bimsa.net/people/pipihu/)
[![Format](https://img.shields.io/badge/Format-Online%20%7C%20In--Person-orange)](#location--schedule)

</div>

---

## Course Overview

This comprehensive course explores the mathematical foundations, algorithmic implementations, and practical applications of **Large Foundation Models**. Students will gain deep understanding of modern generative AI through rigorous mathematical treatment and hands-on implementations.

### Learning Objectives

By the end of this course, you will be able to:

- **Explain** what it means to learn a data distribution $p_\theta(\mathbf{x})$ or conditional $p_\theta(\mathbf{x}\mid\mathbf{c})$
- **Compare** the five major families: Autoregressive, VAE, GAN, Normalizing Flows, Diffusion/Flow Matching
- **Relate** training objectives to a unifying divergence/likelihood view
- **Distinguish** training vs. sampling costs and typical latency/quality trade-offs
- **Choose** appropriate model families for specific tasks
- **Understand** how reinforcement learning works in the context of foundation models
- **Construct** your own models from scratch

---

## Course Materials

### Lecture Slides

All lecture slides are available in the [`lectures/`](lectures/) directory:

- **Source Files**: LaTeX source files in [`lectures/source/`](lectures/source/)
- **Figures**: All course figures in [`lectures/figures/`](lectures/figures/)
- **Compiled PDFs**: Ready-to-use PDF slides in [`lectures/source/compiled_pdfs/`](lectures/source/compiled_pdfs/)
- **Individual Lectures**: Each lecture has its own slide deck
- **Introduction**: [`lecture0_introduction.pdf`](lectures/source/compiled_pdfs/lecture0_introduction.pdf) - Course overview and objectives

### Course Book

Comprehensive course materials are available in the [`book/`](book/) directory:

- **Main Book**: [`book.pdf`](book/compiled_pdfs/book.pdf) - course textbook under construction
- **Individual Chapters**: Source files in [`book/chapters/`](book/chapters/)


### Course Content

The course covers 13 comprehensive lectures on Large Foundation Models:

| Lecture | Topic | Description |
|---------|-------|-------------|
| **Lecture 0** | Introduction | Course overview and objectives |
| **Lecture 1** | Diffusion Models | Mathematical foundations of diffusion models and the algorithms |
| **Lecture 2** | Flow Matching | flow matching and its relation with Diffusion|
| **Lecture 3** | Variational Autoencoders | VAE theory and implementation |
| **Lecture 4** | Normalizing Flows | Normalizing flow architectures and conditional normalizing flow |
| **Lecture 5** | Generative Adversarial Networks | GAN theory and training |
| **Lecture 6** | Autoregressive Models | Transformer architectures and autoregressive generation |
| **Lecture 7** | Discrete Diffusion | Discrete diffusion models and language generation by diffusion |
| **Lecture 8** | World Models | World models in machine learning and AGI |
| **Lecture 9** | Reinforcement Learning | RL in the context of foundation models |
| **Lecture 10** | Reasoning | Large foundation models and reasoning capabilities |
| **Lecture 11** | Agent Technologies | LLM agents and intelligent systems |
| **Lecture 12** | AI for Science | Modern machine learning algorithms for the important scientific problems |

---

## Course Information

### Location & Schedule

- **Online Access**: [Course Website](https://bimsa.net/activity/LarFouModMatAlgandApp/)
- **In-Person**: Room C546, Shuangqing Complex Building A, Tsinghua University （校外，清华大学双清综合楼A座C546）
- **Semester**: Autumn 2025
- **Institution**: [Beijing Institute of Mathematical Sciences and Applications (BIMSA)](https://www.bimsa.cn/)

### Instructor

**[Pipi Hu](https://bimsa.net/people/pipihu/)**  
*Beijing Institute of Mathematical Sciences and Applications*

---

## Technical Prerequisites

### Mathematical Background
- Linear Algebra
- Probability Theory I with basic concepts of conditional probability
- Calculus I/II with basic understanding of multivariable calculus
- Basic Machine Learning concepts such as MLP, nonlinear activations, and backpropagation

### Programming Skills
- Basic Python and PyTorch programming skills
- Basic understanding of neural networks

---

## Repository Structure

```
CS25_Large_Foundation_model/
├── lectures/                      # Lecture materials and slides
│   ├── source/                    # Source LaTeX files
│   │   ├── lecture0_introduction.tex
│   │   ├── lecture1_diffusion_model.tex
│   │   ├── lecture2_Flow_matching.tex
│   │   ├── lecture3_vae.tex
│   │   ├── lecture4_normalizing_flow.tex
│   │   ├── lecture5_GANs.tex
│   │   ├── lecture6_autoregressive.tex
│   │   ├── lecture7_discrete_diffusion.tex
│   │   ├── lecture8_world_model.tex
│   │   ├── lecture9_reinforcementlearning.tex
│   │   ├── lecture10_reasoning.tex
│   │   ├── lecture11_agent.tex
│   │   ├── lecture12_ai4science.tex
│   │   ├── compiled_pdfs/         # Generated PDF slides
│   │   └── README.md             # Lecture documentation
│   ├── figures/                   # Course figures and diagrams
│   └── README.md                  # Lecture documentation
├── book/                          # Course book and comprehensive materials
│   ├── book.tex                   # Main book source
│   ├── compiled_pdfs/            # Compiled book PDF
│   ├── chapters/                  # Individual book chapters
│   ├── figures/                   # Book figures and diagrams
│   └── README.md                  # Book documentation
└── examples/                      # Code examples and implementations
    ├── notebooks/                 # Jupyter notebooks
    ├── scripts/                   # Python scripts
    ├── datasets/                  # Sample datasets
    ├── requirements.txt           # Python dependencies
    └── README.md                  # Examples documentation
```

---

## Getting Started

### Accessing Materials

1. **Clone the repository**:
   ```bash
   git clone https://github.com/cam1681/CS25_Large_Foundation_model.git
   cd CS25_Large_Foundation_model
   ```

2. **View course materials**:
   - **Lectures**: Navigate to the [`lectures/`](lectures/) directory for lecture materials and slides
   - **Book**: Check the [`book/`](book/) directory for comprehensive course materials
   - **Examples**: Explore the [`examples/`](examples/) directory for code implementations


### Current Status

- **13 Complete Lectures**: All lecture materials are ready
- **Figure Integration**: All figures are properly linked and accessible
- **PDF Generation**: All lectures compile to high-quality PDFs
- **Course Book**: Comprehensive textbook is under construction
- **Code Examples**: Implementation examples and datasets are under construction

### Key Features

- **Mathematical Foundation**: Deep mathematical understanding of all topics
- **Practical Implementation**: Hands-on code examples and implementations
- **Comprehensive Coverage**: From basic concepts to advanced applications
- **Multiple Formats**: Both lecture slides and comprehensive book (under construction)
- **Real-world Applications**: Focus on practical applications and use cases

---

## Course Philosophy

> **"The Bitter Lesson"** - *Rich Sutton*
> 
> Hand-crafted domain knowledge scales poorly; progress comes from **general-purpose** methods that learn directly from data with lots of compute. Design **mathematical learning algorithms** so models **acquire** the distribution, rather than hard-coding it.

### Key Principles

- **Scalable Objectives**: Maximize $\log p_\theta(\mathbf{x})$ or minimize divergence $D(p_{\text{data}} \Vert p_\theta)$
- **Generic Representations**: Use data-driven architectures (Transformers, CNNs, U-Nets)
- **Scale Data/Compute**: Reduce bespoke heuristics and narrow domain rules
- **Self-Supervision**: Leverage generic, data-driven representations

---

## Contributing

This course material is actively maintained. Contributions are welcome for:

- Content improvements
- Bug fixes
- Visual enhancements
- Additional examples

---
## Acknowledgement

This course material is built with the help of Large Foundation Models through Cursor Editor, including:

- Summarizing the initial several slides from published papers
- Generating illustrations of the figures
- Converting the lecture slides to the initial backbone of the book
- Reorganizing the structure of the repo and helping to modify the README.md file
- Providing the initial structure of the example codes
- Correcting grammer errors.

This course on Large Foundation Models and the construction of the course materials also benefits from Large Foundation Models. In my experience, they really accelerate the process of spreading knowledge and summarizing ideas without redundant dirty work. One can focus more on high-level abstract ideas and have the repeated dirty work done by LLMs with human guidance and monitoring.  

---

## Citation

If you use this course material in your research or teaching, please cite it as follows:

```bibtex
@misc{cs25_large_foundation_models_2025,
  title={Large Foundation Models: Mathematics, Algorithms, and Applications},
  author={Pipi Hu},
  year={2025},
  institution={Beijing Institute of Mathematical Sciences and Applications (BIMSA)},
  url={https://github.com/cam1681/CS25_Large_Foundation_model},
  note={CS25 Course - Autumn 2025}
}
```

**BibTeX Entry:**
```bibtex
@misc{cs25_large_foundation_models_2025,
  title={Large Foundation Models: Mathematics, Algorithms, and Applications},
  author={Pipi Hu},
  year={2025},
  institution={Beijing Institute of Mathematical Sciences and Applications (BIMSA)},
  url={https://github.com/cam1681/CS25_Large_Foundation_model},
  note={CS25 Course - Autumn 2025}
}
```

---

## License

This course material is provided for educational purposes. Please respect the intellectual property rights and cite appropriately when using these materials.

---

## Contact

For questions about the course content or materials:

- **Course Website**: [BIMSA Course Page](https://bimsa.net/activity/LarFouModMatAlgandApp/)
- **Instructor**: [Pipi Hu](https://bimsa.net/people/pipihu/)
- **Institution**: [Beijing Institute of Mathematical Sciences and Applications](https://www.bimsa.cn/)

---

<div align="center">

**Happy Learning!**

*Man is born to a better life with the AI Copilot*

</div>