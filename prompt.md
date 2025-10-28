### Prompt 2 - Protein Structure Prediction with Quantum Computing, from Cleveland Clinic (Intermediate/Advanced)

#### Background and motivation:
Predicting a protein’s three-dimensional structure from its amino acid sequence remains a central challenge in molecular biology. While AI-based methods such as AlphaFold have achieved remarkable success, they often struggle with sequences lacking known structural homologs. Physics-based free modeling approaches offer greater accuracy in principle but are computationally prohibitive on classical hardware.

Quantum computing offers a fundamentally different approach. By combining quantum algorithms with coarse-grained lattice models, which discretize protein structures into simplified representations, quantum processors can efficiently sample the vast conformational landscape of proteins. However, the choice of lattice model significantly impacts accuracy and resource demands. Tetrahedral lattices are efficient but too rigid to model key secondary structures. In contrast, face-centered cubic (FCC) lattices provide higher geometric fidelity, enabling more realistic folding patterns such as α-helices and β-sheets, though at increased quantum resource cost.

**Your challenge is to go further:** Design a quantum algorithm for protein structure prediction using a 3D lattice model of your choice, with a focus on leveraging the capabilities of current IBM quantum hardware (Eagle R3, Heron R2). Go beyond the tetrahedral and FCC lattices, explore possibilities such as body-centered cubic (BCC), custom hybrid lattices, and others to balance biological realism with quantum efficiency.


#### Getting started:
- Create a quantum algorithm that predicts the folded structure of a short protein (5–10 amino acids) by minimizing a Hamiltonian that encodes energy terms and structural constraints on your chosen 3D lattice. Use Qiskit to:
- Encode the protein’s fold using turn-based or coordinate-based lattice encodings.
- Construct Hamiltonians that account for interaction energies (e.g., hydrophobic-polar, Miyazawa-Jernigan)

[Prompt 2 Additional Info Slides](https://docs.google.com/presentation/d/1GmzvFQC5Ri7DzjBlcfdu7o9Jw7F4Yuz-EZ2wBDfUfEQ/edit)

