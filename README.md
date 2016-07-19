# FindLargestNumber

import java.util.Scanner;

public class LargestNumberAmongThreeInput {
	public static void main(String []arg)
	{

	Scanner get=new Scanner(System.in);
	System.out.println("enter Integer A"); 
	int input1=get.nextInt();
	System.out.println("enter Integer B"); 
	int input2=get.nextInt();
	System.out.println("enter Integer C"); 
	int input3=get.nextInt();
	if(input1>input2 && input1>input3)
	{
		System.out.println("A is greater");
	}
	else if(input2>input1 && input2>input3)
	{
		System.out.println("B is greater");
	}
	else
	{
		System.out.println("C is greater");
	}

	}
}
