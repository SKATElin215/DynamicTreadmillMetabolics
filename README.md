# Dynamic Treadmill Metabolics
Data and code for manuscript titled, "Energy Expenditure During Walking with a Novel Treadmill Controller That Induces Gait Asymmetry"\
Data extraction was completed in Matlab using custom scripts, see [Brooke Hall's Dynamic Treadmill Analysis Code Repository](https://github.com/brookehall/DynamicTreadmillAnalysisCode/releases/tag/v1.0.0)\
All data analysis was completed in R using RStudio

## Code and Accompanying Data
### Metabolic Summary Code
- Code: [MetabolicSummary_2026-05-19.Rmd](DynamicTreadmillMetabolics/MetabolicSummary_2026-05-19.Rmd)
- Data: [SummaryData_NetPower_2025-03-20.csv](DynamicTreadmillMetabolics/SummaryData_NetPower_2025-03-20.csv)
- Completed code with embedded results: [MetabolicSummary_2026-05-19.html](DynamicTreadmillMetabolics/MetabolicSummary_2026-05-19.html) (download to view in native format)

### Speed Plotting Code
- Code: [SpeedPlots_2026-05-19.Rmd](DynamicTreadmillMetabolics/SpeedPlots_2026-05-19.Rmd)
- Data:
  - [CBcontrols_TrialAvgSpeeds_2026-03-10.csv](DynamicTreadmillMetabolics/CBcontrols_TrialAvgSpeeds_2026-03-10.csv) - Average speeds across full trial
  - [CBcontrols_Last30AvgSpeeds_202603-24.csv](DynamicTreadmillMetabolics/CBcontrols_Last30AvgSpeeds_202603-24.csv) - Average speeds across last 30 strides
  - [rmse_max_table.csv](DynamicTreadmillMetabolics/rmse_max_table.csv) - Root mean square values for estimated speeds
- Completed code with embedded results: [SpeedPlots_2026-05-19.html](DynamicTreadmillMetabolics/SpeedPlots_2026-05-19.html)

### Metabolic and Biomechanical Correlations
- Code: [MetabolicsBiomechanics_2026-05-19.Rmd](DynamicTreadmillMetabolics/MetabolicsBiomechanics_2026-05-19.Rmd)
- Data:
  - [SummaryData_NetPower_2025-03-20.csv](DynamicTreadmillMetabolics/SummaryData_NetPower_2025-03-20.csv) - Net metabolic power data, same as used in Metabolic Summary Code
  - [ChangeData_NetPower_2026-05-15.csv](DynamicTreadmillMetabolics/ChangeData_NetPower_2026-05-15.csv) - Net metabolic power, formatted as change from baseline 1.125m/s condition
  - [DynamicTread_KineticsKinematics_CBcontrols_2025-04-17.csv](DynamicTreadmillMetabolics/DynamicTread_KineticsKinematics_CBcontrols_2025-04-17.csv) - Average kinematic and kinetic data
  - [DynamicTread_Asymmetries_CBcontrols_2025-04-17.csv](DynamicTreadmillMetabolics/DynamicTread_Asymmetries_CBcontrols_2025-04-17.csv) - Calculated kinematic and kinetic asymmetries
  - [DynamicTread_CBControls_CrossCorrelation_Averages_2026-03-03.xlsx](DynamicTreadmillMetabolics/DynamicTread_CBControls_CrossCorrelation_Averages_2026-03-03.xlsx) - Cross correlation data
- Completed code with embedded results: [MetabolicsBiomechanics_2026-05-19.Rmd](DynamicTreadmillMetabolics/MetabolicsBiomechanics_2026-05-19.Rmd)
