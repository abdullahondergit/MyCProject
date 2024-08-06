#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() 
{

    int n;
    printf("tabloda olmasini istediginiz en buyuk sayiyi giriniz:");
    scanf("%d", &n);
    int iuzaklik,juzaklik,matrisboyu,sayi;
    matrisboyu=2*(n-1)+1;
    for(int i=0;i<matrisboyu;i++){
        for(int j=0;j<matrisboyu;j++){
            if(i>matrisboyu/2)
            iuzaklik=i-matrisboyu/2;//merkeze olan uzaklık
            else {
            iuzaklik=matrisboyu/2-i;
            }
             if(j>matrisboyu/2)
            juzaklik=j-matrisboyu/2;
            else {
            juzaklik=matrisboyu/2-j;
            }
            if(iuzaklik>juzaklik)//merkeze uzaklıkların büyüğünün seçimi
            sayi=iuzaklik;
            else {
            sayi=juzaklik;
            }
            printf("%d ",sayi+1);//ortada 0 değil de 1 olmasını istiyoruz
        }printf("\n");
    }
  	// Complete the code to print the pattern.
    return 0;
}
