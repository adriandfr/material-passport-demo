# Material Passport Demo – HEA 300 Steel Beam

**▶ Live demo:** https://adriandfr.github.io/material-passport-demo/
**📄 Paper:** [Digital Twins as Material Passports (PDF)](./Digital_Twins_as_Material_Passports.pdf.pdf)

Interactive prototype from my seminar paper *"Digital Twins as Material Passports: Enabling Circular Economy and Embodied Carbon Reduction in the Built Environment through Component Reuse"*. TU Wien, Digital Architecture and Planning, May 2026.

## The Problem
Structural components are rarely reused, so most steel ends up melted down in electric arc furnaces. The barrier isn't technical. It's missing information and trust: without documented material data, load history and condition, no engineer can certify a used beam.

## The Concept
- **RFID tag** on every component, acting as a permanent physical ID that links to its digital record
- **Digital Twin** (BIM + IoT) that collects data passively from sensors the building already runs for energy and facility management
- **Material Passport** as the output of the twin: one component-level record (MongoDB) structured along the EN 15978 lifecycle phases A1 → D

At end-of-life, the passport replaces costly hardness testing and lets buildings act as **material banks**.

## Key Result
For one HEA 300 beam (S355, 8.4 m, 739 kg), direct reuse cuts net lifecycle carbon from **1,497 to 62 kgCO₂e**. That is about 96% less than linear disposal and about 93% less than recycling.

## The Demo
The demo follows this beam over 45 years, from production in 2025 to its reuse approval in 2070. It includes 40 data fields, clickable source documents (mill certificate, EPD, structural report and more) and an IFC model view.

*Illustrative scenario. Companies, people and documents are examples created for the paper.*

Built with HTML/CSS/JS · hosted on GitHub Pages
