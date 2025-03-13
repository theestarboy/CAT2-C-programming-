#include <stdio.h>

int main() {
    int scores[4][2] = {
        {65, 92},
        {84, 72},
        {35, 70},
        {59, 67}
    };

    int matrix_1[2][2];
    int matrix_2[2][2];
 for(int m = 0; m< 2; m++) {
        for(int n = 0; n< 2; n++) {
            matrix_1[m][n] = scores[m][n];
        }
    }
 for(int m = 2; m < 4; m++) {
        for(int n = 0; n < 2; n++) {
            matrix_2[m-2][n] = scores[m][n];
        }
    }
 printf("Matrix 1:\n");
    for(int m = 0; m< 2; m++) {
        for(int n= 0; n < 2; n++) {
            printf("%d ", matrix_1[m][n]);
        }
        printf("\n");
    }
 printf("Matrix 2:\n");
    for(int m = 0; m< 2; m++) {
        for(int n= 0; n < 2; n++) {
            printf("%d ", matrix_2[m][n]);
        }
        printf("\n");
    }
  return 0;
}
