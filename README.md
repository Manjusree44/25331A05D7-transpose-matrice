#include<stdio.h>
int main(){

int m, n;
printf("2533a05d7\n");
printf("enter the no of rows");
scanf("%d", &m);
printf("enter the no of columns");
scanf("%d", &n);
int A[m][n], T[n][m];
printf("enter the matrice A");
for(int i = 0; i < m; i++){
 for(int j = 0; j < n; j++){
   scanf("%d", &A[i][j]);
}
}
 
for(int i = 0; i < m; i++){
  for(int j = 0; j < n; j++){
   T[j][i] = A[i][j];
}
}
printf("the transpose matrix is ");

for(int i = 0; i < n; i++){
for(int j = 0; j < m; j++){
  printf(" %d",  T[i][j]);

}
printf("\n");
}
