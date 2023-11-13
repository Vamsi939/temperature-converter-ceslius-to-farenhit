import java.util.Scanner;

public class CelsiusToFahrenheitConverter {
    public static void main(String[] args) {
       
        Scanner scanner = new Scanner(System.in);
        System.out.print("Enter temperature in Celsius: ");
        double celsius = scanner.nextDouble();
        scanner.close();
        double fahrenheit = celsiusToFahrenheit(celsius);

        System.out.println(celsius + " Celsius is equal to " + fahrenheit + " Fahrenheit");
    }

    private static double celsiusToFahrenheit(double celsius) {
        return (celsius * 9 / 5) + 32;
    }
}