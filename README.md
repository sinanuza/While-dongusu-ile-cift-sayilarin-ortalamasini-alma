# While-dongusu.java
www.patika.dev odev



        import java.nio.file.StandardOpenOption;
        import java.util.Scanner;

        public class for_dongusu {
        public static void main(String[] args) {
        int k, i,ortalama=0;
        int toplam = 0;
        System.out.println("Lufen bir sayi giriniz:");
        Scanner input = new Scanner(System.in);
        k = input.nextInt();
        i = 0;
        int j=1;
        while (i <= k) {
            i++;
            if ((i % 3 == 0) && (i % 4 == 0)) {
                    toplam += i;
                    j++;
            }
            ortalama=toplam/j;
        }System.out.println("sayilarin toplami:" + toplam);
        System.out.println("sayilarin ortalamasi:" + ortalama);
    }
}
