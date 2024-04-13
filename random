import pandas as pd
import seaborn as sns
import matplotlib.pyplot as plt

# Load the Excel file into a DataFrame
excel_file_path = "/content/excel_file.xlsx"
df = pd.read_excel(excel_file_path)

# Define variables
variables = ['rain', 'population_density', 'rural_facilities',
             'land_surface_temperature_during_day', 'land_surface_temperature_during_night',
             'ultraviolet_index', 'pm_2.5', 'number_of_tb_cases',
             'number_of_heart_disease_cases', 'number_of_cancer_cases',
             'number_of_child_malnutrition_cases', 'number_of_maternal_anemia_cases',
             'number_of_smoker_cases', 'number_of_lung_problem_cases']

# summary statistics for all variables
summary_statistics = df[variables].describe().transpose()

# print summary statistics table
print("Summary Statistics for All Variables:")
print(summary_statistics.to_string())
print()
