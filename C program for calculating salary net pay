#include <stdio.h>

int main() {
    float hours_worked, hourly_wage, grosspay, tax, net_pay;
    
    printf("Enter the number of hours worked ( in aweek): ");
    scanf("%f", &hours_worked);
    printf("Enter your hourly wage: ");
    scanf("%f", &hourly_wage);
    
    if (hours_worked <= 40) {
        grosspay = hours_worked * hourly_wage;
    } else {
        float regular_pay = 40 * hourly_wage;
        float overtime_hours = hours_worked - 40;
        float overtime_pay = overtime_hours * (hourly_wage * 1.5);
        grosspay = regular_pay + overtime_pay;
    }
    if (grosspay <= 600) {
        tax = grosspay * 0.15;
    } else {
        tax = (600 * 0.15) + ((grosspay - 600) * 0.20);
    }

    net_pay = grosspay - tax;

    printf("Gross Pay: $%.2f\n", grosspay);
    printf("Taxes: $%.2f\n", tax);
    printf("Net Pay: $%.2f\n", net_pay);

    return 0;
}
