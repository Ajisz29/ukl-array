package ARRAY;
import java.util.Scanner;
public class ukaell {

    static void gabunganMethod() {
       homeMethod();
    }
    static void myMethod() {
        Scanner input = new Scanner(System.in);
        System.out.println("Masukkan Data Yang Anda Cari ( Dapat Berupa Nama, Kelas Ataupun NISN )");
        String pilihan = input.nextLine();

    }

    static void homeMethod() {
        Scanner input = new Scanner(System.in);
        System.out.println("Masukkan Data Yang Anda Cari ( Dapat Berupa Nama, Kelas Ataupun NISN )");
        String pilihan = input.nextLine();
        String[] nama = {"Agus", "Surya", "Budi", "Danang"};
        String[] kelas = {"xr4", "xr5", "xr6", "xr7","xr10"};
        String[] nisn = {"1234", "5678", "8765", "4321"};
        String[][] kelompok = {nama, kelas, nisn};
        int b = 0;

        for (int i = 0; i < 3; i++) {
            for (int j = 0; j < 4; j++) {
                if (pilihan.equalsIgnoreCase(kelompok[i][j])) {
                    System.out.println("============= R E S U L T =============");
                    System.out.println("Nama\t: " + kelompok[0][j] + "\nKelas\t: " + kelompok[1][j] + "\nNISN\t: " + kelompok[2][j]);
                    b = 1;
                }

            }
        }

        if (b == 0) {
            System.out.println("!==================================================================!");
            System.out.println("Data Yang Anda Masukkan Tidak Ada Di Dalam Database\nMohon Memasukkan Data Yang Benar !!");
            System.out.println("====================================================================");
            gabunganMethod();
        }

    }

    public static void main(String[] args) {
        homeMethod();
    }
}
