# 💳 HBL Gig-Power: Banking the Unbanked Gig Economy

[![Domain](https://img.shields.io/badge/Domain-FinTech-blue.svg)]()
[![Strategy](https://img.shields.io/badge/Type-Product%20Proposal-green.svg)]()
[![Impact](https://img.shields.io/badge/Market-%24400M%20Opportunity-orange.svg)]()

## 📋 Executive Summary
**HBL Gig-Power** is a strategic product proposal designed to bridge the gap between traditional banking and the modern workforce. 

Pakistan is the **4th largest freelance market** globally, yet millions of high-earning freelancers are rejected for credit cards and loans simply because they lack a "Salary Slip." This project proposes a **Data-Driven Credit Scoring Model** that evaluates applicants based on their remittance history and platform ratings (Upwork/Fiverr) rather than traditional employment documents.

> **[📄 Read the Full Proposal](docs/Project_Proposal.pdf)** | **[📊 View the Pitch Deck](docs/Presentation_Slides.pdf)**

## 🛑 The Problem: "Financially Invisible"
* **The Persona:** "Ahmed," a software developer earning $2,500/month (PKR 700k+).
* **The Conflict:** Despite high liquidity, he is rejected for a car loan because he cannot provide a stamped employment letter.
* **The Result:** Banks lose high-value customers to digital wallets like Payoneer or Wise.

## 💡 The Solution: Algorithmic Trust
We propose shifting the risk model from **"Document-Based"** to **"Data-Based"**.

### Core Features
1.  **API Integration:** Users link their Upwork/Fiverr profiles directly to the HBL App.
2.  **AI Credit Scoring:** An algorithm analyzes 6 months of remittance inflow consistency.
3.  **Dynamic Limits:** Credit limits adjust automatically based on a rolling average of income.

## 🏗️ System Architecture
The proposed system relies on a secure data pipeline:

1.  **Input:** User authorizes API access to Freelance Platforms.
2.  **Processing:** * `Data Ingestion`: Extract Transaction History & Job Success Score.
    * `Risk Engine`: Check for volatility (Income stability test).
3.  **Output:** Generate a "Gig-Score" (0-100) to approve/reject loans instantly.

## 📉 Risk Mitigation Strategy
| Risk | Mitigation Strategy |
| :--- | :--- |
| **Income Volatility** | **Dynamic Limits:** If income drops for 2 months, the credit limit automatically decreases. |
| **NPL (Default)** | **Kill Switch:** If portfolio default rate > 4%, lending pauses automatically. |
| **Data Privacy** | **Consent First:** Strict OAuth 2.0 implementation; data is never sold. |

## 👥 Project Team
* **Muhammad Shahan** - *Product Lead (Vision & Strategy)*
* **Syed Noor Hussain Shah** - *Data Architect (Scoring Logic)*
* **Muhammad Idrees** - *Risk Officer (Compliance)*
* **Muhammad Amir** - *UX/UI Designer*
* **Nizar Bahadur** - *Marketing Strategist*

---
*Proposed for the HBL Innovation Challenge.*
