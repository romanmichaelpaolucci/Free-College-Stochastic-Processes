# 🎲 Free College: Stochastic Processes

### A Free, Open-Source Course by Quant Guild

**Learn to model randomness, understand systems that evolve over time, and build the mathematical foundations of quantitative finance, machine learning, and applied probability.**

Welcome to **Free College: Stochastic Processes**, a 16-week, upper-level undergraduate course offered by **Quant Guild**.

This course provides a rigorous yet approachable introduction to stochastic processes: mathematical models for systems that evolve unpredictably over time.

From random walks and Markov chains to Poisson processes, queueing systems, and Brownian motion, we'll develop the theory, solve practical problems, and explore how randomness can be understood mathematically.

Our philosophy is simple:

> **High-quality quantitative education should be accessible to everyone.**

No tuition. No gatekeeping. Just mathematics, curiosity, and a community of learners.

---

## 📚 Course at a Glance

| | |
|---|---|
| 🏛️ **Organization** | Quant Guild |
| 🎓 **Program** | Free College |
| 📖 **Course** | Stochastic Processes |
| 📅 **Duration** | 16 instructional weeks + orientation |
| ⏱️ **Lecture Length** | 75 minutes |
| 🧮 **Level** | Upper-Level Undergraduate |
| 📕 **Textbook** | *Introduction to Probability Models*, Sheldon M. Ross, 10th Edition |
| 💻 **Format** | Lectures, mathematical derivations, exercises, and computational demonstrations |
| 💰 **Cost** | Free |
| 🌍 **Audience** | Anyone interested in probability, mathematics, or quantitative modeling |

## 🎯 What You'll Learn

By the end of this course, you should be able to:

- **Understand stochastic processes:** Define and classify random processes using their time and state spaces.
- **Analyze Markov chains:** Work with transition matrices, communicating classes, stationary distributions, and hitting times.
- **Model random arrivals:** Understand Poisson processes, exponential waiting times, and compound Poisson models.
- **Study continuous-time systems:** Construct CTMCs using generator matrices, birth–death processes, and Kolmogorov equations.
- **Understand renewal theory:** Analyze repeated random events and calculate long-run rewards and costs.
- **Model queueing systems:** Apply Little's law and analyze M/M/1 and finite-capacity queues.
- **Explore Brownian motion:** Understand Gaussian increments, covariance, and Brownian motion with drift.
- **Connect theory to computation:** Use simulations to investigate and validate mathematical results.

The emphasis is on building mathematical intuition alongside the ability to derive, calculate, and interpret results.

---

## 🧠 Prerequisites

This is an upper-level undergraduate mathematics course.

You should be comfortable with:

- **Probability:** Random variables, probability distributions, conditional probability, independence, expectation, and variance.
- **Calculus:** Differentiation, integration, infinite series, and basic differential equations.
- **Linear Algebra:** Matrix multiplication, matrix powers, and systems of linear equations.
- **Mathematical Reasoning:** Following derivations and constructing mathematical arguments.

**Programming:** Python familiarity is helpful for computational demonstrations but is not a strict prerequisite.

We'll briefly review essential probability concepts before moving into stochastic processes.

---

## 🗺️ Course Roadmap

The course is organized into five major units.

| Unit | Weeks | Topics |
|---|---|---|
| **I. Foundations & Markov Chains** | 1–7 | Probability review, discrete-time Markov chains, recurrence, stationary distributions, random walks, reversibility |
| **II. Poisson Processes** | 7–10 | Exponential distributions, Poisson arrivals, thinning, superposition, nonhomogeneous and compound Poisson processes |
| **III. Continuous-Time Markov Chains** | 10–13 | Generator matrices, birth–death processes, Kolmogorov equations, stationary distributions |
| **IV. Renewal & Queueing Theory** | 13–15 | Renewal processes, renewal reward theorem, Little's law, M/M/1 queues |
| **V. Brownian Motion & Synthesis** | 16 | Brownian motion, drift, diffusion, and connections across stochastic models |

