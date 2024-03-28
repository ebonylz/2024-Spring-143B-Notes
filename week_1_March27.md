

# coding demo


## How to store code in markdown file

'''java
public class HelloWorld {
    public static void main(String[] args) {
        float initialValue = 1000;
        float interestRate = 10;
        int numOfYears = 18;
        float monthlyDeposit = 2000;

        float total = initialValue;

        for (int i = 0; i < numOfYears; i++) {
            total += (total * (interestRate/100)) + (monthlyDeposit * 12);
        }

        System.out.printf("The total after %d years is %.2f", numOfYears, total);
    }

'''
