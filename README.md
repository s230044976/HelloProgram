
import java.util.Scanner;
public class HelloProgram
{
    public static void main (String[] args){
        //Ask the user to enter his/her full name
        System.out.println(" Kindly Enter your full name");
        //Read the input and store it in the varible(name)
        Scanner in = new Scanner(System.in);
        
        String name = in.nextLine();//read every click in the keyboard by 
        //the user in the varible
        //print a welcoming message with the user name
        System.out.print(" Welcome and Good morning" +  " " + name);
        
    }
}
