- 👋 Hi, I’m @adityashah8877
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
adityashah8877/adityashah8877 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
#include<stdio.h>
#include<string.h>
int main(){
    char name[1000];
   char name2[2000];
   int l1,l2;
   gets(name);
   gets(name2);
   puts(name);
   puts(name2);
   l1=strlen(name);
   l2=strlen(name2);

    strncat(name,name2,l1+l2); 
    puts(name);
    }
