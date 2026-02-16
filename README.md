<p align="center">
  <img src="https://www.especial.gr/wp-content/uploads/2019/03/panepisthmio-dut-attikhs.png" alt="UNIWA" width="150"/>
</p>

<p align="center">
  <strong>UNIVERSITY OF WEST ATTICA</strong><br>
  SCHOOL OF ENGINEERING<br>
  DEPARTMENT OF COMPUTER ENGINEERING AND INFORMATICS
</p>

<hr/>

<p align="center">
  <strong>Technical Writing </strong>
</p>

<h1 align="center" style="letter-spacing: 1px;">
  Technical Documentation Standards
</h1>

<p align="center">
  <strong>Vasileios Evangelos Athanasiou</strong><br>
  Student ID: 19390005
</p>

<p align="center">
  <a href="https://github.com/Ath21" target="_blank">GitHub</a> ·
  <a href="https://www.linkedin.com/in/vasilis-athanasiou-7036b53a4/" target="_blank">LinkedIn</a>
</p>

<p align="center">
  Supervisor: Panagiotis Giannakopoulos, Professor
</p>
<p align="center">
  <a href="https://ice.uniwa.gr/en/emd_person/panagiotis-yannakopoulos/" target="_blank">UNIWA Profile</a> ·
  <a href="https://www.linkedin.com/in/panos-yannakopoulos-b9b6987/" target="_blank">LinkedIn</a>
</p>

<p align="center">
  Athens, March 2022
</p>

---

# Technical Documentation Standards

This project outlines the best practices for technical writing and document formatting, using the **"PSpice Simulation Workflow"** as a primary case study.

---

## Table of Contents

| Section | Folder/File | Description |
|------:|-------------|-------------|
| 1 | `docs/` | Documentation for Times New Roman project |
| 1.1 | `docs/Times-New-Roman.docx` | Word document version |
| 1.2 | `docs/Times-New-Roman.pdf` | PDF version |
| 2 | `README.md` | Repository overview and usage instructions |

---

## 1. Document Typography & Style

To maintain professional clarity and readability, the following typography standards are applied:

- **Typeface:** Times New Roman, chosen for high legibility in dense technical content.  
- **Font Size:**  
  - Body Text: 12pt for standard descriptions  
  - Headings: 14pt–16pt bold for major section identifiers  
- **Alignment:** Left-aligned or justified to ensure a clean "river" of text for the reader

---

## 2. Technical Writing Principles

Effective technical writing aims to simplify complex processes. This document follows three core tenets:

### A. Modular Organization
Information is broken down by the specific software tools used in the workflow:

- **Capture:** Used for design input and simulation preparation  
- **Stimulus Editor:** Used for graphical waveform input  
- **Model Editor:** Used for creating model definitions from datasheets

### B. Procedural Clarity
When describing a process (e.g., preparing a circuit in Capture), structured lists define each requirement:

1. Place and connect component symbols  
2. Set element values and attributes  
3. Enable specific analyses (e.g., Bode plots or histograms)

### C. Error Identification
Technical documentation must provide troubleshooting guidance. For example, the system should specify how to identify:

- Setup and hold violations  
- Timing hazards within digital circuits

---

## 3. File Requirements for Simulation

To ensure successful technical simulation, the following data files must be present:

| File Type | Source | Purpose |
| :--- | :--- | :--- |
| Netlist/Circuit File | Capture | Describes parts and connections |
| Stimulus Definitions | Stimulus Editor | Tests the circuit response |
| Simulation Models | Model Editor | Provides device characteristic curves |