### Course Progress Tracker

Use this checklist to track your progress throughout the semester.

- [ ] **Week 0:** Orientation, syllabus, resources, GitHub, and probability review
- [ ] **Week 1:** Foundations of stochastic processes
- [ ] **Week 2:** Discrete-time Markov chains
- [ ] **Week 3:** State classification
- [ ] **Week 4:** Stationary and limiting behavior
- [ ] **Week 5:** Random walks and absorption
- [ ] **Week 6:** Reversibility and Markov chain review
- [ ] **Week 7:** Midterm 1 and exponential distributions
- [ ] **Week 8:** Poisson process fundamentals
- [ ] **Week 9:** Advanced Poisson processes
- [ ] **Week 10:** Compound Poisson processes and CTMC introduction
- [ ] **Week 11:** Birth–death processes and Kolmogorov equations
- [ ] **Week 12:** CTMC long-run behavior
- [ ] **Week 13:** Midterm 2 and renewal processes
- [ ] **Week 14:** Renewal theorems and rewards
- [ ] **Week 15:** Queueing theory
- [ ] **Week 16:** Brownian motion and course synthesis

---

## 📅 Weekly Lecture Schedule

Each instructional week contains two planned 75-minute lecture blocks. Topics progress from foundational probability concepts toward continuous-time models and applications.

### Unit I — Foundations & Discrete-Time Markov Chains

*Weeks 1–7*

**Week 1 — Foundations of Stochastic Processes**

- **Lecture 1:** Introduction to stochastic processes and probability refresher
- **Lecture 2:** Conditional probability, expectation, and first-step analysis

Define stochastic processes, sample paths, time spaces, and state spaces. Review essential probability concepts and derive first-step recursions using conditional expectation.

**Week 2 — Discrete-Time Markov Chains**

- **Lecture 1:** The Markov property and transition matrices
- **Lecture 2:** Chapman–Kolmogorov equations

Construct transition diagrams, calculate multi-step transition probabilities, and evolve probability distributions using matrix powers.

**Week 3 — Classification of States**

- **Lecture 1:** Communication, recurrence, and transience
- **Lecture 2:** Periodicity and absorbing chains

Classify communicating classes, identify recurrent and transient states, determine periods, and formulate absorption probabilities.

**Week 4 — Stationary & Limiting Behavior**

- **Lecture 1:** Stationary distributions
- **Lecture 2:** Limiting probabilities and long-run behavior

Solve stationary distribution equations, distinguish equilibrium from limiting behavior, and introduce long-run rewards.

**Week 5 — Random Walks & Absorption**

- **Lecture 1:** Gambler's ruin
- **Lecture 2:** Hitting times and absorption times

Analyze absorbing random walks, derive ruin probabilities, and calculate expected hitting times through first-step equations.

**Week 6 — Reversibility & Review**

- **Lecture 1:** Time reversibility and detailed balance
- **Lecture 2:** Markov chain synthesis and computational review

Study reversible chains and random walks on graphs. Integrate the major Markov-chain methods and check selected results with simulation.

**Week 7 — Midterm I & Exponential Distributions**

- **Lecture 1:** Midterm Exam I — Discrete-Time Markov Chains
- **Lecture 2:** Exponential waiting times and memorylessness

Assess Markov-chain concepts before transitioning to continuous-time probability models through exponential waiting times and competing exponential clocks.

### Unit II — Poisson Processes

*Weeks 8–10*

**Week 8 — The Poisson Process**

- **Lecture 1:** Counting processes and Poisson arrivals
- **Lecture 2:** Interarrival times and waiting times

Define the homogeneous Poisson process, derive arrival-count probabilities, and connect exponential interarrival times to Poisson counts.

**Week 9 — Advanced Poisson Processes**

- **Lecture 1:** Superposition, thinning, and conditional arrivals
- **Lecture 2:** Nonhomogeneous Poisson processes

