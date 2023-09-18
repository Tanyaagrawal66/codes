Modern Student 
DILIP KUMAR 	
	

COMPUTER ASSINGMENT FILE 
Section Title
COMPUTER ASSINGMENT BASIC PROGRAM FILE
	

	“MY NAME IS DILIP KUMAR SISODIYA
SECTION - BTECH 1st YEAR AY1
ASSINGMENT OF C LANGUAGE”		

Q1. Write a C program for calculating the price of a product after adding the sales tax to its original price. Where rate of tax and price is inputted by user.

SOLUTION::  
#include<stdio.h>
#include<conio.h>
int main()
{ 
int product_rate, sales_tax,total;
printf(“enter product rate and sales tax  :”);
scanf(“%d %d”,&product_rate,&sales_tax);
total=product_rate+sales_tax;
printf(“%d”,total);
return 0;
}

Q2. Write a C program to calculate the weekly wages of an employee. The pay depends on wages per hour and number of hours worked. Moreover, if the employee has worked for more than 30 hours, then he or she gets twice the wages per hour, for every extra hour that he or she has worked.

Solution:
#include<stdio.h>
#include<conio.h>
int main()
{
int wages_per_hour; 
int  working_hours;	
printf("enter wages per hour and working hours");
scanf("%d %d",&wages_per_hour,&working_hours);
if(working_hours>30){
  int extra_hour= working_hours -30;
  int  total_wages=(30*wages_per_hour)+(extra_hour *2*wages_per_hour);
 printf("%d",total_wages);
}else{
         printf("%d",wages_per_hour*working_hours);
return 0;

}
}

Q.3 Mr. X goes to market for buying some fruits and vegetables. He is having a currency of Rs 500 with him for marketing. From a shop, he purchases 2.0 kg Apple priced Rs. 50.0 per kg, 1.5 kg Mango priced Rs.35.0 per kg, 2.5 kg Potato priced Rs.10.0 per kg, and 1.0 kg Tomato priced Rs.15 per kg. He gives the currency of Rs. 500 to the shopkeeper. Find out the amount shopkeeper will return to X by writing a C program.
Solution:
#include<stdio.h>
#include<conio.h>
int main()
{
int apple_per_kg=50;
int mango_per¬_kg=35;
int potato_per_kg=10;
int tomato_per_kg=15;
float total=(50*2)+(35*1.5)+(10*2.5)+(1*15);
float net=500-total;
printf(“%f”,net);
rteurn 0;
}

Q4.Write a C program to print your name, date of birth and mobile number in 3 different lines?
Solution:
#include<stdio.h>
#include<conio.h>
int main()
{
int date_of_birth,name,mobile_number;
printf(“enter date of birth, name and mobile no.”);
scanf(“%d %d %d”,&date_of_birth,&name,&mobile_number);
printf(“\n%d”,date_of_birth);
printf(“\n%d”,name);
printf(“\n%d”,mobile_number);
return 0;
}
Q5.Write a program to read an integer, a character and a float value from keyboard and display the same in different lines on the screen
Solution::

