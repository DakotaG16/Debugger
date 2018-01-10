# Debugger
import java.util.Scanner;

public class Program {

        public static void main(String[] args) {

        	Scanner sc = new Scanner(System.in);

                
                int seconds;

                System.out.println("How many seconds until liftoff?");
                
                
               
                seconds = sc.nextInt();

                

                while(seconds >= 1) {
                	System.out.println(seconds + "!");
                	seconds--;
                }if(seconds  == 1);
                   System.out.println("Blastoff!");
                
                }

        }
