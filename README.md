# JAVA Ortalama Çözümü


import java.util.Scanner;

public class ortalama {
    public ortalama() {
    }

    public static void main(String[] args) {
        Scanner inp = new Scanner(System.in);
        System.out.print("Matematik puani: ");
        double mat = inp.nextDouble();
        System.out.println(mat);
        System.out.print("Fizik puani: ");
        double fizik = inp.nextDouble();
        System.out.println(fizik);
        System.out.print("Kimya puani: ");
        double kimya = inp.nextDouble();
        System.out.println(kimya);
        System.out.print("Turkce puani: ");
        double turkce = inp.nextDouble();
        System.out.println(turkce);
        System.out.print("Tarih puani: ");
        double tarih = inp.nextDouble();
        System.out.println(tarih);
        System.out.print("Muzik puani: ");
        double muzik = inp.nextDouble();
        System.out.println(muzik);
        double toplam = mat + fizik + kimya + turkce + tarih + muzik;
        double ortalama = toplam / 6.0;
        System.out.println("Not ortalamasi: " + ortalama);
        boolean SinifiGecti = ortalama >= 60.0;
        String str = SinifiGecti ? "Sinifi gecti" : "Sınıfta kaldı";
        System.out.println(str);
    }
}
