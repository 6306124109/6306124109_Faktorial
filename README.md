6306124109_Faktorial
====================
import java.util.Scanner;

public class Faktorial_109 {

    public static void main(String[] args) {

        int n, c, fact = 1;

        System.out.println("Masukkan angka: ");
        Scanner in = new Scanner(System.in);

        n = in.nextInt();

        if (n < 0) {
            System.out.println("Angka tidak boleh negatif.");
        } else {
            for (c = 1; c <= n; c++) {
                fact = fact * c;
            }

            System.out.println("Faktorial dari " + n + " adalah = " + fact);
        }
    }
}
