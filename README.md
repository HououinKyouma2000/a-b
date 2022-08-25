import java.util.Scanner;

public class MainAkbar {
    static int a = 0;
    static int b = 0;
    static Scanner sc = new Scanner(System.in);

    public static void main(String[] args) {
        Scanner in = new Scanner(System.in);
        System.out.println(" Number: ");
        int n = in .nextInt();
        for (int i = 1; i <= 10; i++) {
            System.out.println(n + "x" + i + " =" + (n * i));
        }

        Math.random();


    }

    public static void sum() {
        a = a + sc.nextInt();
        b = b + sc.nextInt();
    }
    }
