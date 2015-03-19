import java.util.Scanner;

public class SwitchCase2 {
	public static void main(String [] args) {
		Scanner keyboard = new Scanner(System.in);

		System.out.println("Enter your role from the list.\n");
		System.out.println("1. Administrator");
		System.out.println("2. Faculty");
		System.out.println("3. Staff");
		System.out.println("4. Student");
		System.out.println("5. Guest");
			
		String role = keyboard.next();

		switch(role) {
		case "Administrator": case "administrator":
			System.out.println("Welcome Administrator!");
			break;
		case "Faculty": case "faculty":
			System.out.println("Welcome Faculty!");
			break;
		case "Staff": case "staff":
			System.out.println("Welcome Staff!");
			break;
		case "Student": case "student":
			System.out.println("Welcome Student!");
			break;
		case "Guest": case "guest":
			System.out.println("Welcome Guest!");
			break;
		
		}
		
		
	}

}
