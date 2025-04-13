# Zakaria Khan's Personal Website

Welcome to my personal website repository!

## About Me

My name is Zakaria Khan. I am a final-year undergraduate student at **Wayne State University**, majoring in **Chemistry** and **Physics**.

This website serves as an online portfolio where I share information about my work and personal life.

Toward the former, I have conducted research at federal laboratories and universities, which has led to my being named a **Goldwater Scholar**. Additionally, I have received research funding abroad as a **Fulbright Scholar**. My primary interests are in **light-matter interactions** and **experimental quantum information**.

Toward the latter, I enjoy reading various prose and the great outdoors. Growing up in Michigan, I've been spoiled by the beauty of the Great Lakes, and a full four seasons. I was also fortunate to have early exposure to various outdoor activities and backcountry living since my time as an **Eagle Scout** and patrol leader in Troop 743.

You can find more details about my work and experiences through the following sections:

- **[My Resume](./zk_resume.pdf)**
- **[My GitHub](https://github.com/zakaria-a-khan)**

### Quantum Chemistry Calculations

As a way to familiarize myself with GitHub, I've included a couple sets of basic quantum chemistry calculations that I have performed using Density Functional Theory and Hartree-Foch. Below are some of the details and results.

#### Styrene Calculations

In the **styrene** calculations, I used Gaussian software to explore molecular properties. These calculations involved:

- Geometry optimization and electronic structure analysis
- Vibrational frequency analysis
- Dipole moment and Mulliken charge calculations
- Electrostatic potential mapping

You can find the detailed files and results in the **[styrene submission files](./quantum_chemistry_calculations/styrene_submission_files)** folder. This includes:

- **[Styrene molecule image](./quantum_chemistry_calculations/as1_styrene_submission_files/styrene.png)**
- **[Styrene charge distribution](./quantum_chemistry_calculations/as1_styrene_submission_files/styrene_charge.png)**
- **[Styrene HOMO orbital](./quantum_chemistry_calculations/as1_styrene_submission_files/styrene_homo.PNG)**
- **[Styrene LUMO orbital](./quantum_chemistry_calculations/as1_styrene_submission_files/styrene_lumo.PNG)**
- **[Styrene Mulliken charges and dipole moment](./quantum_chemistry_calculations/as1_styrene_submission_files/styrene_mulliken_charges.png)**
- **[Styrene electrostatic potential map](./quantum_chemistry_calculations/as1_styrene_submission_files/styrene_electrostaticV.png)**

#### Formaldehyde Calculations

For my formaldehyde calculations, I used **HF/3-21G** and **B3LYP/6-31G(d,p)** levels of theory to compute vibrational frequencies and thermochemical properties. The calculations involved:

- **Geometry optimization** and vibrational frequency calculations at both HF/3-21G and B3LYP/6-31G(d,p) levels.
- **Thermochemical corrections** for zero-point energy, thermal correction to enthalpy, and free energy.
- **Comparison of experimental and theoretical frequencies** for formaldehyde.

You can find the relevant files and results in the **[formaldehyde submission files](./quantum_chemistry_calculations/formaldehyde_submission_files)** folder. These include:

- **[Formaldehyde B3LYP log archive](./quantum_chemistry_calculations/as2_formaldehyde_submission_files/formaldehyde_b3lyp_log_archive.PNG)**
- **[Formaldehyde HF log archive](./quantum_chemistry_calculations/as2_formaldehyde_submission_files/formaldehyde_hf_log_archive.PNG)**
- **[Formaldehyde B3LYP vibrational frequencies](./quantum_chemistry_calculations/as2_formaldehyde_submission_files/formaldehyde_b3lyp_vibrational_freq.PNG)**
- **[Formaldehyde HF vibrational frequencies](./quantum_chemistry_calculations/as2_formaldehyde_submission_files/formaldehyde_hf_vibrational_freq.PNG)**
- **[Formaldehyde B3LYP thermochemistry](./quantum_chemistry_calculations/as2_formaldehyde_submission_files/formaldehyde_b3lyp_thermochem.PNG)**
- **[Formaldehyde NIST thermochemistry experimental data](./quantum_chemistry_calculations/as2_formaldehyde_submission_files/formaldehyde_nist_thermochem_exp.PNG)**
- **[Formaldehyde summary of quantum chemistry calculations](./quantum_chemistry_calculations/as2_formaldehyde_submission_files/formaldehyde_assignment2.pdf)**

#### Acetaldehyde → Vinyl Alcohol (Transition State) Calculations

In this calculation, I explored the **reaction energy and activation barrier** for the conversion of acetaldehyde to vinyl alcohol. Calculations were performed at the **HF/3-21G** and **HF/6-31G(d,p)** levels of theory, and included:

- Geometry optimizations for the **reactant**, **transition state**, and **product**
- Use of **QST2/QST3** methods and the **Opt=NoEigenTest** keyword to locate the transition state
- Extraction of total energies, zero-point energies, enthalpies, free energies, and bond lengths for key atoms (C-C, C-O, C-H₁, O-H₁)
- Final results include activation barriers and reaction energies at both theory levels

This calculation was particularly interesting as it followed directly from a guest lecture by **Bernhard Schlegel**, a pioneer of transition state theory.

You can find the full writeup in:  
**[Assignment 3 – Acetaldehyde → Vinyl Alcohol](./quantum_chemistry_calculations/as3_acetaldehyde_submission_files/Assignment%203-2_take2.docx)**

#### DFT Calculation of Silicon Using Quantum ESPRESSO

In this calculation, I used **Quantum ESPRESSO** on **Google Colab** to perform a self-consistent field (SCF) calculation of **crystalline silicon**. Tasks included:

- Modifying the input files for pseudopotentials and crystal structure
- Running the SCF calculation and analyzing convergence
- Visualizing the silicon unit cell in both 3D and 2D
- Creating a custom 2D plot of the system’s total energy, which was found to be approximately **–15.84 Ry** — a value consistent with the expected stability of crystalline solids

I encountered and resolved issues related to pseudopotential downloads and output interpretation. This assignment sparked my interest in using **Colab/Jupyter** as a lightweight framework for **prototyping simulations and sharing reproducible workflows** in computational chemistry and materials modeling.

You can view my edited notebook here:  
**[Quantum ESPRESSO SCF for Si (Colab Notebook)](./quantum_chemistry_calculations/as4_qespresso/zk_edited_Quantum_Espresso_Colab.html)**

#### Quantum Tunneling in [Fe(CO)₅] (Final Project)

For my final project, I am investigating the **quantum tunneling behavior** in the transition metal complex **[Fe(CO)₅]**, which undergoes Berry pseudorotation between axial and equatorial ligand positions. This system is known for its fluxionality, and the project was partly inspired by a guest lecture from **Dr. Bernhard Schlegel**, one of the key developers of modern transition state theory.

The study uses **HF and DFT (B3LYP)** methods, applying a **6-31G(d)** basis set for light atoms and **def2-TZVP** for iron. Calculations include geometry optimizations and a scan along the reaction coordinate to build the **potential energy surface (PES)**. The goal is to evaluate tunneling probabilities using the **WKB approximation**, compare HF and DFT performance, and relate structural distortions to tunneling efficiency.

As of now, I have submitted a project proposal and generated preliminary PES plots. These reveal a shallow double-well energy profile consistent with degenerate structures and quantum tunneling between them.

You can view the materials below:

- **[Project Proposal (PDF)](./quantum_chemistry_calculations/as5_project/project_proposal.pdf)**
- **[3D PES Plot – fe_co5_3d_pes.png](./quantum_chemistry_calculations/as5_project/fe_co5_3d_pes.png)**  
  *Simulated 3D PES for Berry pseudorotation in [Fe(CO)₅], showing a symmetric double-well potential along the ligand displacement coordinate.*
- **[1D PES Scan – fe_co5_pes_plot.png](./quantum_chemistry_calculations/as5_project/fe_co5_pes_plot.png)**  
  Relaxed scan along the reaction coordinate (B3LYP/LANL2DZ//6-31G(d)), revealing a ~4 kcal/mol barrier consistent with tunneling behavior.

This preliminary work supports the hypothesis that [Fe(CO)₅] undergoes pseudorotation via a low-energy tunneling pathway. Full results and analysis will be added here upon project completion in the coming weeks.

### Monte Carlo for Physical Modeling

As part of my computational physics coursework, I am developing a Monte Carlo simulation to model **exciton transport in quantum dot systems**, a problem relevant to **quantum information**, **photonics**, and **materials design**. This project merges concepts from **solid-state physics**, **quantum optics**, and **stochastic numerical modeling**, with implementation in **C++** and visualization planned in **Python** and **ROOT**.

#### Project Summary

Excitons — bound electron-hole pairs — are central to the optical behavior of quantum dots. Understanding how they move, recombine, or get trapped is crucial for optimizing **single-photon sources** and **energy transport** in optoelectronic devices. The simulation will use a **Monte Carlo random walk** approach on a 2D array of quantum dots to track exciton behavior under varying assumptions about trapping and recombination probabilities, disorder, and defect states.

This is an ongoing project. The following two slide decks outline the core plan and numerical approach:

- **[Project Proposal (PPTX)](./monte_carlo/proposal_draft1.pptx)**  
  Covers motivation, physical model, and how Monte Carlo methods will simulate stochastic exciton dynamics.

- **[Numerical Approach & Simulation Plan (PPTX)](./monte_carlo/approach_draft2.pptx)**  
  Details algorithmic steps, assumptions, data structures, parallelization strategy, and output/visualization plans.

The final simulation will:
- Represent a 2D quantum dot grid using `std::vector` or arrays
- Model exciton movement as a random walk with probabilistic decay and trapping
- Output key statistics such as diffusion lengths, recombination rates, and trap probabilities
- Explore effects of system size, temperature, and lattice disorder
- Use **OpenMP** for parallelism and **ROOT** for structured output and visual analysis

Further updates and results will be posted here as the project progresses.

### Physics Vida: Review of Theory (Beginning March 2025)

**Physics Vida** is my recent initiative to review core topics in physics in preparation for graduate school (qualifying exams, etc) and continued study. The initiative will focus on three key areas via their respective texts, listed below:

- **Classical Mechanics**: Goldstein, Poole, Safko (3rd Ed)
- **Electrodynamics**: Griffiths, Schroeter (3rd Ed)
- **Quantum Mechanics**: Griffiths (5th Ed)

For full transparency, the texts were all sourced as pdf's from one of the following open-source sites:
- https://libgen.li
- https://annas-archive.org 

Note that the libgen umbrella is constantly taking down and putting up new url's so if these links are unavailable at any time, reddit likely has more updated url's.

#### Plan:
- Review **10 pages/day** from each of the three texts. So in total **30 pages/day** of material.
- Goal: Complete all three texts by term end in May 2025.
- Duration: **60 days** (starting March 1, 2025).
- Time: Approx. **3 hours/day** for reading and working problems.
- Extension: Spend the summer on more advanced, graduate level theory texts in optics, advanced quantum physics.

#### Weekly Progress Updates:
I'll track my progress in a weekly log, summarizing what I’ve covered and key concepts learned. May include notes but may be difficult because all my notes are hand-written.

#### Progress Log:

**March 1–7:**
- Classical Mechanics: 70 pages completed
- Electrodynamics: 70 pages completed
- Quantum Mechanics: 70 pages completed

Key Concepts:
- Classical Mechanics: Newtonian Mechanics, Lagrangian Formulation
- Electrodynamics: Gauss's Law, Electric Potential
- Quantum Mechanics: Wave-Particle Duality, Operators

#### Physics Vida Resources:

- **Notes**: [Link to Notes Folder]
- **Problems/Examples**: [Link to Problems Folder]

### Fitness

I got considerably lazy during the first few years of college and at the recent turn of the year decided to up my cardiovascular fitness. To hold myself accountable, I track my running progress in [`running_log.md`](running_log.md). This includes distances, times, and notes.

Future extensions include adding more wholistic cardiovascular activities (swimming, etc), and attending amateur competitions (half-marathons, etc). When the weather gets sufficiently warm I'll move my runs to outside. While I don't touch weights, I'm beginning to incorporate calesthenics and body-weight-sourced-resistance exercises.

## My Website

You can view my live website at:

[https://zakaria-a-khan.github.io](https://zakaria-a-khan.github.io)

## License

This repository is available under the [MIT License](LICENSE).
