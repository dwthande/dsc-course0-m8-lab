# Aviation Safety Analysis

## Project Overview
This project analyzes commercial and passenger jet airline safety using aviation accident data from 1948-2023. The analysis was conducted for an airline/airplane insurer to identify aircraft makes/models with low rates of destruction and low likelihood of fatal or serious passenger injuries.

## Key Findings

### Aircraft Recommendations

**Small Aircraft (≤20 passengers):**
- Safest makes identified by combining low injury rates and low destruction rates
- Top performers show consistently low fatal/serious injury fractions in their distributions

**Large Aircraft (>20 passengers):**
- Safest makes identified through combined injury and destruction metrics
- Best performers demonstrate narrow distributions around low mean injury rates

### Risk Factors Identified

1. **Weather Condition:** IMC (Instrument Meteorological Conditions) shows significantly higher destruction and injury rates compared to VMC (Visual Meteorological Conditions).

2. **Phase of Flight:** Takeoff, climb, approach, and landing phases show the highest accident and destruction rates.

### Recommendations
- Prioritize aircraft with strong instrument-flight capabilities
- Focus on safety systems for takeoff and landing phases
- Consider both injury rates AND destruction rates when selecting aircraft

## Data
- Source: Aviation accident data (1948-2023)
- Filtered to accidents from 1983 onwards (40-year aircraft lifetime)
- Separated into small (≤20 passengers) and large (>20 passengers) aircraft categories

## Visualizations

### Small Aircraft - 15 Safest Makes by Injury Rate
![Small Aircraft Injury Rates](images/small_aircraft_injury.png)

### Large Aircraft - 15 Safest Makes by Injury Rate
![Large Aircraft Injury Rates](images/large_aircraft_injury.png)

### Weather Condition Impact
![Weather Analysis](images/weather_analysis.png)

### Phase of Flight Impact
![Phase of Flight Analysis](images/phase_analysis.png)

## Technologies Used
- Python (Pandas, NumPy)
- Data Visualization (Matplotlib, Seaborn)
- Statistical Analysis
- Jupyter Notebook
