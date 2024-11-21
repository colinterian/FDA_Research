Loading faers files_final
- This is the data extraction and loading code. all the file paths refer to locations on my local computer.
- data files can be downloaded from https://fis.fda.gov/extensions/FPD-QDE-FAERS/FPD-QDE-FAERS.html

Ventolin_Cleaned
- This code cleaned the dataframe created from Loading faers files_final
- it involves, adding columns, removing NAs and duplicates
- it includes conversion of values and renaming labels of associated converted values

Ventolin_Cleaned_2024
- Similar to Ventolin_Cleaned, but specific for 2024 data.
- it involves, adding columns, removing NAs and duplicates
- it includes conversion of values and renaming labels of associated converted values

Ventolin_EDA
- this includes the exploratory data analysis charts
- it includes histograms, proportions charts and wordcloud frequency charts
- some were implemented by age-specific categories, others were speculative but not included in the final analysis such as the gender word cloud frequencies.

Ventolin_AssocRuleMining_pt
- This involves the analysis by association rule mining.
- including analysis by specific age groups.

Ventolin_Random Forest
- Comprises of Random Forest Predictive Model
- Includes Models for two different scnearios with 100 and 1000 Trees respectively.

Ventolin_ARIMA
- Comprises of ARIMA Predictive Model