Q6.Write a program to print the following line ( Assume the total value is contained in a variable named cost)
The sales total is : $ 172.53
Solution:
#include<stdio.h>
#include<conio.h>
Int main()
{
float cost=172.53;
printf(“the sales total is %.2f”,cost);
return 0;
} 	+
Q7.Raju got 6 and half apples from each of Raghu, Sheenu and Akash. He wants to know how many apples he has in total without adding them. Write a program which could help Raju in doing this.
Solution;
#include<stdio.h>
#include<conio.h>
Int main()
{
  

 

 
Q8 .Write a program that prints the floating point value in exponential format correct to two decimal places.
Solution:
#include<stdio.h>
#include<conio.h>
int main()
{
float cost=172.53;
printf("the sales total is %.f",cost);
return 0;
}	
	

Q9.Write a program to input and print your mobile number (i.e. of 10 digits).
Solution: #include<stdio.h>
#include<conio.h>
int main()
{
int mobile_number;
	printf("enter your mobile number: ");
	scanf("%d",&mobile_number);
	printf("mobile number is  %d",mobile_number);
return 0;
}

Q10.The population of a city is 30000. It increases by 20 % during first year and 30% during the second year. Write a program to find the population after two years? (Ans: 46800)
Solution: 
#include<stdio.h>
#include<conio.h>
int main()
{
int population=30000;
	int population_increased_infirst_war=(30000*20)/100;
	int total_population_after_1st_war=population+population_increased_infirst_war;
    int population_increased_insecond_war=(total_population_after_1st_war*30)/100;
    int total_population_after_2nd_war=(total_population_after_1st_war+population_increased_insecond_war);
    int net_population=total_population_after_2nd_war;
    printf("%d",net_population);
return 0;
}

Q11. Write a program to find the ASCII value of a character.

Solution:
#include<stdio.h>
#include<conio.h>
int main()
{
	char n;
	printf("enter any value: ");
	scanf("%c",&n);
	printf("%d",n);
	return 0;
}
Q12. Write a program to calculate salary of an employee, given his basic pay (entered by user), HRA=15% of the basic pay and TA=20% of the basic pay.
Solution:
#include<stdio.h>
#include<conio.h>
int main()
{
	float basic_pay,salary,TA,HRA,total_salary;
	printf("enter employee basic pay");
	scanf("%f",&basic_pay);
	HRA=0.15*basic_pay;
	TA=0.20*basic_pay;
    total_salary=TA+HRA+basic_pay;
	printf("%.2f",total_salary);
	return 0;
}
Q13. Write a program to find  the slope of a line and angle of inclination that passes through two points P and Q with coordinates (xp, yp) and (xq, yq) respectively.
Solution:
#include<stdio.h>
#include<conio.h>
int main()
{
int xp,yp,xq,yq,slope;
printf(“enter values of co-ordinates of P and Q”);
scanf(“%d,%d,%d,%d”,&xp,&yp,&xq,&yq);
slope=(yq-yp)/(xq-xp);
printf(“%d”,slope);
return 0;
}


Q14. The SPI (Semester Performance Index) is a weighted average of the grade points earned by a student in all the courses he registered for in a semester. If the grade points associated with the letter grades awarded to a student are g1, g2, g3,…….gk etc. and the corresponding credits are c1, c2, c3,.…..ck, the SPI is  given by:
SPI=(∑_(i=1)^k▒〖c_i g_i 〗)/(∑_(i=1)^k▒c_i )
Where, k is the number of courses for which the candidate remains registered for during the semester/ trimester. Write a program in C to calculate SPI for k =5.
Solution:
#include<stdio.h>
#include<conio.h>
int main()
{
	int g1,g2,g3,g4,g5,c1,c2,c3,c4,c5,SPI;
	printf("enter grade points values");
	scanf("%d,%d,%d,%d,%d",&g1,&g2,&g3,&g4,&g5);
	printf("enter c values: ");
	scanf("%d,%d,%d,%d,%d",&c1,&c2,&c3,&c4,&c5);
	SPI=(g1*c1+g2*c2+g3*c3+g4*c4+g5*c5)/(c1+c2+c3+c4+c5);
	printf(" THE SEMESTER PERFOMANCE INDEX VALUE IS %d",SPI);
	return 0;
}
Q 15. Write a program to calculate the frequency (f) of a given wave with wavelength (λ) and speed (c), where c=λ*f.
SOLUTION:
#include<stdio.h>
#include<conio.h>
int main()
{
	int wavelenght,frequency;
	int speed=300000000;
	printf("enter wavelenght of a light");
	scanf("%d",&wavelenght);
	frequency=speed/wavelenght;
	printf("%d",frequency);
	return 0;
}
Q 16. A car travelling at 30 m/s accelerates steadily at 5 m/s2 for a distance of 70 m. What is the final velocity of the car? [Hint: v2 = u2 + 2as]
Solution:
#include<stdio.h>
#include<conio.h>
#include<math.h>
int main()
{
	float a=5,s=70,u=30;
	float final_velocity=sqrt(u*u+2*a*s);
	
	printf("%.2f",final_velocity);
	return 0;
}
Q 17.A horse accelerates steadily from rest at 4 m/s2 for 3s. (a) What is its final velocity? (b) How far has it travelled? [Hint: (a) v = u + at (b)  s = ut + ½at2 ]
Solution:
#include<stdio.h>
#include<conio.h>
#include<math.h>
int main()
{
	float a=4,t=3,u=0;
	float final_velocity=(u+a*t);
	printf("%.2f",final_velocity);
	float total_distance=(u*t+(a*t*t)/2);
	printf("\n%.2f",total_distance);
	return 0;
}
Q 18. Write a program to find the sum of your four last digit of your university roll number .
Solution:
#include<stdio.h>
#include<conio.h>
int main()
{
	int roll_number,count;
	int sum=0;
	int i=1;
	printf("enter roll no. ");
	scanf("%d",&roll_number);
	{ for(i=1;i<=roll_number;i++)
	 	count+=roll_number%10;
	 	roll_number/=10;
	    }
	}
		printf("THE SUM OF LAST FOUR DIGIT OF YOUR ROLL NUMBER IS %d",count);
		return 0;
}
Q19. Write a program to initialize your height and weight in cm. and kgs respectively demonstrating compile time initialization and convert them in feets and pounds respectively.  Note :- 1 cm = 0.393701inch , 1 Kg = 2.20462
Solution:
#include <stdio.h>
#include<conio.h>
int main()
{
	float height = 170.0;
	int weight = 52;
	float height_in_feet = height * 0.0328084;
	float weight_in_pounds = weight * 2.20462;
 	 printf("Height in feet: %f\n", height_in_feet);
 	 printf("Weight in pounds: %f\n", weight_in_pounds);

  return 0;
}

 
Q 20 . Code the variable declarations for each of following:
	A character variable named option.
	An integer variable sum initialized to 0
	A floating point variable, product, initialized to 1

