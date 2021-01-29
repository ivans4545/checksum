import java.util.Scanner;

class checksum  
{  

  public static void main(String args[]) {
  Scanner stdin = new Scanner(System.in);
  System.out.println( " Enter 10 numbers, in the range of 2 - 255. " );
  int num1 = stdin.nextInt();
  int num2 = stdin.nextInt();
  int num3 = stdin.nextInt();
  int num4 = stdin.nextInt();
  int num5 = stdin.nextInt();
  int num6 = stdin.nextInt();
  int num7 = stdin.nextInt();
  int num8 = stdin.nextInt();
  int num9 = stdin.nextInt();
  int num10 = stdin.nextInt();

    final int max_int = 255;  // The maximum size for the input
    int count = 10;           // The number of integers to read from stdin
    int checksum = num6;
    num6 = 0;
    int sum = num1+num2+num3+num4+num5+num6+num7+num8+num9+num10;              // Note that the "sum" might exceed max_int
    int quotient = (sum / (max_int + 1));             // The result of evaluating the assignment:  quotient   = sum / (max_int + 1);
    int remainder = (sum % (max_int + 1 ));            // The result of evaluating the assignment:  remainder  = sum % (max_int + 1 );
    sum = quotient + remainder;
    int complement = max_int - sum;           // The result of evaluationg the assignment: complement = max_int - sum;
    
System.out.printf("Stored Checksum: %d, Computed Checksum: %d\n", checksum, complement);
  if (checksum != complement ) {
    System.err.printf("Error Detected!\n");  
  }
  
}
}