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
