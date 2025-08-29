### Understanding How Weather Impacts the Way People Interact with Places: An Analysis of Footfall across UK Retail Areas
### August 2025

---

This repository provides the code for a research project analysing how weather affects footfall in UK retail areas. It combines footfall data, retail characteristics, and weather variables to build predictive models and identify trends across retail typologies.

#### Data Sources
The study combines proprietary and open-source data to explore how weather impacts footfall patterns across UK retail areas.

- **Proprietary:**
  - Footfall and retail data from **CACI**.

- **Open Data:**
  - **Weather (Met Office):**
    - [HadUK-Grid](https://catalogue.ceda.ac.uk/uuid/f02cc6ddd92f45b18b9ab6ab544df7d9/) temperature and rainfall data.
    - [Mean wind speed](https://catalogue.ceda.ac.uk/uuid/91cb9985a6c2453d99084bde4ff5f314/) from station observations.
  - **Retail Centre Typologies:**
    - [Geographic Data Service – Retail Centre Boundaries and Indicators](https://data.geods.ac.uk/dataset/retail-centre-boundaries-and-open-indicators).

#### Repository Structure

The analysis is organized into **three Jupyter notebooks**, which must be run in order.

1. **`mobile_retail_processing.ipynb`**  
   - Initial processing of footfall and retail data.

2. **`weatherdata_processing.ipynb`**  
   - Integration and processing of weather variables.

3. **`modelling.ipynb`**
    - Visualises weather–footfall relationships.
    - Builds Random Forest models to estimate the impact of temperature, rainfall, and wind on footfall.

#### Contact

For any questions or inquiries, please contact:  
📧 **stefan.krysa.24@ucl.ac.uk**
