import java.util.Scanner;
public class buyukKucuk {
    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);
        int a,b,c;
        System.out.println("A Sayısını Giriniz");
        a = input.nextInt();
        System.out.println("B Sayısını Giriniz");
        b = input.nextInt();
        System.out.println("C Sayısını Giriniz");
        c = input.nextInt();
        if ( (a>b) && (b>c)){
            System.out.println("1 = a>b>c");
        } else if ( (a > c) && (c>b)) {
            System.out.println("2 = a>c>b");
        } else if ((b>a)&&(a>b)) {
            System.out.println("3 = b>a>c");
        } else if ((c>a)&&(a>b)) {
            System.out.println("4 = c>a>b");
        } else if ((b>c)&&(c>b)) {
            System.out.println("5 = b>c>a");
        } else if ((c>b)&&(b>a)) {
            System.out.println("6 = c>b>a");
        } else {
            System.out.println("Geçersiz sayı girişi");
        }
    }
}

