# c-with-using-length-function
#include <stdio.h>
#include<string.h>
#define MAX_SIZE 100
int main()
{
  char text[MAX_SIZE];
  int length;
  printf("enter any string: ");
  scanf("%s",text);
  length = strlen(text);
  printf("length of '%s' = %d", text, length);
  return 0;
}
