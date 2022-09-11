# CALKULATOR-PENJUMLAHAN-BITWISE
#JAVA
just having fun  hehe
//program penjumlahan BITWISE
//by yudonidlomf
import java.util.Scanner;

public class tes{
    public static void main(String[] args) {
        System.out.println(" ");
        System.out.println("            BITWISE         ");
        Scanner inputuser = new Scanner(System.in);
        System.out.print("masukan input = " + " ");
        int i = inputuser.nextInt();
        Scanner inputuser2 = new Scanner(System.in);
        System.out.println("masukan Input 2 = " + " ");
        int r = inputuser2.nextInt();
        System.out.println("Input = " + i);
        System.out.println("Input2 = " + r);
        String i_bits;
        String r_bits;
        int hasil;
        System.out.println("i : ");
        i_bits = String.format(
            "%8s" , Integer.toBinaryString(i)).replace(' ', '0'
            );
        System.out.printf("%s = %d",i_bits,i);
        System.out.println(" ");
        System.out.println("r : ");
        r_bits = String.format(
            "%8s" , Integer.toBinaryString(r)).replace(' ' , '0'
            );
        System.out.printf("%s = %d" , r_bits , r);
        System.out.println(" ");
        hasil = i + r;
        String h_hasil;
        h_hasil = String.format(
            "%8s" , Integer.toBinaryString(hasil)).replace(' ', '0'
            );
        System.out.println(" ");
        System.out.println(" i " + " + " + " r " + " = " + h_hasil );
        System.out.printf("%s = %d" , h_hasil , hasil);


    }
}
