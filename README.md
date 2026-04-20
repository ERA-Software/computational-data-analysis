# Computational Data Analysis with Python (CDAP)

TUM School of Engineering and Design  

Instructors: Pablo G. Morato, Lorenzo Brocchi, Chupei Lin, Theresa Hefele, and Daniel Straub

---

## Overview

We live in a data-driven world where decisions in engineering, science, and society are increasingly shaped by data. This course equips students with the tools to:

- Formulate meaningful questions  
- Analyze real-world and synthetic data  
- Build predictive models  
- Communicate insights for decision-making  

Computational Data Analysis is not just about tools. It is a structured, iterative process that transforms raw data into actionable knowledge.

---

## Learning Objectives

By the end of this course, you will be able to:

- Formulate data-driven problems from real-world contexts  
- Think algorithmically using Python  
- Collect, clean, and process data  
- Build and validate predictive models  
- Visualize and communicate results effectively  
- Translate analysis into actionable decisions

---

## Course Structure

Each week follows a structured format:

### Pre-class (1–2 hours)
- Readings and videos  
- Quizzes and small coding tasks  

### In-class sessions

**Fundamentals (08:00 – 09:30)**  
- Concepts and theory  
- Real-world examples  
- Interactive discussions  

**Hackathon (10:00 – 11:30)**  
- Hands-on coding  
- Project work and feedback  

The course emphasizes learning by doing, with a strong focus on practical implementation.

---

## Project

The project runs from **Week 2 to the end of the course**.

Students will work in teams to:

- Define a data-driven problem  
- Develop a complete analysis pipeline  
- Implement models in Python  
- Present results and insights  

See the [`project/`](./project) folder for details on project tracks and guidelines.

---

## Repository Structure

```text
.
├── notebooks/          # Lecture notebooks and in-class exercises
│   ├── week01_intro.ipynb
│   ├── week02_wrangling.ipynb
│   └── ...
├── project/            # Project description, tracks, and guidelines
│   ├── README.md
│   ├── tracks.md
│   └── data/           # (optional) small sample datasets
├── LICENSE
└── README.md
```

---

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/your-username/computational-data-analysis.git
cd computational-data-analysis
```

### 2. Create a Python environment

```bash
python -m venv .venv
```

Activate the environment:

**macOS / Linux**
```bash
source .venv/bin/activate
```

**Windows**
```bash
.venv\Scripts\activate
```

### 3. Install dependencies

```bash
pip install numpy pandas matplotlib scikit-learn jupyter
```

Optional, recommended for a cleaner setup:

```bash
pip install jupyterlab seaborn
```

### 4. Launch Jupyter

```bash
jupyter notebook
```

or

```bash
jupyter lab
```

---

## License

This repository is licensed under the MIT License. See the `LICENSE` file for details.


