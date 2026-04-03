## 📊 Strontium Antimony Iodide (Sr₃SbI₃) Perovskite Solar Cell Dataset

This repository contains a comprehensive simulation dataset for a **Strontium Antimony Iodide (Sr₃SbI₃)-based Perovskite Solar Cell (PSC)**. The dataset is generated using the **SCAPS-1D** simulation tool and is intended for research in photovoltaic device optimization and machine learning-based performance prediction.

---

## 🔢 Dataset Overview

- **Total Samples:** 15,550  
- **Total Features:** 12  
- **Target Variable:** Power Conversion Efficiency (**PCE**)  


---

## 📌 Input Features

The dataset includes key physical and electrical parameters that influence the performance of the PSC device:

| Feature | Description |
|--------|------------|
| Absorber Layer Thickness (µm) | Thickness of the perovskite absorber layer |
| HTL Thickness (µm) | Thickness of the Hole Transport Layer |
| ETL Thickness (µm) | Thickness of the Electron Transport Layer |
| Temperature (K) | Operating temperature of the device |
| Absorber Defect Density (cm⁻³) | Defect density within the absorber layer |
| Absorber Acceptor Density (cm⁻³) | Acceptor doping concentration in the absorber |
| ETL/Absorber Interface Defect Density (cm⁻²) | Interface defects between ETL and absorber |
| HTL/Absorber Interface Defect Density (cm⁻²) | Interface defects between HTL and absorber |

---

## ⚡ Output Parameters

| Parameter | Description |
|----------|------------|
| Jsc (mA/cm²) | Short-circuit current density |
| Voc (V) | Open-circuit voltage |
| FF (%) | Fill Factor |
| PCE (%) | Power Conversion Efficiency (target variable) |

---

## 🎯 Applications

This dataset is suitable for:

- Machine Learning & Deep Learning modeling  
- Regression analysis for solar cell performance prediction  
- Optimization of PSC device parameters  
- Sensitivity analysis  
- Correlation analysis  

---

## ⚙️ Methodology

- Generated using **SCAPS-1D** simulation software  
- Systematic variation of device parameters  
- Absorber material: **Sr₃SbI₃ (lead-free perovskite)**  
- Each row represents a unique device configuration  

---

## 📁 File Structure

```bash
StrontiumAntimonyIodideDataset.csv
```

---

## 🧪 Notes

- Data is **simulation-based**, not experimental  
- No missing values  
- Ready for ML pipelines  

---

## 📚 Citation

If you use this dataset, please cite your associated publication or this repository.

---

## 🤝 Contribution

Contributions are welcome! Feel free to open issues or submit pull requests.
