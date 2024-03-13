# DNA-PATTERN
I have completed DNA design pattern program in java and I have understood how to do pattern programs in java as well as c programming languages.
import java.util.*;

public class Main {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        int x = sc.nextInt();
        for (int i = 0; i < x; i++) {
            for (int j = 0; j < x; j++) {
                if (i == j || i + j == x - 1) {
                    System.out.print("*");
                } else {
                    System.out.print(" ");
                }
            }
            System.out.println();
        }
        for (int i = 0; i < x; i++) {
            for (int j = 0; j < x; j++) {
                if (i == j || i + j == x - 1) {
                    System.out.print("*");
                } else {
                    System.out.print(" ");
                }
            }
            System.out.println();
        }
    }
}


