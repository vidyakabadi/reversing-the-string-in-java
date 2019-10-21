# reversing-the-string-in-java
java code to reverse the string
package reverse_string;

import java.util.Scanner;
public class rev_str {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		Scanner sc=new Scanner(System.in);
		
		System.out.println("enter string");
	   
		String s=sc.next();
		String fin="";
		char ch[]=s.toCharArray();
		int len=s.length();
		
			for(int j=len-1;j>=0;--j)
			{
			   fin=fin+ch[j];
	
			}
	
		System.out.println(fin);
	
		
		
	}		
		
}
	
