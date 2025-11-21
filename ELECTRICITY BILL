// Aim: To calculate electricity bill using else if ladder

#include <stdio.h>

int main()
{
    int units;
    float bill;

    printf("Enter total units consumed: ");
    scanf("%d", &units);

    if (units <= 50)
        bill = units * 3.0;                      // Rs. 3 per unit for 0-50 units
    else if (units <= 150)
        bill = 50 * 3.0 + (units - 50) * 4.0;    // Rs. 4 per unit for next 100 units
    else if (units <= 250)
        bill = 50 * 3.0 + 100 * 4.0 + (units - 150) * 5.0; // Rs. 5 per unit for next 100 units
    else
        bill = 50 * 3.0 + 100 * 4.0 + 100 * 5.0 + (units - 250) * 6.0; // Rs. 6 per unit for units above 250

    printf("Total electricity bill = Rs. %.2f
", bill);

    return 0;
}
