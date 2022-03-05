[p.11] Light it up
================
C언어의 기본 자료형을 구분하는 기준은 `메모리 용량`과 `자료형`입니다.

------------
```C
#include <studio.h>


int main()
{

  char c; int t; long l; float f; double d;

  printf("%d %d %d %d\n", sizeof(c), sizeof(i), sizeof(f), sizeof(d));
  printf("%d %d %d\n", sizeof(char), sizeof(int), sizeof(long));
  printf("%d %d\n", sizeof(float), sizeof(double));
  printf("%d %d\n", sizeof(153), sizeof(5.2));
  return 0;
}
```
------------

