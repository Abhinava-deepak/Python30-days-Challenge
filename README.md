# Python30-days-Challenge
python 30 days Challenge my self


 # leap year

def is_leap(year):
    if (year%400==0) or (year%4==0 and year%100!=0):
        return True
    else:
         return False
year = int(input())
print(is_leap(year))
