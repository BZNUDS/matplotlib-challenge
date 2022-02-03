# matplotlib-challenge

My work can be found at https://github.com/BZNUDS/matplotlib-challenge/tree/main/Pymaceuticals

    Jupyter Notebook File: pymaceuticals.ipynb 
    Analysis File: pymaceuticals_analysis.docx

Our Pymaceuticals company specializes in anti-cancer pharmaceuticals. In its most recent efforts, it began screening for potential treatments for squamous cell carcinoma (SCC), a commonly occurring form of skin cancer. As a senior data analyst at the company, I've been given access to the complete data from their most recent animal study. In this study, 249 mice identified with SCC tumor growth were treated through a variety of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals' drug of interest, Capomulin, versus the other treatments.
=======
  Jupyter Notebook File: pymaceuticals.ipynb
  Analysis File: pymaceuticals_analysis.docx
  
Our Pymaceuticals company specializes in anti-cancer pharmaceuticals. In its most recent efforts, it began screening for potential treatments for squamous cell carcinoma (SCC), a commonly occurring form of skin cancer. As a senior data analyst at the company, I've been given access to the complete data from their most recent animal study. In this study, 249 mice identified with SCC tumor growth were treated through a variety of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals' drug of interest, Capomulin, versus the other treatments. 
>>>>>>> cdf0d8745c94556bd708810b2b725a39b44616c3

The executive team asked me to generate all of the tables and figures needed for the technical report of the study. The executive team also has asked for a top-level summary of the study results.

Before beginning the analysis, I checked the data for any mouse ID with duplicate time points and remove any data associated with that mouse ID. Mouse ID g989 was the only one identifed (and it had duplicate Timeport 0's).

I removed the duplicate and used the cleaned data for the remaining steps.

Generate a summary statistics table consisting of the mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen.

<<<<<<< HEAD
Generate a bar plot using both Pandas's DataFrame.plot() and Matplotlib's pyplot that shows the total number of timepoints for all mice tested for each drug regimen throughout the course of the study. NOTE: These plots should look identical.

Generate a pie plot using both Pandas's DataFrame.plot() and Matplotlib's pyplot that shows the distribution of female or male mice in the study. NOTE: These plots should look identical.

Calculate the final tumor volume of each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. Calculate the quartiles and IQR and quantitatively determine if there are any potential outliers across all four treatment regimens.

Using Matplotlib, generate a box and whisker plot of the final tumor volume for all four treatment regimens and highlight any potential outliers in the plot by changing their color and style. Hint: All four box plots should be within the same figure. Use this Matplotlib documentation page for help with changing the style of the outliers.
=======
Generate a bar plot using both Pandas's DataFrame.plot() and Matplotlib's pyplot that shows the total number of timepoints for all mice tested for each drug regimen throughout the course of the study.
NOTE: These plots should look identical.

Generate a pie plot using both Pandas's DataFrame.plot() and Matplotlib's pyplot that shows the distribution of female or male mice in the study.
NOTE: These plots should look identical.

Calculate the final tumor volume of each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. Calculate the quartiles and IQR and quantitatively determine if there are any potential outliers across all four treatment regimens.

Using Matplotlib, generate a box and whisker plot of the final tumor volume for all four treatment regimens and highlight any potential outliers in the plot by changing their color and style.
Hint: All four box plots should be within the same figure. Use this Matplotlib documentation page for help with changing the style of the outliers.
>>>>>>> cdf0d8745c94556bd708810b2b725a39b44616c3

Select a mouse that was treated with Capomulin and generate a line plot of tumor volume vs. time point for that mouse.

Generate a scatter plot of tumor volume versus mouse weight for the Capomulin treatment regimen.

Calculate the correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment. Plot the linear regression model on top of the previous scatter plot.

Look across all previously generated figures and tables and write at least three observations or inferences that can be made from the data. Include these observations at the top of notebook.

Here are some final considerations:

Must use proper labeling of your plots, to include properties such as: plot titles, axis labels, legend labels, x-axis and y-axis limits, etc.

Enjoy,

<<<<<<< HEAD
Brian
=======
Brian
>>>>>>> cdf0d8745c94556bd708810b2b725a39b44616c3