Analyze combinations and subdivisions of Poisson streams, conditional arrival times, and time-dependent arrival intensities.

**Week 10 — Compound Poisson Processes & CTMCs**

- **Lecture 1:** Compound Poisson processes
- **Lecture 2:** Introduction to continuous-time Markov chains

Model aggregate random sums and their moments. Introduce exponential holding times, transition rates, and generator matrices.

### Unit III — Continuous-Time Markov Chains

*Weeks 11–13*

**Week 11 — Birth–Death Processes & Kolmogorov Equations**

- **Lecture 1:** Birth–death processes
- **Lecture 2:** Kolmogorov forward and backward equations

Construct state-dependent transition-rate models and derive differential equations governing continuous-time transition probabilities.

**Week 12 — Long-Run CTMC Behavior**

- **Lecture 1:** Stationary distributions for CTMCs
- **Lecture 2:** Reversibility and CTMC review

Solve global balance equations, apply detailed balance, and compare analytical predictions with simulation.

**Week 13 — Midterm II & Renewal Processes**

- **Lecture 1:** Midterm Exam II — Poisson Processes and CTMCs
- **Lecture 2:** Introduction to renewal processes

Assess continuous-time models before introducing renewal epochs, renewal counts, and general interarrival distributions.

### Unit IV — Renewal Processes & Queueing Theory

*Weeks 14–15*

**Week 14 — Renewal Theory**

- **Lecture 1:** Elementary renewal theorem
- **Lecture 2:** Renewal reward processes

Analyze long-run event frequencies and use renewal reward methods to calculate average rewards, costs, and replacement rates.

**Week 15 — Queueing Theory**

- **Lecture 1:** Queueing models and Little's law
- **Lecture 2:** M/M/1 and finite-capacity queues

Introduce arrival and service rates, utilization, and Kendall notation. Derive basic queue performance measures and study stability and blocking.

### Unit V — Brownian Motion & Course Synthesis

*Week 16*

**Week 16 — Brownian Motion**

- **Lecture 1:** Introduction to Brownian motion
- **Lecture 2:** Brownian motion with drift and course synthesis

Define Brownian motion, study Gaussian independent increments, and compute mean and covariance functions. Introduce drift and diffusion while connecting the major stochastic models studied throughout the semester.

**Scope:** Brownian motion is treated as an introduction to continuous-path stochastic processes. Stochastic integration, Itô's lemma, and stochastic differential equations are outside the core scope of this course.

---

## 📖 Textbook & Learning Resources

### Primary Textbook

**Sheldon M. Ross — *Introduction to Probability Models*, 10th Edition**

This textbook provides the main theoretical reference and a broad collection of examples and exercises.

The course follows a topic-based progression, so textbook chapters may be used selectively rather than in strict order.

### Additional Resources

Useful supplementary references include:

- **MIT OpenCourseWare:** https://ocw.mit.edu/
- **Harvard Stat 110:** https://projects.iq.harvard.edu/stat110
- **ProbabilityCourse.com:** https://www.probabilitycourse.com/
- **NumPy Documentation:** https://numpy.org/doc/
- **SciPy Documentation:** https://docs.scipy.org/doc/scipy/

These resources are optional and can help reinforce mathematical concepts and computational techniques.

---

## 💻 Computational Learning

Stochastic processes are best understood through both mathematics and experimentation.

Throughout the course, we will use computational demonstrations to visualize random systems and verify analytical results.

Potential exercises include:

- Simulating random walks and gambler's ruin
- Estimating Markov-chain stationary distributions
- Visualizing Poisson arrival processes
- Simulating birth–death chains
- Exploring renewal counting processes
- Comparing theoretical and simulated queueing performance
- Generating Brownian motion sample paths

Python is the recommended computational language.

Suggested libraries:

```python
import numpy as np
import scipy
import matplotlib.pyplot as plt
```

