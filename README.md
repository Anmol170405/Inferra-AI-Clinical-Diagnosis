Inferra-AI is a web-based diagnostic tool designed to provide evidence-driven symptom-to-disease analysis. Built with a forward-chaining inference engine and aligned with WHO ICD-10 standards, it offers clinicians, students, and health professionals a structured, transparent reasoning framework.

Live Demo: inferra-ai.netlify.app

Overview
Inferra-AI combines a comprehensive knowledge base with an explainable inference engine to generate ranked disease predictions. Each result is accompanied by detailed reasoning, pathophysiology insights, and actionable recommendations.

Key workflow:

Symptom Input – Users select symptoms from predefined categories or enter free-text aliases.

Inference Engine – Required symptom gating → weighted fuzzy scoring → normalized confidence (0–98%) → ranked output.

Deep Reasoning – Each diagnosis includes symptom match analysis, molecular/cellular pathophysiology, ICD-10 codes, and evidence-based guidance.

Features
Knowledge Base: 20+ diseases fully modeled, including Malaria, COVID-19, Tuberculosis, Diabetes, Hypertension, and more.

Inference Engine: Forward-chaining logic with weighted fuzzy scoring and confidence normalization.

Symptom Visualization: Interactive symptom match charts with hit/miss weighting.

User Interface: 120+ symptom chips, free-text input with alias normalization, confidence bars, severity indicators, expandable cards, and dark mode support.

Reference Integration: WHO and CDC data for global disease burden and ICD-10 alignment.

Technical Scope
Inferra-AI is designed for:

Rapid clinical assessment – Supporting initial differential diagnosis in educational or research settings.

Explainable AI – Transparent inference trace for each prediction.

Cross-platform deployment – Standalone index.html for web, optionally ported to Python via core/rules.py and core/inference.py.

Deployment
GitHub Pages – Host directly from the repository.

Netlify – Drag-and-drop deployment of index.html for instant live access.

Fully portable; backend logic can be extended or integrated with Python applications.

Impact
Inferra-AI enables:

Faster, data-driven clinical reasoning.

Interactive learning of pathophysiology and diagnostic logic.

Increased awareness of disease patterns and global health trends.

References
WHO ICD-10: https://www.who.int/classifications/icd/en/

CDC Disease Facts: https://www.cdc.gov

