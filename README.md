# Welcome to Advanced Machine Learning: SCIENTIFIC MACHINE LEARNING.

**Course number:** CISC 889-010

**Course site:** Canvas

Advanced machine learning methods for scientific computing, probabilistic modeling, deep learning, and physics-informed learning. This course explores Scientific Machine Learning (SciML), focusing on the integration of data-driven methods with mechanistic models to solve complex problems in scientific and engineering systems. Topics include physics-informed neural networks (PINNs), neural operators, and large language models. Optional topics may include graph neural networks and diffusion models, with an emphasis on modeling dynamical systems, inverse problems, and uncertainty quantification.

Students will gain hands-on experience implementing SciML approaches using modern machine learning frameworks (e.g., PyTorch, TensorFlow, and JAX) and applying them to real-world datasets. The course emphasizes both theoretical foundations and practical implementation, preparing students to develop interpretable, robust, and physically consistent models for scientific discovery and engineering applications.

[**Course schedule** (check for important dates regarding assignments, exams)](https://docs.google.com/spreadsheets/d/118OpcxvQy7__pV9KGZZGMc3EAdH9MeOO/edit?usp=sharing&ouid=108632683420235816511&rtpof=true&sd=true) **Please open using UDEL Google account.**

## Prerequisites and expected background

Students should have prior coursework or equivalent experience in:

- Calculus and linear algebra, including derivatives, gradients, matrix operations, eigenvalues, and eigenvectors
- Basic probability and statistics, including random variables, common probability distributions, expectation, and variance
- Differential equations at the level of an introductory ordinary differential equations course
- Programming in Python or a comparable language

Prior exposure to machine learning is helpful but not required. The course will provide focused reviews of the mathematical and computational foundations needed for students from physics, civil engineering, computer and information sciences, and related disciplines. Students who are uncertain about their preparation are encouraged to contact the instructor and attend office hours early in the semester.

## Learning outcomes

By the end of the course, students will be able to:

- Explain the mathematical foundations of selected machine learning methods used in scientific and engineering applications
- Implement and evaluate machine learning models using a modern computational framework such as PyTorch, TensorFlow, or JAX
- Integrate observational data with governing equations, physical constraints, or other domain knowledge
- Develop and assess models including neural networks, Gaussian processes, physics-informed neural networks, neural operators, and selected generative models
- Apply uncertainty quantification and Bayesian optimization methods to scientific and engineering problems
- Compare modeling approaches in terms of accuracy, computational cost, interpretability, robustness, and physical consistency
- Design, document, and communicate a reproducible Scientific Machine Learning project through a proposal, code repository, and oral presentation

## Recommended resources and readings

### Textbook

Christopher M. Bishop, [*Pattern Recognition and Machine Learning*](https://www.microsoft.com/en-us/research/wp-content/uploads/2006/01/Bishop-Pattern-Recognition-and-Machine-Learning-2006.pdf), Springer, 2006. This textbook is recommended as a reference; assigned course materials and announcements will be provided through Canvas.

Kevin P. Murphy, [*Probabilistic Machine Learning: An Introduction*](https://probml.github.io/pml-book/book1.html), MIT Press, 2022.

### Online resources

- [*Physics-Based Deep Learning*](https://physicsbaseddeeplearning.org/intro.html), an online introduction to combining deep learning with physical modeling
- [PINN Course 2026](https://github.com/androbomb/PINN_Course_2026), course notes, code, and examples for physics-informed neural networks

### Selected papers

- M. Raissi, P. Perdikaris, and G. E. Karniadakis, [“Physics-informed neural networks: A deep learning framework for solving forward and inverse problems involving nonlinear partial differential equations”](https://doi.org/10.1016/j.jcp.2018.10.045), *Journal of Computational Physics*, 378, 686–707, 2019. Foundational PINN paper.
- G. E. Karniadakis, I. G. Kevrekidis, L. Lu, P. Perdikaris, S. Wang, and L. Yang, [“Physics-informed machine learning”](https://doi.org/10.1038/s42254-021-00314-5), *Nature Reviews Physics*, 3, 422–440, 2021. Broad review of physics-informed learning methods and applications.
- L. Lu, X. Meng, Z. Mao, and G. E. Karniadakis, [“DeepXDE: A deep learning library for solving differential equations”](https://doi.org/10.1137/19M1274067), *SIAM Review*, 63(1), 208–228, 2021. Practical PINN algorithms and an educational software framework.

## Instructor info

- Name: Yixiang Deng
- Email: yixiangd@udel.edu
- Preferred contact method: Email with the subject line containing **[CISC889]**
- Meetings outside the designated office hours require an appointment requested at least 24 hours in advance.

## Lecture info

- Time: Tu Th 3:55 PM - 5:15 PM
- Location: Memorial Hall Room 109
- Course materials, announcements, assessments, and submissions: Canvas

## Office hours

- Time: Tu Th 2:30 PM - 3:30 PM
- Location: Smith Hall Room 102

## Course grading and exams

- Final project: 50% (25% for oral presentation, 15% for code repository and slides, 10% for proposal)
- In-class midterm: 20% (Tue, Oct 13, 2026)
- Online final on Canvas: 20% (available Tue, Dec 8, 2026; due Tue, Dec 15, 2026)
- Guest lecture attendance: 10% (5% for one attended lecture; full 10% for attending at least two)

### Letter-grade scale

| Letter grade | Final course percentage |
| ------------ | ----------------------: |
| A            |               93%–100% |
| A−          |               90%–<93% |
| B+           |               87%–<90% |
| B            |               83%–<87% |
| B−          |               80%–<83% |
| C+           |               77%–<80% |
| C            |               73%–<77% |
| C−          |               70%–<73% |
| D+           |               67%–<70% |
| D            |               63%–<67% |
| D−          |               60%–<63% |
| F            |                    <60% |

### Practice assignments

Practice assignments are ungraded and do not contribute to the final course grade. Solutions will be released on the suggested completion dates listed in the course schedule. Students who do not understand an assignment or its solution are strongly encouraged to attend office hours for help.

### Final project

The final project asks students to apply Scientific Machine Learning methods to a substantive problem in science or engineering. Projects should connect a clearly defined scientific question with appropriate data, governing equations, physical constraints, or domain knowledge. Students are expected to justify their modeling choices, evaluate their results critically, and communicate the limitations of their approach. **The size of the group and the duration of the presentation will be determined after registration of the course is finalized.**

#### Research scope and expected outcomes

You are expected to complete a small but well-defined research project on either **solving differential equations using deep learning** or **applying machine learning to scientific data**. Keep the scope focused enough to implement, evaluate, and analyze within the semester.

The project should go beyond simply reproducing existing work. You should:

- Identify a specific research question or potential improvement, and explain how it builds on existing work.
- Implement appropriate methods and compare them with at least one relevant baseline using clearly defined evaluation metrics.
- Conduct experiments that directly address your question, such as testing the effects of data availability, noise, model choices, or physical constraints.
- Analyze the results, explain what they support, and discuss limitations and possible reasons for success or failure.

A focused comparison or a modest, carefully evaluated improvement is sufficient; a new state-of-the-art method is not required. For example, you might investigate whether a sampling strategy improves a neural differential-equation solver, or whether adding a physical constraint improves prediction from limited scientific data. A well-supported finding that an approach does not improve performance is also a valid outcome.

Example papers for project inspiration are available in [Robotics](https://drive.google.com/drive/folders/1oMoS0m4Fq6cJL5BHxvI9OJPOYZWfsoAR?usp=sharing) and [Time series](https://drive.google.com/drive/folders/1FiTY_M4gIjh5m5fS1SKL04ZKv8v0Y6Qi?usp=drive_link). Projects are not limited to these papers or topics; other projects within the scope described above are welcome.

**The final results should be communicated through a total of five figures and tables combined** (for example, three figures and two tables). These should support the research question, method comparisons, and experimental analysis, with clear labels, captions, and an explanation of the main findings. Include them in the final presentation slides and make them available in the code repository.

The final project consists of the following components:

#### Project proposal — 10%

The proposal should clearly describe:

- Team member names
- The scientific or engineering problem and its significance
- The research question or modeling objective
- The proposed dataset, simulation, governing equations, or other sources of domain knowledge
- The planned machine learning or Scientific Machine Learning approach
- At least one baseline or comparison method
- The proposed evaluation metrics and criteria for success
- A feasible implementation timeline and expected final deliverables

The proposal will be evaluated on problem formulation, technical feasibility, connection to course concepts, appropriateness of the proposed evaluation, and clarity of presentation.

#### Code repository — 15%

The repository should provide a clear and reproducible record of the project. It should include:

- A README explaining the problem, methods, repository structure, and instructions for reproducing the main results
- Organized and readable source code
- Environment or dependency information
- Data-access or data-generation instructions, when applicable
- Training, evaluation, and visualization scripts or notebooks
- Saved configurations or parameters needed to reproduce key experiments
- A concise summary of the main results, limitations, and known issues

The repository will be evaluated on correctness, reproducibility, organization, documentation, appropriate use of version control, and the quality of the computational analysis.

#### Oral presentation — 25%

The presentation should communicate the project to an interdisciplinary audience and include:

- The scientific motivation and problem statement
- Relevant background and domain context
- The data, physical model, or governing equations used
- The selected methodology and justification for its use
- Experimental design, baselines, and evaluation metrics
- Key results supported by appropriate figures or tables
- Limitations, lessons learned, and potential future work

The presentation will be evaluated on technical content, quality of analysis, organization, visual communication, clarity for an interdisciplinary audience, and responses to questions. Presentation format and time limits will be announced before the presentation date.

### Final project milestones

- Project proposal due: Sun, Oct 18, 2026 at 11:59 PM
- Oral presentation: Tue, Dec 8, 2026 during the scheduled class period
- Code repository due date: Tue, Dec 8, 2026 at 11:59 PM

### Guest lecture attendance

Two to three guest lectures will be scheduled during the semester. Attendance at one complete guest lecture earns 5% of the final course grade. Attendance at two or more complete guest lectures earns the full 10%. Students who cannot attend because of an emergency, documented illness, religious observance, or another university-approved absence should contact the instructor as soon as possible to discuss an alternative arrangement.

## Important notes

*Exams are open book and open notes, and calculators are allowed. Laptops and phones are not permitted during the in-class midterm. A computer may be used for the online final.

*“In class” means during the regularly scheduled class time and in the assigned classroom.

*No makeup exams unless:

a. You have informed the instructor of the absence at least 24 hours before the start of the exam.

b. You miss the exam or quiz because of an emergency beyond your control (such as a serious illness or a death in the immediate family). In this case, official documentation from the Office of the Academic Assistant Dean is required before any makeup exam is given.

## Course policies

### Canvas and course communication

Canvas is the official course site for announcements, materials, assignment information, grades, and the online final. Students are responsible for checking Canvas and their University email regularly. Important schedule changes will be announced through Canvas.

### Attendance and participation

Regular attendance and active participation are strongly encouraged because lectures integrate mathematical, computational, and discipline-specific perspectives. Attendance at ordinary class meetings is not directly graded. Guest-lecture attendance is graded as described above. Students are responsible for material and announcements from any class they miss.

### Late work and extensions

Students who anticipate difficulty meeting a graded deadline should contact the instructor before the deadline whenever possible. Extensions may be granted for documented emergencies, illness, religious observances, or other university-approved circumstances. Late submissions without an approved extension may receive reduced or no credit. Practice assignments are ungraded; their listed dates indicate suggested completion and solution release.

### Academic integrity

Students must follow the University of Delaware's [Academic Integrity Policy](https://www.udel.edu/students/support/community-standards/academic-integrity/). Submitted work must accurately represent the student's or project team's own contributions. Unauthorized assistance, plagiarism, fabrication or falsification of results, and misrepresentation of individual contributions are prohibited. Suspected violations will be handled according to University procedures.

### Collaboration and use of generative AI

Collaboration is encouraged when explicitly permitted, especially for discussion of course concepts and approved team projects. Unless otherwise stated, graded examinations must be completed independently. Generative AI tools may be used for learning, brainstorming, and code debugging on practice work and the final project, but their use must be disclosed in the submitted work. Students remain responsible for verifying generated code, text, citations, data, and results. Generative AI tools may not be used during the in-class midterm or online final. Using AI for exams will result in a grade of 0 for the exam.

### Disability accommodations

The University of Delaware's [Disability Support Services](https://www.udel.edu/students/support/dss/) coordinates reasonable accommodations for students with disabilities, medical or psychological conditions, and temporary injuries. Students seeking accommodations should register with DSS and send the instructor an official accommodation letter as early as possible. Students using the Test Accommodation Center should follow its scheduling requirements.

### Religious observances

Absences for religious holidays recognized under University policy are excused. Students should notify the instructor as early as possible so that reasonable arrangements can be made for missed work. Additional information is available through UD's [Religious and Spiritual Resources](https://www.udel.edu/students/support/student-advocacy-support/religious-and-spiritual-resources/).

### Weather, emergencies, and class cancellation

The course will follow official University decisions concerning weather, emergencies, campus closures, and class cancellations. Students should monitor UD alerts, University communications, and Canvas. Students are not expected to take unnecessary risks traveling to campus during adverse conditions; they should notify the instructor when conditions prevent attendance.

### Changes to the syllabus

The instructor may adjust topics, dates, or course procedures when necessary. Material changes will be communicated through Canvas, and the most recently posted syllabus and course schedule will govern.

### Instructor discretion

The instructor may exercise reasonable discretion in interpreting and applying course procedures, evaluating circumstances not specifically addressed in this syllabus, and making case-by-case decisions concerning deadlines, participation, assessments, and course activities. Such decisions will be made in good faith, applied as consistently and equitably as practicable, and remain subject to University policy and approved accommodations. This clause does not alter the published grading weights or waive students' rights under University policy. When a discretionary decision materially affects the class, it will be communicated through emails.
