## CODE
```c++
#include <stdio.h>

int* GetSet(int *num);

int main() {
    int *data, num;
    data = GetSet(&num);
    return 0;
}

int* GetSet(int *num) {
    int row;
    int col;
    printf("Enter Array :\n");
    scanf("%d", &row);
    scanf("%d", &col);
    num = new int[ row * col ];
    for(int i = 0; i< row; i++) {
        for(int j = 0; j < col; j++) {
            printf("a[%d][%d] = ", i, j);
            scanf("%d", &num[ i * col + j ]);
        }
    }
    return num;
}

```