Computational experiments supplement mathematical derivations rather than replace them.

---

## 📝 Exams & Practice

The course includes two planned midterm assessments.

| Assessment | Timing | Primary Coverage |
|---|---|---|
| **Midterm I** | Week 7 | Probability foundations and discrete-time Markov chains |
| **Midterm II** | Week 13 | Exponential distributions, Poisson processes, and CTMCs |

Students are encouraged to practice by deriving formulas, solving textbook exercises, constructing examples, and testing mathematical predictions with simulations.

The goal is not merely to memorize formulas, but to understand **why stochastic models work and when to use them**.

---

## 🗂️ Repository Structure

The following is a suggested organization for course materials as they become available.

```text
free-college-stochastic-processes/
│
├── README.md
├── syllabus/
│   └── syllabus.md
│
├── lectures/
│   ├── week-00-orientation/
│   ├── week-01-foundations/
│   ├── week-02-markov-chains/
│   ├── week-03-state-classification/
│   ├── week-04-stationary-distributions/
│   ├── week-05-random-walks/
│   ├── week-06-reversibility/
│   ├── week-07-exponential-distributions/
│   ├── week-08-poisson-processes/
│   ├── week-09-advanced-poisson/
│   ├── week-10-compound-poisson-ctmc/
│   ├── week-11-birth-death-processes/
│   ├── week-12-ctmc-long-run/
│   ├── week-13-renewal-introduction/
│   ├── week-14-renewal-theory/
│   ├── week-15-queueing-theory/
│   └── week-16-brownian-motion/
│
├── notebooks/
├── exercises/
├── exams/
└── resources/
```

Materials, notebooks, exercises, and supporting resources can be added incrementally as the course progresses.

---

## 🚀 Getting Started

**1. Review the prerequisites**

Make sure you're comfortable with introductory probability, calculus, and basic linear algebra.

**2. Get the textbook**

The primary reference is Ross's *Introduction to Probability Models*, 10th Edition. Access to the textbook is recommended, but the course's original materials can be studied independently as they become available.

**3. Clone the repository**

```bash
git clone <repository-url>
cd free-college-stochastic-processes
```

Replace `<repository-url>` with the actual GitHub repository URL.

**4. Set up Python (optional)**

```bash
python -m venv .venv
```

Install the recommended scientific computing packages:

```bash
pip install numpy scipy matplotlib jupyter
```

**5. Begin with Week 0**

Review the syllabus, familiarize yourself with the repository, and complete the probability refresher before starting Week 1.

**6. Learn actively**

Follow the lectures, work through derivations by hand, attempt exercises, and experiment with simulations.

---

## 🤝 Contributing

Quant Guild believes that learning is a collaborative process.

Contributions that improve the accessibility, clarity, and quality of this course are welcome.

Ways to contribute include:

- Reporting mathematical errors or unclear explanations
- Suggesting additional examples or practice problems
- Contributing Python notebooks and visualizations
- Improving documentation
- Sharing useful open educational resources
- Helping other learners understand challenging concepts

For substantial changes, please open a GitHub issue to discuss your proposal before submitting a pull request.

All contributions should respect the copyright of textbooks and other third-party materials.

---

## 🌐 About Quant Guild

**Quant Guild** is a community centered on quantitative learning, mathematical thinking, and the practical application of technical knowledge.

Through **Free College**, our aim is to make rigorous, structured education available to anyone willing to put in the work.

We believe that subjects such as probability, statistics, mathematics, programming, and quantitative finance should be accessible beyond traditional academic institutions.

This course is part of that mission.

### Who Is This Course For?

- Mathematics and statistics students
- Aspiring quantitative researchers and traders
- Data scientists and machine learning practitioners
- Engineers and computer scientists
- Independent learners seeking a rigorous introduction to stochastic modeling
- Anyone who wants to understand how randomness evolves over time

Whether you're preparing for advanced coursework, exploring quantitative finance, or simply fascinated by probability, you're welcome here.

