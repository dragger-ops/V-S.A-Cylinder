#include <stdio.h>

// define PI
#define PI 3.14159

int main() {
    double r, h;    
     // Where r = radius, h = height
    double volume;
    double surfaceArea;

    // Ask user to enter radius
    printf("Enter radius of cylinder: ");
    scanf("%lf", &r);

    // Ask user to enter height
    printf("Enter height of cylinder: ");
    scanf("%lf", &h);

    // Calculate volume = PI * r^2 * h
    volume = PI * r * r * h;

    // Calculate total surface area
    // Formula: Surface Area = 2 * PI * r^2 + 2 * PI* r * h
    surfaceArea = 2 * PI * r * r + 2 * PI * r * h;

    // Print the results
    printf("Volume of cylinder = %.2lf\n", volume);
    printf("Total Surface Area of cylinder = %.2lf\n", surfaceArea);

    return 0;
}
    
