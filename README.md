#include <stdio.h>

int main() {

    int n, k, i, even_sum = 0, odd_sum = 0;

    

    printf("Enter the value of n: ");

    scanf("%d", &n);

    printf("Enter the value of k: ");

    scanf("%d", &k);

    

    for (i = 1; i <= n; i++) {

        if (i % k == 0) {

            printf("%d is divisible by %d\n", i, k);

            if (i % 2 == 0) {

                even_sum += i;

            } else {

                odd_sum += i;

            }

        }

    }

    

    printf("Sum of even numbers: %d\n", even_sum);

    printf("Sum of odd numbers: %d\n", odd_sum);

}
