# 2020cce
## 進階題:分式化簡
```C
#include <stdio.h>
int main()
{
	int m,n,i;
	scanf("%d%d" ,&m, &n);
	for(int i=m;i>=1;i--)
	{
		if((m%i==0)&&(n%i==0))
		{
			m=m/i;
			n=n/i;
		}
	}
	printf("%d %d\n",m,n);
	return 0;
}
```
## 進階題：讀入整數反序列印
```C
#include <stdio.h>
int main()
{
	int m,n,i;
	scanf("%d%d" ,&m, &n);
	for(int i=m;i>=1;i--)
	{
		if((m%i==0)&&(n%i==0))
		{
			m=m/i;
			n=n/i;
		}
	}
	printf("%d %d\n",m,n);
	return 0;
}
```
## 進階題：A的B次方函數
```C
#include <stdio.h>
int main()
{
	int m,n,i;
	scanf("%d%d" ,&m, &n);
	for(int i=m;i>=1;i--)
	{
		if((m%i==0)&&(n%i==0))
		{
			m=m/i;
			n=n/i;
		}
	}
	printf("%d %d\n",m,n);
	return 0;
}
```
## 進階題：漸增數列相加 
```C
#include <stdio.h>
int main()
{
	int a,n=0;
	scanf("%d", &a);
	for(int i=2;i<=a;i++)
	{
		int j,z;
		j=i-1;
		z=j*i;
		n=n+z;
	}
	printf("%d\n",n);
}
```
## 基礎題：找零錢
```C
#include <stdio.h>
int main()
{
	int n;
	scanf("%d",&n);
	printf("%d=50*%d+5*%d+1*%d\n",n,n/50,n%50/5,n%50%5);
}
```
## 基礎題：因數個數
```C
#include <stdio.h>
int main()
{
	int a;
	scanf("%d",&a);
	int k=0;
	for(int i=1;i<=a;i++){
		if(a%i==0){
			k++;
		}
	}
	printf("%d\n",k);
}
```
## 基礎題：找倍數 
```C
#include <stdio.h>
int main()
{
	int a,k=0;
	for(int i=1;i<=10;i++){
		scanf("%d",&a);
		if(a%3==0){
			k++;
		}
	}
	printf("%d\n",k);
}
```

## 基礎題：整數轉換為等級 
```C
#include <stdio.h>
int main()
{
	int n;
	scanf("%d",&n);
	if(n>=90)printf("A\n");
	else if(n>=80)printf("B\n");
	else if(n>=60)printf("C\n");
	else if(n<60)printf("F\n");
}
```
##week2-1
```C
#include<stdio.h>
int main()
{
    int n1=10,n2=20,n3=30;
    printf("n1:%d n2:%d n3:%d\n",n1,n2,n3);

    int *p=&n1;
    *p=200;
    printf("n1:%d n2:%d n3:%d\n",n1,n2,n3);
    return 0;
}
```
##week2-2
```C
#include<stdio.h>
int main()
{
    int n1=10,n2=20,n3=30;
    printf("n1:%d n2:%d n3:%d\n",n1,n2,n3);

    int *p=&n1;
    *p=200;
    printf("n1:%d n2:%d n3:%d\n",n1,n2,n3);

    int *p2=&n3;
    *p2=300;
    printf("n1:%d n2:%d n3:%d\n",n1,n2,n3);

    return 0;
}
```
##week2-3
```C
#include<stdio.h>
int main()
{
    int n1=10,n2=20,n3=30;
    printf("n1:%d n2:%d n3:%d\n",n1,n2,n3);

    int *p=&n1;
    *p=200;
    printf("n1:%d n2:%d n3:%d\n",n1,n2,n3);

    int *p2=&n3;
    *p2=300;
    printf("n1:%d n2:%d n3:%d\n",n1,n2,n3);

    p2=p;
    *p2=400;
    printf("n1:%d n2:%d n3:%d\n",n1,n2,n3);

    return 0;
}
```
