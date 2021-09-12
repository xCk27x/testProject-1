# include <stdio.h>

int main (void)
{
  char userName[21];
  
  printf("Please enter your name, new member. ");
  scanf_s("%s", userName);
  printf("Hello, %s. It's nice to meet you.\n", userName);

  return 0;
}
