<div id="top"></div>

[![LinkedIn][linkedin-shield]][linkedin-url]



<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/chetnasahu-max/Boom_Bikes_Demand_Analysis">
    <img src="logo.jpg" alt="Logo" width="80" height="80">
  </a>

<h3 align="center">Boom Bikes Demand Analysis</h3>

  <p align="left">
    Assignment for upGrade PG Diploma Data Science
    <br />
    Student : Chetna Sahu
    <br />
    Date : 16th Dec 2021
    <br />
    </p>
</div>


<!-- ABOUT THE PROJECT -->
## Subjective Questions

<h4>Q1. From your analysis of the categorical variables from the dataset,
what could you infer about their effect on the dependent variable?
<br /><br />
Ans: Here are the inferences which I made from my analysis of the Categorical
variables on the dependent variables i.e count are:<br />
1) Boombikes renting were more in 2019 as compared to 2018 and also the
median of 2019 (i.e 6000) is more than that of 2018 (i.e 4000).<br />
2) The median of People renting bikes is more for holidays than to non
holidays but the data is more spread out for non holiday peoples, the
reason may be on holidays people prefer to rent bikes and go on drive or
on vacation but they can’t do that on non-holidays.<br />
3) People renting bikes on working and non-working days are pretty similar,
there is slight difference in their median but it’s pretty small.<br />
4) People renting bikes on Fall season is very high so is the median so it means
that the weather condition on fall season is optimal to ride bikes.<br />
5) People renting bikes on July is high so does the median than comes
September this implies that Fall season month have high median.<br />
6) Clear weather is most optimal for bike renting as temperature is optimal
and humidity is less.<br />
7) People renting bikes on Thursday, Friday and Sunday is more as compared
to rest of the days.<br />
<br />Q2. Why is it important to use drop_first=True during dummy variable
creation?<br /><br />
Ans: drop_first=True is important to use, as it helps in reducing the extra column
created during dummy variable creation. Hence it reduces the correlations
created among dummy variables. If we have categorical variable with n-levels,
then we need to use n-1 columns to represent the dummy variables.<br />
<br />Q3) Looking at the pair-plot among the numerical variables, which one
has the highest correlation with the target variable?<br /><br />
Ans: By looking at the pair-plot among the numerical variables I found that ‘temp’
variables has highest correlation (0.63) with target variable i.e ‘count’.<br />
<br />Q4) How did you validate the assumptions of Linear Regression after
building the model on the training set?<br /><br />
Ans: The assumptions of Linear Regression can be validated after building the
model on the training set:<br />
1. Linear regression states only linear relationship between dependent and
independent variables. It can be validated by plotting a scatter plot between
the features and the target.<br />
2. Homoscedasticity can be validated by using scatter plot of residual values vs
predicted values.<br />
3. Multicollinearity is a state of very high inter-correlations among the
independent variables and it can be validated by using Pair-plots and
Heatmaps for identifying highly correlated features.<br />
4. The error(residuals) follow a normal distribution and it can be validated by
plotting a q-q plot.<br />
5. Autocorrelation occurs when the residual errors are dependent on each
other. Autocorrelation can be tested with the help of Durbin-Watson test.<br />
<br />Q5) Based on the final model, which are the top 3 features contributing
significantly towards explaining the demand of the shared bikes?<br /><br />
Ans: The top 3 features contributing significantly towards the demand of share
bikes are:<br />
- Temperature (positively correlated i.e 0.63)<br />
- Year (positively correlated i.e 0.57)<br />
- Season spring (negatively correlated i.e -0.56)
</h4>

<p align="right">(<a href="#top">back to top</a>)</p>


<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: www.linkedin.com/in/chetnasahu
