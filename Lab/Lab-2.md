## Lab 2 :-> WAP that reads marks in 5 subjects of a student and then test whether the sutdent is fail or pass.

```c

#include <stdio.h>
int main(void)
{
  int markOfSub_1, markOfSub_2, markOfSub_3, markOfSub_4, markOfSub_5;
  
  printf("Enter your marks in 5 different subjects [F.M. = 100] & [P.M = 32]\nEx. 80 80 80 80 80");
  scanf("%d%d%d%d%d", &markOfSub_1, &markOfSub_2, &markOfSub_3, &markOfSub_4, &markOfSub_5);
  
  if(markOfSub_1 >= 32 && markOfSub_2 >= 32 && markOfSub_3 >= 32 && markOfSub_4 >= 32 && markOfSub_5)
    printf("Sorry, You failed the examination.\nBetter Luck next time");
  else
    printf("Horray!, you aced the examination");
  
  return 0;
}

```
