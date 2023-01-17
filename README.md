# github-firstrepository

import java.util.Scanner;

public class Main
{
	public static void main(String[] args) {
	    char operator;
	    double result;
	    
		Scanner sc = new Scanner(System.in);
		System.out.println("Enter operator");
		operator = sc.next().charAt(0);
		System.out.println("Enter number 1");
		double n1=sc.nextDouble();
		System.out.println("Enter number 2");
		double n2=sc.nextDouble();
		
		switch(operator){
		    case'+':
		        result=n1+n2;
		        System.out.println(n1+" + "+n2+" = "+result);
		        break;
		        
		    case'-':
		        result=n1-n2;
		        System.out.println(n1+" - "+n2+" = "+result);
		        break;
		        
		    case'*':
		        result=n1*n2;
		        System.out.println(n1+" * "+n2+" = "+result);
		        break;
		        
		    case'/':
		        result=n1/n2;
		        System.out.println(n1+" / "+n2+" = "+result);
		        break;
		        
		    default:
		        System.out.println("Invalid operator");
		}
		
	}
}
