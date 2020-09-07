# Program-2.java
Problem-2: With a single integer as the input, generate the following until a = x [series of numbers as shown in below examples]

Output: (examples)
1) if a = 1, then output : 1
2) if a = 2, then output : 1, 3
3) if a = 3, then output : 1, 3, 5
4) if a = 4, then output : 1, 3, 5, 7

import java.util.Scanner;

class Exam{
	public static void main(String[] args) {

	        Scanner s=new Scanner(System.in);
	        System.out.println("enter a number");
	        int a=s.nextInt();
	        String as="";
	        for(int i=1;i<=a*2;i=i+2){
	            as=i+",";
	            System.out.print(as);
	        }
	     }
	}
