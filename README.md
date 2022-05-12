# Java-If-Else-By-DexRapsing

import java.util.*;
class Main {
  public static void main(String[] args) {
      int age;
 Scanner in = new Scanner(System.in);
 System.out.print("Please enter your age:");
 age = in.nextInt();
    
    if (age <= 0) {
    System.out.println("Invalid Input");
    }
    else if (age >= 1 && age <=5) {
      System.out.println("May gatas kapa sa labi");
    }
    else if (age >=6 && age <=12) {
      System.out.println("uhugin kapa");
    }
    else if (age >=13 && age <=19) {
      System.out.println("pwede kana mag jowa");
    }
    else if (age >=20 && age <=59) {
      System.out.println("pwede kana mag asawa");
    } else if (age >=60 && age <=100) {
      System.out.println("lolo kana");
    }
    else {
      System.out.println("isa kang alamat");
    }
    
  }
}
