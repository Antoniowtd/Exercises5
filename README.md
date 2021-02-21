# Exercises 5
### Exercises 5.1
#include <stdio.h>
char  line[100];   
float c;   

int main()
{
    printf("Enter centigrade: ");
    fgets(line, sizeof(line), stdin);
    sscanf(line, "%f", &c);

    printf("In Farenheit is %.2f", 1.8*c + 32);
    return (0);
}
### Exercises 5.2
#include <stdio.h>
char  line[100];   
float r;   

int main()
{
    printf("Enter radius: ");
    fgets(line, sizeof(line), stdin);
    sscanf(line, "%f", &r);

    printf("The volume of the sphere is %.2f", r*r*r*4.18879);
    return (0);
}
### Exercises 5.3
#include <stdio.h>
char  line[100];   
int   width;   
int   height;   
int main()
{
    printf("Enter width: ");
    fgets(line, sizeof(line), stdin);
    sscanf(line, "%d", &width);
    printf("Enter height: ");
    fgets(line, sizeof(line), stdin);
    sscanf(line, "%d", &height);
    
    printf("Perimeter is %d", height*2+ width*2);
    return (0);
}
### Exercises 5.4
#include <stdio.h>
char  line[100];   
float kh;   

int main()
{
    printf("Enter kilometer per hour: ");
    fgets(line, sizeof(line), stdin);
    sscanf(line, "%f", &kh);

    printf("In miler per hour is %.2f", 0.62*kh);
    return (0);
}
### Exercises 5.5
#include <stdio.h>
char  line[100];   
int   hours;   
int   minutes;   
int main()
{
    printf("Enter hours: ");
    fgets(line, sizeof(line), stdin);
    sscanf(line, "%d", &hours);
    printf("Enter minutes: ");
    fgets(line, sizeof(line), stdin);
    sscanf(line, "%d", &minutes);
    printf("The time in minutes is %d", hours*60 + minutes);
    return (0);
}
### Exercises 5.6
#include <stdio.h>
char  line[100];      
int   minutes;   
int main()
{
    printf("Enter minutes: ");
    fgets(line, sizeof(line), stdin);
    sscanf(line, "%d", &minutes);
    printf("The time %d hour/s", minutes/60);
    printf(" and ");
    printf("%d minutes", minutes%60);
    return (0);
}
