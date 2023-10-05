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



2 задача



import java.util.Scanner;


public class Main {
    public static void main(String[] args) {
        


        Scanner in = new Scanner(System.in);
      int num  ;
          num = in.nextInt();
      num +=2;
 num -= num %2;

        System.out.print(num);
















        }





    }

еще задача




import java.util.Scanner;


public class Main {
    public static void main(String[] args) {


        Scanner in = new Scanner(System.in);


         int a = in.nextInt();
        int b= in.nextInt();
         int n = in.nextInt();

        int p;

        p=  n* (100*  a+b);

        System.out.print (  "" + p/100 + " " + p%100 );



        }





    }



и еще одна


import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner in = new Scanner(System.in);

        int n = in.nextInt();
        int h, m1, m2, s1, s2;

        h = (n / 3600) % 24;
        n = n % 3600;
        m1 = n / 60 / 10;
        m2 = n / 60 % 10;
        n = n % 60;

        s1=n/10;
        s2=n%10;
        
        System.out.println(h+":"+m1+""+m2+":"+s1+""+s2);
    }
}
и еще



import java.util.Scanner;


public class Main {
    public static void main(String[] args) {


        Scanner in = new Scanner(System.in);


        int n = in.nextInt();

        int k=n/10;
int p= k%10;




        System.out.print (p);



        }





    }
еще


import java.util.Scanner;


public class Main {
    public static void main(String[] args) {


        Scanner in = new Scanner(System.in);


        int n = in.nextInt();

        int k=n%10;
        int p=n/10%10;
        int m=n/100;
        int l=m%10;



        System.out.print (k+l+p);



        }





    }
еще

import java.util.Scanner;


public class Main {
    public static void main(String[] args) {


        Scanner in = new Scanner(System.in);



int a=in.nextInt();
      int b=in.nextInt();
int d=a*a+b*b;

        System.out.print (d);



        }





    }



еще...

    import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner in = new Scanner(System.in);

        int A = in.nextInt();
        int i= in.nextInt();
        System.out.println(i != 0 ? A & -(1 << i) : A);
    }
}




и еще




import java.util.Scanner;
 
public class Main
{
    public static int pow2(int n)
    {
        return 1<<n;
    }
    
    public static void main(String[] args) {
        Scanner inp = new Scanner(System.in);
        int n = inp.nextInt();
        System.out.println(pow2(n));
    }
}


еще

import java.util.*;



public class Main

{

    public static void main(String[] args)

    {

        Scanner con = new Scanner(System.in);

        int a = con.nextInt(), k = con.nextInt();

        int res = a | (1 << k);

        System.out.println(res);

        con.close();

    }

}
еще


import java.util.*;



public class Main

{

    public static void main(String[] args)

    {

        Scanner con = new Scanner(System.in);

        int A= con.nextInt();
        int i= con.nextInt();




        System.out.println(A & ((1 << i) - 1));


        con.close();

    }

}

