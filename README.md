# greatest-among-three-numbers
import java.util.Scanner;  
public class Greatestamongthreenumbers  
{  
public static void main(String[] args)   
{  
int a, b, c, greatest, temp;  
Scanner sc = new Scanner(System.in);  
System.out.println("Enter the first number:");  
a = sc.nextInt();  
System.out.println("Enter the second number:");  
b = sc.nextInt();  
System.out.println("Enter the third number:");  
c = sc.nextInt();  
temp=a>b?a:b;    
Greatest=c>temp?c:temp;   
System.out.println("The Greatest number is: "+Greatest);  
}  
}  
