# Sum-of-Array
package Array;

public class SumOfArray {

        public static void main(String[] args) {
            int[] arr = {5, 10, 15, 20, 25};  // sample array
            int sum = 0;

            for (int i = 0; i < arr.length; i++) {
                sum += arr[i];
            }

            System.out.println("Sum of array elements: " + sum);
        }
    }
