# gradeCalculator
Calculating academic grades.
package patikaAcademy;

import java.util.Scanner;

public class notOrtalamasi {

	public static void main(String[] args) {
		
		int mat, turkce , tarih , fizik , kimya , biyoloji ;
		
		Scanner input = new Scanner(System.in);
		
		System.out.print("Matematik Notu:");
		mat = input.nextInt();
		
		System.out.print("Kimya Notu:");
		kimya = input.nextInt();
		
		System.out.print("Fizik Notu:");
		fizik = input.nextInt();
		
		System.out.print("Türkçe Notu:");
		turkce = input.nextInt();
		
		System.out.print("Tarih Notu:");
		tarih = input.nextInt();
		
		System.out.print("Biyoloji Notu:");
		biyoloji = input.nextInt();
		
		int num= (mat+tarih+turkce+fizik+kimya+biyoloji);
		double result =num/6;
		System.out.print("Ortalama:"+ result);
		
		boolean sonuc = result<60 ;
		
		String str = sonuc ?  "KALDI" : "GEÇTİ";
		
		System.out.println(" " + str);
		
		
		
		

	}

}
