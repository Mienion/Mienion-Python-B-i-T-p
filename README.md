Excesie:
my_min
def my_min(a, b):
    if a > b:
        return b
    else:
        return a
Parentheses notation 
def parentheses_notation(x):
    if x > 0:
        return x
    else:
        return "("+str(abs(x))+")"

Average:
def average3(a,b,c):
    return round((a+b+c)/3,0)

Indicator:
def get_indicator(result,kpi):
    if result > kpi:
        return "😊"
    elif result == kpi:
        return "😐"
    else:
        return "☹️"
https://colab.research.google.com/drive/1F0x7aOMRF8UzX7gX9x2qG2tK7sLuw20z#scrollTo=6xGkQy3cpzBc

https://colab.research.google.com/drive/1obDmp4fy43tKEO9jJ4j_fPKZBiDazWi8#scrollTo=A35xYp_IHft7
https://colab.research.google.com/drive/1pzhm65Zo45n78l74KJCJlD4GYINAup6v#scrollTo=7uTa7KMhOId7

import pandas as pd
import statsmodels.api as sm
x = df['Head Size(cm^3)']
y = df['Brain Weight(grams)']
x = sm.add_constant(x)
model = sm.OLS(y, x).fit()
print(model.summary())

Xử lý outliers bằng tứ phân vị
Q1 - 1.5IQR < x < Q3 + 1.5IQR


