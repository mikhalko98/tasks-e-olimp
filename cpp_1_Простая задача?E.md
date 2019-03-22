# tasks-e-olimp
tasks from the site e-olimp.com

#include <iostream>
#include <cctype>
    using namespace std;
int main()
{
    char str[9999];
    string sp;
    int kol=0;
    cin.get(str,9999);
   for(int i=0;str[i]!='\0';i++){
    cout<<str[i]<<" ";
   }
    return 0;
}
