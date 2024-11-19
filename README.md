# Cin-Zodyagi-Burc-Hesaplama
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        //Kullanıcıdan doğum yılı al
        System.out.print("Doğum yılınızı giriniz: ");
        int dogumYili = scanner.nextInt();

        //Çin zodyağı burcunu hesapla
        int zodyak = dogumYili % 12;
        String burc = "";

        //burçları belirleme
        switch (zodyak) {
            case 0:
                burc = "Maymun";
                break;
            case 1:
                burc = "Horoz";
                break;
            case 2:
                burc = "Köpek";
                break;
            case 3:
                burc = "Domuz";
                break;
            case 4:
                burc = "Fare";
                break;
            case 5:
                burc = "Öküz";
                break;
            case 6:
                burc = "Kaplan";
                break;
            case 7:
                burc = "Tavşan";
                break;
            case 8:
                burc = "Ejderha";
                break;
            case 9:
                burc = "Yılan";
                break;
            case 10:
                burc = "At";
                break;
            case 11:
                burc = "Koyun";
                break;
        }

        // Sonucu yazdır
        System.out.println("Çin zodyağı Burcunuz: " + burc);
    }

}
