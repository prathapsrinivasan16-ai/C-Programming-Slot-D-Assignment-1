#include <stdio.h>

int main() {
    int units;
    float bill;
    scanf("%d", &units);

    if (units <= 200)
        bill = units * 0.5f;
    else if (units <= 400)
        bill = units * 0.65f + 100;
    else if (units <= 600)
        bill = units * 0.80f + 200;
    else
        bill = units * 1.25f + 425;

    printf("Rs.%g\n", bill);
    return 0;
}
