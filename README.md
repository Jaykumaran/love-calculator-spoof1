# love-calculator spoof


print("Welcome to affection calculator")
name1= input("what is your name: \n")
name2= input("what is their name: \n")
combined_name=name1+name2
lower_case_name=combined_name.lower()
t=lower_case_name.count("t")
r=lower_case_name.count("r")
u=lower_case_name.count("u")
e=lower_case_name.count("e")

t_rue= t+r+u+e

l=lower_case_name.count("l")
o=lower_case_name.count("o")
v=lower_case_name.count("v")
e=lower_case_name.count("e")

love=l+o+v+e

love_score = int(str(t_rue)+str(love))

if (love_score<10) or (love_score>90):
    print("ÿou go together like coke and mentos")
    
elif (love_score>=40) and (love_score <=50):
 print(f" Your score is {love_score},you are alright together:") 
else:
    print(love_score)
    
    
    sample output:
    Welcome to affection calculator
what is your name: 
JAy  
what is their name: 
KUMARAN
20

    



