# Publications
Selected publications highlighting research study in the domain of water, environmental and health  

# Groundwater Quality Assessment - Akure, Nigeria

[![Project Status](https://img.shields.io/badge/Status-Completed-success)]()
[![Analysis](https://img.shields.io/badge/Analysis-Water_Quality-blue)]()
[![WHO Standards](https://img.shields.io/badge/Standards-WHO-green)]()

## 📊 Project Overview

Comprehensive assessment of groundwater quality from 30 boreholes in Akure, Ondo State, evaluating suitability for domestic and irrigation purposes using physicochemical analysis and multi-index evaluation methods.

---

## 🎯 Key Results at a Glance

| Metric | Result |
|--------|--------|
| **Boreholes Analyzed** | 30 |
| **Overall Quality** | 82% Good, 16% Excellent, 2% Moderate |
| **Irrigation Suitable** | 96.7% |
| **Domestic Use Safe** | 96.7% |
| **WHO Compliance** | TDS, EC, Chloride, Alkalinity ✓ |

---

## 🔬 Methodology

### Analytical Framework
- **Physicochemical Parameters**: pH, TDS, EC, Ca²⁺, Mg²⁺, Na⁺, Cl⁻, K⁺, Total Alkalinity
- **Water Quality Indices**:
  - Water Quality Index (WQI)
  - Sodium Absorption Ratio (SAR)
  - Kelly's Ratio (KR)
  - Magnesium Hazard (MH)
  - Soluble Sodium Percentage (SSP)

### Tools & Technologies
- `Python` - Data analysis and visualization
- `ArcGIS` - Spatial mapping
- `Excel/R` - Statistical analysis
- `Spectrophotometry` - Metal concentration analysis

---

## 📈 Key Findings

### 1. Water Quality Classification (WQI)
```
Excellent: ████████████████ 16%
Good:      ████████████████████████████████████████████████████████████████████████████████ 82%
Moderate:  ██ 2%
```

### 2. Irrigation Suitability Indices

#### Sodium Ratio Distribution
- ✅ **Good**: 76.7%
- ⚠️ **Permissible**: 20%
- ❌ **Poor**: 3.3%

#### Kelly's Ratio Analysis
- ✅ **Suitable**: 96.7%
- ❌ **Not Suitable**: 3.3%

#### Magnesium Hazard
- ✅ **Safe (MH <50)**: 100%

### 3. Compliance Summary
| Parameter | WHO Limit | Status |
|-----------|-----------|--------|
| TDS | 500 mg/L | ✅ Within Limit |
| EC | 1000 μS/cm | ✅ Within Limit |
| Chloride | 250 mg/L | ✅ Within Limit |
| Alkalinity | 200 mg/L | ✅ Within Limit |
| pH | 6.5-8.5 | ⚠️ Slightly Acidic |

---

## 💡 Impact & Recommendations

### Positive Outcomes
- **96.7%** of groundwater sources validated as safe for domestic use
- Majority of samples suitable for agricultural irrigation
- Identified specific locations requiring pH adjustment

### Action Items
1. Monitor pH levels in identified acidic sources
2. Implement treatment for 3.3% non-compliant sources
3. Establish regular water quality monitoring program

---

## 📁 Repository Structure
```
groundwater-quality-assessment/
│
├── data/
│   ├── raw/                    # Raw water sample data
│   ├── processed/              # Cleaned and processed datasets
│   └── results/                # Analysis results and indices
│
├── notebooks/
│   ├── 01_data_preprocessing.ipynb
│   ├── 02_wqi_calculation.ipynb
│   ├── 03_irrigation_indices.ipynb
│   └── 04_visualization.ipynb
│
├── scripts/
│   ├── calculate_wqi.py
│   ├── irrigation_indices.py
│   └── statistical_analysis.py
│
├── results/
│   ├── figures/                # Charts and graphs
│   ├── maps/                   # GIS spatial distribution maps
│   └── reports/                # Summary reports
│
├── docs/
│   ├── methodology.md
│   └── WHO_standards.md
│
├── requirements.txt
└── README.md
```

---

## 🚀 Getting Started

### Prerequisites
```bash
pip install pandas numpy matplotlib seaborn scipy
```

### Run Analysis
```python
# Calculate Water Quality Index
python scripts/calculate_wqi.py --input data/raw/samples.csv

# Generate irrigation indices
python scripts/irrigation_indices.py --output results/
```

---

## 📊 Sample Visualizations

![Water Quality Distribution](results/figures/wqi_distribution.png)
![Spatial Map](results/figures/spatial_map.png)
![Irrigation Indices](results/figures/irrigation_indices.png)

---

## 📝 Publications & Reports

- **Research Paper**: [Link to published paper]
- **Technical Report**: [docs/technical_report.pdf]
- **Presentation**: [docs/presentation.pdf]

---

## 👥 Contributors

**Your Name** - Environmental Engineer | Water Resources Specialist
- 📧 Email: your.email@example.com
- 💼 LinkedIn: [Your Profile]
- 🌐 Portfolio: [Your Website]

---

## 📄 License

This project is licensed under the MIT License - see [LICENSE](LICENSE) file for details.

---

## 🙏 Acknowledgments

- Landmark University, Department of Civil Engineering
- WHO Guidelines for Drinking Water Quality
- Local community stakeholders in Akure, Ondo State

---

## 📚 References

1. WHO (2017). Guidelines for Drinking-Water Quality
2. Davis and De Wiest (1966). Hydrogeology Classification
3. [Additional references from your research]
