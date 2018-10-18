# batch11package day9;

import java.util.Scanner;

public class Cvv {
    public static void main(String[] args) {
        Scanner scan=new Scanner(System.in);
        String cvvNumber=scan.next();
        Cvv ccv=new Cvv();

    }

    private void numberProcessing(String cvvNumber) throws InvalidCvvNumber {
        if ((cvvNumber.length()==3)){
            System.out.println("Valid CVV Number");
            }else {
            throw new InvalidCvvNumber();

        }



    }
}
