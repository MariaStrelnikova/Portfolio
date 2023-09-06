# Analysis of User Behavior in a Mobile Application

## In this project, I have studied the principles of event analytics: built a sales funnel, explored user pathways leading to purchases, and analyzed the results of an A/B test involving the introduction of new fonts. I compared the two control groups, ensured proper traffic allocation, and then compared them with the test group. It was found that the new font would not significantly impact user behavior.

#### *Please note that the project uses interactive charts that are not supported by github. Use this link to view if needed:*

[View on nbviewer](https://nbviewer.org)

1. [Core Skills and Tools](#core-skills-and-tools)
2. [Key-words](#key-words)
3. [Results](#results)
   

## Core Skills and Tools

- A/B-testing
- Python, 
- Pandas, 
- Matplotlib, 
- Seaborn,
- Plotly, 
- Product metrics, 
- Data visualization, 
- Hypothesis testing

## Key-words

A/B-test, visualization, statistical test


## Results

The log file was analysed for the period from August 1, 2019, to August 7, 2019, where each entry represents an action of a user or an event. There are a total of 5 events: 1. tutorial, 2. main screen view, 3. product selection, 4. payment method selection, and 5. payment. We disregarded the tutorial event because only a small number of customers went through it.

I found that a small portion of customers (1.5%) bypass the main screen and directly access the product selection section. The results of the simple conversion analysis showed that more than half of the app users do not make a purchase, with only 40% making a purchase. The conversion funnel results led us to suspect that many customers drop off after the first step. There could be several factors contributing to such user behavior. However, it's worth at least checking whether the button for accessing the product selection section is easily visible.

Finally, I tested the hypothesis put forward by managers and designers regarding the new font. According to the results of the statistical test, there are no statistically significant differences in conversions between the groups. This suggests that the font change is not associated with user behavior in the app. It might be worth paying attention to the layout of the product section as the conversion data suggests that there could be an issue there.