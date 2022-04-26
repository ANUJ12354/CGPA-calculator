#include<stdio.h>

int main()
{
    float a1,a2,a3,a4,a5,b1,b2,b3,b4,b5;
    float cgpa;
    printf("GRADE POINTS:\nO=10\nA=9\nB=8\nC=7\nD=6\nE=5\nF=0");
    printf("\nEnter your first credit and grade point:\n");
    scanf("%f %f",&a1,&b1);
    printf("Enter your second credit and grade point:\n");
    scanf("%f %f",&a2,&b2);
    printf("Enter your third credit and grade point:\n");
    scanf("%f %f",&a3,&b3);
    printf("Enter your fourth credit and grade point:\n");
    scanf("%f %f",&a4,&b4);
    printf("Enter your fifth credit and grade point:\n");
    scanf("%f %f",&a5,&b5);
    cgpa=((a1*b1)+(a2*b2)+(a3*b3)+(a4*b4)+(a5*b5))/(a1+a2+a3+a4+a5);
    if(cgpa<5){
        printf("Your CGPA is %0.2f and you are failed this semester",cgpa);
    }
    else{
        printf("Your CGPA is %0.2f and you are passed\nCONGRATS! PARTY HARD",cgpa);
    }
    return 0;
}
