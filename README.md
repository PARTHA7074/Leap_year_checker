# Leaper_checker
#Hackerrank Python parctice problem
def is_leap(year):
    if year%100==0:
        if year%400==0:
            leap = True
        else:
            leap = False
    else:
        if year%4==0:
            leap = True
        else:
            leap = False

        

    # Write your logic here
    
    return leap

year = int(input())
