#include <stdio.h>
int main() {
        float sqfeet,acre;
        scanf("%f",&sqfeet);
        acre=sqfeet/43560;
        printf("%0.2f sq.ft is equal to %0.2f acres",sqfeet,acre);
        return 0;
        }