Solution:
char option::
 A character variable named option.

int sum = 0:: 
 An integer variable sum initialized to 0.

float product = 1.0:: 
A floating point variable product initialized to 1.

Q21. Write a program that reads nine integers. Display these numbers by printing three numbers in a line separated by commas.
Solution:
include <stdio.h>
include<conio.h>
int main() 
{

  int numbers[9];

  for (int i = 0; i < 9; i++) {
    scanf("%d", &numbers[i]);
  }

  for (int i = 0; i < 9; i += 3) {
    printf("%d, %d, %d\n", numbers[i], numbers[i + 1], numbers[i + 2]);
  }

  return 0;
}


	
Q22. What are header files and what are its uses in C programming?
Solution:
A header file is a file with extension .h which contains C function declarations and macro definitions to be shared between several source files. There are two types of header files: the files that the programmer writes and the files that comes with your 

Q23. What will be the output of following program
#include<stdio.h>
int main()
{   int num=070;
printf(“%d\t%o\t%x”,num,num,num);

solution: 
output=  The output of the following program will be:
56   70  38
	
Q 24. What will be the output of following program?
#include <stdio.h>
void main() 
{
int x = printf("GLA UNIVERSITY");
   	printf("%d", x);
  	 }
Solution:
Output=15.

       Q25. What are library functions? List any four library                functions.
       Solution:
      Library functions are built-in functions that are grouped
      together and placed in a common location called 
      library. Each function here performs a specific                                                             operation. We can use this library functions to get the pre- 
     defined output. All C standard library functions are
     declared by using many header files.
Q26. What will be the output of following program?
#include <stdio.h>
void main() 
{
 	  int x = printf("C is placement oriented Language") – printf(“Hi”);
 	  printf("%d %o %x", x,x,x);
 	}
        Solution:
        26  32  1a
	
	

	




 
Q27. What is the meaning of following statement?    printf(“%d”,scanf(“%d%d”,&a,&b));
Solution:
 It means first value assign to a and then second value assign to second.

Q28. What will be the output of following program?
#include <stdio.h> 
void main() 
{ 
  printf(" \"C %% FOR %% PLACEMENT\""); 
}
Solution:
Output= “C%%FOR%%PLACEMENT”

Q29. Suppose distance between GLA University and Delhi is m km (to be entered by user), by BUS you can reach Delhi in 4 hours. Develop a ‘C’ program to calculate speed of bus.
Solution:
#include<stdio.h>
#include<conio.h>
int main()
{
int distance;
int time=4;
printf(“enter distance in km”);
scanf(“%d”,&distance);
int speed =distance/time;
printf(“%d”,speed);
return 0;
}

Q30. In an exam Satyam got 50 marks, Suman got 70 marks and Shyam got 80 marks, Write a ‘C’ program to find average marks of these three participants.
Solution:
#include<stdio.h>
#include<conio.h>
int main()
{
	float m1=50;
	float m2=70;float m3=80;
	float total_marks=m1+m2+m3;
	float average=(total_marks)/3;
	printf("%.2f",average);
	return 0;
}
Q31. One day, Mohan called Saurav and Sajal and gave some money to them, later he realized that money that was given to Saurav should be given to Sajal and vice-versa. Develop a ‘C’ program to help Mohan so that he can rectify his mistake.
Solution:
#include <stdio.h>
#include<conio.h>
int main()
 {
  int money_given_to_saurav, money_given_to_sajal;

  printf("Enter the money that was given to Saurav: ");
  scanf("%d", &money_given_to_saurav);

  printf("Enter the money that was given to Sajal: ");
  scanf("%d", &money_given_to_sajal);
  
  int temp = money_given_to_saurav;
  money_given_to_saurav = money_given_to_sajal;
  money_given_to_sajal = temp;
  printf(" Now,the correct money distribution is:\n");
  printf("Saurav: %d\n", money_given_to_saurav);
  printf("Sajal: %d\n", money_given_to_sajal);

  return 0;
}










 
Q32. One day when I was going for a lunch, suddenly rain started, I was very hungry so started running with speed of 4km/h and it took 3 min to reach mess. Help me to develop a ‘C’ program to calculate distance travelled by me.
Solution:
#include<stdio.h>
#include<conio.h>
int main()
{
	float speed=4;
	float time=3;
	//convert time to hours//
	time=time/60;
	float distance=speed*time;
	printf("distance travelled: %.2fkm",distance);
	return 0;
}

Q33. Can two or more escape sequences such as \n and \t be combined in a single line of program code?
Solution:
Yes, two or more escape sequences can be combined in a single line of program code. For example, the following code will print the following output:

printf("Hello, world!\n\tThis is a new line with a tab.\n”);

output:

hello,world!
   This is a new line with a tab.




Q34. What are comments and how do you insert it in a C program?
Solution:
The Multi-line comment in C starts with a forward slash and asterisk ( /* ) and ends with an asterisk and forward slash ( / ). Any text between / and */ is treated as a comment and is ignored by the compiler.

Q35. What is wrong in this statement?  scanf(“%d”,number);
Solution:
“&” is not here, so this statement is wrong.

Q36. What will be the output?

#include <stdio.h>
int main()
{
    if (sizeof(int) > -1)
        printf("Yes");
    else
        printf("No");
    return 0;
}
Solution: “yes”.

Q37. Point out which of the following variable names are invalid: 
gross-salary INTEREST , salary of emp , avg. , thereisbookinmysoup

solution:

valid: “INTEREST” and “thereisbookinmysoup”
invalid: “salary of emp” and “avg.”


Q38. Tom works at an aquarium shop on Saturdays. One Saturday, when Tom gets to work, he is asked to clean a 175-gallon reef tank. His first job is to drain the tank. He puts a hose into the tank and starts a siphon. Tom wonders if the tank will finish draining before he leaves work. He measures the amount of water that is draining out and finds that 12.5 gallons drain out in 30 minutes. So, he figures that the rate is 25 gallons per hour. Develop a ‘C’ program to help Tom to calculate time required to completely clean tank.

Solution:

#include <stdio.h>

#include<conio.h>

int main() 
{
  int tank_capacity = 175;

  int drainage_rate = 25;

  float time_required = (float)tank_capacity / drainage_rate;
  printf("Time required to completely clean tank: %.f hours\n", time_required);

  return 0;

}





	
 

Q39. The percent y (in decimal form) of battery power remaining x hours after you turn on a laptop computer is y = −0.2 x + 1. Develop a ‘C’ program to calculate after how many hours the battery power is at 75%?

Solution:
#include <stdio.h>

int main() {
  
  float y = -0.2 * x + 1;

  
  float target_battery_power = 0.75;

  
  float time_required = 
(1 - target_battery_power) / 0.2;

  
  printf("Time required to reach 75% battery power: %f hours\n", time_required);

  return 0;

}









 

		
		
Q40.Which of the following is used to convert the high level language in machine language in a single go?
a. Compiler		b.Interpreter 
c. Linker		d.Assembler 
solution: 
(A)compiler

Q 41. What is the format specifier for an Octal Number?
a.%0	 	b.%d 
c. %o		d. %e
solution:
 (C)%o

Q 42. Which format specifier is used to print the exponent value upto 2 decimal places.
a. %e	b.%.2f 	c. %f		d.%.2e 
solution: 
(D) %.2F

Q 43. Which of the following is not a basic data type?
a. char
b. array
c. float	
d. int
solution: 
(B) array

Q 44. What is the output of following code?
#include<stdio.h>
void main()
{
  int x=0;
  x= printf("\"hello\b\"");
  printf(“%d”,x);
}
a. hello7     b. “hello”7	 c. “hell”8      d. hell8
solution:
(D) hell8 

Q 45.  What is the output of following code?
#include<stdio.h>
void main()
{
  int b,c=5 ;
  int(“%d , %d”, b,c);
}
a. 5, 5			  b. 5, 5.000000	
c. Garbage, 5.000000       d. Garbage, 5
solution:
 (D) garbage,5.

Q46. Which of the following is an identifier?
a. &fact      b. Basic_pay    c. enum         d. 1sum 
solution: 
(A) basic_pay

Q 47. What is the output of the following program?
#include<stdio.h>
void main()
{
   char x, a=’c’;
   x=printf("%c",a);
   printf(“%d”,x);
}
a. c1		b. cgarbage
c. 1		c. c
solution:
	 C1

Q48. Perform the following conversion from Decimal to other number as directed-
	(365.55)10 =  (?)2
	(453.65)10 =  (?)8
	(5164.12)10 = (?)16
	(23.65)10 =  (?)5
	(772)10 =       (?)7
Solution:
a) 365.55 to binary
365.55 = 10110101.1101
(b) 453.65 to octal
453.65 = 701.65
(c) 5164.12 to hexadecimal
5164.12 = 1464.6
(d) 23.65 to quinary
23.65 = 42.14
(e) 772 to septenary
772 = 1754


Q49. Covert the following numbers to decimal number system-
	(325.54)6 = (?)10
	(1001010110101.1110101)2 = (?)10
	(742.72)8 = (?)10
	(AC94.C5)16 = (?)10
Solution:
(a) 325.54 base 6 to decimal
(325.54)6 = 3 * 6^2 + 2 * 6^1 + 5 * 6^0 + 5 * 6^-1 + 4 * 6^-2 = 129.94
(b) 1001010110101.1110101 base 2 to decimal
(1001010110101.1110101)2 = 1 * 2^10 + 0 * 2^9 + 0 * 2^8 + 1 * 2^7 + 0 * 2^6 + 1 * 2^5 + 1 * 2^4 + 0 * 2^3 + 1 * 2^2 + 0 * 2^1 + 1 * 2^0 + 1 * 2^-1 + 1 * 2^-2 + 0 * 2^-3 + 1 * 2^-4 = 973.705
(c) 742.72 base 8 to decimal
(742.72)8 = 7 * 8^2 + 4 * 8^1 + 2 * 8^0 + 7 * 8^-1 + 2 * 8^-2 = 448 + 32 + 2 + 0.875 + 0.03125 = 482.90625
(d) AC94.C5 base 16 to decimal
(AC94.C5)16 = 10 * 16^3 + 12 * 16^2 + 9 * 16^1 + 4 * 16^0 + 12 * 16^-1 + 5 * 16^-2 = 4096 + 192 + 144 + 4 + 0.75 + 0.03125 = 4346.78125


Q50. Perform the following conversion from Hexadecimal to other number as directed-
 (DB56.CD4)16 = (?)2,   (?)8,   (?)4
Solution:
DB56.CD4 (hexadecimal) to binary:
57344.475 (decimal) = 11100111110101110101.01100101 (binary)
DB56.CD4 (hexadecimal) to octal:
57344.475 (decimal) = 115551606.72 (octal)
DB56.CD4 (hexadecimal) to quinary:
57344.475 (decimal) = 11012203.43 (quinary)
DB56.CD4 (hexadecimal) to septenary:
57344.475 (decimal) = 175465.2 (septenary)
Therefore, the answers to your questions are:
(DB56.CD4)16 = 11100111110101110101.01100101 (binary)
(DB56.CD4)16 = 115551606.72 (octal)
(DB56.CD4)16 = 11012203.43 (quinary)
(DB56.CD4)16 = 175465.2 (septenary)


Q51. Perform the following conversion from octal to other number as directed-
(473.42)8 = (?)2,   (?)10,   (?)16,   (?)5
Solution:
473.42 (octal) to binary:
347.525 (decimal) = 10101111.0101 (binary)
473.42 (octal) to decimal:
347.525 (decimal) = 347.525 (decimal)
473.42 (octal) to hexadecimal:
347.525 (decimal) = 15B.3 (hexadecimal)
473.42 (octal) to quinary:
347.525 (decimal) = 1042.24 (quinary)
473.42 (octal) to septenary:
347.525 (decimal) = 175.2 (septenary)
Therefore, the answers to your questions are:
(473.42)8 = 10101111.0101 (binary)
(473.42)8 = 347.525 (decimal)
(473.42)8 = 15B.3 (hexadecimal)
(473.42)8 = 1042.24 (quinary)
(473.42)8 = 175.2 (septenary)

Q52. Find the value of A?
	(23)10 = (17)A
	(21)16 = (41)A
	(32)8 = (101)A
Solution:
The answers to the questions are:
	a)(23)10 = (17)17
	b)(21)16 = (31)
    c)(32)8 = (22)4 



Q53:  What will be the output of following program? Assume integer is of 2 bytes
void main(){
int  a=32770;
printf(“%d”,a);
}
Solution:
The output of the following program will be 32770.

Q54: #include <stdio.h>
 int main()
{
 float c = 5.0;
 printf ("Temperature in Fahrenheit is %.2f", (9/5)*c + 32);
 return 0;
}
Solution:

	OUTPUT=”Temperature in fehrenheit is 41.00.” 












 
		
	
 
	finally complete.
