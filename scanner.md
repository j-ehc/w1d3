import java.util.Scanner;
import java.time.LocalDate;


class Main {
  public static void main(String[] args) {

// This is where I define

  Scanner N = new Scanner(System.in);
  LocalDate RN = LocalDate.now();
  

// This is where I prompt for inputs

    System.out.println("What's your name? ");
      String name = N.nextLine();

    System.out.println("What's your email? ");
      String email = N.nextLine();

    System.out.println("When's your birthday? (January 1st 1970) ");
      String bday = N.nextLine();

// This is where I return the output

   System.out.println("name: " + name);
   System.out.println("email: " + email);
   System.out.println("B-day: " + bday);
   System.out.println ("today's date: " + RN);


  }
}
