
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

Detail of each histogram:

![whole_dataset_tip_value](https://github.com/user-attachments/assets/8fb1cb72-6280-409e-8fb3-2244036e16e2)


![smoker_tip_value](https://github.com/user-attachments/assets/a76125b2-ff48-43fb-8912-a6b25947d1f8)


![non-smoker_tip_value](https://github.com/user-attachments/assets/1ac0f353-aa00-42b4-a3a6-002370fa7189)

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

![whole_dataset_tip_value](https://github.com/user-attachments/assets/8fb1cb72-6280-409e-8fb3-2244036e16e2)

![female_tip_value](https://github.com/user-attachments/assets/2d971b40-137b-4355-9851-78c1745a2afa)

![male_tip_value](https://github.com/user-attachments/assets/cecc8511-709c-4610-ad67-30f79bc110af)

Overlapping histograms of the 3:

![female vs male hist-overlap](https://github.com/user-attachments/assets/2ddacd15-46f6-4e31-aab4-b4e74c78493d)


![female vs male hist side-by-side](https://github.com/user-attachments/assets/2e5fb57a-f1e9-4df5-a1e1-8285efd83eaa)

Insight: Male customers do give higher tips; and they tend to tip more frequently when they use the service, in comparison to Female customers.
   
_3. Bills on Weekend vs Bill on Weekdays analysis findings:_

|        |    Common | Weeknd_tip | Weekday_tip |
|-------:|----------:|-----------:|------------:|
|   min  |  1.000000 |   1.000000 |     1.00000 |
|   max  | 10.000000 |  10.000000 |     6.70000 |
|  mean  |  2.998279 |   3.115276 |     2.76284 |
| median |  2.900000 |   3.000000 |     2.50000 |


![weekend_tip_value](https://github.com/user-attachments/assets/910aa9bd-d79c-48a3-8f5f-cec16b0571d6)


![weekday_tip_value](https://github.com/user-attachments/assets/f4e07a90-8e4b-44cf-916e-649932b2d23d)


![weekend vs weekday hist side-by-side](https://github.com/user-attachments/assets/f3ec915e-500b-4e11-b518-5c7f106758f4)
7)

Overlapping histograms of the 3:

![weekend vs weekday hist-overlap](https://github.com/user-attachments/assets/07bb9ec4-73f0-4b55-b3a5-dff1bcf3263

Insight: The restaurant will gain more tips on weekend, in deed. The difference in amount of tips received in weeknd is extreme. Restaurant owners should think about solutions to increase the occupancy in weekends to take advantage of this point.  

_5. Dinner vs Other meals analysis findings:_

|        |    Common | Dinner_tip | Other_meal_tip |
|-------:|----------:|-----------:|---------------:|
|   min  |  1.000000 |    1.00000 |       1.250000 |
|   max  | 10.000000 |   10.00000 |       6.700000 |
|  mean  |  2.998279 |    3.10267 |       2.728088 |
| median |  2.900000 |    3.00000 |       2.250000 |



![Dinner_tip_value](https://github.com/user-attachments/assets/981a706f-4453-4a5d-bf08-8836cbcb2cd9)

![Other-meal_tip_value](https://github.com/user-attachments/assets/40a8bc58-5293-447c-862b-9fc615303d69)


![dinner vs other-meals hist side-by-side](https://github.com/user-attachments/assets/145fe3a9-f22c-41a3-9a5a-1d79cf038377)

Overlapping histograms of the 3:

![dinner vs other-meal hist-overlap](https://github.com/user-attachments/assets/e1145537-15e1-421a-9bad-8ce27532f353)

Insight:
Customers of this restaurant tend to give more tip for Dinner, in comparison to other meals of a day. Restaurant owner can think about methods to increase the customer experience or service quality for other meals of day to increase the tipping.

