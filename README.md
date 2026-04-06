# 25331a05d8-copy
#include <stdio.h>
#include <string.h>
int main(){
char str1[100],str2[100];
char copystr[100];
printf("25331a05d8\n");
printf("enter the first string:");
scanf("%s",str1);
printf("enter the second string:");
scanf("%s",str2);
printf("enter the length of first string: %lu",strlen(str1));
printf("enter the length of second string: %lu",strlen(str2));
strcpy(copystr,str1);
printf("\n copied string: %s",copystr);
strcat(str1,str2);
printf("\n concatenated string=%s",str1);
if(strcmp(copystr,str2)==0){
printf("\n strings are equal");
}
else{
printf("\n strings are not equal");
}
return 0;
}
