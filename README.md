# yanlis-odev-1
eğitmenimin ders verirken anlattığı konuyu ödev zannedip yazdım, bitirip kontrol etmek için girdiğimde yanlıs yaptığımı fark ettim. (pratik pratiktir!!)



import java.util.Scanner;

public class Main {

    public static void main(String[] args) {
        int r = 3;
        double pi=3.14;
       Scanner girdi = new Scanner(System.in);
         System.out.println("Dairenin yarı çapını giriniz:");

         double alan = pi * r * r;
         double cevre = 2 * pi * r;
        girdi.nextInt();
         System.out.println("dairenin alanını : "+ alan);
System.out.print("dairenin cevresi : "+ cevre);
