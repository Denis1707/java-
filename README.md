import java.util.Scanner;

// Press Shift twice to open the Search Everywhere dialog and type `show whitespaces`,
// then press Enter. You can now see whitespace characters in your code.
public class Main {
    public static void main(String[] args) {
        // Press Alt+Enter with your caret at the highlighted text to see how
        // IntelliJ IDEA suggests fixing it.

        // Press Shift+F10 or click the green arrow button in the gutter to run the code.


        Scanner in = new Scanner(System.in);
       int sum ;
      int n;
      int result;
        int n1;
        int n2;
        int n3;
        int n4;
         n = in.nextInt();



      result=0;

      sum= result + n % 10;


      n2 = n/10;

n1= n2 %10;

n4=n2/10;
       n3= n4%10;



        System.out.print(n1+n3+sum);
        in.close();















        }





    }
