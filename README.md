# TP1
import java.util.Scanner;

 public class Volumen{
 public void main(String [] args) {

System.out.println("Écrire les valeurs du pavé: ");

 Float a,b,c,r =0;

 Scanner scan = new Scanner(System.in);
do{
a= scan.nextFloat();
b= scan.nextFloat();
c= scan.nextFloat();

if(a<=0 || b<=0 || c<=0)
{System.out.println(" Les valeurs ne sont pas correct. Retaper les valeurs: ");}

}while (a<=0 || b<=0 || c<=0)


 // System.out.println permet d'AFFICHER des variables a l'ecran
 System.out.println(" J'ai lu :" + a + " , " + b +" et" + c + " ! ");

r=a*b*c;

System.out.println(" Le volume du pavé est " + r + " ! ");


 }
}
