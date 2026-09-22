# research_work
Patient Data Tracking & Analysis Project

This project takes sample patient data and employs ClinicalBERT to compare its analysis of patient data (text-based) with actual lab data to see how well ClinicalBERT is able to capture actual trends. Then, Google Gemini is initially used to act as a Medical Analyst, and summarize a patient's health condition based on their previous history, medications, BERT severity score, aggregated lab score, and other numerical data from the datafile. The data is then modified to include patients with multiple rows (to show different lab appointment data for the same patient) and the BERT DataFrame is re-ran on the new data. Average statistics are gathered per patient, and the Google MedGemma model is used instead of Google Gemini to compare summary quality. The MedGemma summary prioritizes recommending follow-up labs, interventions, or other monitoring frequencies. In the final dashboard, users can choose from any patient, see their lab history, and the MedGemma model generated summary on their health condition. 

To find the Jupyter Notebook with the work, expand the ClinicalBERT folder, then click on the research.ipynb file. The final dashboard link is at the bottom.
If the dashboard link doesn't work for some reason, you may have to download the repository and run the .ipynb file yourself to regenerate the dashboard link.

Enjoy!
