# Palindrome-Number
import java.util.*;
import java.io.*;
class Palindrome
{
	public static void main (String[] args) 
	{
	   int n,temp,r,sum=0;
	   System.out.println("Enter the no.:");
	   Scanner s=new Scanner(System.in);
	   n=s.nextInt();
	   temp=n;
	   while(n>0)
       {
       r=n%10;
       n=n/10;
       sum=sum*10+r;
        }
    if(temp==sum)
         System.out.println(temp+" is a palindrome");
    else
         System.out.println(temp+" is not a palindrome");
	}
}
