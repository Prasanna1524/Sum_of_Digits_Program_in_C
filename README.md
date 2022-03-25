# Sum_of_Digits_Program_in_C

      #include<stdio.h>
      int main()
      {
        int num,mod,sum=0;
        scanf("%d", &num);
        while(num>0)
        {
          mod=num%10;
          sum=sum+mod;
          num=num/10;
        }
        printf("%d",sum);
        return 0;
      }
