# Atomistic Simulations of 2D Semiconductors

This project investigates phonon-limited charge transport in novel 2D materials using a multiscale simulation pipeline combining DFT (Quantum ESPRESSO), Wannier90, and Perturbo.

## 🔬 Objective

To validate a first-principles computational framework by simulating monolayer graphene and extend it to predict transport properties in HHK silicene.

## 🧰 Tools Used

- Quantum ESPRESSO
- Wannier90
- Perturbo

## 🧪 Methodology

1. **DFT Calculations** using QE with LDA functional.
2. **Phonon Calculations** using DFPT.
3. **Wannierization** for accurate interpolation.
4. **Electron-Phonon Transport** via BTE in Perturbo.

## 📂 Repository Structure

- `scripts/`: Input files for each stage (SCF, phonons, Wannier90, Perturbo)
- `results/`: Band structures, phonon dispersion, and mobility plots
- `docs/`: Final BTP report
- `presentations/`: Slides for committee evaluation

## 📈 Key Results

- Graphene mobility: 1.85×10⁵ cm²/(V·s) using RTA
- Validated convergence with ultra-dense k/q grids
- Framework ready for application to HHK silicene
![graphene_wannier_dft](https://github.com/user-attachments/assets/2f68da34-e23f-4347-bf20-39a9ac9e5aac)


## 📜 License

MIT License
