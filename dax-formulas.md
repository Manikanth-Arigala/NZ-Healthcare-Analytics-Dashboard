Total_Patients = COUNT(nz_healthcare_dataset[patient_id])
Total_Cost = SUM(nz_healthcare_dataset[treatment_cost_nzd])
Avg_Cost = AVERAGE(nz_healthcare_dataset[treatment_cost_nzd])
Avg_Stay = AVERAGE(nz_healthcare_dataset[length_of_stay])
