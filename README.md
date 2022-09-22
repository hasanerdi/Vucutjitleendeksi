# Vucutjitleendeksi
import java.util.Scanner;

public class vucudkitleendeksi {
    public static void main(String[] args) {

        double kilo, boy ;

        Scanner girilenler = new Scanner(System.in);

        System.out.println("kilo" );
        kilo = girilenler.nextDouble();

        System.out.println(" boy ");
        boy = girilenler.nextDouble();


        double vucutkitleendeksi = (kilo / (boy*boy));
        System.out.println(" Vücut kitle endeksiniz = " + vucutkitleendeksi);
