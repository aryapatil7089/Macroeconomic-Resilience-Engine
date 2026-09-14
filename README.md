# Macroeconomic Resilience Engine 🌍📈

[![Tableau](https://img.shields.io/badge/Tableau-Public-blue?style=for-the-badge&logo=tableau)]([Link-to-your-Tableau-Public-Profile])
[![Data](https://img.shields.io/badge/Data-World_Bank-orange?style=for-the-badge)]([Link-to-World-Bank-Data])

## Project Overview
An interactive, parameter-driven Tableau application designed to evaluate the economic stability of major global economies between 2015 and 2025. This project translates raw macroeconomic indicators into pre-attentive visual insights, allowing analysts to quickly identify stagflation risks and structural economic shifts.

**[View the Live Interactive Dashboard on Tableau Public]([Insert-Your-Tableau-Public-Link-Here])**

## 📸 Dashboard Gallery

### 1. Global Overview (Macro Trends & Correlation)
*[Insert a high-res screenshot of Dashboard 1 here: `![Overview](assets/dashboard1.png)`]*
*   **Sparkline:** Tracks average global inflation over a decade.
*   **Correlation Engine:** Scatter plot analyzing the relationship between Consumer Inflation (CPI) and GDP Growth to identify stagflation clusters.
*   **Resilience Score Matrix:** A custom-engineered metric `((GDP * 1.5) - CPI)` utilizing a diverging heat map to instantly flag economic distress.

### 2. Country Deep Dive (Micro-Analysis)
*[Insert a high-res screenshot of Dashboard 2 here: `![Deep Dive](assets/dashboard2.png)`]*
*   **Dynamic Navigation:** Parameter Actions allow users to click any entity on the overview page to instantly load a filtered deep-dive profile.
*   **Dual-Axis Focus Trend:** Contrasts local inflation spikes against local economic growth.
*   **Bump Chart Ranking:** Tracks shifting global economic dominance over time using custom Z-order highlighting.

## 🛠️ Technical Arsenal
*   **Advanced Calculations:** Fixed Level of Detail (LOD) expressions for Year-over-Year (YoY) variance independent of visual filters.
*   **Interactivity:** Parameter Actions, custom navigation buttons, and synchronized floating containers.
*   **UI/UX Design:** Dark-theme "Glass UI", pre-attentive color formatting, hidden axis redundancy, and custom tooltip formatting.
*   **Data Pipeline (ETL):** Extracted, cleaned, and modeled raw indicator data from the World Bank.

## 🗄️ Data Dictionary
*   **GDP Growth (%):** Annual percentage growth rate of Gross Domestic Product.
*   **Inflation (CPI):** Consumer Price Index reflecting the cost of living.
*   **GDP Deflator:** Broad measure of inflation across all domestically produced goods and services.
*   **Total Reserves:** Central bank holdings of foreign currencies and gold.

## 🚀 How to Run Locally
1. Clone this repository: `git clone https://github.com/yourusername/macroeconomic-resilience-engine.git`
2. Download the `/data` folder and the `.twbx` file.
3. Open `Macroeconomic_Resilience_Engine.twbx` using Tableau Desktop or the free Tableau Reader.
