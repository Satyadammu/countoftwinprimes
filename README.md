# countoftwinprimes
import java.util.*;

public class countoftwinprimes


 {

   static boolean prime(int n)

   {

      int count=0;

      for(int i=1;i<=n;i++)

      {

        if(n%i==0)

        count++;

      }

      if(count==2)

      return true;

      else

      return false;

   }

 public static void main (String args[])

 {  

     int count1=0;

    Scanner sc=new Scanner(System.in);

    System.out.print("Enter n1:");

    int n1=sc.nextInt();

    System.out.print("Enter n2:");

    int n2=sc.nextInt();

    for(int i=n1;i<=n2;i++)

    {

     if(prime(i)&&prime(i+2)==true)

       count1++;

    }

    System.out.print(count1);

 }

    }
    
