# EU Device Classifier — MDR & IVDR Annex VIII
** Access here --> https://afif718.github.io/eu-device-classifier/ **

A lightweight, single-page web application designed to assist regulatory affairs professionals and manufacturers in classifying medical products for the European market. 

This tool provides a guided, wizard-style interface to navigate the Annex VIII classification rules for both general medical devices and in vitro diagnostics[cite: 1].

## 📋 Overview

The application separates products into two distinct regulatory frameworks:

*   **EU MDR (Regulation (EU) 2017/745):** Covers general medical devices (e.g., instruments, implants, active equipment, software)[cite: 1]. The tool routes the user through 22 classification rules across non-invasive, invasive, active, and special-purpose categories to land on Class I, IIa, IIb, or III[cite: 1].
*   **EU IVDR (Regulation (EU) 2017/746):** Covers in vitro diagnostics (e.g., test kits, reagents, analysers, companion diagnostics)[cite: 1]. The tool routes the user through 7 classification rules driven by individual and public-health risks to land on Class A, B, C, or D[cite: 1].

## ✨ Key Features

*   **Under-the-Hood Rule Checking:** The framework does not stop at the first applicable rule[cite: 1]. It asks one question at a time and quietly checks every relevant rule in the background[cite: 1].
*   **Highest Class Wins:** Mirroring actual Annex VIII requirements, the tool ensures that if multiple rules apply, the strictest rule governs the final output[cite: 1].
*   **Comprehensive Results:** The final result screen displays the governing classification, highlights the specific rules applied, and accounts for special sub-types (e.g., Class Is, Im, Ir requiring Notified Body involvement)[cite: 1].
*   **Quick Reference:** Includes built-in reference tables to view all 22 MDR rules and 7 IVDR rules at a glance[cite: 1].

## 🚀 Usage

This is a zero-dependency, static web application. 

1. Clone or download the repository.
2. Open `index.html` directly in any modern web browser.
3. Select either **EU MDR** or **EU IVDR** from the landing page to begin the classification wizard[cite: 1].

## 🛠️ Tech Stack

*   **HTML5 & CSS3:** Fully responsive design utilizing CSS variables, Flexbox, and Grid layouts[cite: 1].
*   **Vanilla JavaScript:** Client-side state machine engine that handles node navigation, rule tracking, and dynamic DOM updates without external libraries[cite: 1].
*   **Typography:** Styled with Google Fonts (Newsreader, IBM Plex Sans, and IBM Plex Mono)[cite: 1].

## ⚠️ Regulatory Disclaimer

This tool acts as a decision-support aid and applies the Annex VIII rule logic to provide a defensible starting classification while citing the specific rule(s) behind it[cite: 1]. 

It does **not** replace a documented classification rationale, Medical Device Coordination Group (MDCG) guidance review, or your Notified Body's own assessment[cite: 1]. Treat the result as a well-informed first pass, not a final regulatory determination[cite: 1].
