# home-work
#include <stdio.h>

int main(void) {
    int a, b;

    // TODO 1: Prompt and read two integers (use scanf)
    printf("Enter two integers: ");
    scanf("%d %d", &a, &b);

    // TODO 2: Print the sum of a and b
    printf("Sum: %d\n", a + b);

    // TODO 3: Print the difference (a - b)
    printf("Difference: %d\n", a - b);

    // TODO 4: Print the product (a * b)
    printf("Product: %d\n", a * b);

    // TODO 5: Print quotient and remainder only if b is not zero
    if (b != 0) {
        printf("Quotient: %d\n", a / b);
        printf("Remainder: %d\n", a % b);
    } else {
        printf("Quotient: undefined (division by zero)\n");
        printf("Remainder: undefined (division by zero)\n");
    }

    return 0;
}
