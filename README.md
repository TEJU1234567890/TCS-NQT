// Online C compiler to run C program online
#include <stdio.h>
int sum_of_even_number(int number[],int size){
    int total =0;
    for(int i=0;i<size;i++){
        if(number[i]%2==0){
            total+=number[i];
        }
    }
    return total;
}

int main() {
    int number[]={1,2,3,4,5,6};
    int size=sizeof(number)/sizeof(number[0]);
    int result=sum_of_even_number(number,size);
    printf("sum of even number:%d\n",result);
    

    return 0;
}
