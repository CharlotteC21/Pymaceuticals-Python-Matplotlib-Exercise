# :chart_with_upwards_trend:Matplotlib Homework - The Power of Plots:bar_chart:

# Background
>What good is data without a good plot to tell the story?
>So, let's take what you've learned about Python Matplotlib and apply it to a real-world situation and dataset:
>
>While your data companions rushed off to jobs in finance and government, you remained adamant that science was the way for you. Staying true to your mission, you've joined Pymaceuticals Inc., a burgeoning pharmaceutical company based out of San Diego. Pymaceuticals specializes in anti-cancer pharmaceuticals. In its most recent efforts, it began screening for potential treatments for squamous cell carcinoma (SCC), a commonly occurring form of skin cancer.
As a senior data analyst at the company, you've been given access to the complete data from their most recent animal study. In this study, 249 mice identified with SCC tumor growth were treated through a variety of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals' drug of interest, Capomulin, versus the other treatment regimens. You have been tasked by the executive team to generate all of the tables and figures needed for the technical report of the study. The executive team also has asked for a top-level summary of the study results.
>

# Observations
- The cancer treatment drug, "Ramicane" had the lowest reported tumor size, on average. Followed by "Capomulin" - These two drugs were far and away better than the   other reported medications/treatments.
- "Propriva" had a very average response rate to other drugs, comparitively... however, it also had the least amount of testing data points.
- The gender/sex breakdown of tested mice is almost a perfect split, making this test batch of data an equal playing field in terms of gender equality

# Instructions
<B>My tasks are to do the following:</B>
>Before beginning the analysis, I checked the data for any mouse ID with duplicate time points and remove any data associated with that mouse ID.


<B>Used the cleaned data for the remaining steps:</B>
>Generate a summary statistics table consisting of the mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen.
>
>Generated a bar plot using both Pandas's DataFrame.plot() and Matplotlib's pyplot that shows the total number of timepoints for all mice tested for each drug >regimen throughout the course of the study.
>
>Generated a pie plot using both Pandas's DataFrame.plot() and Matplotlib's pyplot that shows the distribution of female or male mice in the study.
>
>Calculated the final tumor volume of each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. Calculate the >quartiles and IQR and quantitatively determine if there are any potential outliers across all four treatment regimens.
>
>Using Matplotlib, I generated a box and whisker plot of the final tumor volume for all four treatment regimens and highlight any potential outliers in the plot by >changing their color and style.
>
>I selected a mouse that was treated with Capomulin and generate a line plot of tumor volume vs. time point for that mouse.
>
>Generated a scatter plot of tumor volume versus mouse weight for the Capomulin treatment regimen.
>
>Calculated the correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment. Plot the linear >regression model on top of the previous scatter plot.
