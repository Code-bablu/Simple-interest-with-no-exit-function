# Simple-interest-with-no-exit-function
This programs finds only si problem and also do not calculate the Amount ... so enjoy in future I might add everything in this project 🫠?

try :
    print("This Program Find out The Simple Interest.")
    print("Please Choose an option")
    print()
    print("1.Every variables given ")
    print("2.Find out the Time")
    print("3.Find out the Principle")
    print("4.Find out the Rate")
    print()
    def math():
        x=int(input("Choose One = "))
        match x:
            case 1:
               Pr=int(input("Principle ="))
               r =int(input("Rate = "))
               t =int(input("Time = "))
               SI = (Pr*r*t)/100
               print("Simple Interest = ",SI)
            case 2:
               Pr=int(input("Principle ="))
               r =int(input("Rate = "))
               SI =int(input("Simple Interest = "))
               t = (SI*100)/(Pr*r)
               print("The Time is = ",t)
            case 4:
               Pr=int(input("Principle ="))
               t =int(input("Time = "))
               SI =int(input("Simple Interest = "))
               r = (SI*100)/(Pr*t)
               print("The Rate Is = ",r)
            case 3:
               r =int(input("Rate = "))
               t =int(input("Time = "))
               SI =int(input("Simple Interest= "))
               Pr = (SI*100)/(t*r)
               print("The Principle Is = ",Pr)  
    print() 
    print("You Want find other variables ??")      
    math()
except:
    math()
        
        
        
        
math()
