#include <stdio.h> 
#include <conio.h> 
#define DAU_CHAM '.' 
void main(void) 
{ 
 char c; 
 int idem = 0; 
 for(; ;) 
 { 
 c = getchar(); 
 if (c == DAU_CHAM) //nhap vao dau cham 
 break; //thoat vong lap 
 idem++; 
 } 
 printf("So ki tu: %d.\n", idem); 
 getch(); 
}
