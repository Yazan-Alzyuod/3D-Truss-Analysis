# 3D-Truss-Analysis
# 🏗️ ANSYS Static Structural Analysis of Complex Truss Structure

## 📋 Project Overview
This repository contains a **static structural analysis** of a complex 3D truss structure with multiple cross-sectional profiles, performed in **ANSYS Mechanical**. The simulation analyzes deformation and von-Mises stress distribution under concentrated loads, demonstrating advanced beam element modeling techniques.

---

## 🎯 Key Results

### 📏 **Maximum Total Deformation:** 2.07 mm
![Total Deformation](StaticFigure96.png)

### ⚠️ **Maximum Equivalent Stress:** 73.647 MPa
![Equivalent Stress](StaticFigure97.png)

---

## 🏗️ **Model Specifications**

### 📐 **Geometry & Mesh**
- **Structure Type:** Complex 3D Truss with 30 beams
- **Dimensions:** 1.1925 m (X) × 0.1 m (Y) × 0.1 m (Z)
- **Total Volume:** 6.3857e-004 m³
- **Total Mass:** 5.0128 kg
- **Number of Nodes:** 368
- **Number of Elements:** 208
- **Element Type:** Beam elements

### 🔩 **Cross-Sectional Profiles (4 Types)**

| Profile | Type | Dimensions | Area (m²) | Iyy (m⁴) | Izz (m⁴) |
|---------|------|------------|-----------|----------|----------|
| **Extracted Profile1** | CTUBE | R1=3.75mm, R2=5mm | 3.4359e-005 | 3.3551e-010 | 3.3551e-010 |
| **Extracted Profile2** | HREC | W1=8.75mm, W2=10mm | 7.3627e-005 | 3.2497e-009 | 3.2497e-009 |
| **Extracted Profile3** | RECT | 20mm × 10mm, t=1.25mm | 6.875e-005 | 1.0514e-009 | 3.3171e-009 |
| **Extracted Profile4** | RECT | B=3.75mm, H=33.75mm | 1.2656e-004 | 1.2014e-008 | 1.4532e-010 |

### ⚙️ **Material Properties** (Structural Steel)
| Property | Value | Unit |
|----------|-------|------|
| Density | 7850 | kg/m³ |
| Young's Modulus | 200 | GPa |
| Poisson's Ratio | 0.3 | - |
| Yield Strength | 250 | MPa |
| Ultimate Tensile Strength | 460 | MPa |
| Thermal Expansion Coefficient | 1.2 × 10⁻⁵ | 1/°C |

---

## 🔧 **Boundary Conditions & Loading**

### 🏗️ **Supports**
- **Type:** Fixed Support
- **Location:** 4 vertices (fully constrained)
- **Degrees of Freedom:** All (UX, UY, UZ, ROTX, ROTY, ROTZ)

### ⬇️ **Applied Load**
- **Force Type:** Concentrated Nodal Force
- **Magnitude:** 400 N
- **Direction:** Downward (negative Y-direction)
- **Components:** (0, -400, 0) N

### ⚙️ **Solver Settings**
- **Analysis Type:** Static Structural
- **Solver:** Mechanical APDL
- **Time Step:** 1 second
- **Large Deflection:** Off
- **Auto Time Stepping:** Program Controlled
- **Solver Type:** Program Controlled

---

## 📈 **Analysis Results Summary**

### 🎯 **Deformation Analysis**
- **Maximum Total Deformation:** 2.076 mm (0.002076 m)
- **Average Deformation:** 0.83597 mm
- **Location of Maximum:** Beam with Extracted Profile3
- **Deformation Pattern:** Symmetrical distribution

### ⚠️ **Stress Analysis**
- **Maximum Equivalent (von-Mises) Stress:** 73.647 MPa
- **Average Equivalent Stress:** 11.963 MPa
- **Location of Maximum Stress:** Beam with Extracted Profile2
- **Safety Factor (based on yield):** ≈3.39

### 📊 **Stress Distribution**
- **Stress Range:** 0 to 73.647 MPa
- **Critical Areas:** Connections and load application points
- **Stress Concentration Factors:** Moderate at beam intersections
## 👨‍💻 Author
**Yazan Alzyuod**
* **Mechanical Engineer**
* 📧 [yqlasem@gmail.com](mailto:yqlasem@gmail.com)
* 🔗 [LinkedIn Profile](https://www.linkedin.com/in/yazan-alzyuod  )
* 💻 [GitHub Profile](https://github.com/Yazan-Alzyuod  )
* 📞 00962775327776   use this for information in the end
