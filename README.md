# Not-Ortalamas-Hesaplayan-Program
 www.patika.dev 
import java.util.Scanner;
public class main {
    public static void main(String[] args) {
       // değişkenleri oluştur
        int mat, fizik, kimya, tukce, tarih, muzük;

        // Scanner sınıfımızı tamamladık
        Scanner imp = new Scanner(System.in);

        System.out.print("Matematik NOTUNUZ: ");
        mat = imp.nextInt();

        System.out.print("Kimya Notunuz");
        kimya = imp.nextInt();

        System.out.print("Tarih Notunnuz");
        tarih = imp.nextInt();

        int toplam = (mat+kimya+tarih );
        double sonuc = toplam/ 3;
        System.out.println("Ortalamanız : " + sonuc);


    }

Matematik NOTUNUZ: 40
Kimya Notunuz=50
Tarih Notunnuz=80
Ortalamanız : 56.0

Process finished with exit code 0


