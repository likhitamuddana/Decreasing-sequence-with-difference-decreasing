# Decreasing-sequence-with-difference-decreasing
two integers N and D are passed as input.The program must print the decreasing sequence from N with common difference D.The difference D is decremented by 1 when calculating the values everytime.The sequence is printed untill D becomes 0'

#include<tdio.h>
#include<stdlib.h>

int main()
{
int n,d;
scanf("%d",&n);
scanf("%d",&d);
do{
n=n-d;
d--;
printf("%d ",n);
}
while(d!=0);
return 0;
}

input:
20 5
output:
15 11 8 6 5
