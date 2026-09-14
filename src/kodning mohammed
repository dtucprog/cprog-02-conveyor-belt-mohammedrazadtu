#include <stdio.h>

int main() {
    int motorCount;
    int totalPackageWeight;
    int MOTOR_CAPACITY = 12;
    int totalCapacity;

    printf("How many motors are carrying the packages?\n");
    scanf("%d", &motorCount);

    printf("How many kg of packages do we expect?\n");
    scanf("%d", &totalPackageWeight);

    totalCapacity = motorCount * MOTOR_CAPACITY;

    if (totalPackageWeight <= totalCapacity) {
        printf("Yes! The conveyor belt can carry the packages.\n");
    } else {
        printf("No. The conveyor belt cannot carry the packages.\n");
    }

    return 0;
}
