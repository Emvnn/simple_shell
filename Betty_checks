#include <stdio.h>

#define MAX_SIZE 100

typedef struct {
    int x;
    int y;
} Point;

int add(int a, int b)
{
    return a + b;
}

int main(void)
{
    int i;
    Point p;

    p.x = 5;
    p.y = 10;

    printf("Sum: %d\n", add(p.x, p.y));

    for (i = 0; i < MAX_SIZE; i++) {
        if (i % 2 == 0) {
            printf("%d is even\n", i);
        } else {
            printf("%d is odd\n", i);
        }
    }

    return 0;
}

