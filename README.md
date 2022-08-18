# Calculator-in-python
first = input("Enter number 1");
operator = input("Enter sign +,*,-,/,%");
second = input("Enter number 2");
first = int(first);  
second = int(second);
operator = str(operator)

if (operator) =='+':
    print (first + second);

elif (operator)=='-':
    
    print(first - second);

elif (operator)=='*':
   
   print(first * second);

elif (operator)=='/':
    
    print(first / second);

elif (operator)=='%':
    
    print(first % second);

else :
    print("Invalid")      
