# n-numbers

1.Write a function that takes a positive integer n and returns the sum of all integers from 1 to n.
A.public class SumNatural {

    public static void main(String[] args) {

        int num = 100, sum = 0;

        for(int i = 1; i <= num; ++i)
        {
            // sum = sum + i;
            sum += i;
        }

        System.out.println("Sum = " + sum);
    }
}
