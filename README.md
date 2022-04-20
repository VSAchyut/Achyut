# Achyut
#include <stdio.h>
int main() {
    int amtgiven,billamt,quotient,remainder;
    scanf("%d%d", &amtgiven,&billamt);
    quotient=amtgiven/billamt;
    remainder=amtgiven%billamt;
    printf("Quotient:%d", quotient);
    printf("\nRemainder:%d", remainder);     
    return 0;
}
