# AutoMorphic-Number
printing AutoMorphic Number in java
package javaproject;
import java.util.Scanner;
public class AutoMorphicNum {
	static public void autoMorphicNum(int n) {
		if((n*n)%10==n)
			System.out.println("AutoMorphic Number");
		else
			System.out.println("Not AutoMorphic Number");
	}

	public static void main(String[] args) {
		Scanner sc=new Scanner(System.in);
		AutoMorphicNum obj=new AutoMorphicNum();
		System.out.println("enter a number: ");
		int n=sc.nextInt();
		obj.autoMorphicNum(n);

	}

}
