# grade-calculater
answer
#include <stdio.h>

int main() {
  int score;
  int grade;
  printf("enter your score: ");
  scanf("%d",&score);
  grade=(score>=90)?'A':(score>=80)?'B':(score>=70)?'C':(score>=60)?'D':(score>=50)?'E':'f';
  printf("your grade is  %c",grade);
  switch(grade){
  case'A':
  printf("Excellent work!");
  break;
  case'B':
  printf("Well done");
  break;
  case'C':
  printf("good job");
  break;
  case'D':
  printf("you passed,but you could do better");
  break;
  }
if(grade!='f'){
printf("Congratulations! You are eligible for the next level");
}else{
    printf("Sorry, you failed");
} 
}
