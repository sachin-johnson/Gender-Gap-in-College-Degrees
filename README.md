#  Gender Gap In College Degrees

The [Department of Education Statistics](nces.ed.gov/programs/digest/2013menu_tables.asp) releases a data set annually containing the percentage of bachelor's degrees granted to women over the past 5 decades. Randal Olson, a data scientist at University of Pennsylvania, has cleaned the data set and made it available on his personal [website](http://www.randalolson.com/blog/). This dataset can be used to visualize the gender gap in college degrees over the same time period.

## Aim

To visualize the growing gender gap in various college degrees over the past 5 decades. 

## Dataset

Dataset can be downloaded in the [link](http://www.randalolson.com/wp-content/uploads/percent-bachelors-degrees-women-usa.csv). The data set is broken up into 17 categories of degrees, with each column as a separate category. The columns in the dataset are a follows.

* Year 
* Agriculture 
* Architecture 
* Art and Performance 
* Biology 
* Business 
* Communications and Journalism 
* Computer Science 
* Education 
* Engineering 
* English 
* Foreign Languages 
* Health Professions 
* Math and Statistics 
* Physical Sciences 
* Psychology 
* Public Administration 
* Social Sciences and History

## Data Cleaning

The dataset is already cleaned by Randal Olson and we only have to convert the column names to snakecase.

## Data Visualization

The steps taken for data visualization is as follows.

* Visualize the gender gap by categorizing into STEM, Liberal Arts and Other groups.
* Hide X-axis labels.
* Simplify Y-axis labels.
* Generate a horizontal line across the entire subplot.

The gender gap reduces as we move across the graph. Engineering has the highest and math_and_statistics has the lowest gender gap in STEM degrees. The gender gap was negligible in psychology and as the year passed it has widened in favour of women. Engineering, Computer_science, Physical_sciences and Math_and_statistics have more men graduates in recent years. Psychology and Biology have more women graduates in recent years.

## Conclusion

The growing gender gap in various college degrees over the past 5 decades has been successfully visualized. 
