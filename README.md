# titanic-eda
Short Exploratory Data Analysis on the Titanic Dataset using pandas and matplotlib.

# Survival Rate Analysis(Age)
![Age Distribution][age]
**As we can see in the charts and the data**

1. Infants and Toddlers have the highest survival rates, there could be numerous reason for this. However, the most fitting reason could be family protecting the younger ones first and the saying "Women And Children First!"<br>
2. One interesting thing we can observe is, there seems to a high number of young adults who survived. 202 of young adults survived which seems large at first but then you realize there were 564 young adults boarding the ship. This is a classic example of how numbers alone can sometimes be misleading without any context.<br>
3. Surprisingly, only 9 out of 25 children survived which beats my earlier point that children were prioritized. Children in this sense are people aging from 5 to 12 years old. The reason could be that, children are at the age where they are aware of what's happening and that they can possibly die but not mature enough to remain calm. Therefore, making it harder for them to survive.<br>

### Actual Raw Data
**Total People**<br>
_Age group_<br>
Infant          14<br>
Todller         30<br>
Child           25<br>
Teenager        95<br>
Young Adult    564<br>
Adult          137<br>
Senior          26<br>


**Total Survivors**<br>
_Age Group_<br>
Infant          12<br>
Todller         19<br>
Child            9<br>
Teenager        39<br>
Young Adult    202<br>
Adult           54<br>
Senior           7<br>


**Survival Rate**<br>
_Age Group_<br>
Infant         86.0 %<br>
Todller        63.0 %<br>
Child          36.0 %<br>
Teenager       41.0 %<br>
Young Adult    36.0 %<br>
Adult          39.0 %<br>
Senior         27.0 %<br>

# Survivors By Gender
![Gender Distribution][gender]

**Females survived more than males**<br>
As we can see at first glance, 109 of the males survived while 233 of the females survived. But the shocking part is, even though the males were larger in numbers(577) , the survivors still comprised of mostly females.<br>

If we are talking about proportions then, the **survival rate** of females was **74.2%**, whereas the **survival rate** of males was **18.9%**. This makes the rates even clearer.

There could be various reasons for such a outcome. However, The saying women and children first seems to be more-fitted as per our analysis. However, it could also certainly be true that most of the females were from the age groups that had a high survival rate. Let's dig more.

# Survivors By Class
![Class Distribution][class]

**Upper classes survived the most**<br>
As we can see in the data below, there are few things we found out:<br>

1.) The survival rate of upper class(63%) was almost three times as much as the lower class(24.2%). This shows that as social status increased, the rates of survival also increased.<br>
2.) The middle class had survival rate of 47.3% such that they fall directly in the middle.
3.) The reasons for this disparity could be many, however one I can think of is the upper classes had access to the lower cabins of the ship, thus having high rates of survival.

# Correlation Between Class And Gender
#### The goal is to find out if the presence of a female population affected the survival rates of any of the classes.
![Gender/Class Distribution][genclass]

**Interesting**<br>
The lower classes comprised of largely males. As we are aware of, males have a less survival rate of only 18.9%. Whereas the upper and middle classes comprised of proportionally more females which could also be the underlying cause of high survival between upper and middle classes.

[age]: "images/age.png"
[gender]: "images/gender.png"
[class]: "images/class.png"
[genclass]: "images/genclass.png"

