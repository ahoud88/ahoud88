
1. import java.util.Scanner;
2. public class Fourth Pattern
3. {
4. public static void main(String[] args)
5. {
6. Scanner scanner = new Scanner(System.in);
7. System.out.println("Please provide number
A
of rows to print... ");
8. int myrows = scanner.nextInt();
9. System.out.println("\nThe star pattern is...
");
10. for (int m 1; m <= myrows; m++)
11. {
12. for (int n myrows; n m; n--)
13. {
14. System.out.print(" ");
15.}
16. for (int p=1; p<=(m*2) -1; p++)
17.{
18. System.out.print("*");
19.}
20. System.out.println();
21.}
22.)
23.}
