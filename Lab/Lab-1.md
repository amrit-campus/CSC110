## Lab-1 :-> WAP that reads a number and tests whether it is multiple of 7 or not.

```c

#include <stdio.h>

int main(void)
{
  int num;
  
  printf("Enter a number, ");
  scanf("%d",&num);
  
  if(num%7 == 0)
    printf("The num, %d is divisible by 7.",num);
  else
    printf("The num, %d is not divisible by 7.",num);
  
  return 0;
}

```

### Output
|----|----|
Run 1|Run2|
