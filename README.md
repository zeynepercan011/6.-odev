# 6.-odev

/*kullan�c�dan pozitif tam say� alan ve bu de�er kadar kenar uzunlu�u olan bir kare �izen ciz() isimli bir fonksiyon yaz�n�z. kare �iziminde * kullan�lmal�d�r.
main() fonksiyonu ciz() fonksiyonunu �a��rmal�d�r.*/

#include<stdio.h>
void ciz(void);
int main(void)
{
	ciz();
	return 0;
}

void ciz(void)
{
	int i,j,x;
	printf("bir tam sayi giriniz: ");
	scanf("%d",&x);
	for(i=0;i<x;i++){
		for(j=0;j<x;j++)
		printf("*");
		printf("\n");
		
	}
}
