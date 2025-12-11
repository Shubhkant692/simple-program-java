import java .util.Scanner;
public class Ncit
{
    public static void main(String a[])
    {
        Scanner sc = new Scanner(System.in);
        System.out.println("Enter name");
        String Name = sc.nextLine();

        System.out.println("Enter roll_no");
        int roll_no = sc.nextInt();
        sc.nextLine();

        System.out.println("Enter the gender(M/F)");
        char gender = sc.nextLine().charAt(0);

        System.out.println("Student name is:" + Name);
        System.out.println("Student roll_no is:" + roll_no);
        System.out.println("Gender is " + gender); 
    }
}
