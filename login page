import java.util.Scanner;

public class prct_basics {
    public static void main(String[] args) {
        Scanner sc=new Scanner(System.in);
        String correctusername="admin";
        String correctpassword="123456";
        int attempts=0;
        String password;String username;
        while(attempts<3){
            System.out.print("ENTER USERNAME ");
            username=sc.nextLine();
            System.out.print("ENTER PASSSWORD: ");
            password=sc.nextLine();
            if(username.equals(correctusername) && password.equals(correctpassword)) {
                System.out.println("login successfull");
                return; //exit program
            }
            else{
                attempts++;
                System.out.println("invalid crediantials  attempts left--> "+ (3-attempts));
            }

        }
        System.out.println("account hacked or block");

    }
}
