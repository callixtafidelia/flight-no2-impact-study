# COVID-19 Aviation Impact Analysis
Assessing the Impact of Flight Activity on Urban NO₂ Pollution During The COVID-19 Pandemic in China

## Overview
This repository contains a comprehensive fixed-effects panel regression analysis examining the relationship between flight activities and urban nitrogen dioxide (NO₂) concentrations across Chinese cities during the COVID-19 pandemic, using travel restrictions as a natural experiment.

## Research Question
How can spatial and temporal variation in flight trajectories explain changes in urban NO₂ concentrations during the COVID-19 pandemic in China?

## Methodology
- **Data**: Multi-source datasets including OpenSky Network flight trajectories, Sentinel-5P satellite NO₂ data, ERA5 wind data (2019-2020)
- **Approach**: Fixed-effects panel regression with city and time effects
- **Sample**: 58 major Chinese airports across 4 pandemic phases
- **Key Variables**: Flight counts, average altitude, wind speed, NO₂ concentrations

## Key Findings
- **Flight count** shows significant positive correlation with NO₂ levels (p = 0.005)
- **Wind speed** moderates aviation's pollution impact through negative interaction effects (p = 0.011)
- Model explains **83.6%** of variation in NO₂ concentrations
- Distinct spatial patterns in eastern China urban centers during pandemic phases

## Usage
1. Clone the repository
2. Install required R packages 
3. Run scripts in numerical order
