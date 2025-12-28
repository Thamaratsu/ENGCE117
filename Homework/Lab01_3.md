## CODE
```c++
#include <stdio.h>

int main() {
    int num1, num2, operationCode, result;
    
    
    if (scanf("%d %d %d", &num1, &num2, &operationCode) != 3) {
        return 1; 
    }

    switch (operationCode)
    {
    case 1:
        printf("%d", result = num1 + num2);
        break;
    case 2:
        printf("%d", result = num1 - num2);
        break;
    case 3:
        printf("%d", result = num1 * num2);
        break;
    case 4:
        printf("%d", result = num1 / num2);
        break;
    
    default:
        printf("Invalid Operation");
        break;
    }

    return 0;
}
```
