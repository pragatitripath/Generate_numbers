# Generate_numbers

#include<stdio.h>
#include<stdlib.h>  //----for generate random number
#include<time.h>

int main(){
    int number;
    number=rand()%100+1; //----for generate random number from 1 to 100
    printf("The number is %d\n", number);
    return 0;
}
