# factors-of-number
import java.util.*;

 // Compiler version JDK 11.0.2

 class Dcoder
 {
   public static void main(String args[])
   { 
     int num,i;
     Scanner in=new Scanner(System.in);
    System.out.println("enter a number");
    num=in.nextInt();
    System.out.println("factors are");
    for( i=1;i<=num;i++)
    {
      if(num%i==0)
      {
        System.out.println(" " +i);
      }
    }
   }
 }
