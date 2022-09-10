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
C:\Program Files\Java\jdk-18.0.2.1\bin\java.exe" "-javaagent:C:\Program Files\JetBrains\IntelliJ IDEA Community Edition 2022.2.1\lib\idea_rt.jar=57716:C:\Program Files\JetBrains\IntelliJ IDEA Community Edition 2022.2.1\bin" -Dfile.encoding=UTF-8 -Dsun.stdout.encoding=UTF-8 -Dsun.stderr.encoding=UTF-8 -classpath C:\Users\ÜMİT\IdeaProjects\java101\out\production\java101 main
Matematik NOTUNUZ: 40
Kimya Notunuz=50
Tarih Notunnuz=80
Ortalamanız : 56.0

Process finished with exit code 0


