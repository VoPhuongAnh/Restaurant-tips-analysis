
# PRACTICE PROJECT

### Session-5.4-Restaurant-tips-analysis
#### This project is to analize the relationships between various factors to the tip amount received from customers of the restaurant. 
### A - Data description and usage
1. Source of the data
       The dataset consists of information from 244 restaurant bills, collected in the US in 1987. 
2. Description of the dataset
       This dataset includes details about the tips given to restaurant staff, such as the total bill, tip amount, gender of the person paying, smoking status, day of the week, time of day, and party size.
3. How to access or download the data if it's not included in the repository
     To download the dataset, go to the link: https://raw.githubusercontent.com/RusAbk/sca_datasets/main/tips.csv
### B - The main goals
Via this project, we will know how these factors below shall effect the tip amount of the restaurant:
1. Smokers vs Non-smokers
2. Female vs Male
3. Bills on Weekend vs Bill on Weekdays
4. Dinner vs Other meals

### C - Results
_1. Smokers vs Non-smokers analysis findings:_
   
   To view the code, visit this link : https://colab.research.google.com/drive/1BOeW24LI2IGgloc0pOFY8XXlE8rBTIn7#scrollTo=d8zSjOXmjG73&line=1&uniqifier=1

We filter our dataset to get measures of central tendency for Smokers group and Non-smokers group and then copmare them to the ones of the whole dataset. Resutl should be as below:

|        |    Common |  Smokers | Non-smokers |
|-------:|----------:|---------:|------------:|
|   min  |  1.000000 |  1.00000 |    1.000000 |
|   max  | 10.000000 | 10.00000 |    9.000000 |
|  mean  |  2.998279 |  3.00871 |    2.991854 |
| median |  2.900000 |  3.00000 |    2.740000 |   

For better review and analysis,  we look at the histograms of the Smokers group, Non-smokers group and the whole dataset:

   ![smoker vs non-smoker hist1](https://github.com/user-attachments/assets/101c71fd-670f-4cc5-97c0-3806a5f6c24e)

Graphs displayed side-by-side for further details:

![smoker vs non-smoker hist2](https://github.com/user-attachments/assets/b33c312f-9828-4c2a-9c8c-3d7524cd3847)

**So what can we get?**

In term of tip amount, Smokers group has higher tip amount, incomparison to average tip gave by all cusomters. $ 3.0 is the amount give by smokers the most. On the other hand, non-smokers have lower average common tip amount, in comparison to Smoker ones. They normally spend $ 2.74 for tipping.

_General conclusion:_ The number in tip amount between these 2 groups are slightly different. However, restaurant should not limit the services offer for the Smokers group since they seem to be more generous than the other one.

_2. Female vs Male analysis findings:_

Comparison table containing measures of central tendency of the 2 genders and the whole dataset:
Link : https://colab.research.google.com/drive/1BOeW24LI2IGgloc0pOFY8XXlE8rBTIn7#scrollTo=_1ODTCaOgUjT&line=1&uniqifier=1

|        |   Common | Female_tip |  Male_tip |
|-------:|---------:|-----------:|----------:|
|   min  | 1.000000 |   1.000000 |  1.000000 |
|   max  | 6.500000 |   6.500000 | 10.000000 |
|  mean  | 2.833448 |   2.833448 |  3.089618 |
| median | 2.750000 |   2.750000 |  3.000000 |

Overlapping histograms of the 3:


Histograms:
   
_3. Bills on Weekend vs Bill on Weekdays analysis findings:_
_5. Dinner vs Other meals analysis findings:_

   (to be continue)
