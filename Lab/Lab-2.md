## Lab 2 :-> WAP that reads marks in 5 subjects of a student and then test whether the sutdent is fail or pass.

```c

#include <stdio.h>
int main(void)
{
  int markOfSub_1, markOfSub_2, markOfSub_3, markOfSub_4, markOfSub_5;
  
  printf("Enter your marks in 5 different subjects [Max. Value = 100] & [Min. Value = 32]\nEx. 80 80 80 80 80\n\n");
  scanf("%d%d%d%d%d", &markOfSub_1, &markOfSub_2, &markOfSub_3, &markOfSub_4, &markOfSub_5);
  
  if(markOfSub_1 >= 32 && markOfSub_2 >= 32 && markOfSub_3 >= 32 && markOfSub_4 >= 32 && markOfSub_5)
    printf("Sorry, You failed the examination.\nBetter Luck next time");
  else
    printf("Horray!, you aced the examination");
  
  return 0;
}

```

### Output

#### Run 1
```bash
Enter your marks in 5 different subjects [Max. Value = 100] & [Min. Value = 32]
Ex. 80 80 80 80 80

23 75 76 77 78
Sorry, You failed the examination.
Better Luck next time
```
#### Run 2
```bash
Enter your marks in 5 different subjects [Max. Value = 100] & [Min. Value = 32]
Ex. 80 80 80 80 80

80 75 76 77 78
Horray!, you aced the examination
```
