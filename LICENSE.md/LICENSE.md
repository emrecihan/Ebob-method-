package sinavsorulari;

import java.util.Scanner;

public class methods1 {

	public static void main(String[] args) {
		Scanner input= new Scanner (System.in);
		int sayi1,sayi2;
		sayi1 = input.nextInt();
		sayi2 = input.nextInt();
		ebob(sayi1, sayi2);

	}
	public static void ebob(int sayi1,int sayi2)
	{
		int lebob = 1;
		int k = 1;
		while(k <= sayi1 && k<=sayi2)
		{
			if(sayi1%k==0 && sayi2 %k==0)
			{
				lebob=k;
			}
			k++;
		}
		System.out.println("en büyük ortak bölen = "+lebob);
	}

}
