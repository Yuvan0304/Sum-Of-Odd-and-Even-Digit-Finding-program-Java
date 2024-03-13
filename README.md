# Sum-Of-Odd-and-Even-Digit-Finding-program-Java
I have uploaded the program Find Sum Of Odd and Even Digit 
Program:
import java.util.*;
public class Main{
	public static void main(String[] args) {
	Scanner sc=new Scanner(System.in);
	System.out.print("Enter the no of digit");
	int n=sc.nextInt();
	int a,b=0;
	System.out.print("Enter the number");
	int m=sc.nextInt();
	for(int i=0;i<=n;i++){
	    a=m%10;
	    b=b+a;
	    m/=10;
	    if(a%2==0){
	        System.out.println("Even digit :"+a);
	    }else{
	        System.out.println("Odd digit :"+a);
	    }
	   
}
}}
