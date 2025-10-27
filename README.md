# System-for-stimulation-of-electric-switch-
Basic c-program to see how a switch operates when it's turned on and off 
#include <stdio.h>

int main() {
    char alarmSwitch;

    printf("Turn alarm ON (O) or OFF (F): ");
    scanf(" %c", &alarmSwitch);

    if(alarmSwitch == 'O' || alarmSwitch == 'o') {
        printf("Alarm is ACTIVE\n");
        printf("Alert! Intrusion detected!\n");
    } else {
        printf("Alarm is INACTIVE. No monitoring.\n");
    }

    return 0;
}

