# LAB-Google-Looker-Studio-Introduction-to-Data-Visualization-and-Google-Looker-Studio

## Introduction

Hello guys! In this lab we will develop a report by our own using Google Looker Studio. We will navigate over the different types of charts in order to learn the strength of each one.

## Initial Setup

### Requirements
Start by forking the provided GitHub repository to your account and then clone it locally. This will be your workspace for completing the lab exercises.

- [Learn how to fork this repo](https://guides.github.com/activities/forking/)
- Clone this repo into your `code/labs` folder

### Scenario

We will analyze the data of a Customer Satisfaction survey. This would have 2 main scoring data:
- **Product Rating**: is the product value that the client has over our data.
- **NPS Score**: is the probability of recommending our product to other client.

In our dataset, there will be a list of reviews done by the client. The reviews are on the products we sell. Each review will have:
- CustomerID: customer id.
- Date: date of review.
- Feedback: Comment written by the client about the product.
- NetPromoterScore: (NPS) customer loyalty, satisfaction, and enthusiasm with a company.
- Product: product id.
- Rating: Client's rating on the product.

### Starter File

You can download the customer_nps.csv file in this repository. This CSV contains all the data for this project.

### Iteration 0: Create a Data Source with the customer_nps.csv file.

Go to your looker studio and create a Data Source with the CSV contained in this repository.

### Iteration 1: Create a blank report with te Data Source.

Create your first blank report with the previous Data Source.

### Iteration 2: Pie Chart 🍰

Design a pie Chart that shows the percentage of reviews, divided by product. The chart has to have:
- A meaningful title.
- A legend.
- The colors of Reboot Academy or similar.
- Disable the 

### Iteration 3: Bar Chart 📊

Create a Bar chart that shows the averange rating of the products. It has to have this characteristics:

- Each bar has to show the number of its averange rating.
- It has to be ordered by the product rating in ascending.
- It needs to have a descriptive title.
- The Legend has to be disabled.
- The rating axis should show the word "Rating", to make it more understandable.
- The colors of Reboot Academy or similar.

### Iteration 4: KPI 🔟

Show in a number the averange NPS (Net Promoter Score) of the dataset:
- Do not forget the title to describe it.
- Add some color, border and round shape to the background.
- Remove the name of the variable.

### Iteration 5: Line Chart 📈

Create an accumulative mean of the NetPromoterScore.
- Show the axis titles.
- Write a meaningful title.
- Disable the legend.

### Iteration 6: Scatter Plot 🫧

Create a ScatterPlot where you can compare the the behaviour of Rating-NetPromoterScore.
- Remove the legend.
- The axis should show what variable is representing.
- Write a meaningful title.
- Colors matching with your report.
- Add a tendency line that could match the trend of the data.

### Bonus 1

In this link you can find the 🚢 Titanic Passenger Data 🚢 --> (Titanic Dataset)[https://www.kaggle.com/c/titanic/data]. There is a link to download, and a table with the explanation of each variable. Get the titanic dataset  and make a report that explains these relations:
- Port of embarcation and survival.
- Age and survival.
- Sex and survival.
- Age and economical status.
- Location and economical status.
- Economical Status and survival.


Use, at least once, these charts:
- Pie Chart.
- Bar Chart.
- KPI.

Do not forget to make it pretty 🌺✨

### Bonus 2

Now lets get a bit classy. We will analyze what makes a good wine. In this link you can find a 🍷 Wine Quality Dataset 🍷 --> (Wine Quality)[https://archive.ics.uci.edu/dataset/186/wine+quality]. Download the data and choose white or red wine. Try to find the next insights and show them in a report:
- What makes a good wine (KPIs).
- What makes a poor wine (KPIs).
- What variables has a linear relationship (use Scatter Plot for that).
- Find a variable that is similar in all qualities. (use Line Chart with dimension).

### Bonus 3

Now we will switch to something more serious. Wine is fun, but we have to take care about ourselves too. This dataset is related to 🩺❤️‍🩹 Breast Cancer Disease ❤️‍🩹🩺 --> (Breast Cancer Wisconsin)[[https://archive.ics.uci.edu/dataset/45/heart+disease](https://archive.ics.uci.edu/dataset/17/breast+cancer+wisconsin+diagnostic)]. Check the variables metadata in the link, and download the csv. The data is contained in the wdbc.data file. The wbdc.names file explains what means each variable.

Now, lets create an interactive report, where you can choose to see the data of the positives and negatives. For this, we will first create a Pie Chart that separate the Benign and the malignants. After this, you should add more charts that explain the other variables distribution and relationships. Be creative, so the doctor 👩‍⚕️ can find the patterns. Good luck!

# Submission
Once you have completed your analysis and visualizations, make a PDF of your reports and push them to your forked GitHub repository. Ensure that your final submission includes narratives explaining your visualizations and insights.

```bash
$ git add .
$ git commit -m "done"
$ git push origin main
```

Then create a Pull Request!!

# Additional Resources

- [Google Looker Studio Documentation](https://support.google.com/lookerstudio/)
- [Google Looker Studio Visualization types](https://cloud.google.com/looker/docs/visualization-types)
- [Looker Charts Reference](https://support.google.com/looker-studio/topic/7059081)
- [Downloading your report as PDF](https://support.google.com/looker-studio/answer/9125317)
