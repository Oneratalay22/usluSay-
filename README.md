import java.util.Scanner;

public class Main {

    static int uslu(int a, int b) {
        int result = 1;
        for (int i = 1; i <= b; i++) {
            result *= a;
        }
        return result;
    }

    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        System.out.println("Sayı Giriniz:");
        int a = sc.nextInt();
        System.out.println("Üs Giriniz:");
        int b = sc.nextInt();
        System.out.println("Üslü Sayı:" + uslu(a, b));
    }
}
