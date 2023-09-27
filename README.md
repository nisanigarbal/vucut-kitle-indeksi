# vucut-kitle-indeksi
import java.util.Scanner;
public class vki {
    public static void main (String[]args){
        double weight, height,index;

        Scanner inp = new Scanner (System.in);

        System.out.print("Enter your weight:");
        weight= inp.nextDouble();

        System.out.print("Enter your height:");
        height=inp.nextDouble();

        index= weight / (height*height);
        System.out.println("your body mass index is: "+ index);
    }
}
