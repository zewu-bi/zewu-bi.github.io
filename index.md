# Bi — CTR Diagnostics × Machine Learning

👋 Hi, I'm **Zewu Bi**.

I work on **laser–plasma electron-beam diagnostics**, focusing on:

- 📡 **Coherent Transition Radiation (CTR)**: spectroscopy, forward modeling, calibration effects  
- 🧠 **Inverse Modeling / ML Reconstruction**: Dilated ResNet, physics-informed losses, stability analysis  
- ⚙️ **PyTorch pipelines**: synthetic dataset generation, 1D spectral inversion, benchmarking  
- 📉 **Ill-posed inverse problems**: phase loss, bandwidth limits, Fourier-domain constraints  
- 🌀 **CTR selection mapping with CNNs (BubbleWrap replacement)**  

---

## 🚀 Featured Work

### CTR Forward Model (FFT / Schroeder)

- 1D forward model for CTR spectrum from longitudinal bunch profile  
- Includes band-limited spectrometer response and calibration uncertainty  
- Used as the **ground truth forward operator** for ML-based inversion

👉 (Repo link to be added later)

---

### ML-based CTR Inversion (Dilated ResNet)

- 1D CNN for reconstructing bunch profile from form factor  
- Handles limited bandwidth and missing phase  
- Trained on synthetic dataset with carefully designed distributions:
  - peak_ratio: log-uniform  
  - sigma: uniform / log-uniform  
  - peak distance: uniform  

👉 (Repo link to be added later)

---

## 🧪 Research Topics I'm Interested In

- Phase retrieval and CDI-like inverse problems in CTR  
- Stability and non-uniqueness of inverse mapping  
- Physics-informed loss functions and data generation  
- Handling spectrometer calibration uncertainty in the forward model

---

## 🔧 Tech Stack

- **Languages:** Python, a bit of C/C++  
- **ML Framework:** PyTorch  
- **Physics / Optics:** CTR, Fourier optics, beam diagnostics  
- **Tools:** Jupyter, VS Code, Git, Linux

---

## 📫 Contact

- GitHub: https://github.com/zewu-bi  
- Email: gecko5@sjtu.edu.cn  
