# manav
import java.util.Scanner;

public class Main {
    public static void main (String []args){
        double armut= 2.14, elma= 3.67, domates =1.11, muz =0.95, patlican =5;

        Scanner manav= new Scanner(System.in);
        System.out.print("armut: ");
        armut=manav.nextDouble();


        System.out.print("elma: ");
        elma= manav.nextDouble();

        System.out.print("domates: ");
        domates= manav.nextDouble();

        System.out.print("muz: ");
        muz= manav.nextDouble();

        System.out.print("patlıcan: ");
        patlican= manav.nextDouble();

        double toplam= (armut+elma+domates+muz+patlican);

        toplam tutar= double toplam;* (armut,elma,domates,muz,patlican);
        System.out.println( "toplam tutar: ");
    }

}
