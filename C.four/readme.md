# 4주차 C언어 실습
  - 4주차 복습
  -- c언어 연산자
  - 4주차 실습

```

#include <stdio.h>

int main()
{
  double x, y, result;
printf("두개의 실수를 입력하시오: ");
scanf("%lf %lf", &x, &y);
result = x + y; 
printf("%lf + %lf = %lf\n", x, y, result);
result = x - y;
printf("%lf - %lf = %lf\n", x, y, result);
result = x % y; 
printf("%lf % %lf = %lf\n", x, y, result);
result = x / y;
printf("%lf / %lf = %lf\n", x, y, result);
}

```
