# Mencoba Alur Balik
https://github.com/ValSyacy/latihan4/blob/c70c5c371207f7c5a358ea28be9832649daebcac/Persegi%20Panjang/PersegiPanjang.java

dengan menguploud job sheet1 ke git hub
import java.util.Scanner;

public class PersegiPanjang {
    public static void main(String[] args) {

        Scanner input = new Scanner(System.in);

        int panjang, lebar, luas, keliling;

        System.out.println("Masukkan Nilai Panjang");
        panjang=input.nextInt();
        System.out.println("\nMasukkan Nilai Lebar");
        lebar=input.nextInt();

        luas= panjang * lebar;
        keliling= 2 * panjang + lebar;

        System.out.println("\nHasil Luas Adalah = " +luas);
        System.out.println("Hasil Keliling Adalah = " +keliling);
    }
}
