# Les2
Java Les 2

import java.util.Scanner;
public class Assignment{
  public void showAssignment(){
    System.out.println("Assignment 1: Jay you just completed your first assignment");
    System.out.println("Assignment 2: create 3 variables here, one for your name, age and one for your postal code. Print the values to the commandline!");
    String firstname = "Job";
    String lastname = "Groen";
    int age = 18;
    String postalcode = "1851 ZP";

    System.out.println(firstname);
    System.out.println(lastname);
    System.out.println(age);
    System.out.println(postalcode);



    
    System.out.println("Assignment 3: Use the Scanner datatype to allow a user to enter the values for name, age, and postal code. ");

    System.out.println("Note: Find out about datatypes at the Application Programming Interface(API) reference https://docs.oracle.com/javase/7/docs/api/allclasses-noframe.html. Select the Scanner link.");

    Scanner newscanner = new Scanner(System.in);
    System.out.println("Wat is je naam?");
    firstname = newscanner.next();
    lastname = newscanner.next();

    System.out.println("Voer leeftijd in");
    age = newscanner.nextInt();

    System.out.println("Wat is je postcode?");
    postalcode = newscanner.next();

    System.out.println("Je naam is:" + firstname + "Je bent:" + age + "Je postcode is:"+ postalcode);
  }
}
