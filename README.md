# Ngoding100DaysH_23

package ngoding100daysh_23;

import java.util.Scanner;


public class Ngoding100daysH_23 {

   
    public static void main(String[] args) {
        Scanner input = new Scanner(System.in); 
        System.out.print("masukkan angka :");
        int angka = input.nextInt();
        int hasil = angka % 2;
        String kondisi = hasil == 0 ? "genap" : "ganjil";
        System.out.println(kondisi);
    }
    
}
