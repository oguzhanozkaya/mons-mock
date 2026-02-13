# MONS Insights — Project Documentation

![Garanti BBVA Genç Fikrinle Parla](https://img.shields.io/badge/Competition-Garanti%20BBVA%20Genç%20Fikrinle%20Parla-green)
![Track](https://img.shields.io/badge/Track-AI%20%2B%20Future%20of%20Banking-teal)
![Version](https://img.shields.io/badge/Version-1.0.0-blue)

## 1. Executive Summary
**MONS Insights** is an AI-powered financial behavior optimization engine integrated into the "Durumum" (My Status) page of Garanti BBVA’s mobile app. Unlike traditional budgeting tools, MONS does not interfere with lifestyle choices. Instead, it detects liquidity inefficiencies, timing gaps, and automation opportunities, converting them into frictionless, one-click banking actions.

Simultaneously, it serves as a **Behavioral Metadata Engine** for the bank, generating structured insights that enable preference-aware personalization and operational efficiency.

---

## 2. The Problem & Opportunity
### 2.1 The Friction Gap
Users have established financial habits (salaries, rent, bill cycles), but banking apps remain passive. Significant balances often sit idle in non-interest-bearing accounts because the "friction" of manual optimization (calculating dates, navigating menus) is too high.

### 2.2 The Efficiency Opportunity
The problem isn't *how* users spend; it's *how* they bank. By bridging the timing gap between cash inflows and outflows, MONS captures "hidden" financial value without requiring any change in the user's lifestyle.

---

## 3. Product Specification

### 3.1 User-Facing Intelligence (The "Durumum" Layer)
*   **Liquidity Intelligence:** Real-time detection of idle balances relative to upcoming expenses.
*   **Timing Awareness:** Predicting liquidity "pressure windows" and estimating "Safe-to-Use" balances.
*   **Automation Detection:** Identifying recurring manual transactions (e.g., utility bills paid manually for 3+ months) and offering one-tap instruction setups.

### 3.2 Bank-Facing Metadata (The Intelligence Layer)
MONS processes raw transaction data into high-level behavioral signals:
*   **Liquidity Tolerance Score:** How much buffer does the user maintain?
*   **Interest Sensitivity Indicator:** Based on product selection history (Participation vs. Traditional).
*   **Automation Readiness:** Propensity to adopt automated banking solutions.

---

## 4. Behavioral Signal Processing
MONS learns from **behavior**, not assumptions. It respects cultural and ethical sensitivities by responding to explicit product interactions:
1.  **Detection:** AI identifies a pattern (e.g., user declines interest-bearing offers 3 times).
2.  **Adaptation:** The system pivots to prioritize Gold or Participation banking insights.
3.  **Refinement:** CRM profiles are updated with "Interest Sensitivity" flags, reducing irrelevant communication.

---

## 5. Competitive Differentiation

| Feature | Traditional Banking App | MONS Insights |
| :--- | :--- | :--- |
| **Insight Type** | Static / Historical | Proactive / Behavioral |
| **Direction** | Bank → User (Push) | Data → Insight → Action (Pull) |
| **Personalization** | Demographic Segmentation | Behavioral Signal-based |
| **Execution** | Manual Navigation | One-click Pre-filled Actions |
| **Internal Value** | Reporting | Structured Metadata for CRM |

---

## 6. Strategic Fit (Garanti BBVA)
*   **Infrastructure:** Built on existing transaction data pipelines.
*   **UGI Synergy:** MONS provides the "Proactive Intelligence" that complements UGI's "Reactive Q&A."
*   **Operational Benefits:** Reduces branch interaction time by providing employees with pre-analyzed behavioral profiles.

---

## 7. Technical Implementation (Prototype)
The current prototype demonstrates the **Frictionless UI Layer**:
*   **`index.html`**: A standalone mobile mock containing the embedded CSS and structural layout.
*   **Components:**
    *   *AI Intelligence Cards:* Dynamic cards with specific CTAs.
    *   *Traditional View:* Integrated legacy data display to show seamless transition.

---

## 8. Roadmap & Future Vision
*   **Phase 1:** Liquidity and Automation optimization (Current).
*   **Phase 2:** Predictive "Cash-Flow Pressure" modeling.
*   **Phase 3:** Automated micro-investment routing (User-authorized auto-pilot).
*   **Phase 4:** Deep CRM integration for personalized branch experiences.

---

## 9. Team: MONS
*   **Selin, Elif, Naz:** Product Design & UX Research
*   **Mert:** AI Strategy & Technical Architecture
*   **Oğuzhan:** Software Engineering & Prototype Development

---
*This document serves as the official project specification for the "Genç Fikrinle Parla" competition.*
