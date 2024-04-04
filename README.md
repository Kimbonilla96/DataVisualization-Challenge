# DataVisualization-Challenge

Prepare the Data: 

  After executing the necessary dependency and data imports, I seamlessly integrated the mouse_metadata and study_results into a single dataframe. Subsequently, I showcased the count of distinct mouse IDs within the dataset. Following this, I conducted a meticulous examination to identify any instances of duplicated time points associated with mouse IDs. Upon identification, I presented the data linked with the duplicate mouse ID, and proceeded to generate a cleaned DataFrame by excluding this data. Then I displayed the updated number of unique mice IDs.

Generate Summary Statistics:

  I generated a DataFrame encapsulating summary statistics. Each drug regimen represented as a row, with regimen names situated in the index column. The columns were calculated by the mean, median, variance, standard deviation, and standard error of the mean(SEM) pertaining to tumor volume.

Create Bar Charts and Pie Charts:

  I produced two sets of visualizations: two bar charts and two pie charts. Both sets should mirror each other in content and display. The bar charts should represent the total number of rows (comprising Mouse ID and Timepoints) attributed too each drug regimen across the study. Utilize the Pandas DataFrame.plot() method for the first bar chart and Matplotlib's pyplot methods for the second. Similarly, the pie charts should illustrate the distribution between female and male mice in the study, with the first generated using the Pandas DataFrame.plot() method and the second with Matplotlib's pyplot methods.

Calculate Quartiles, Find Outliers, and Create a Box Plot

  
