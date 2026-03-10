# Mahbub
Beecrowd beginner problem 1009 solution with java code 
<br>Aurthor-Mahbubur Rahman
<br>
import java.util.Scanner; //<br>
import java.text.DecimalFormat; //<br>
public class praticee {
    public static void main(String[] args) {
        
    Scanner s = new Scanner(System.in);

    System.out.print("Enter your name: ");
    String name = s.nextLine();
    
    System.out.print("Enter your salary: ");
    double salary = s.nextDouble();
    
    System.out.print("Enter your total sold: ");
    double sold = s.nextDouble();

    double total = salary + (sold * 15/100);

    DecimalFormat df = new DecimalFormat("#.00");
    
    System.out.println("Name: " + name);
    System.out.println("Total salary = $ " + df.format(total));

    s.close();
}
}
