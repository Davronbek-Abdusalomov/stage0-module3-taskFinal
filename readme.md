## FINAL MODULE TASK
#### 1) Print false.
You will be given 2 variables and your task will be to print false using those vars:


        public class PrintingFalse {
            public static void main(String[] args) {
                int first = 9;
                int second = -17;
                System.out.println(first<second);
            }
        }

#### 2) Division by zero.
In the given code snippet you should pick correct primitive type to allow division by zero. Which means that the program must be able to perform division without any exception, etc. In order to do this you will have to search for additional info yourself.


        public class DivisionByZero {
            public static void main(String[] args) {
                float number = 10;
                System.out.println(number/0);
            }
        }

Instead of "_" sign set correct var type.

#### 3) Positive numbers detector.
Implement program that will print if number is positive true, otherwise false
(no if or ternary). Code snippet:


    public class NumbersPrinter {
        public void printIsPositive(int number) {
     if (number>0){
            System.out.println(true);
        }
        else
            System.out.println(false);
        }
    }

Where number - variable that should be used within the program.

#### 4) Numbers reverter.
Revert 3-digit number that will be passed (e.g.: given -> 489, expected -> 984) and print it. Code snippet:


        public class NumberReverter {
            public void revert(int number) {
              int a=number%10;
        int b=(number%100-a)/10;
        int c=(number-b*10-a)/100;

        System.out.println(a+""+b+""+c);
            }
        }
Where number - variable that should be used within the program.

#### 5) Digits sum calculator.
You will be given a four-digit number your task will be to find the sum of all digits in the
given number. Code snippet:


        public class DigitsSumCalculator {
            public void calculateSum(int number) {
             int i=4;
        while(i>0){
            int remainder = number%10;
            remainder+=remainder;
            number=number/10;
            i++;
            System.out.println(remainder);
            }
        }

Where number - variable that should be used within the program.


#### 6) Temperature converter.
You will be given temperature in celsius and your task will be to print this temperature in
fahrenheit (formula will be required). Code snippet:


        public class TemperatureConverter {
            public void toFahrenheit(int temperatureCelsius){
            float fahrenheit = (float) (temperatureCelsius*1.8+32);
        System.out.println(fahrenheit);
            }
        }

Where temperatureCelsius - variable that should be used within the program.
