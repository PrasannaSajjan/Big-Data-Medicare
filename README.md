# Big-Data-Medicare
Using Hadoop's map-reduce framework and Pig

  In this project, we try to answer the professor's questions which states "What is the correlation between the average Medicare billings 
for the “Cardiovascular stress test” procedure by address and the total cost of pharmaceutical payments made to each address?"

  It is important because the professor wants to know what factors might affect different costs of her medical procedure throughout the 
country. He feels that some pharmaceutical companies pay the physicians to use their products with some procedures that have the highest 
profit margin. He also thinks that, there is a correlation between the average Medicare billings of her procedure “Cardiovascular 
stress test” with that of the payments made by the pharmaceutical companies to the physicians’ offices. Hence, he is interested to find 
out the correlation between the average cost of all Medicare billings made for cardiovascular stress test procedures and the total of 
all payments made to a physicians’ office.

![Correlation-Value](https://github.com/PrasannaSajjan/Big-Data-Medicare/blob/master/images/Cor-rel.PNG)

![Venn-diagram](https://github.com/PrasannaSajjan/Big-Data-Medicare/blob/master/images/Venn.PNG)

  We found the correlation value to be 0.003328825 for the CPT code 93015 (Cardio Vascular Stress-test). This value is very close to 0. 
  From this, we can conclude that both the Medicare billings and the pharmaceutical costs are not closely related to each other. 
  There is a huge difference in the cost between these two and hence the correlation value is almost 0. The scatterplot also did not 
  show any relevant correlation. The Venn diagram shows how the number of records in each data set are on par with each other and how 
  many common records exist in between these two. This concludes that the professor's hypothesis is invalid. Pharmaceutical companies 
  don’t necessarily pay physicians to use their products with procedures that have the highest profit margin.
