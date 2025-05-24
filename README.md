# Ischemic Stroke Patient Visualization Dashboard

## Project Overview
This project presents an interactive dashboard designed for a hospital in Ontario to help visualize and understand key patterns in the care of ischemic stroke patients. The dashboard allows exploration of patient demographics, hospital stay durations, and other important metrics.

The project is built using Python in a Jupyter Notebook environment, using `ipywidgets` for interactivity, and `matplotlib`/`seaborn` for visualizations. The dashboard is deployed using `voila` to provide a user-friendly interface.

---

## Features and Visualizations

1. **Patient Demographic Analysis**
   - Interactive filters:  
     - Gender (`All`, `Male`, `Female`)  
     - Factors: `Age`, `Emergency Response Time`, `Admit Duration`  
     - Checkbox: Show/Hide Comorbidities
   - Histogram comparing Age distributions for patients **with** and **without** comorbidities.

2. **Hospital Stay Analysis**
   - Interactive filters:
     - Gender (`All`, `Male`, `Female`)
     - Stay Type: `Hospital Stay` or `ICU Stay`
     - Checkbox: Comorbidities filter
   - Bar chart of **Average Time Spent in Hospital** grouped by age bands (0-45, 45-60, 60-70, 70-80, 80+ years).

3. **Comorbidity Impact Analysis** 
   - Visual comparisons of patient characteristics and outcomes based on the presence of comorbidities.

4. **Emergency Response Analysis** 
   - Filtered metrics on response times, admitting durations, and age breakdowns for different genders and comorbidity statuses.

---

## Tools and Libraries
- Python 3.x
- Jupyter Notebook
- `ipywidgets`
- `Matplotlib` and `Seaborn` for plots
- `Voila` for deployment

---

