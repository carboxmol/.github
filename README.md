<div align="center">

# 🧬 CarboxMol
### Universal 3D Macromolecular Crystallography Workbench & Structural Biology Ecosystem
**High-Throughput Crystallographic Survey, LBHB Mining, and Progressive Web App (PWA) Studio**

<br/>

[![Live Studio](https://img.shields.io/badge/🌐_Live_Studio-carboxmol.github.io-06b6d4?style=for-the-badge&logo=google-chrome&logoColor=white)](https://carboxmol.github.io)
[![Documentation](https://img.shields.io/badge/📚_Documentation-carboxmol.readthedocs.io-0284c7?style=for-the-badge&logo=read-the-docs&logoColor=white)](https://carboxmol.readthedocs.io/en/latest/)
[![Organization](https://img.shields.io/badge/GitHub_Org-@carboxmol-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/carboxmol)
[![Private Data Access](https://img.shields.io/badge/🔒_Private_Data_Access-Request_via_Email-dc2626?style=for-the-badge&logo=gmail&logoColor=white)](mailto:suleyman.hacizade1@gmail.com?subject=Private%20Data%20%26%20Repository%20Access%20Request%20-%20CarboxMol)
[![Contact](https://img.shields.io/badge/📧_Contact-suleyman.hacizade1%40gmail.com-10b981?style=for-the-badge&logo=gmail&logoColor=white)](mailto:suleyman.hacizade1@gmail.com)
[![PWA Ready](https://img.shields.io/badge/📱_PWA-100%25_Offline_Ready-2ea44f?style=for-the-badge&logo=pwa&logoColor=white)](https://carboxmol.github.io)
[![License: MPL-2.0](https://img.shields.io/badge/License-MPL_2.0-blue?style=for-the-badge)](https://opensource.org/licenses/MPL-2.0)
[![Python 3.9+](https://img.shields.io/badge/Python-3.9%2B-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)

</div>

---

> [!IMPORTANT]
> ### 🔒 Private Data & Repository Access Notice
>
> All raw crystallographic datasets, full 7,230+ high-resolution PDB screening matrices, $2mF_o - DF_c$ and $mF_o - DF_c$ electron density map caches, core source repositories (`carboxmol` and `carbox`), internal 64+ note LLM research knowledge base (Wiki), and pre-publication manuscripts housed in this organization are **strictly Private**.  
> If you are a researcher, academic reviewer, or prospective collaborator wishing to obtain access to the private research datasets or source code, please submit an inquiry via email:  
> 📧 **[suleyman.hacizade1@gmail.com](mailto:suleyman.hacizade1@gmail.com?subject=Access%20Request%20-%20CarboxMol%20Private%20Data%20%26%20Repositories)**

---

## 📚 Official Documentation Portal (Read the Docs)

The official scientific and technical documentation is hosted live on **Read the Docs**:  
👉 🌐 **[https://carboxmol.readthedocs.io/en/latest/](https://carboxmol.readthedocs.io/en/latest/)** *(or for the core computation engine: [https://project-carbox.readthedocs.io/en/latest/](https://project-carbox.readthedocs.io/en/latest/))*

### 📖 What is Available on the Documentation Portal?

The Read the Docs portal serves as an interactive, comprehensive encyclopedia compiling the theoretical, algorithmic, biophysical, and crystallographic guidelines of the Carbox & CarboxMol ecosystem:

1. 🌍 **100% Trilingual Parity:**
   - **English (🇬🇧):** International standard guides, API specifications, and crystallographic tutorials for the global community.
   - **Azerbaijani (🇦🇿):** Complete academic explanations of all algorithms, mathematical equations, and operational workflows.
   - **Hebrew (🇮🇱 עברית RTL):** Fully localized right-to-left documentation for international biophysics partnerships.

2. 🔬 **Scientific Theory & Biophysical Principles:**
   - **Anomalous Carboxyl Protonation:** Mechanisms driving neutral Aspartate (`ASH`) and Glutamate (`GLH`) states in hydrophobic microenvironments.
   - **Low-Barrier Hydrogen Bonds (LBHBs):** Quasi-covalent proton delocalization and single-well potential energy surfaces at $d(O\cdots O) \le 2.55\text{ \AA}$.
   - **Dielectric Shielding & Born Desolvation:** Local low-dielectric cavities ($\varepsilon_{\text{eff}} \approx 2\text{--}4$) amplifying Coulombic repulsion by 20-fold, inducing macroscopic $\Delta \mathrm{p}K_a \ge +2.0$ shifts.

3. 🚦 **Murshudov 6-Stage Crystallographic Gate Protocol:**
   - **Stage 1 (Geometric Screening):** Ultra-high resolution ($d \le 1.20\text{ \AA}$) and carboxyl–carboxyl pairwise contact distances ($d(O\cdots O) \le 3.20\text{ \AA}$).
   - **Stage 2 (Ground-State Occupancy Law — $occ = 1.00$):** Elimination of partial occupancy artifacts and alternate conformation (`AltLoc A/B`) ambiguities.
   - **Stage 3 (Thermal B-Factor Audit):** Standardized $B_z \le 5.0\sigma$ audit and non-parametric Tukey interquartile range (IQR) bounds.
   - **Stage 4 (Electron Density & RSCC Validation):** Real-space density correlation $\text{RSCC} \ge 0.80$ in $2mF_o - DF_c$ and $\pm 3.0\sigma$ residual bounds in $mF_o - DF_c$ difference maps.
   - **Stage 5 (70-Cation Metal Screening & pKa Analysis):** Strict exclusion of 70 metal cations from the carboxyl coordination sphere.
   - **Stage 6 (Restraint Card Delivery):** Delivery of custom stereochemical restraints for REFMAC5 and Servalcat.

4. 📐 **Crystallographic Refinement Restraints:**
   - AceDRG-compliant `exte dist ... alph 2` restraint cards eliminating spurious van der Waals steric clash penalties.
   - Barron adaptive robust loss function parameter formatting for sub-angstrom MX and Cryo-EM models.

5. 💻 **Python API & Command-Line Interface (CLI):**
   - `carbox.stages.runner` — CLI orchestrator options (`--pka`, `--geom`, `--batch`, `--out`).
   - Granular documentation for `carbox.analysis`, `carbox.density`, `carbox.refine`, and `carbox.validation`.
   - `.cxl` (Carbox Crystallographic Language) macro automation tutorial.
   - Zero-dependency local workstation server (`server.py`) and 3D WebGL Studio integration.

6. 📑 **Master Manual, Benchmark Compendium & Citation:**
   - Full technical monograph (`CARBOX_MASTER_MANUAL`).
   - Analytical dossiers for Golden Benchmark structures (3X2M, 5SAO, 8PO0, 8W8U, 1G33, 1I10).
   - BibTeX, APA, and RIS academic citation templates.
   - Server-side full-text search and offline formats (PDF / ePub).

---

## 🏛️ About CarboxMol

**CarboxMol** is a state-of-the-art macromolecular X-ray crystallography (MX), cryogenic electron microscopy (Cryo-EM), and structural bioinformatics ecosystem.

The mission of the organization is to unify automated mining of anomalous carboxyl–carboxyl interactions (Asp/Glu dyads), low-barrier hydrogen bonds (LBHBs), microenvironment dielectric shielding, real-time 3D electron density visualization, and crystallographic refinement restructuring under a unified, high-performance platform.

---

## 🔬 Scientific Leadership & Citation

The Carbox and CarboxMol ecosystem is authored and maintained through international academic collaboration:

* 👨‍🔬 **Suleiman M. Hajizadeh** ([@SuleimanHajizadeh](https://github.com/SuleimanHajizadeh))  
  *Institute of Molecular Biology & Western Caspian University*, Baku, Azerbaijan.  
  📧 Data Access & Collaboration Inquiries: **[suleyman.hacizade1@gmail.com](mailto:suleyman.hacizade1@gmail.com?subject=Access%20Request%20-%20CarboxMol%20Private%20Data)**
* 👨‍🔬 **Prof. Garib N. Murshudov**  
  *MRC Laboratory of Molecular Biology (LMB), Cambridge Biomedical Campus*, Cambridge, United Kingdom.

### 📚 Citation
> **Structural Identification of Anomalous Carboxyl Protonation States, Low-Barrier Hydrogen Bonds, and Microenvironment Dielectric Shielding in High-Resolution Protein Crystal Structures**  
> **Suleiman M. Hajizadeh** & **Garib N. Murshudov** (2026)  
> *Carbox & CarboxMol Macromolecular Crystallography Suite*  
> ORCID: [0000-0001-5795-177X](https://orcid.org/0000-0001-5795-177X) · [0000-0002-3909-0524](https://orcid.org/0000-0002-3909-0524)

---

## 🗂️ Organization Architecture & Data Governance

To preserve scientific rigor and protect pre-publication crystallographic caches, core source and dataset repositories are maintained in **Private** status:

```text
carboxmol (GitHub Organization)
│
├── 🔒 carboxmol (Private Core Workbench & Datasets — Access by Request)
│   ├── 3D WebGL crystallographic graphics engine and local Python server (server.py)
│   ├── Raw crystallographic datasets, electron density caches, and 6-stage pipeline runs
│   ├── REFMAC5 / Servalcat external restraints generator and .cxl macro scripts
│   ├── Internal 64+ note LLM research knowledge base (Wiki) and LaTeX monograph manuscripts
│   └── 📩 Request Access: suleyman.hacizade1@gmail.com
│
├── 🔒 carbox (Private Mathematical Core Engine — Access by Request)
│   ├── High-throughput structural contact mining and analytical LBHB classification (d ≤ 2.55 Å)
│   ├── Non-parametric Tukey IQR B-factor filter, Fisher z-RSCC, and 70-cation metal audit
│   ├── Empirical pKa perturbation engine and comprehensive PDB screening catalogs
│   └── 📩 Request Access: suleyman.hacizade1@gmail.com
│
├── 📚 docs (Public Documentation Repository — Read the Docs Source)
│   ├── 🌟 GitHub: https://github.com/carboxmol/docs
│   ├── 🌟 Live Docs: https://carboxmol.readthedocs.io/en/latest/
│   └── Sphinx source trees, trilingual manuals (EN, AZ, HE RTL), and RTD build triggers
│
├── 🌐 carboxmol.github.io (Public Web Portal)
│   ├── 🌟 Official URL: https://carboxmol.github.io
│   └── Public landing portal, maintenance notices, academic citations, and contact links
│
└── ⚙️ .github (Public Organization Profile)
    └── Public organization profile, data governance policy, and access guidelines
```

| Repository / Portal | Status | Description | Access / Link |
| :--- | :---: | :--- | :---: |
| 📚 [**docs**](https://github.com/carboxmol/docs) | `🌐 Public` | **Documentation Source for Read the Docs** — Trilingual (EN, AZ, HE RTL) Sphinx/MyST manuals powering Read the Docs. | [GitHub Repo](https://github.com/carboxmol/docs) · [Read the Docs](https://carboxmol.readthedocs.io/en/latest/) |
| 🌐 [**carboxmol.github.io**](https://github.com/carboxmol/carboxmol.github.io) | `🌐 Public` | **CarboxMol Official Web Portal** — Public web presence, maintenance status, citations, and contact information. | [Web Portal](https://carboxmol.github.io) |
| 🖥️ [**carboxmol**](https://github.com/carboxmol/carboxmol) | `🔒 Private` *(By Request)* | **CarboxMol Desktop, Server & Datasets** — 3D crystallographic graphics engine, CCP4/MRC density maps, REFMAC5/Servalcat restraint generator, raw datasets, and local server (`server.py`). | [📧 Request Access (`suleyman.hacizade1@gmail.com`)](mailto:suleyman.hacizade1@gmail.com?subject=Access%20Request%20-%20carboxmol%20Private%20Repository) |
| 🧮 [**carbox**](https://github.com/project-carbox/carbox) | `🔒 Private` *(By Request)* | **Carbox Mathematical Engine & Raw Data** — High-throughput contact mining, LBHB classification ($d(O\cdots O) \le 2.55\text{ \AA}$), empirical pKa solver, and atomic Zeta-score engine. | [📧 Request Access (`suleyman.hacizade1@gmail.com`)](mailto:suleyman.hacizade1@gmail.com?subject=Access%20Request%20-%20carbox%20Private%20Repository) |
| ⚙️ [**.github**](https://github.com/carboxmol/.github) | `🌐 Public` | **Organization Profile & Governance** — Public profile description, private data policies, and scientific directory. | [Profile](https://github.com/carboxmol/.github) |

---

## 🌟 Key Capabilities

```
┌─────────────────────────────────────────────────────────────────────────────┐
│                       CarboxMol Integrated Architecture                     │
├──────────────────────────────────────┬──────────────────────────────────────┤
│  🔬 Real-Time Density Contouring     │  ⚡ 2mFo - DFc and mFo - DFc         │
│     (WebGL 3D Isosurfaces)           │     difference Fourier density maps  │
├──────────────────────────────────────┼──────────────────────────────────────┤
│  🧪 Anomalous Protonation & LBHB     │  🔍 d(O···O) ≤ 2.55 Å short contacts │
│     Detection Algorithms             │     and neutral ASH/GLH modeling     │
├──────────────────────────────────────┼──────────────────────────────────────┤
│  📐 Crystallographic Restraints      │  🛠️ AceDRG-compatible external       │
│     Bridge                           │     distance restraints for REFMAC5  │
├──────────────────────────────────────┼──────────────────────────────────────┤
│  📱 Cross-Platform Progressive App   │  🌐 100% offline-ready across macOS, │
│     (PWA & Offline First)            │     Linux, Windows, iPadOS & Android │
├──────────────────────────────────────┼──────────────────────────────────────┤
│  🌍 Trilingual Documentation         │  🇬🇧 English                          │
│     (Comprehensive Parity)           │  🇦🇿 Azerbaijani                      │
│                                      │  🇮🇱 Hebrew (עברית RTL)               │
└──────────────────────────────────────┴──────────────────────────────────────┘
```

1. **Interactive 3D WebGL Molecular Graphics:**
   - Real-time rendering of protein and nucleic acid atomic models without browser plugins.
   - Dynamic slider-based contour adjustments ($\sigma$ RMSD) for $2mF_o - DF_c$ and $mF_o - DF_c$ difference maps.
2. **Real-Space Crystallographic Validation:**
   - Instant validation of Ramachandran angles, rotamer outliers, and bioinorganic coordination polyhedra (Zn, Fe, Mg, Ca).
3. **REFMAC5 and Servalcat Refinement Bridge:**
   - Automated generation of custom `EXTERNAL RESTRICTIONS` files for anomalous carboxyls and LBHB pairs.
4. **Offline & Mobile Architecture:**
   - Service Worker and IndexedDB architecture ensuring 100% operational readiness in laboratories and travel without an active internet connection.

---

## 📬 Private Data Access & Contact

All raw research datasets and core source code in this organization are **Private**. Researchers, reviewers, or collaborators requesting access may contact:

- **Lead Researcher:** Suleiman M. Hajizadeh ([@SuleimanHajizadeh](https://github.com/SuleimanHajizadeh))
- **Email (Data & Repo Access):** 📧 **[suleyman.hacizade1@gmail.com](mailto:suleyman.hacizade1@gmail.com?subject=Access%20Request%20-%20CarboxMol%20Private%20Data%20%26%20Repositories)**
- **Official Documentation Portal:** 📚 **[https://carboxmol.readthedocs.io/en/latest/](https://carboxmol.readthedocs.io/en/latest/)**
- **Official Web Portal:** 🌐 **[https://carboxmol.github.io](https://carboxmol.github.io)**

---

<div align="center">

**CarboxMol — Universal Macromolecular Crystallography & Structural Biology Suite**  
*Lead Authors: Suleiman M. Hajizadeh & Prof. Garib N. Murshudov*  
&copy; 2026 CarboxMol Ecosystem · All Private Datasets & Repositories Protected (Access by Request: `suleyman.hacizade1@gmail.com`)

</div>