---

## ⭐ Support the Project

If you find this course useful:

- ⭐ **Star the repository** to support the project.
- 🍴 **Fork the repository** to experiment with the material.
- 🤝 **Contribute** examples, improvements, or corrections.
- 📢 **Share the course** with someone who wants to learn.

Every contribution helps make quantitative education more accessible.

---

## ⚖️ Disclaimer

This course is an independent educational initiative by Quant Guild.

It is not affiliated with or endorsed by Sheldon M. Ross or the publisher of *Introduction to Probability Models*.

References to the textbook are for educational guidance. Copyrighted textbook content is not included unless permission or applicable licensing allows it.

The course is provided for educational purposes and does not constitute financial or investment advice.

---

## 🌐 Quant Guild Around the Web

**The classroom is just the beginning.**

Quant Guild is more than a collection of lectures. It's a growing community of students, developers, researchers, and quantitative finance enthusiasts who believe in making technical education accessible to everyone.

Whether you want to watch lectures, explore open-source code, ask questions, or connect with fellow learners, there's a place for you.

### 🚀 Join the Community

| Platform | Description | Link |
|:---|:---|:---|
| 🌎 **Quant Guild** | Explore the Quant Guild platform and educational resources. | [Visit Website](https://quantguild.com) |
| 👾 **Discord** | Join the community, discuss mathematics, ask questions, and connect with other learners. | [Join Discord](https://discord.gg/quantguild) |
| 🎥 **YouTube** | Watch quantitative finance, mathematics, programming, and stochastic modeling lectures. | [Watch Lectures](https://www.youtube.com/@quantguild) |
| 🐙 **GitHub** | Explore open-source quantitative research, projects, and educational code. | [Quant Guild GitHub](https://github.com/Quant-Guild) |
| 📚 **Lecture Library** | Browse Jupyter notebooks and source code accompanying Quant Guild video lectures. | [Explore Library](https://github.com/romanmichaelpaolucci/Quant-Guild-Library) |

### 📱 Follow Quant Guild

Stay connected for educational content, new lectures, project announcements, and community updates.

| Platform | Link |
|:---|:---|
| 📸 **Instagram** | [@quantguild](https://www.instagram.com/quantguild/) |
| 𝕏 **X / Twitter** | [@quantguild](https://x.com/quantguild) |
| 💼 **LinkedIn** | [Quant Guild](https://www.linkedin.com/company/quant-guild/) |
| 🎵 **TikTok** | [@quantguild](https://www.tiktok.com/@quantguild) |
| ✍️ **Medium** | [Quant Guild Blog](https://quantguild.medium.com/) |

### 🔬 Explore More Quantitative Resources

Looking to go beyond the course? Explore these additional resources from the Quant Guild ecosystem.

- 📓 **[Quant Guild Lecture Library](https://github.com/romanmichaelpaolucci/Quant-Guild-Library)** — Open-source Jupyter notebooks and companion lecture videos.
- 🧮 **[The Gaussian Cookbook](https://gaussiancookbook.com)** — Resources focused on simulating stochastic processes.
- 👨‍🏫 **[Roman Paolucci on GitHub](https://github.com/RomanMichaelPaolucci)** — Explore projects and research from the founder of Quant Guild.

---

### 💬 Learn Together. Build Together.

Studying stochastic processes can be challenging, but you don't have to do it alone.

**Join the Quant Guild Discord** to connect with other students, share your progress, discuss difficult concepts, and continue learning beyond the lectures.

**[👾 Join the Quant Guild Community on Discord](https://discord.gg/quantguild)**

*Free education. Open knowledge. A community built around quantitative curiosity.*

---

<div align="center">

### 🎓 Quant Guild — Free College

**Learn deeply. Think mathematically. Build openly.**

*Making rigorous quantitative education accessible to everyone.*

**Welcome to Stochastic Processes.**

</div>
