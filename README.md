d = 5
u = 999
  
for number in range(d,u + 1):  
   if number > 1:  
       for i in range(2,number):  
           if (number % i) == 0:  
               break  
       else:  
           print(number)  
